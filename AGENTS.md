# AGENT INSTRUCTIONS

This repository uses .NET 8 and .NET 9. Before committing changes run the following commands:

```bash
dotnet build /WarnAsError
dotnet test
```

Ensure added features have accompanying tests. Build warnings should be treated as errors. Formatting is controlled by `.editorconfig`:

- C# files use four spaces for indentation.
- JSON, YAML and XML files use two spaces.
- Trim trailing whitespace (except in Markdown).
- End files with a newline.

Refer to `README.md` for additional development details.
