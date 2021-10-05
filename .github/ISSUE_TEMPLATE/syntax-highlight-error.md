---
name: Syntax highlight error
about: When syntax highlighting has been defined wrong
title: "[BUG]: Syntaxherr --replace with scope-- "
labels: bug, syntax
assignees: ''

---

**Describe the bug**
A clear and concise description of what the bug is.
Include a code snippet of the case to test against:

    mylabel:; My first label
      lda #%10
      ror

**Self-test report**
Use `>Developer: inspect Editor Tokens and Scopes` on the syntax and list it's `textmate scopes` as such:
1. constant.numeric.binary
2. immediate.asm
3. text.vasm.oldstyle.asm

Does this behaviour appear in a specific case or in the whole script?

**Screenshots or minimal (broken)working example**
Visual is key to reproduce - if it can not be reproduced the issue will be closed.
