<h1 align="center" style="font-weight: bold;">Sistema de Login com JWT 💻</h1>

<p align="center">
    <b>Este é um sistema de autenticação e autorização desenvolvido com Java e Spring Boot, utilizando Spring Security e JWT (JSON Web Token) para gerenciar o login seguro dos usuários. Ao fazer login, um token de acesso é gerado para validar as solicitações subsequentes.</b>
</p>

<h2 id="technologies">💻 Tecnologias</h2>

- Java
- Spring Boot
- Spring Web
- Spring Security
- JPA
- H2 Database
- Lombok


<h2 id="started">🚀 Iniciando o projeto</h2>
<h3>Pré Requisitos</h3>
- [Java](https://github.com/)

<h3>Clonando</h3>

```bash
git clone https://github.com/hendrickm97/login-system.git
```
<h3>Navegue até o diretório</h3>

```bash
cd nome-do-repositorio
```

-Executando Projeto:

```bash
mvn spring-boot:run
```
<h2 id="routes">📍 API Endpoints</h2>
​
<h3 id="get-auth-detail">POST /auth/ register</h3>
Nessa rota iremos cadastrar novos usuários.

**REQUEST**

```json
{
  "name": "Jon Doe",
  "email": "test@email.com",
  "password": "**************"
}
```

**RESPONSE**

```json
{
  "name": "Jon Doe",
  "token": "************************"
}
```


<h3 id="get-auth-detail">POST/auth/login</h3>

**REQUEST**

```json
{
  "email": "test@email.com",
  "password": "**************"
}
```
**RESPONSE**

```json
{
  "name": "Jon Doe",
  "token": "************************"
}
```




