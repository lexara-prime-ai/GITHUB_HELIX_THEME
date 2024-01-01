* GitHub theme config for the Helix editor

```toml
theme = "github_dark"

[editor]
true-color = true

[editor.cursor-shape]
insert = "bar"

[editor.soft-wrap]
enable = true

[editor.statusline]
left = ["mode", "spinner"]
center = ["file-name"]
right = ["diagnostics", "selections", "position", "file-encoding", "file-line-ending", "file-type"]
separator = "|"
mode.normal = "NORMAL"
mode.insert = "INSERT"
mode.select = "SELECT"

[editor.lsp]
enable = true
display-messages = true
auto-signature-help = true
display-inlay-hints = true
display-signature-help-docs = true
snippets = true
goto-reference-include-declaration = true
```
