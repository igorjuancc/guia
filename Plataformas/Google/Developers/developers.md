# Google Developers

O [Google Developers](https://developers.google.com/) é uma plataforma do Google para desenvolvedores de softwares configurarem e integrarem os serviços públicos do Google com suas aplicações, através das APIs disponíveis.

## Índice

<!--ts-->
   * [Resumo](#Título) 
   * [Índice](#Índice) 
   * [Configuração de Novo Projeto](#Configuração-de-Novo-Projeto)
       * [Pré-Requisitos](#Pré-Requisitos)  
       * [Criar um Novo Projeto](#Criar-um-Novo-Projeto)
       * [Habilitar API do Google Drive](#Habilitar-API-do-Google-Drive)
       * [Criar e Configurar Credenciais](#Criar-e-Configurar-Credenciais)
         * [Tela de Permissão OAuth](#Tela-de-Permissão-OAuth)
         * [Criar Credencias](#Criar-Credencias)
   * [Links Úteis](#Links-Úteis)  
   * [Referências](#Referências)  	
   * [Autor](#Autor)
<!--te-->

## Configuração de Novo Projeto

### Pré-Requisitos

* Possuír uma conta ativa do Google
* Navegador de internet

### Criar um Novo Projeto

1. Utilizando o navegador de internet, realize o [login](https://console.developers.google.com/?hl=pt-br) na plataforma Google Developers.
2. No painel inicial, clique no menu superior "Selecione um projeto".
<div align="center">
     <h4>Selecione um projeto</h4>
     <img height="150vh" width="300vw" src="https://github.com/igorjuancc/guia/blob/main/Plataformas/Google/Developers/img/1.png" />   
</div>
<br />

3. Na tela exibida, pressione o botão "Novo Projeto" localizado no canto superior direito.
<div align="center">
     <h4>Novo projeto</h4>
     <img height="160vh" width="230vw" src="https://github.com/igorjuancc/guia/blob/main/Plataformas/Google/Developers/img/2.png" />   
</div>
<br />

4. Preencha o "Nome do projeto" no formulário que foi aberto, o campo "Local" é opcional e depois clique em criar.
<div align="center">
     <h4>Formulário novo projeto</h4>
     <img height="290vh" width="350vw" src="https://github.com/igorjuancc/guia/blob/main/Plataformas/Google/Developers/img/3.png" />   
</div>
<br />

5. Projeto criado com sucesso.

### Habilitar API do Google Drive

1. Com o projeto que fara uso das APIs selecionado, utilize a barra de pesquisa para buscar a(s) API(s) necessária(s).
2. Digite "google drive api" e selecione o primeiro link apresentado.
<div align="center">
     <h4>Busca de API</h4>
     <img height="150vh" width="350vw" src="https://github.com/igorjuancc/guia/blob/main/Plataformas/Google/Developers/img/4.png" />   
</div>
<br />

3. Clique no botão "ativar" apresentado.
<div align="center">
     <h4>Ativar API</h4>
     <img height="150vh" width="350vw" src="https://github.com/igorjuancc/guia/blob/main/Plataformas/Google/Developers/img/5.png" />   
</div>	
<br />

4. API habilitada com sucesso.	

### Criar e Configurar Credenciais	

#### Tela de Permissão OAuth

1. Para criar as credenciais de utilização das APIs, se faz necessário primeiramente configurar a tela de autenticação OAuth.
2. Inicialmente, clique no icone do menu superior esquerdo.
<div align="center">
     <h4>Menu do projeto</h4>
     <img height="200vh" width="250vw" src="https://github.com/igorjuancc/guia/blob/main/Plataformas/Google/Developers/img/6.png" />   
</div>	
<br />

3. Selecione a opção "APIs e serviços" e posteriormente "Painel".
<div align="center">
     <h4>APIs e serviços</h4>
     <img height="200vh" width="330vw" src="https://github.com/igorjuancc/guia/blob/main/Plataformas/Google/Developers/img/7.png" />   
</div>
<br />

4. Na janela aberta, selecione a opção "Tela de permissão OAuth".
<div align="center">
     <h4>Tela de permissão OAuth</h4>
     <img height="200vh" width="200vw" src="https://github.com/igorjuancc/guia/blob/main/Plataformas/Google/Developers/img/8.png" />   
</div>
<br />

5. No formulário exibido, selecione a opção "Externo" de "User Type" e clique em criar.
<div align="center">
     <h4>User Type</h4>
     <img height="220vh" width="380vw" src="https://github.com/igorjuancc/guia/blob/main/Plataformas/Google/Developers/img/9.png" />   
</div>
<br />

6. Em "Informações do app" preencha os dados de "Nome do app", "E-mail para suporte do usuário" e na parte inferior do formulario "Endereço de e-mail" da seção "Dados de contato do desenvolvedor", clique em Salvar e Continuar.

<div align="center">
<table>  
  <tr align="center">    
    <td>      
      <h5>Informações do app - "Nome do app" e "E-mail para suporte do usuário" </h5>
    </td>
    <td>      
      <h5>Dados de contato do desenvolvedor - "Endereço de e-mail"</h5>
    </td>
  </tr>  
  <tr align="center">    
    <td>
      <img height="220vh" width="250vw" src="https://github.com/igorjuancc/guia/blob/main/Plataformas/Google/Developers/img/10.png" />           
    </td>  
    <td>
      <img height="100vh" width="380vw" src="https://github.com/igorjuancc/guia/blob/main/Plataformas/Google/Developers/img/11.png" /> 
    </td>
  </tr> 
</table>
</div>
<br />

7. Em escopos, não existe a necessidade de indicar quais serão utilizados, clique em "Salvar e Continuar", todas as funcionalidades estarão disponíveis.
8. Na tela de usuários de testes, também não há a necessidade de adicionar dados, selecione "Salvar e Continuar". 
9. Ao final, no ultimo formulario, clique em  "Voltar para o painel".
10. Configuração de Tela de permissão OAuth finalizada.  

#### Criar Credencias	

1. Apos a configuração da tela de permissão OAuth, selecione a opção no menu lateral a opção "Credenciais".
<div align="center">
     <h4>Credenciais</h4>
     <img height="220vh" width="250vw" src="https://github.com/igorjuancc/guia/blob/main/Plataformas/Google/Developers/img/12.png" />   
</div>
<br />

2. No menu superior clique em "Criar Credenciais" e selecione a opção "ID do cliente OAuth". 
<div align="center">
     <h4>Criar Credenciais</h4>
     <img height="200vh" width="300vw" src="https://github.com/igorjuancc/guia/blob/main/Plataformas/Google/Developers/img/13.png" />   
</div>
<br />

3. Na tela aberta de criação do id do cliente do oauth, em "Tipo de aplicativo" selecione a opção "App para computador".
<div align="center">
     <h4>Tipo de aplicativo</h4>
     <img height="200vh" width="400vw" src="https://github.com/igorjuancc/guia/blob/main/Plataformas/Google/Developers/img/14.png" />   
</div>
<br />	

4. Deixe o campo "Nome" com o padrão criado pelo sistema e sem fazer modificações e clique em criar.
5. Com as "credencias" criadas, clique na opção "Fazer o download do json", esse arquivo sera utilizado para autenticar as suas aplicações com a api do google.
<div align="center">
     <h4>Cliente OAuth criado</h4>
     <img height="300vh" width="400vw" src="https://github.com/igorjuancc/guia/blob/main/Plataformas/Google/Developers/img/15.png" />   
</div>
<br />

6. Credencial criada com sucesso.

## Links Úteis

* [Google Developers Console](https://console.developers.google.com/?hl=pt-br) 
* [Google Workspace for Developers Guide](https://developers.google.com/workspace/guides/create-project)
* [Google Sheets and Java](https://www.youtube.com/watch?v=8yJrQk9ShPg&t=288s)
* [Como Integrar Python com o Google Sheets](https://www.youtube.com/watch?v=ZU30e4gkV8g)

## Referências

JAVA quickstart. Google Developers, 2022. Disponivel em: <https://developers.google.com/sheets/api/quickstart/java>. Acesso em: 28 de jan. de 2022.
<br />
GOOGLE Developers. Wikipédia, 14 de out. de 2021. Disponível em: <https://pt.wikipedia.org/wiki/Google_Developers>. Acesso em: 28 de jan. de 2022.
<br />
COMO Integrar Python com o Google Sheets. YouTube - Hashtag Programação, 2021. Disponível em: <https://www.youtube.com/watch?v=ZU30e4gkV8g>. Acesso em: 28 de jan. de 2022.

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
