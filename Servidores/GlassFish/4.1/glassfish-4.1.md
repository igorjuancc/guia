# GlassFish 4.1

O GlassFish é um servidor de aplicação open source desenvolvido pela Sun Microsystem que implementa tecnologias desenvolvidas na plataforma Java EE.

## Instalação e Configuração

### Pré-Requisitos

* Java Runtime Environment 8 
* UnZip (Ou semelhante)

### Instalação

#### Ambiente Linux

1 - Realize o download da aplicação
```
wget download.oracle.com/glassfish/4.1/release/glassfish-4.1.zip
```

2 - Descompacte o arquivo
* 2.1 - Indicado utilizar a pasta /opt
* 2.2 - Indicado utilizar o comando "sudo" em conjunto 
```
unzip glassfish-4.1.zip -d /opt
```
3 - Defina a pasta do GlassFish como diretório principal
```
export PATH=/opt/glassfish4/bin:$PATH
```

4 - Finalizado, o servidor já pode ser iniciado
```
sudo /opt/glassfish4/bin/asadmin start-domain
```

### Possíveis erros

#### GlassFish requires Java SE version 6.  Your JDK is version 0

1 - Abra o arquivo asenv.conf da pasta config do glassfish com o editor de texto de sua preferência, aqui utilizaremos o "VI"
```
sudo vi /opt/glassfish4/glassfish/config/asenv.conf
```

2 - Insira na última linha do arquivo o caminho do Java 8 no seu computador
```
AS_JAVA="/usr/lib/jvm/java-8-openjdk-amd64"
```
3 - Salve e inicialize o servidor

### Links Úteis

* [GlassFish](https://javaee.github.io/glassfish/)
* [Java](https://www.java.com/pt-BR/)

### Referências

ARAUJO, Israel Sousa. Instalando servidor web Glassfish no Ubuntu Server. Medium, 2015. Disponível em: <https://medium.com/israel-araujo/instalando-servidor-web-glassfish-no-ubuntu-server-ecef64a5c95e>. Acesso: 18 de jan. de 2022.
