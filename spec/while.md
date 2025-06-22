# while

Execute code while condition is true

- Repeatedly executes code block while the specified condition remains true

## Usage

```txt
username@system ~ % while {condition code} do {code}
```

## Examples

```txt
username@system ~ % while {calc (get_key count '{"count":0}') < 3} do {echo "Loop iteration"}
Loop iteration
Loop iteration
Loop iteration

username@system ~ % while {calc (random 1 10) != 5} do {echo "Rolling dice..."}
Rolling dice...
Rolling dice...
Rolling dice...
```

## Notes

- The condition code is evaluated before each iteration
- Loop continues only if the condition code returns exactly "true"
- Code block executes when condition evaluates to true
- Loop stops when condition returns anything other than "true"
- Use braces `{}` to group the condition code and execution code block
- Supports command substitution within conditions using parentheses `()`
- Be careful to avoid infinite loops by ensuring the condition can eventually return something other than "true"
