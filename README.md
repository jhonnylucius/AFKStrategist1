# 🚀 Iniciando um Projeto Spring Boot do Zero</BR>
</BR>
📋 Visão Geral</BR>
</BR>
Este guia vai te ajudar a iniciar um projeto Spring Boot do zero, configurar as ferramentas necessárias e preparar o ambiente de desenvolvimento para começar a codificar. Vamos passar por cada etapa, desde a criação do projeto até a instalação das ferramentas essenciais, como Java, PostgreSQL, Docker, Angular, entre outras.</BR>
</BR>


## 🔧 Tecnologias Utilizadas

### 1. <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/java/java-original.svg" width="40px"/> **Java**
Java é a linguagem de programação principal usada no desenvolvimento do backend do projeto.

---

### 2. <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/spring/spring-original.svg" width="40px"/> **Spring Framework**
Spring é um framework que facilita o desenvolvimento de aplicativos Java, especialmente os baseados em web.

---

### 3. <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/postgresql/postgresql-original.svg" width="40px"/> **PostgreSQL**
PostgreSQL é o banco de dados utilizado para armazenar as informações da aplicação de forma segura e eficiente.

---

### 4. <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/angularjs/angularjs-original.svg" width="40px"/> **Angular**
Angular é o framework utilizado para o desenvolvimento da interface gráfica (frontend) do projeto.

---

### 5. <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/nodejs/nodejs-original.svg" width="40px"/> **Node.js**
Node.js é usado para executar o Angular e gerenciar pacotes no projeto frontend.

---

### 6. <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/docker/docker-original.svg" width="40px"/> **Docker**
Docker é utilizado para criar containers que isolam o ambiente de desenvolvimento, facilitando a portabilidade e escalabilidade do sistema.

---

### 7. <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/intellij/intellij-original.svg" width="40px"/> **IntelliJ IDEA**
IntelliJ IDEA é a IDE principal usada para desenvolvimento do backend Java com o framework Spring.

---

### 8. <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/vscode/vscode-original.svg" width="40px"/> **Visual Studio Code**
VS Code é a IDE usada para o desenvolvimento frontend com Angular e edição de arquivos de configuração do projeto.

---

### 9. <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/linux/linux-original.svg" width="40px"/> **WSL (Windows Subsystem for Linux)**
O WSL é utilizado para rodar o ambiente Linux diretamente no Windows, proporcionando melhor compatibilidade com Docker e outras ferramentas Linux.

---

### 10. <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/amazonwebservices/amazonwebservices-original-wordmark.svg" width="40px"/> **AWS S3**
O AWS S3 é o serviço de armazenamento de objetos da Amazon, utilizado para armazenar imagens e outros arquivos da aplicação.

---

### 11. <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/github/github-original.svg" width="40px"/> **GitHub**
GitHub é a plataforma usada para versionamento de código, facilitando o trabalho colaborativo e o gerenciamento do código-fonte.

---

### 12. <img src="https://avatars.githubusercontent.com/u/44036562?s=200&v=4" width="40px"/> **GitHub Actions**
GitHub Actions é usado para configurar o CI/CD (integração contínua e entrega contínua), automatizando o processo de build, testes e deploy.

---

### 13. <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/googlecloud/googlecloud-original.svg" width="40px"/> **Google Cloud**
Google Cloud é a plataforma de nuvem onde o aplicativo será implantado, proporcionando escalabilidade e recursos de infraestrutura.

---

</BR>
🔧 Preparando o Projeto Spring Boot</BR>
</BR>
1. Acesse o Spring Initializr
</BR>
Configuração do Projeto Maven</BR>
</BR>
Você será direcionado para a tela abaixo, onde deve configurar o projeto. Escolha a linguagem Java, o tipo de projeto Maven, e as dependências principais como Spring Web, Spring Data JPA, Lombok, e outras que precisar.
</BR>

Dependências principais a serem selecionadas:</BR>

Spring Web: Para criar APIs RESTful e aplicações web com o Spring MVC.</BR>

Spring Data JPA: Para facilitar a integração com o banco de dados relacional usando JPA/Hibernate.</BR>

Spring Security: Para adicionar segurança e controle de autenticação e autorização.</BR>

Spring Thymeleaf: Para renderizar views HTML no lado do servidor com o motor de templates Thymeleaf.</BR>

Spring Actuator: Para monitorar e gerenciar sua aplicação em produção.</BR>

PostgreSQL Driver: Para conectar sua aplicação ao banco de dados PostgreSQL.</BR>

Lombok: Para reduzir o código boilerplate (como getters, setters, e constructors).</BR>

Spring Boot DevTools: Para melhorar a experiência de desenvolvimento com auto-reload de código.</BR>

Spring Boot Docker Compose: Para gerenciar containers Docker diretamente do Spring Boot.</BR>

