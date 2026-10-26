```bash
# once
wget https://github.com/owenthereal/upterm/releases/download/v0.37.0/upterm_linux_amd64.deb
sudo apt install -y ./upterm_linux_amd64.deb
ssh-keygen -t ed25519 -N '' -f ~/.ssh/upterm

# each session
upterm host --private-key ~/.ssh/upterm --authorized-user github:nejeoui --accept -- bash
```
