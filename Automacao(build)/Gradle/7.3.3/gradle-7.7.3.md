# Gradle 7.3.3

O Gradle é uma ferramenta utilizada para automação de compilação na construção de softwares. Baseia-se nos conceitos do Apache Ant e Apache Maven e introduz uma linguagem de domínio específico (DSL) baseada em Groovy em vez do XML usado pelo Apache Maven para declarar a configuração do projeto.

## Índice

<!--ts-->
   * [Resumo](#Título) 
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

* [Java Development Kit 8](https://www.oracle.com/br/java/technologies/javase/javase8-archive-downloads.html)

### Instalação

#### Ambiente Linux

1 - Realize o [download](https://gradle.org/next-steps/?version=7.3.3&format=bin) da aplicação <br />
2 - Crie uma nova pasta e descompacte o arquivo nesse diretório
```
$ mkdir /opt/gradle
$ unzip -d /opt/gradle gradle-7.3.3-bin.zip
```
3 - Configure a variável de ambiente PATH para incluir o diretório bin, encontrado na pasta que foi criada no passo anterior e descompactado o arquivo baixado
```
 $ export PATH=$PATH:/opt/gradle/gradle-7.3.3/bin
```
4 - Confirme a instalação com o comando 
```
$ gradle -v
```

5 - A saída do comando dever ser semelhante a
```
------------------------------------------------------------
Gradle 7.3.3
------------------------------------------------------------
``` 
6 - Para criar uma estrutura básica de um novo projeto, utilize o comando 
```
gradle init --type basic
``` 

## Links Úteis

* [Gradle Build Tool](https://gradle.org/)


## Referências

KAINULAINEN, Petri. **Getting Started With Gradle**. Petri Kainulainen. Disponível em <https://www.petrikainulainen.net/getting-started-with-gradle/>. Acesso em: 28 de jan. de 2022. <br />
GRADLE. Wikipédia, 06 de fev. de 2021. Disponível em: <https://pt.wikipedia.org/wiki/Gradle>. Acesso em: 28 de jan. de 2022. <br />
INSTALLATION. Gradle. Disponível em: <https://gradle.org/install/>. Acesso em: 28 de jan. de 2022.

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
