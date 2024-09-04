# 🚀 Iniciando um Projeto Spring Boot do Zero</BR>
</BR>
📋 Visão Geral</BR>
</BR>
Este guia vai te ajudar a iniciar um projeto Spring Boot do zero, configurar as ferramentas necessárias e preparar o ambiente de desenvolvimento para começar a codificar. Vamos passar por cada etapa, desde a criação do projeto até a instalação das ferramentas essenciais, como Java, PostgreSQL, Docker, Angular, entre outras.</BR>
</BR>
🛠️ Tecnologias Utilizadas</BR>
</BR>
<p align="center"> <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/java/java-original.svg" width="50px" alt="Java"/> <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/spring/spring-original.svg" width="50px" alt="Spring Boot"/> <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/postgresql/postgresql-original.svg" width="50px" alt="PostgreSQL"/> <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/docker/docker-original.svg" width="50px" alt="Docker"/> <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/angularjs/angularjs-original.svg" width="50px" alt="Angular"/> <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/nodejs/nodejs-original.svg" width="50px" alt="Node.js"/> <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/intellij/intellij-original.svg" width="50px" alt="IntelliJ"/> <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/vscode/vscode-original.svg" width="50px" alt="VS Code"/> </p></BR>
</BR>
🔧 Preparando o Projeto Spring Boot</BR>
</BR>
1. Acesse o Spring Initializr
</BR>
Você será direcionado para a tela abaixo, onde deve configurar o projeto. Escolha a linguagem Java, o tipo de projeto Maven, e as dependências principais como Spring Web, Spring Data JPA, Lombok, e outras que precisar.
</BR>
<img src="/mnt/data/image.png" alt="Spring Initializr" style="border:1px solid gray;"/>
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
📚 Documentação da API Java 17
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
📚 Documentação do VS Code</BR>
</BR>
5. PostgreSQL</BR>
</BR>
Baixe e instale a última versão do PostgreSQL.
</BR>
📚 Documentação Oficial PostgreSQL</BR>
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
📚 Documentação Docker Desktop para WSL
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
📚 Documentação Angular
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
Banco de Dados - MariaDB:

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
