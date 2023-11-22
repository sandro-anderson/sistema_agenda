```mermaid
classDiagram
  class User {
    + ID
    + Name
    + Email
    + Password
    + Tasks[]
    + Notifications[]
    + LogIn()
    + Register()
    + AddTask()
    + EditTask()
    + DeleteTask()
  }

  class Task {
    + ID
    + Title
    + Description
    + DueDate
    + Priority
    + Status
    + User
  }

  class Notification {
    + ID
    + Message
    + DateTime
    + Recipient
  }

  User --|> Task
  User --|> Notification
  Task --|> User

```


# sistema_agenda
Registro de testes

![print01](https://github.com/sandro-anderson/sistema_agenda/assets/102873267/7cc77a1c-7627-47bd-b152-98b3f5478b59)

![print02](https://github.com/sandro-anderson/sistema_agenda/assets/102873267/dc1b5677-3fc1-49a6-9194-63a2dd7b28bc)



Projeto Criado para compor a nota da disciplina Teste de Software - Nele usamos CRUD/NODE.JS/PRISMA/SQLITE E JEST. Projeto de sistema de agendas com criação, edição e delete de tarefas. 


Integrantes: 
- José Lenildo ferreira da Silva 
- Gabriel da Silva Freire
- João Luiz Silva
- Sandro Anderson Neris dos Santos
- Moisés Vitor de Araújo candido

Link para a planilha de testes: https://docs.google.com/spreadsheets/d/1fJ8f296Frf-cGcgumA1WW1NNCRdwQ0ctOtE-yDC7zvk/edit?usp=sharing
