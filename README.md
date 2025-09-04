# Workshop Spring Boot 3 com JPA

**Workshop Spring Boot 3 com JPA** é um projeto criado durante o curso *"Java COMPLETO Programação Orientada a Objetos + Projetos"* da Udemy. O objetivo é demonstrar como aplicar Spring Boot 3 com JPA (Hibernate) para construir um serviço back-end robusto com operações CRUD e boa arquitetura.

## Tecnologias Utilizadas

- **Java 17+**
- **Spring Boot 3**
- **Spring Data JPA (Hibernate)**
- **Banco de dados H2** (em memória, para testes)
- **Maven** como ferramenta de build

## Funcionalidades Principais

- Modelagem de entidades JPA (como `User`, `Product`, `Order`)
- Repositórios Spring Data (interfaces `JpaRepository`)
- Camadas estruturadas: `resource` (controladores REST), `service`, `repository` :contentReference[oaicite:1]{index=1}
- CRUD completo: criar, listar, atualizar e excluir recursos (por exemplo, usuários, pedidos, produtos) :contentReference[oaicite:2]{index=2}
- Exposição de endpoints RESTful
- Tratamento de exceções personalizado

## Como Executar Localmente

### Pré-requisitos

- JDK 17 ou superior
- Maven 3+
- Git (opcional)

### Clonar o repositório

```bash
git clone https://github.com/rafaelpivacm/workshop-springboot3-jpa.git
cd workshop-springboot3-jpa
