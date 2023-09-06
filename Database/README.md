# Database
Provides a base database to consume, the database must have a volume for persistence. All the values of the database must be defaulted, except for password and database.

```
PASSWORD=secret
DATABASE_NAME=data
```

## Available databases:
<hr>
<details>
<summary><b>MySQL</b></summary>
Connection settings:

```
url: jdbc:mysql://localhost:3306/data
username: root
password: secret
```
</details>
<hr>
<details>
<summary><b>PostgreSQL</b></summary>
Connection settings:

```
url: jdbc:postgresql://localhost:5432/data
username: postgres
password: secret
```
</details>
<hr>