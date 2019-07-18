# NVM a gerenciar versões do NodeJs

O nvm(Node Version Manager) é um script que gerencia diferentes versões do Node.js

  
### Instalação

  
```
curl -o- https://raw.githubusercontent.com/nvm-sh/nvm/v0.34.0/install.sh | bash
```
ou
```
wget -qO- https://raw.githubusercontent.com/nvm-sh/nvm/v0.34.0/install.sh | bash
```
- Para baixar, compilar e instalar uma versão específica do node.js:
```
$ nvm install 0.10
```
- Para definir a versão default do usuário:
```
$ nvm use 0.10
```
- Pronto e agora vamos ver a versão atual
```
$ nvm current
```
ou
```
$ node --version
```
- Para listar as versões ja instaladas no sistema:
```
$ nvm ls
```
- Para listar as versões disponíves para instalar:
```
$ nvm ls-remote
```

### Desinstalação

- Para desinstalar uma versão específica:
```
$ nvm uninstall 0.10
```

Mais informações completo:
[nvm-sh](https://github.com/nvm-sh/nvm)



