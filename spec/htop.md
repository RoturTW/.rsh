# htop

Display process information

- Shows information about running processes and system resources

## Usage

```txt
username@system ~ % htop [flags]
```

## Flags

- `-l`: Display only the number of running processes
- `-g`: Display detailed information about a specific process (requires process ID)
- `-r`: Display raw process data in JSON format

## Examples

```txt
username@system ~ % htop
Total Processes: 15
Name                                    Ms to render
process1                                42
process2                                18
process3                                35

username@system ~ % htop -l
15

username@system ~ % htop -g 1
{process data for process ID 1}

username@system ~ % htop -r
[raw JSON data of all processes]
```
