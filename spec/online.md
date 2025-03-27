# online

Display online users

- Shows a list of currently connected users

## Usage

```txt
username@system ~ % online
You Are Connected As username
user1
user2
user3
```

```txt
username@system ~ % online -u
username
```

```txt
username@system ~ % online -r
[username, user1, user2, user3]
```

## Notes

- Shows the current user at the top
- Lists all other connected users
- Does not include the current user in the list
- -u flag can be used to get the connected username
