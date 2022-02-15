<h1>Criando o 1º projeto no Spring Initializer</h1>

<br />

<h2>👣 Passo 01 - Abrindo o Spring Initializr no Spring Tool Suite (STS)</h2>

<br />

1) Abra o STS
2) Para abrir o **Spring Initializer**, clique no menu **File ⇨ New**, e clique na opção **Spring Starter Project**

<br />

<div align="center"><img src="https://i.imgur.com/XLRyeRq.png" title="source: imgur.com" /></div>

<br /> 

<h2>👣 Passo 02 - Setup do Projeto</h2>

<br />

<h3>Configurações iniciais</h3>

<br />

<div align="center"><img src="https://i.imgur.com/ES3D1bA.png" title="source: imgur.com" /></div>

<br />

| Item             | Descrição                                                    |
| ---------------- | ------------------------------------------------------------ |
| **Name**         | Nome do Projeto (Geralmente em letras minúsculas)            |
| **Type**         | Define o Gerenciador de Dependências (Maven)                 |
| **Packaging**    | Define como a aplicação será empacotada (JAR)                |
| **Java Version** | Versão do Java (a versão da imagem pode ser diferente da sua tela) |
| **Language**     | Linguagem (Java)                                             |
| **Group**        | O domínio reverso de sua empresa ou organização. **Exemplo:** *generation.com* ⇨ ***com.generation*** |
| **Artifact**     | O artefato a ser gerado, ou seja, o nome da aplicação que será criada (Mesmo nome do projeto) |
| **Version**      | Versão da API (não alterar)                                  |
| **Description**  | Descrição do projeto                                         |
| **Package**      | Estrutura do pacote inicial da aplicação (Group + Artifact). Exemplo: ***<u>com.generation.helloworld</u>*** |

<br />

**Dependências**

<br />

Neste projeto vamos inserir 3 dependências, conforme mostra a figura abaixo:

<br />

<div align="center"><img src="https://i.imgur.com/xkwG1en.png" title="source: imgur.com" /></div>

<br />

| Dependência               | Descrição                                                    |
| ------------------------- | ------------------------------------------------------------ |
| **Spring Web**            | Fornece todas as Bibliotecas necessárias para trabalhar com o protocolo http. |
| **Spring Boot Dev Tools** | Permite a atualização do projeto em tempo real durante o processo de Desenvolvimento da aplicação. |


<br />

Clique no botão **Finish** para concluir.

<br />

<div align="center"> <h2>*** IMPORTANTE ***</h2></div>

Como é o primeiro projeto que você está criando no Spring, o processo de geração do projeto será um pouco lento, porquê será feito o download de diversos arquivos. Nos próximos projetos o processo será um pouco mais rápido.

Caso o projeto apresente algum erro no arquivo pom.xml, utilize o <b>Guia de correção do arquivo pom.xml</b> para corrigir o problema.



<h2>👣 Passo 03 - Codar!</h2>



Siga as instruções do seu Instrutor!



<h2>👣 Passo 04 - Executar o Projeto</h2>



1. No **STS**, abaixo da **Package Explorer**, está localizada a janela **Boot Dashboard**.

<div align="center"><img src="https://i.imgur.com/MNofI7p.png" title="source: imgur.com" /></div>

2. Caso ela não esteja visível, Na barra de ferramentas do STS, logo abaixo do menu **Search**, clique no ícone: <img src="https://i.imgur.com/oWQ9c9p.png" title="source: imgur.com" />

3. Observe que a janela **Boot Dashboard** exibe a lista de projetos que foram criados dentro do STS (Por enquanto só temos o Hello World). 

4. Clique no Projeto **helloworld** (marcado em verde na imagem abaixo) e na sequência clique no ícone **Start / Restart** (marcado em amarelo na imagem abaixo) para executar o projeto.

   <div align="center"><img src="https://i.imgur.com/4VXoICV.png" title="source: imgur.com" /></div>
