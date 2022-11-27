
# Set up Go on Ubuntu

Install Git:

    sudo apt install git

Install Go:

Get the link from https://go.dev/doc/install

```bash
rm -rf /usr/local/go
wget -qO- https://go.dev/dl/go1.19.3.linux-amd64.tar.gz | sudo tar xvz -C /usr/local

cat >> ~/.bash_aliases << 'EOF'

export PATH=$PATH:/usr/local/go/bin

EOF
```
