# GlassFish 4.1

O [GlassFish](https://javaee.github.io/glassfish/) é um servidor de aplicação open source desenvolvido pela Sun Microsystem que implementa tecnologias desenvolvidas na plataforma Java EE.

## Instalação e Configuração

### Pré-Requisitos

* [Java Runtime Environment 8](https://www.java.com/pt-BR/download/manual.jsp)    
* [Java Development Kit 8](https://www.oracle.com/br/java/technologies/javase/javase8-archive-downloads.html)    
* UnZip (Ou semelhante)

### Instalação

#### Ambiente Linux

1 - Realize o download da aplicação
```
wget download.oracle.com/glassfish/4.1/release/glassfish-4.1.zip
```

2 - Descompacte o arquivo
    * 2.1 - Indicado utilizar a pasta /opt
```
unzip glassfish-4.1.zip -d /opt
```
3 - Defina a pasta do GlassFish como diretório principal
```
export PATH=/opt/glassfish4/bin:$PATH
```

4 - Configure o caminho da JDK para o servidor 
    * 4.1 - bra o arquivo asenv.conf da pasta config do glassfish com o editor de texto de sua preferência, aqui utilizaremos o "VI"
```
vi /opt/glassfish4/glassfish/config/asenv.conf
```
    * 4.2 - Insira na última linha do arquivo "AS_JAVA" acompanhado do caminho da JDK no seu computador 
```
AS_JAVA="/usr/lib/jvm/java-8-openjdk-amd64"
```
    * 4.3 - Salve e feche o editor de texto


5 - Finalizado, o servidor GlassFish já pode ser iniciado
```
/opt/glassfish4/bin/asadmin start-domain
```

6 - Para encerrar o servidor GlassFish utilize o comando "stop-domain"
```
/opt/glassfish4/bin/asadmin stop-domain
```

## Links Úteis

* [GlassFish](https://javaee.github.io/glassfish/)
* [Java](https://www.java.com/pt-BR/) 
* [UnZip](https://linuxize.com/post/how-to-unzip-files-in-linux/) 

## Referências

ARAUJO, Israel Sousa. Instalando servidor web Glassfish no Ubuntu Server. Medium, 2015. Disponível em: <https://medium.com/israel-araujo/instalando-servidor-web-glassfish-no-ubuntu-server-ecef64a5c95e>. Acesso: 18 de jan. de 2022.
