<h1>Criando o 1º projeto no Spring Initializer</h1>

<br />

<h2>👣 Passo 01 - Criando uma nova Workspace no Spring Tool Suite (STS)</h2>

<br />

1) Abra o STS
2) No STS, clique no Menu **File 🡪 Switch Workspace 🡪 Other...**

<div align="center"><img src="https://i.imgur.com/NYX9Csu.gif" title="source: imgur.com" /></div>

3. No item **Workspace**, clique no botão **Browse...** e crie a pasta **spring** na **Área de Trabalho**, como mostra a animação abaixo.

<div align="center"><img src="https://i.imgur.com/FdwKDZf.gif" title="source: imgur.com" /></div>

4. Deixe marcada a opção **Preferences**, para copiar as configurações atuais do Eclipse/STS na nova Workspace. Clique no botão **Launch** para concluir.

<div align="center"><img src="https://i.imgur.com/iBImPhV.png" title="source: imgur.com" /></div>

5. Aguarde o Eclipse/STS reiniciar.
6. O Eclipse será inicializado sem nenhum projeto

<div align="center"><img src="https://i.imgur.com/wyK0RV0.png" title="source: imgur.com" /></div>

<br />

<h2>👣 Passo 02 - Configurando o Terminal do Spring Tool Suite (STS)</h2>

<br />

1) clique no Menu **Window 🡪 Preferences**
2) Na Guia **Terminal**, clique na opção **Local Terminal**
3) No item **Initial Working Directory**, selecione a opção **Eclipse Workspace**, como mostra a nimação abaixo:

<div align="center"><img src="https://i.imgur.com/XGohM3r.gif" title="source: imgur.com" /></div>

4. Clique no botão **Apply and Close** para concluir.

<br />

<h2>👣 Passo 03 - Abrindo o Spring Initializr no Spring Tool Suite (STS)</h2>

<br />

1) Para abrir o **Spring Initializer** no STS, clique no menu **File 🡪 New**, e clique na opção **Spring Starter Project**

<div align="center"><img src="https://i.imgur.com/XLRyeRq.png" title="source: imgur.com" /></div>

<br />

<h2>👣 Passo 04 - Setup do Projeto</h2>

<br />

<h3>Configurações iniciais</h3>

<br />

1. Configure o Projeto conforme a imagem abaixo:

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

2. Clique no botão **Next** para continuar.

<br />

**Dependências**

<br />

3. No Projeto Hello World vamos inserir 2 dependências, conforme mostra a figura abaixo:

<br />

<div align="center"><img src="https://i.imgur.com/cxUHXho.png" title="source: imgur.com" /></div>

<br />

4. Observe que quando esta imagem foi capturada, **a versão atual do Spring era 3.0.5**, conforme indicado na imagem. Hoje a versão atual do Spring pode ser outra.

<br />

| Dependência               | Descrição                                                    |
| ------------------------- | ------------------------------------------------------------ |
| **Spring Web**            | Fornece todas as Bibliotecas necessárias para trabalhar com o protocolo http. |
| **Spring Boot Dev Tools** | Permite a atualização do projeto em tempo real durante o processo de Desenvolvimento da aplicação. |

<br />

5. Clique no botão **Finish** para concluir.

<br />

<div align="center"> <h2>*** IMPORTANTE ***</h2></div>

Como é o primeiro projeto que você está criando no Spring, o processo de geração do projeto será um pouco lento, porquê será feito o download de diversos arquivos. Nos próximos projetos o processo será um pouco mais rápido.

Caso o projeto apresente algum erro no arquivo pom.xml, utilize o <b>Guia de correção do arquivo pom.xml</b> para corrigir o problema.



<h2>👣 Passo 05 - Codar!</h2>



Siga as instruções do seu Instrutor!



<h2>👣 Passo 06 - Executar o Projeto</h2>



1. No **STS**, abaixo da **Package Explorer**, está localizada a janela **Boot Dashboard**.

<div align="center"><img src="https://i.imgur.com/MNofI7p.png" title="source: imgur.com" /></div>

2. Caso ela não esteja visível, Na barra de ferramentas do STS, logo abaixo do menu **Search**, clique no ícone: <img src="https://i.imgur.com/oWQ9c9p.png" title="source: imgur.com" />

3. Observe que a janela **Boot Dashboard** exibe a lista de projetos que foram criados dentro do STS (Por enquanto só temos o Hello World). 

4. Clique no Projeto **helloworld** (marcado em verde na imagem abaixo) e na sequência clique no ícone **Start / Restart** (marcado em amarelo na imagem abaixo) para executar o projeto.

   <div align="center"><img src="https://i.imgur.com/4VXoICV.png" title="source: imgur.com" /></div>

<br />

<h2>👣 Passo 07 - Enviar o Projeto para o Github</h2>

<br />

1. Clique com o botão direito do mouse sobre a **pasta do projeto helloworld**. No menu que será aberto clique na opção **Show in Local Terminal 🡪 Git Bash**, como mostra a animação abaixo:

<div align="center"><img src="https://i.imgur.com/twV1Ljk.gif" title="source: imgur.com" /></div>

2. Será aberto o **Terminal Git Bash**, dentro da pasta do projeto. Antes de continuar, observe se a pasta selecionada no terminal está correta, semelhante a imagem abaixo:

<div align="center"><img src="https://i.imgur.com/oGJDBCE.png" title="source: imgur.com" /></div>

3. No **Git Bash**, digite o comando abaixo para criar o Repositório Local dentro da pasta **Worskspace do Eclipse/STS**.

```bash
git init
```

4. Digite o comando abaixo para adicionar o Projeto na **Stage Area** do Git:


```bash
git add .
```

5. Na sequência, faça o commit do Projeto, através do comando abaixo:

```bash
git commit -m "Projeto Hello World"
```

6. Acesse o seu **Github** e crie um novo **Repositório**, através da opção **New repository**.

7. Crie o **Repositório Remoto** chamado **spring_helloworld**.

8. Na próxima tela, copie o endereço **HTTPS do Repositório Remoto**, indicado na imagem abaixo:

<div align="center"><img src="https://i.imgur.com/qTlxToL.png" title="source: imgur.com" /></div>

9. Volte para o Git Bash e execute o comando abaixo para conectar o seu **Repositório Local** com o seu **Repositório Remoto**, onde o endereço **https**, será o endereço do seu **Repositório Remoto**.

```bash
git remote add origin https://github.com/rafaelq80/spring_helloworld.git
```

10. Digite o comando abaixo para checar se o seu  **Repositório Local** está conectado com o seu **Repositório Remoto**:

```bash
git remote -v
```

11. Na sequência, utilize o comando abaixo, para enviar o conteúdo do **Repositório Local** com o seu **Repositório Remoto**:

```bash
git push origin main
```

12. Volte para o Github, atualize a página do seu **Repositório Remoto** e verifique se ele está semelhante a imagem abaixo:

<div align="center"><img src="https://i.imgur.com/fFI1jOO.png" title="source: imgur.com" /></div>

<br />
