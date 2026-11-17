# Java OOP Lab Sheet 09 — MCA203P

Solutions to all 30 exercises from Lab Sheet 09: Object Oriented Programming Using Java.

## Requirements
- JDK 17 or newer (JDK 21 recommended)
- No external libraries required

## Run any question
Each question is in its own folder and has one public Java class. Open a terminal in that folder:

```bash
javac ClassName.java
java ClassName
```

For example:

```bash
cd Q01_ArrayListPrint
javac ArrayListPrint.java
java ArrayListPrint
```

## Folder index
| Folder | Exercise |
|---|---|
| Q01–Q09 | ArrayList operations |
| Q10–Q13 | LinkedList operations |
| Q14–Q16 | HashSet operations |
| Q17–Q18 | TreeSet operations |
| Q19 | LinkedHashSet insertion order |
| Q20 | Compare HashSet, LinkedHashSet and TreeSet |
| Q21–Q23 | PriorityQueue operations |
| Q24–Q25 | Queue interface operations |
| Q26 | Custom Student objects and Iterator |
| Q27 | Sort custom Student objects using Comparator |
| Q28 | Convert List to Set |
| Q29 | Convert Set to List |
| Q30 | Clear List, Set and Queue |

## OOP concepts
- **Encapsulation:** The `Student` classes in Q26 and Q27 keep fields private and expose getters.
- **Classes and objects:** Every exercise uses classes and creates collection objects.
- **Abstraction / polymorphism:** Several programs use interface references such as `List`, `Set`, and `Queue` while storing concrete implementations such as `ArrayList`, `HashSet`, and `LinkedList`.
- **Generics:** Collections specify element types, for example `ArrayList<Integer>` and `List<Student>`.

## Important observations
- `HashSet` does not guarantee iteration order.
- `LinkedHashSet` maintains insertion order.
- `TreeSet` stores elements in sorted order.
- A `PriorityQueue` displays its internal arrangement when printed; use repeated `poll()`/`remove()` to observe priority order.
- `peek()` reads the queue head without removing it.
- A `Set` removes duplicates according to equality rules.
