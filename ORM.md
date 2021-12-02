# ORM

### ORM 이란?

Object Relational Mapping
RDBMS <-> OOP

- technique to query, manipulate data from a DB using OOP paradigm
- ORM usually is a library that implements the Object Relational Mapping techhnique.
- ORM Library = written in programming language that encapsulates the code needed to manipulate the data -> X need to use SQL anymore; Interact directly with an object in the same programming language that is being used.

### Pros of ORM

- Write the data model in only one place
  - easier to update, maintain, reuse the code
- Automation; DB handling -> I18N
- Utilizes MVC code -> cleaner code
- Sanitizing; uses prepared statements / trxns are as easy as calling a method.
- Good maintainability, reusability
- Additional Flexibility
  - Fits in with the natural way of coding
  - Abstracts the DB system -> change it whenever you want
  - Model is weakly bound to the rest of the system -> change it / use it anywhere else
  - Can use OOP techniques such as (data) inheritance.

### Cons of using ORM

- Additional complication
- Learning curve
- ORM libraries are not lightweight
- Setting up = problem
- Performance might be better if you are good at SQL (The performance could be better with better SQL techniques)
- Abstraction of DB

### Example Usage

- Map schema <-> Classes
- Use methods (functions) to write queries
- Fetch tables as an object
