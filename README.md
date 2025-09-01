# Projeto de Cadastro de Usuário

Este é um projeto simples de cadastro de usuário desenvolvido em Java para web, utilizando JSP, Spring MVC e Bootstrap.

## Funcionalidades

- Formulário de cadastro de usuário com os seguintes campos:
  - Nome
  - Sobrenome
  - E-mail
  - Senha
  - CEP
  - Rua
  - Bairro
  - Cidade
  - Estado
  - Número
  - Complemento
- Preenchimento automático dos campos de endereço (Rua, Bairro, Cidade e Estado) a partir do CEP informado, utilizando a API ViaCEP.
- Validação de formulário.

## Tecnologias Utilizadas

- **Backend:** Java, Spring MVC
- **Frontend:** JSP, HTML, CSS, JavaScript, Bootstrap
- **Servidor de Aplicação:** Apache Tomcat

## Como Executar o Projeto

1. **Clone o repositório:**
   ```bash
   git clone <url-do-repositorio>
   ```
2. **Importe o projeto em sua IDE de preferência (NetBeans, Eclipse, etc.).**
3. **Configure um servidor de aplicação (ex: Apache Tomcat).**
4. **Compile e execute o projeto no servidor.**
5. **Acesse a aplicação em seu navegador, geralmente em `http://localhost:8080/CadastroUsuario/`.**

## Estrutura do Projeto

- `src/main/java`: Contém os controladores e outras classes Java.
- `src/main/webapp`: Contém as páginas JSP, arquivos de configuração e recursos estáticos.
  - `WEB-INF/jsp/index.jsp`: Arquivo principal da aplicação.
  - `WEB-INF/web.xml`: Arquivo de configuração do servlet.
  - `WEB-INF/dispatcher-servlet.xml`: Arquivo de configuração do Spring MVC.
  - `WEB-INF/applicationContext.xml`: Arquivo de configuração do Spring.
- `pom.xml`: Arquivo de configuração do Maven para gerenciamento de dependências.
