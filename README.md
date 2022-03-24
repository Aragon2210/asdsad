# Turmas

Distributed Systems Project 2021/2022

**Group G28**

### Team Members

| Number | Name           | User                             | Email                                         |
|--------|----------------|----------------------------------|--------------------------------------------   |
| 95588  | Gustavo Simões | <https://github.com/ggfcsimoes1> | <mailto:gustavo.simoes@tecnico.ulisboa.pt>    |
| 95606  | João Aragonez  | <https://github.com/Aragon2210>  | <mailto:joao.aragonez@tecnico.ulisboa.pt>     |
| 95656  | Pedro Lynce    | <https://github.com/Plyncesilva> | <mailto:pedro.lynce.silva@tecnico.ulisboa.pt> |


## Prerequisites

The project was made on Java 17.0.2 and Maven 3.8.4

### Installation

To compile and install all modules:

```s
mvn clean install
```

## Running the program & command line arguments

The overall system is made up of several modules. The main server is the _ClassServer_. The clients are the _Student_,
the _Professor_ and the _Admin_. The definition of messages and services is in the _Contract_. The future naming server
is the _NamingServer_.

To run the project, open each module and execute them using `mvn compile exec:java`

ClassServer command line arguments:

- `-debug` (optional): mvn compile exec:java -Dexec.args="-debug"

Student command line arguments:

- `studentId studentName`: mvn compile exec:java -Dexec.args="studentId studentName"~

Admin command line arguments:

- `(no arguments)`: mvn compile exec:java

Professor command line arguments:

-``(no arguments)`: mvn compile exec:java

