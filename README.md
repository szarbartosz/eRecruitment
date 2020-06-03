# eRekrutacja

[![Maven badge](https://img.shields.io/badge/Maven-4.0.0-red)](https://maven.apache.org)
[![Lombok badge](https://img.shields.io/badge/Project_Lombok-1.18.12-green)](https://mvnrepository.com/artifact/org.projectlombok/lombok)
[![Hibernate badge](https://img.shields.io/badge/Hibernate-5.4.13-yellow)](https://mvnrepository.com/artifact/org.hibernate/hibernate-core)
[![PostgreSql badge](https://img.shields.io/badge/PostgreSQL-42.2.12-%2346A9EE)](https://mvnrepository.com/artifact/org.postgresql/postgresql)

## Krótki opis

Serwer obsługujący bazę danych do zarządzania procesem e-rekrutacji na studia magisterskie.

## Diagram bazy danych
![diagram](https://github.com/szarbartosz/eRecruitment/blob/master/diagram.png)

## Struktura projektu
```
  .
  ├── controller                              # Klasy odpowiadające za REST API
  │   ├── AuthenticationController.java
  │   ├── config                              # Konfiguracja zwracanych JSONów
  │   │   ├── StandardResponse.java
  │   │   └── Status.java
  │   ├── Controller.java
  │   ├── ExamController.java
  │   ├── FacultyController.java
  │   ├── FieldController.java
  │   ├── RecruitmentController.java
  │   └── StudentController.java
  ├── dao                                     # Metody odpowiedzialne za komunikację z bazą danych
  │   ├── SessionFactoryDecorator.java        
  │   ├── StudentDao.java                     # Metody po stronie aplikanta
  │   └── UniversityDao.java                  # Metody po stronie uczelni
  ├── Main.java
  └── model                                   # Model danych
      ├── Address.java
      ├── Candidate.java
      ├── Exam.java
      ├── Faculty.java
      ├── Field.java
      └── Student.java
```
## Kontrybutorzy :poland: :onion:
<table>
  <tr>
    <td align="center"><a href="https://github.com/szarbartosz"><img src="https://avatars3.githubusercontent.com/u/48298481?s=400&u=f61ccb0f734a51dc2a1115e6478839be62cb2216&v=4" width="100px;" alt=""/><br /><sub><b>Bartosz Szar</b></sub></a><br /></td>
    <td align="cefix fixanter"><a href="https://github.com/kraleppa"><img src="https://avatars1.githubusercontent.com/u/56135216?s=460&u=359e017d16c70a31d3bdb086172308cc6f045acf&v=4" width="100px;" alt=""/><br /><sub><b>Krzysztof Nalepa</b></sub></a><br />
    </td>
  </tr>
</table>


