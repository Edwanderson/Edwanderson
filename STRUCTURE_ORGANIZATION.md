```textplan
  mf-auth-app/
          ├── .github/
          │   ├── ISSUE_TEMPLATE/
          │   │   ├── bug_report.md
          │   │   └── feature_request.md
          │   ├── PULL_REQUEST_TEMPLATE.md
          │   ├── RELEASE_TEMPLATE.md
          │   └── workflows/
          │       └── ci.yml    # Arquivo do fluxo de trabalho de CI/CD no GitHub Actions
          ├── docs/
          │   ├── README.md
          │   ├── CHANGELOG.md
          │   ├── CONTRIBUTING.md
          │   ├── CODE_OF_CONDUCT.md
          │   ├── LICENSE.md
          │   └── SUPPORT.md
          ├── repository-app/
          │   ├── pom.xml        # Arquivo de configuração do Maven
          │   └── src/
          │       └── main/
          │           └── java/
          │               └── com.example.mfauth/
          │                   ├── controller/      # Camada de controle (Controllers)
          │                   ├── service/         # Camada de serviço (Serviços)
          │                   ├── repository/      # Camada de persistência (Repositories)
          │                   ├── model/           # Modelos de dados (Entidades)
          │                   └── config/          # Configurações do projeto (Spring, segurança, etc.)
          │           └── resources/
          │               ├── application.properties  # Configurações do Spring Boot
          │               ├── static                 # Arquivos estáticos (JS, CSS, imagens)
          │               ├── templates              # Templates (ex: Thymeleaf)
          │               └── db                      # Scripts SQL ou arquivos de configuração de banco de dados
          └── .gitignore       # Arquivo que lista arquivos/diretórios a serem ignorados pelo Git

Organização (ex: 2BoxLab)
├── spring-boot-auth         # Nome do repositório
│   ├── .github
│   │   ├── ISSUE_TEMPLATE   # Modelos de issues (bug, feature request, etc.)
│   │   ├── PULL_REQUEST_TEMPLATE.md  # Template para pull requests
│   │   ├── RELEASE_TEMPLATE.md       # Template para releases
│   │   └── workflows           # Fluxos de trabalho para GitHub Actions (CI/CD)
│   ├── docs
│   │   ├── README.md           # Documento principal explicando o projeto
│   │   ├── CHANGELOG.md        # Histórico de mudanças
│   │   ├── CONTRIBUTING.md     # Guia de contribuição
│   │   ├── CODE_OF_CONDUCT.md  # Código de conduta
│   │   ├── LICENSE.md          # Licença do projeto
│   │   ├── SUPPORT.md          # Informações de suporte
│   │   ├── SECURITY.md         # Informações de segurança
│   ├── src
│   │   ├── main
│   │   │   ├── java
│   │   │   │   ├── com.example.auth
│   │   │   │   │   ├── controller    # Contém os controllers do Spring
│   │   │   │   │   ├── service       # Lógica de negócio
│   │   │   │   │   ├── repository    # Interfaces para interação com DB
│   │   │   │   │   ├── model         # Modelos de entidades
│   │   │   │   │   └── config        # Configurações do Spring Boot
│   │   │   ├── resources
│   │   │   │   ├── application.properties  # Arquivo de propriedades
│   │   │   │   ├── static         # Arquivos estáticos (JS, CSS, imagens, etc.)
│   │   │   │   └── templates      # Templates Thymeleaf (se necessário)
├── outro-projeto
│   ├── .github
│   ├── docs
│   └── src
└── mais-projetos...


```
