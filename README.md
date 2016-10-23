# SSH Key Management Utilities

A basic repository of script / utilities to help with `ssh` key management.

## remove_user_keys

Helps to remove `ssh` keys from an `authorized_keys` file for a given user based on the public keys that user has listed on [GitHub](https://github.com).

```
Usage:

    remove_user_keys <github_username>

Or, if you want to specify the authorzied_keys file

    authorized_keys=/path/to/file remove_user_keys <github_username>

```

## add_user_keys

Quick script to add `ssh` keys to an `authorized_keys` file for a given user based on the public keys that user has listed on [GitHub](https://github.com).
```
Usage:

    add_user_keys <github_username>

Or, if you want to specify the authorzied_keys file

    authorized_keys=/path/to/file add_user_keys <github_username>

```