Spring Security Test: Para realizar testes de integração focados em segurança.</BR>

Spring Boot Starter Test: Para suporte de testes unitários e de integração.</BR>

Essas dependências garantem que você tenha todos os recursos necessários para desenvolver uma aplicação Java moderna, robusta e escalável, integrando segurança, banco de dados e templates de interface com a facilidade do Spring Boot. </br>
</br>

<a href="https://start.spring.io/" target="_blank"><img src="(coloque-o-caminho-da-imagem-aqui)" alt="Spring Initializr" style="border:1px solid gray;"/></a>
</br>
</BR>
2. Configuração Básica</BR>
</BR>
Após selecionar as configurações, clique em Gerar. Isso fará o download de um arquivo .zip contendo seu projeto Spring Boot.</BR>
</BR>
Dica: Por enquanto, deixe o arquivo baixado no seu diretório local. Vamos primeiro instalar todas as ferramentas necessárias.</BR>
</BR>
🚀 Instalando as Ferramentas Essenciais</BR>
</BR>
3. Java Development Kit (JDK) 17</BR>
</BR>
Baixe e instale o JDK 17 do site oficial.</BR>
</BR>
Configuração da variável de ambiente: Certifique-se de que a variável JAVA_HOME está configurada corretamente no sistema.
</BR>
📚 Documentação da API Java 17 ao final
</BR>

4. IntelliJ IDEA ou VS Code</BR>
</BR>
Você pode escolher entre usar o IntelliJ IDEA ou o Visual Studio Code (VS Code) como sua IDE.</BR>

</BR>
🖥️ IntelliJ IDEA
</BR>
Baixe a versão Ultimate se for estudante (grátis com a conta acadêmica).</BR>
</BR>
📚 Documentação IntelliJ IDEA</BR>
🖥️ Visual Studio Code</BR>
</BR>
Baixe o VS Code do site oficial.
</BR>
📚 Documentação do VS Code ao final</BR>
</BR>
5. PostgreSQL</BR>
</BR>
Baixe e instale a última versão do PostgreSQL.
</BR>
📚 Documentação Oficial PostgreSQL ao final</BR>
</BR>
🚀Ferramentas de Administração para PostgreSQL:</BR>
</BR>
pgAdmin
</BR>
DataGrip
</BR>
🚀6. Docker Desktop</BR>
</BR>
🚀Baixe e instale o Docker Desktop, que já inclui o Docker Compose. Certifique-se de que o WSL está habilitado se estiver no Windows.</BR>
</BR>

🚀Configurando o WSL</BR>
</BR>
O WSL (Windows Subsystem for Linux) é necessário para melhorar a performance e permitir que você execute containers Linux diretamente no ambiente Windows. Aqui estão os passos para configurá-lo:</BR>

🚀Baixe e instale o Docker Desktop.</BR>
</BR>
Durante a instalação, habilite o WSL2.</BR>
</BR>
O Docker Desktop detectará automaticamente o WSL e configurará o ambiente.
</BR>
Vantagens:</BR>
</BR>
Melhor performance no desenvolvimento.</BR>
</BR>
Integração com o sistema operacional Windows.</BR>
</BR>
Interface gráfica amigável para gerenciamento de containers.</BR>
</BR>
📚 Documentação Docker Desktop para WSL ao final
</BR>
🚀7. Angular e Node.js</BR>
</BR>
O Angular será instalado mais tarde, mas você pode preparar o ambiente agora:
</BR>
Instale o Node.js do site oficial (versão LTS recomendada).
</BR>
Verifique se o npm foi instalado corretamente:
</BR>
bash
Copiar código
node -v
npm -v
Instale o Angular CLI globalmente:
</BR>
bash
Copiar código
npm install -g @angular/cli

</BR>
📚 Documentação Angular ao final
</BR>
📦 Checklist de Configuração Inicial</BR>
 🚀Instale o Java 17 e configure as variáveis de ambiente.</BR>
🚀 Instale sua IDE de preferência.</BR>
🚀 Instale o PostgreSQL.</BR>
🚀 Instale o Docker Desktop e habilite o WSL.</BR>
 🚀Instale o Angular, Node.js e npm.</BR>
🚀Crie o repositório do projeto no GitHub e adicione um .gitignore e a licença MIT.</BR>
🚀 Extraia o arquivo .zip do Spring Initializr na pasta local do projeto.</BR>
 🚀Abra o projeto na sua IDE.</BR>
🚀 Publique o projeto no GitHub.</BR>
</BR>
🎉 Parabéns!</BR>
Seu ambiente de desenvolvimento está pronto para começar a trabalhar no backend com Spring Boot, PostgreSQL e Docker! Agora você pode começar a codificar com um ambiente bem configurado e pronto para escalar.
</BR>
Aqui estão os links de documentação para as tecnologias e ferramentas mencionadas no README do seu projeto:

