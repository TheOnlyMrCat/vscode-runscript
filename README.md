# vscode-runscript

Support for my language [Runscript](https://github.com/TheOnlyMrCat/runscript) in vscode

Shell script tokenisation comes from [jeff-kyhin/better-shell-syntax](https://github.com/jeff-hykin/better-shell-syntax).
Pretty much everything in the `"repository"` key comes verbatim from that, except `#comment`, which was changed to runscript 
comments, and `#custom_command_names`, to which I added `run`.