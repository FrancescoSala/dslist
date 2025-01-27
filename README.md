# DSList

O **DSList** é um projeto desenvolvido durante o Intensivo Java Spring, realizado pela [Dev Superior](https://devsuperior.com.br) e ministrado pelo Dr. Prof. Nelio Alves. Este projeto tem como objetivo explorar o back-end de uma aplicação utilizando o framework Spring Boot e outras tecnologias relacionadas. O principal foco foi criar uma lista de jogos com a funcionalidade de reordenar os itens da lista, atualizando as posições também no banco de dados.

---

### 🚀 Funcionalidades
- Visualizar uma lista de jogos cadastrados.
- Mover itens da lista e atualizar automaticamente suas posições no banco de dados.

### 🛠️ Tecnologias Utilizadas
- **Java**: Linguagem de programação principal.
- **Spring Boot**: Framework para desenvolvimento do back-end.
- **SQL**: Linguagem para interação com o banco de dados.
- **Postgres**: Banco de dados relacional.
- **H2 Database**: Banco de dados em memória para testes.
- **Docker**: Para containerização da aplicação.
- **Railway**: Deploy da aplicação.
- **Postman**: Testes de requisições.
- **GitHub**: Controle de versão.
- **IntelliJ IDEA**: IDE utilizada para o desenvolvimento.

![image](https://github.com/user-attachments/assets/02487af8-1f9c-4f77-a401-019bed2105cf)


### 🏗️ Estrutura do Projeto
O projeto segue o padrão de arquitetura em camadas, organizando o código de forma a facilitar sua manutenção e escalabilidade. A estrutura do projeto inclui:
- **config**: Configurações gerais da aplicação.
- **controllers**: Pontos de entrada para as requisições.
- **dto**: Objetos de transferência de dados (Data Transfer Objects).
- **entities**: Classes representando as entidades do domínio (ex.: `Game` e `GameList`).
- **projections**: Consultas customizadas no banco de dados.
- **repositories**: Interfaces para acesso e manipulação dos dados no banco de dados.
- **services**: Contém as regras de negócio da aplicação.

**Resources:
- **application.properties**: Configurações gerais da aplicação.
- **application-dev.properties**: Configurações específicas para o ambiente de desenvolvimento.
- **application-prod.properties**: Configurações específicas para o ambiente de produção.
- **application-test.properties**: Configurações específicas para testes.

Com essa estrutura, a aplicação foi testada localmente, em homologação e em produção, sendo posteriormente implantada na nuvem.

![image](https://github.com/user-attachments/assets/861b6241-fe6e-42be-bdf6-c0b98dbdae26)

### 🖥️ Como Rodar o Projeto
1. Clone este repositório: `git clone https://github.com/FrancescoSala/dslist.git`
2. Certifique-se de ter o **Java JDK 17** ou superior instalado. Recomendo o 17 para evitar problemas com Railway.
3. Configure o banco de dados Postgres e atualize as credenciais no arquivo `application-dev.properties`.
4. Execute o projeto através da sua IDE ou utilizando o comando `mvn spring-boot:run`.
5. Acesse `http://localhost:8080` para verificar os endpoints.

---

### 🤝 Agradecimentos
Agradeço à toda equipe do DevSuperior, mas com uma menção especial ao Dr. Prof. Nelio Alves pela didática ímpar. Cheguei a comentar com amigos que ele "conseguiria ensinar um pato a programar em Java".
