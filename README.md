# NVM e gerenciar as versões do NodeJs 

O nvm(Node Version Manager) é um script que gerencia diferentes versões do Node.js

## Instalação

```
curl https://raw.githubusercontent.com/creationix/nvm/v0.23.2/install.sh | bash  
```

ou

```
wget -qO- https://raw.githubusercontent.com/creationix/nvm/v0.23.2/install.sh | bash  
```


![node](https://user-images.githubusercontent.com/8229421/29643475-bcda8f04-8845-11e7-8dfd-f890840901e8.png)



pronto e agora vamos ver a versão atual

```
nvm current
```

instalar para a nova versão 8.4.x do Node.js e rodar

```
nvm install 8.4
```
Começar dar o apelido a versão 'nova'

```
nvm alias nova 8.4
```
![node2](https://user-images.githubusercontent.com/8229421/29643483-c1a3ebfc-8845-11e7-841a-c03b374c649a.png)

se quiser usar a versão 8.x.x

```
nvm use nova
```

quer voltar a versão 6.x.x

```
nvm use 6
```

![node3](https://user-images.githubusercontent.com/8229421/29643486-c49ad8fc-8845-11e7-9621-a338deeb4777.png)

