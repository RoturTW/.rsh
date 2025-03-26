# msg

Send message to users

- Sends a message to one or more users
- First select users, then send the message

## Usage

```txt
username@system ~ % msg - [user1,user2,...] 
username@system ~ % msg message_text
```

## Examples

```txt
username@system ~ % msg - ["user1"]
Selected users to send to

username@system ~ % msg Hello, how are you?
```

## Notes

- The first command with `-` sets the recipient(s)
- The second command sends the actual message
- Cannot send messages to system users
- Returns an error if you try to send without selecting recipients first
