# Golang snippets
Welcome to Golang Snippets, a collection of Golang patterns/snippets

## Go installation
> See: https://golang.org/doc/install
1. Download archive:
```sh
wget https://golang.org/dl/go1.22.6.linux-amd64.tar.gz
```
2. Untar it in `/usr/local` folder:
> You may need to run the command as root or through sudo
```sh
sudo rm -rf /usr/local/go && sudo rm -rf /usr/bin/go && sudo rm -rf /bin/go && sudo tar -C /usr/local -xzf go1.22.6.linux-amd64.tar.gz
```
3. Add this to `.zprofile` file:
```sh
export PATH=$PATH:/usr/local/go/bin
```
4. Test the installation:
```sh
go version
```
5. Remove archive:
```sh
rm go1.22.6.linux-amd64.tar.gz
```
6. Follow this tutorial to configure Go + VSCode: https://learn.microsoft.com/en-us/azure/developer/go/configure-visual-studio-code


## Snippets
- [ ] [Go random logger](https://github.com/veben/go_random_logger/blob/main/readme.md)