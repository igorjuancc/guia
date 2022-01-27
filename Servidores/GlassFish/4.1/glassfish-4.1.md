# GlassFish 4.1

O [GlassFish](https://javaee.github.io/glassfish/) é um servidor de aplicação open source desenvolvido pela Sun Microsystem que implementa tecnologias desenvolvidas na plataforma Java EE.

## Índice

<!--ts-->
   * [Resumo](#GlassFish-4.1) 
   * [Índice](#Índice) 
   * [Instalação e Configuração](#Instalação-e-Configuração)
   * [Pré-Requisitos](#Pré-Requisitos)  
   * [Instalação](#Instalação)  
       * [Ambiente Linux](#Ambiente-Linux)
   * [Links Úteis](#Links-Úteis)  
   * [Referências](#Referências)  	
   * [Autor](#Autor)
<!--te-->

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

4 - Configure o caminho da JDK no servidor 
* 4.1 - Abra o arquivo asenv.conf da pasta config do glassfish com o editor de texto de sua preferência, aqui utilizaremos o "VI"
```
vi /opt/glassfish4/glassfish/config/asenv.conf
```
* 4.2 - Insira na última linha do arquivo de configuração o texto "AS_JAVA=" acompanhado do caminho da JDK no seu computador 
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

## Autor
<a href="https://br.linkedin.com/in/igor-juan-cordeiro-da-costa-2b4a77101">
<img src="https://avatars.githubusercontent.com/u/50890812?s=400&u=566e615dd1691c75eabd1dcb4ba749be82d1e86c&v=4" width="100px;" alt="Igor Juan" />
</a>
<br />
<a href="https://br.linkedin.com/in/igor-juan-cordeiro-da-costa-2b4a77101" target="_blank"> > Igor Juan < </a><br /><br />
Desenvolvido por Igor Juan 🤙<br />
Em caso de dúvidas, sugestões e informações, entre em contato: <br /> 
<a href="https://br.linkedin.com/in/igor-juan-cordeiro-da-costa-2b4a77101" target="_blank"> <img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white" target="_blank"> </a>
<a href="https://www.facebook.com/igorjuan.cordeirodacosta" target="_blank"> <img src="https://img.shields.io/badge/Facebook-1877F2?style=for-the-badge&logo=facebook&logoColor=white" target="_blank"> </a>
<a href="https://twitter.com/zig_cwb" target="_blank"> <img src="https://img.shields.io/badge/Twitter-1DA1F2?style=for-the-badge&logo=twitter&logoColor=white" target="_blank"> </a>
<a href="https://github.com/igorjuancc" target="_blank"> <img src="https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white" target="_blank"> </a>
