# CMD Hook

Executes the argument string in the shell as a Python subprocess.

For more information about how this works, see the
[subprocess documentation](https://docs.python.org/3/library/subprocess.html)

Syntax:

```yaml
<hook_point>:
  - !cmd <shell_command>
```

Example:

```yaml
before_create:
  - !cmd 'echo hello'
```
