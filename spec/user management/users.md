# Users

users

- returns each username of the users you have access to on newlines

Example:

```txt
username@os ~ % users
Mist

```

users -r

- returns a raw list of users that you have access to
- each item in the array should be a [rotur account object](https://docs.rotur.dev/my-account/rotur-account-objects) without the "password" or "key" included

```txt
username@os ~ % users -r
[{rotur account object},{rotur account object}]
```
