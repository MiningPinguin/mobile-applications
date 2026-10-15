# boilderplate
# boilderplate

## Line endings

This repository uses LF (`\n`) line endings. `.gitattributes` enforces them
automatically (`* text=auto eol=lf`), so whatever your editor or OS defaults to,
Git records only your real changes instead of showing whole files as modified.

If every line of a file suddenly shows up as changed, something is writing CRLF
into it. Set your editor to insert LF — VS Code: `"files.eol": "\n"`.
