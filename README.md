# ansible-pre-commit

A set of [pre-commit](http://pre-commit.com) hooks that help with Ansible

## Hooks

### encryption-check
Verifies that vault files are encrypted. Defaults to checking files starting with `vault`, ending with `.vault.yml` or ending in `.vault`
