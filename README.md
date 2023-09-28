# Docs

- https://docs.projectile.mx/projectile/index.html
- https://emacs-lsp.github.io/lsp-mode/page/lsp-intelephense/
- https://github.com/emacs-lsp/lsp-treemacs

# HowTo

@see https://chocolatey.org/

- Add 
`C:\Users\natha\.emacs.d\bin` to PATH

- Set
HOME = `C:\Users\natha`

- In an administrator powershell
```bash
Set-ExecutionPolicy Bypass -Scope Process -Force; [System.Net.ServicePointManager]::SecurityProtocol = [System.Net.ServicePointManager]::SecurityProtocol -bor 3072; iex ((New-Object System.Net.WebClient).DownloadString('https://chocolatey.org/install.ps1'))

choco install git emacs ripgrep fd jq html-tidy shellcheck pandoc editorconfig.core php composer nodejs winlibs sqlite grep gtk-runtime shfmt hunspell.portable llvm python
```

- In a new administrator powershell
```bash
npm install -g js-beautify
npm install -g stylelint
npm install -g dockerfile-language-server-nodejs
```

- In a command (cmd) prompt
```bash
set PATH=C
```

- In normal powershell
```bash
git clone https://github.com/hlissner/doom-emacs $HOME\.emacs.d
doom install
# maybe copy conf files and co
doom sync
# check install with
doom doctor
# start emacs with
doom run
```

- Under Emacs
```
M-x all-the-icons-install-fonts
M-x nerd-icons-install-fonts
```

- Add personnal librairies in 
```bash
C:\ProgramData\chocolatey\lib\winlibs\tools\mingw64\x86_64-w64-mingw32\sys-root\mingw\include
```