---

### 📚 Documentação das Dependências:

1. **[Spring Web](https://docs.spring.io/spring-framework/docs/current/reference/html/web.html)**
   - Para criar APIs RESTful e aplicações web com Spring MVC.

2. **[Spring Data JPA](https://docs.spring.io/spring-data/jpa/docs/current/reference/html/)**
   - Para facilitar a integração com bancos de dados relacionais usando JPA e Hibernate.

3. **[Spring Security](https://docs.spring.io/spring-security/site/docs/current/reference/html5/)**
   - Para adicionar segurança e controle de autenticação e autorização na sua aplicação.

4. **[Thymeleaf](https://www.thymeleaf.org/doc/tutorials/3.0/usingthymeleaf.html)**
   - Para renderização de páginas HTML no lado do servidor com o motor de templates Thymeleaf.

5. **[Spring Actuator](https://docs.spring.io/spring-boot/docs/current/reference/html/actuator.html)**
   - Para monitorar e gerenciar sua aplicação em produção.

6. **[PostgreSQL JDBC Driver](https://jdbc.postgresql.org/documentation/head/)**
   - Para conectar sua aplicação ao banco de dados PostgreSQL.

7. **[Lombok](https://projectlombok.org/features/all)**
   - Para reduzir o código boilerplate, como getters, setters, e construtores automáticos.

8. **[Spring Boot DevTools](https://docs.spring.io/spring-boot/docs/current/reference/html/using.devtools.html)**
   - Para acelerar o desenvolvimento com auto-reload e outras ferramentas úteis.

9. **[Spring Boot Docker Compose](https://docs.spring.io/spring-boot/docs/current/reference/htmlsingle/#features.docker.compose)**
   - Para gerenciar containers Docker diretamente a partir da aplicação Spring Boot.

10. **[Spring Boot Starter Test](https://docs.spring.io/spring-boot/docs/current/reference/html/features.html#features.testing)**
    - Suporte para testes de unidade e integração no Spring Boot.

11. **[Spring Security Test](https://docs.spring.io/spring-security/site/docs/current/reference/html5/#test)** 
    - Para testes específicos de segurança com Spring Security.

---

### 📚 Documentação das Ferramentas Utilizadas:

1. **[Java 17](https://docs.oracle.com/en/java/javase/17/docs/)**
   - Documentação da API Java SE 17.

2. **[Spring Framework](https://spring.io/projects/spring-framework)**
   - Página oficial do Spring Framework.

3. **[PostgreSQL](https://www.postgresql.org/docs/current/)**
   - Documentação completa do PostgreSQL.

4. **[Angular](https://angular.io/docs)**
   - Documentação oficial do Angular.

5. **[Node.js](https://nodejs.org/en/docs/)**
   - Documentação oficial do Node.js.

6. **[Docker](https://docs.docker.com/)**
   - Documentação oficial do Docker.

7. **[IntelliJ IDEA](https://www.jetbrains.com/idea/documentation/)**
   - Documentação da IDE IntelliJ IDEA.

8. **[Visual Studio Code](https://code.visualstudio.com/docs)**
   - Documentação oficial do Visual Studio Code.

9. **[WSL (Windows Subsystem for Linux)](https://learn.microsoft.com/en-us/windows/wsl/)**
   - Guia de instalação e documentação oficial do WSL.

10. **[AWS S3](https://docs.aws.amazon.com/s3/index.html)**
    - Documentação oficial do Amazon S3.

11. **[GitHub](https://docs.github.com/en)**
    - Documentação oficial do GitHub.

12. **[GitHub Actions](https://docs.github.com/en/actions)**
    - Documentação oficial do GitHub Actions.

13. **[Google Cloud](https://cloud.google.com/docs)**
    - Documentação oficial do Google Cloud.

---

Com esses links, você terá todas as documentações oficiais das ferramentas e dependências usadas no seu projeto. Isso ajudará tanto você quanto qualquer colaborador a entender melhor cada tecnologia e como configurá-las adequadamente.

# 🖥️ O PROJETO

# ProjectAFKStrategist
Projeto para praticar programação em java e integrações de serviços e tecnologias, usando a criação de um app para a Comunidade de Jogadores do jogo AFK Arena.

# AFKStrategist

AFKStrategist é uma aplicação que permite aos membros da guilda gerenciar e analisar heróis, configurar suas equipes e realizar outras operações offline após o primeiro download. Este projeto é desenvolvido usando Spring Boot para o backend, MariaDB na Cloud Cluster sendo nosso banco de dados e Amazon S3 para armazenamento de imagens.

## 📋 Descrição

AFKStrategist foi projetado para ser uma ferramenta robusta que facilita a gestão de heróis e configurações de usuários. Ele oferece a capacidade de operar offline após um download inicial, garantindo que as informações estejam sempre disponíveis para os usuários, mesmo sem conexão com a internet.

## 🛠️ Funcionalidades

- **Gerenciamento de Heróis**: Visualização e configuração dos heróis disponíveis.
- **Sincronização Offline**: Primeiro download completo de dados, permitindo o uso offline.
- **Armazenamento Seguro**: Uso de Amazon S3 para armazenar e recuperar imagens de heróis.
- **Conexão com Banco de Dados**: Integração com MariaDB para persistência de dados.
- **Configuração de Equipes**: Interface para configurar equipes de heróis.
- **Integração com Google Cloud**: Deploy do backend e frontend utilizando Google Cloud.

## 📝 Requisitos

Antes de começar, certifique-se de que você atenda aos seguintes requisitos:

- **Java 17** (ou superior)
- **Maven** (para gerenciar dependências do projeto)
- **Node.js & npm** (para o frontend Angular)
- **Docker & Docker Compose** (para containerizar a aplicação)
- **Conta no Amazon S3** (para armazenamento de imagens)
- **Conta no Google Cloud** (para deploy)

## 🚀 Instalação

1. **Clone o Repositório:**

   ```bash
   git clone https://github.com/seu-usuario/afkstrategist.git
   cd afkstrategist

   Backend - Spring Boot:

Navegue até o diretório do backend:</br>
</br>
cd backend
</br>
Compile o projeto:
</br>
mvn clean install
</br>
Execute a aplicação:
</br>
mvn spring-boot:run
</br>
Frontend - Angular:
</br>
Navegue até o diretório do frontend:</br>
</br>
cd frontend</br>
</br>
Instale as dependências:
</br>
npm install</br>
</br>
Inicie o servidor de desenvolvimento:
</br>
ng serve</br>
Banco de Dados - PostegreSql:

Use Docker para iniciar o banco de dados:</br>

docker-compose up -d</br>
</br>
Verifique a conexão com o banco de dados.
</br>
🔧 Configuração
</br>
1. Variáveis de Ambiente
</br>
Configure as seguintes variáveis de ambiente no seu sistema:</br>
</br>
DB_APP_USER: Usuário do banco de dados.</br>
DB_APP_PASSWORD: Senha do usuário do banco de dados.</br>
AWS_ACCESS_KEY_ID: Chave de acesso para o S3.</br>
AWS_SECRET_ACCESS_KEY: Chave secreta para o S3.</br>
SPRING_DATASOURCE_URL: URL do banco de dados.</br>
SPRING_DATASOURCE_USERNAME: Nome de usuário do banco de dados.</br>
SPRING_DATASOURCE_PASSWORD: Senha do banco de dados.</br>
</br>
2. Arquivo application.properties</br>
</br>
Certifique-se de que o arquivo application.properties no backend contenha as configurações corretas para o banco de dados e S3.
</br>
properties
</br>
spring.datasource.url=${SPRING_DATASOURCE_URL}
spring.datasource.username=${SPRING_DATASOURCE_USERNAME}
spring.datasource.password=${SPRING_DATASOURCE_PASSWORD}
cloud.aws.credentials.access-key=${AWS_ACCESS_KEY_ID}
cloud.aws.credentials.secret-key=${AWS_SECRET_ACCESS_KEY}
cloud.aws.region.static=sa-east-1
cloud.aws.s3.bucket=afk-union-app-images
💻 Uso
Acesse o Frontend:

Abra seu navegador e vá para http://localhost:4200.
Acesse o Backend:

O backend estará disponível em http://localhost:8080/api.
Testando Conexões:

Use ferramentas como Postman para testar os endpoints do backend.
Verifique se as operações de upload/download no S3 estão funcionando corretamente.
</br>
🗂️ Estrutura do Projeto
plaintext</br>
Copiar código</br>
AFKStrategist/</br>
│</br>
├── backend/</br>
│   ├── src/</br>
│   ├── pom.xml</br>
│   └── Dockerfile</br>
│</br>
├── frontend/</br>
│   ├── src/</br>
│   ├── angular.json</br>
│   └── Dockerfile</br>
│</br>
├── docker-compose.yml</br>
└── README.md</br>
🤝 Contribuição</br>
Se você deseja contribuir com este projeto, siga as etapas abaixo:</br>

Fork o repositório.
Crie um branch para suas alterações (git checkout -b feature/nova-funcionalidade).
Commit suas mudanças (git commit -m 'Adiciona nova funcionalidade').
Push para o branch (git push origin feature/nova-funcionalidade).
Abra um Pull Request.
📄 Licença
Este projeto está licenciado sob os termos da licença MIT. Veja o arquivo LICENSE para mais detalhes.

💬 Agradecimentos

A Rafael e Leonardo por terem topado esse desafio de aprendizado e crescimento na área da programação, Analise e Desenvolvimento de Sistemas.
