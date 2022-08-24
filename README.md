<div align="center">

<h1>Desafio de projeto</h1>



Script de provisionamento de um servidor web Apache





![Image bootcamp](Servidor web apache/img/linux.png)

</div>



Baixando os dados do github

```

https://github.com/denilsonbonatti/linux-site-dio

```

atualizando e Instalando apache2 e unzip no servidor

```
apt-get update
apt-get upgrade -y
apt-get install apache2 unzip -y
```

Na pasta /tmp instalar os arquivos do github

```
wget https://github.com/denilsonbonatti/linux-site-dio/archive/refs/heads/main.zip
```

Descompactar arquivo:

``` 
unzip main.zip
```

Abrir diretório descompactado:

```
cd linux-site-dio-main
```

Copiar arquivos para a pasta /html:

```
cp -R * /var/www/html/
```

Dar permissão para o arquivo Script.sh

```
chmod +x Script.sh
```

E Executar o arquivo

```
./Script.sh
```



Verificar se o site está funcionando acessando qualquer browser e inserir o IP