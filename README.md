# hello-cpp


LLVM - Low Level Virtual Machine


# Troubleshooting

1. `zsh: command not found: code`

`Command+shift+P`, enter `shell command`

See https://code.visualstudio.com/docs/setup/mac

2. `clang: error: linker command failed with exit code 1 (use -v to see invocation)`

```tasks.json
- "command": "/usr/bin/clang",
+ "command": "/usr/bin/clang++",
```
