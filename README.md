# Enable VS-Code Assembly Breakpoint


## Description

In VS-Code, most of assembly extensions don't include breakpoint function, but actually C/C++ extension can catch the breakpoint in assembly. This extension aims to enable debug breakpoint for assembly file.


## How to use

Just install the extension.

## How to add mroe language support

Enable breakpoint for other language-id by add the array of language under ```contributes``` in packages.json

Open detail pages of language extension and go to feature Contributions, find the Languages, and the ID in the table is language-id