# Agent instructions

## Do not read `j2735-asn-files/`

Do not read, open, search, index, summarize, or otherwise access the contents of any directory named `j2735-asn-files`, anywhere in this repository (including inside submodules).

This applies to every means of access: file-reading tools, code search and indexing, and shell commands (`cat`, `grep`, `type`, `Get-Content`, scripts that open the files, etc.). Do not send the contents of these files to any model or external service.

If a task appears to require the contents of that directory, stop and ask the user instead.

### Why

The ASN.1 files that belong in that directory are copyrighted by SAE International, and SAE's policy forbids access to them by AI tools. This repository does not distribute those files. Users may place local copies there that they have legitimately obtained from SAE; those copies are gitignored. The purpose of this rule is to keep AI tools from picking up a user's local copies of those copyrighted files.
