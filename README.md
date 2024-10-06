# Lista de Tarefas - JavaFX Project

Este projeto é uma aplicação de Lista de Tarefas desenvolvida com **JavaFX** para a interface gráfica, integrando com um banco de dados para armazenamento das tarefas e utilizando uma API para comunicação entre o cliente e o servidor. O projeto inclui ainda o **deploy** em nuvem e implementação de um **pipeline CI/CD** para automatizar o processo de deploy.

## Funcionalidades

- **Adicionar Tarefas**: O usuário pode adicionar uma tarefa com um título, descrição e prazo.
- **Marcar como Concluída**: Possibilidade de marcar tarefas como concluídas.
- **Editar Tarefas**: O usuário pode editar as informações de uma tarefa existente.
- **Excluir Tarefas**: Remoção de tarefas da lista.
- **Listar Tarefas**: Visualização de todas as tarefas cadastradas no banco de dados, com status de concluída ou pendente.

## Tecnologias Utilizadas

### 1. **Frontend - JavaFX**
- **JavaFX**: Usado para criar a interface gráfica, possibilitando a interação do usuário com as tarefas.
- **FXML**: Utilizado para definir a interface visual de maneira estruturada.
- **Scene Builder**: Ferramenta para auxiliar no design das telas.

### 2. **Backend - API RESTful**
- **Spring Boot**: Framework para criar a API RESTful que processa as requisições de tarefas.
- **Java**: Linguagem principal para o desenvolvimento da lógica de negócio e API.
- **Banco de Dados**: Utilização de um banco de dados **MySQL** ou **PostgreSQL** para armazenamento das tarefas.

### 3. **Banco de Dados**
- **JDBC**: Usado para comunicação entre a aplicação Java e o banco de dados.
- **Hibernate (JPA)**: Ferramenta de mapeamento objeto-relacional (ORM) para gerenciar a persistência dos dados no banco de dados.

### 4. **Deploy e Pipeline**
- **Nuvem (AWS/Azure/GCP)**: Deploy da aplicação usando serviços de nuvem, como **Elastic Beanstalk** da AWS, **Heroku**, ou **Azure App Service**.
- **Docker**: Containerização da aplicação para facilitar o deploy.
- **CI/CD Pipeline**: Utilização de ferramentas como **GitHub Actions**, **Jenkins**, ou **GitLab CI** para automação do build, testes e deploy automático.

## Requisitos

Para executar a aplicação localmente, você precisará ter os seguintes componentes instalados:

- **Java 11+**
- **Maven** ou **Gradle**
- **MySQL/PostgreSQL** (ou outro banco de dados relacional)
- **Scene Builder** (para edição de interfaces FXML, opcional)
- **Git** (para versionamento)
- **Docker** (para deploy containerizado)
