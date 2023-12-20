## NeoVim Config with NvChad and Mason plugin

### References
[NvChad](https://nvchad.com/)
[Mason](https://github.com/williamboman/mason.nvim)
[NeoVim for Golang](https://www.youtube.com/watch?v=i04sSQjd-qo)
[NeoVim for Python](https://www.youtube.com/watch?v=4BnVeOUeZxc)

### Go Dependencies
```bash 
go install golang.org/x/tools/cmd/goimports@latest
go install github.com/segmentio/golines@latest
go install github.com/go-delve/delve/cmd/dlv@latest
go install mvdan.cc/gofumpt@latest
sudo apt install python3-pip
sudo apt install python3-venv
```

### Python Dependencies
```bash
pip install pyright 
npm install -g pyright
```

### Enable LSP Support
```bash
:TSInstall go python
```
