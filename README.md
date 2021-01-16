# NVM a gerenciar versões do NodeJs

O nvm(Node Version Manager) é um script que gerencia diferentes versões do Node.js. Criei um pequeno tutorial, se vc seguir os passos aqui e a sua versão do nvm se tudo ocorrer bem. Depois de configurar, seu update Node JS vai se tornar fácil.

>Instalei foi no sistema operacional Linux(Debian versão 10).

![nodejs](https://user-images.githubusercontent.com/8229421/61498982-dd56f780-a99b-11e9-9dc1-cd6ff269474a.png)

  
### Instalação

  
```
curl -o- https://raw.githubusercontent.com/nvm-sh/nvm/v0.37.2/install.sh | bash
```
ou
```
wget -qO- https://raw.githubusercontent.com/nvm-sh/nvm/v0.37.2/install.sh | bash
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
![Captura de tela de 2019-07-18 20-17-10](https://user-images.githubusercontent.com/8229421/61499130-77b73b00-a99c-11e9-9869-4c2a979137b4.png)

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

Mais informações completas:
[nvm-sh](https://github.com/nvm-sh/nvm)



