# OBE-based-Bloom-Taxonomy-Developing-Questions
# Software Design – Question Paper (OBE-based)

**Course:** Software Engineering
**Topic:** Software Design (source: lecture slides *4-SoftEng-Design*, 155 slides)
**Full Marks:** 40 | **Time:** 1 Hour
**Level:** Bachelor (BNQF Level 6)
**Cognitive domain (Bloom's Taxonomy):** C1 – Knowledge, C2 – Understanding

---

## 1. Analysis of the Lecture Slides

All 155 slides were read and grouped by topic. Three things decided the importance of a topic:

- **Lecture structure.** Slide 109 is a divider titled "More topics on Software Design". Everything after it (slides 110–146) is the instructor's own extension material, and the user interface design chapter (slides 147–155) comes last as a separate chapter. The main body is therefore slides 1–108.
- **Share of the main body.** The number of slides a topic gets.
- **Depth.** Whether the topic has a formal definition, a structure, benefits and liabilities, or a worked example, because such topics give clear C1/C2 questions.

### 1.1 Main body (slides 1–108): the topics questions are drawn from

| Topic | Slides | Share of main body | Depth |
|---|---|---|---|
| GoF design patterns (slides 40–80) | 41 | 38% | Six patterns, each with intent, structure, benefits and liabilities |
| Enterprise Application Architecture patterns (slides 81–108) | 28 | 26% | Domain Model, ORM, Data Mapper, inheritance mapping, MVC and web controllers; pros and cons for inheritance mapping |
| Design quality and CK metrics (slides 15–29) | 15 | 14% | Formal definitions, formulas and worked examples: CBO, LCOM, LCOM2, WMC |
| Design fundamentals (slides 2–14) | 13 | 12% | Design process, modularity, coupling, cohesion, abstraction; foundation of every later topic |
| Architectural styles (slides 30–39) | 10 | 9% | Layered, event-based, MVC, blackboard, pipes and filters; MVC appears again in slide 104 |

### 1.2 Which GoF patterns (main body)

Ranked by slide count: Composite (7), Adapter (6), Facade (6), then Strategy, Template Method and Command (5 each). The top three are selected: **Composite, Adapter, Facade**.

### 1.3 Not used for questions

| Material | Slides | Reason |
|---|---|---|
| "More topics" divider and its content: LCOM3, RFC, DIT, NOC, Factory Method, Prototype, Singleton, Decorator, Observer | 109–146 | Marked by the lecture itself as extra material |
| User interface design | 147–155 | Separate chapter; checklist-style content with no formal definitions |
| Strategy, Template Method, Command | 47–56, 76–80 | Fewer slides than Composite, Adapter and Facade |

### 1.4 Mark allocation

Marks follow each topic's share of the main body, rounded so that every course outcome has a workable question.

| Topic | Main-body share | Marks | Share of marks |
|---|---|---|---|
| GoF design patterns | 38% | 14 | 35% |
| Enterprise Application Architecture patterns | 26% | 10 | 25% |
| Design quality and CK metrics | 14% | 6 | 15% |
| Design fundamentals | 12% | 5 | 12.5% |
| Architectural styles | 9% | 5 | 12.5% |

---

## 2. Course Outcomes (CO)

No official CO list exists for this course, so the following outcomes were defined from the selected topics.

| CO | Course Outcome | Bloom Level |
|---|---|---|
| CO1 | Recall and explain the fundamental concepts of software design: modularity, coupling and cohesion. | C1, C2 |
| CO2 | Explain how design quality is assessed using OO metrics (CBO, WMC, LCOM). | C1, C2 |
| CO3 | Describe architectural styles such as layered, event-based and MVC. | C1, C2 |
| CO4 | Explain GoF design patterns (Composite, Adapter, Facade) in terms of intent, structure, benefits and liabilities. | C1, C2 |
| CO5 | Describe enterprise application patterns for mapping the domain model to a database (ORM, Data Mapper, inheritance mapping). | C1, C2 |

---

## 3. Question Paper

**Instructions:** Answer all questions. Marks are shown beside each question.

### Question 1 — Short Questions (C1: Knowledge) [10 marks]

| No | Question | Marks | Bloom | CO |
|---|---|---|---|---|
| 1(a) | Define cohesion. | 2 | C1 | CO1 |
| 1(b) | What does the CBO metric measure? | 2 | C1 | CO2 |
| 1(c) | List four architectural styles. | 2 | C1 | CO3 |
| 1(d) | State the intent of the Facade pattern. | 2 | C1 | CO4 |
| 1(e) | What is Object-Relational Mapping (ORM)? | 2 | C1 | CO5 |

### Question 2 [3 marks] — C2 (Understanding), CO1

Explain coupling and cohesion. Why does a good design aim for low coupling and high cohesion?

### Question 3 [4 marks] — C2 (Understanding), CO2

Explain what the metrics CBO, WMC and LCOM2 measure. What does a smaller LCOM2 value indicate?

### Question 4 [3 marks] — C2 (Understanding), CO3

Explain the Model–View–Controller (MVC) architectural style by describing the role of each of its three components.

### Question 5 [7 marks] — C2 (Understanding), CO4

Explain the Composite pattern. Describe its intent, its participants, two benefits and one liability.

### Question 6 [5 marks] — C2 (Understanding), CO4

Explain the Adapter pattern. Describe its intent, its participants, one benefit and one liability.

### Question 7 [8 marks] — C2 (Understanding), CO5

**(a)** Explain the Data Mapper pattern. What is its responsibility, and how does it relate to the Domain Model pattern? **[4 marks]**

**(b)** Explain how Single Table Inheritance and Class Table Inheritance represent an inheritance hierarchy in a database. Give one advantage of each. **[4 marks]**

---

## 4. Mapping of Questions to Course Outcomes

| Question | CO1 | CO2 | CO3 | CO4 | CO5 | Marks | Bloom |
|---|---|---|---|---|---|---|---|
| 1(a) | ✔ | | | | | 2 | C1 |
| 1(b) | | ✔ | | | | 2 | C1 |
| 1(c) | | | ✔ | | | 2 | C1 |
| 1(d) | | | | ✔ | | 2 | C1 |
| 1(e) | | | | | ✔ | 2 | C1 |
| 2 | ✔ | | | | | 3 | C2 |
| 3 | | ✔ | | | | 4 | C2 |
| 4 | | | ✔ | | | 3 | C2 |
| 5 | | | | ✔ | | 7 | C2 |
| 6 | | | | ✔ | | 5 | C2 |
| 7(a) | | | | | ✔ | 4 | C2 |
| 7(b) | | | | | ✔ | 4 | C2 |
| **Total per CO** | **5** | **6** | **5** | **14** | **10** | **40** | |

---

## 5. Bloom's Taxonomy Distribution

| Level | Marks | Percentage |
|---|---|---|
| C1 – Knowledge | 10 | 25% |
| C2 – Understanding | 30 | 75% |
| **Total** | **40** | **100%** |

---

## 6. Suggested Time Allocation

| Question | Marks | Time (min) |
|---|---|---|
| Q1 | 10 | 8 |
| Q2 | 3 | 4 |
| Q3 | 4 | 6 |
| Q4 | 3 | 5 |
| Q5 | 7 | 11 |
| Q6 | 5 | 8 |
| Q7 | 8 | 13 |
| Revision | – | 5 |
| **Total** | **40** | **60** |

---

<img width="1075" height="1521" alt="exam_page-1 (1)" src="https://github.com/user-attachments/assets/74f1a924-ba83-41ed-948e-aa745eec1ff6" />



<img width="1075" height="1521" alt="exam_page-2 (1)" src="https://github.com/user-attachments/assets/91fae371-e66c-44bc-8d43-3fb351ddde48" />



## 7. Answer Hints (Marking Guide)

Slide numbers refer to the lecture file *4-SoftEng-Design*.

### Q1

- **(a)** Cohesion is a measure of the strength of association of the elements within a component. *(slide 13)*
- **(b)** CBO (Coupling Between Object classes) is the number of classes used by a class; inheritance is typically not counted. *(slide 17)*
- **(c)** Any four of: layered, event-based, MVC, blackboard/repository, pipes and filters. *(slides 35–39)*
- **(d)** Provide a unified interface to a set of interfaces in a subsystem; Facade defines a higher-level interface that makes the subsystem easier to use. *(slide 71)*
- **(e)** Mapping objects to database relations and vice versa: one table per class in the domain layer, each object stored as a table row. *(slide 88)*

### Q2 (3)

- **Coupling:** measure of interdependence among components (1). *(slide 12)*
- **Cohesion:** measure of the strength of association of elements within a component (1). *(slide 13)*
- **Good split:** software is decomposed into smaller named components with well-defined interfaces, with different functionalities and responsibilities in different components; low coupling and high cohesion keep components independent and focused (1). *(slide 10)*

### Q3 (4)

- **CBO:** number of classes used by a class (1). *(slide 17)*
- **WMC:** sum of the complexities of the class's methods, measured by lines of code or McCabe (conditions + 1) (1). *(slide 27)*
- **LCOM2** = 1 − Σ(m_a_i) / (m·a), where m = number of methods and a = number of attributes (1). *(slide 23)*
- **Smaller LCOM2 is better,** meaning higher cohesion (1). From the formula, 0 means every method uses every attribute and 1 means no method uses any attribute. *(slide 23)*

### Q4 (3)

- **Model:** represents information about the domain (1).
- **View:** the display of the model in the UI (1).
- **Controller:** takes user input, manipulates the model and makes the view update appropriately (1). *(slide 37)*

### Q5 (7)

- **Intent:** compose objects into structures to represent part-whole hierarchies; clients treat individual objects and compositions of objects uniformly (2). *(slide 64)*
- **Participants:** Component (interface for objects in the composition), Primitive or leaf (such as Rectangle, Line), Composite (behavior for components having children, such as Picture), Client (uses the Component interface); half a mark each (2). *(slide 68)*
- **Benefits, any two:** clients become simple because they treat composites and individual objects uniformly; new kinds of components are easy to add (2). *(slide 69)*
- **Liability:** can make the design too general, since it becomes harder to restrict the components of a composite (1). *(slide 69)*

### Q6 (5)

- **Intent:** convert the interface of a class into another interface clients expect; lets classes work together that could not otherwise because of incompatible interfaces (2). *(slide 58)*
- **Participants:** Target, Client, Adaptee, Adapter (1). *(slide 60)*
- **Benefit:** adaptees can be added and used without changing existing code (1). *(slide 62)*
- **Liability:** overall code complexity increases because of the new classes and the level of indirection (1). *(slide 62)*

### Q7(a) (4)

- Data Mapper (also known as Repository or DAO) is a layer of mappers that moves data between objects and the database while keeping them independent of each other (2). *(slides 89–90)*
- It separates the in-memory objects from the database, so the objects need not know a database is present (1). *(slide 90)*
- It fits well with the Domain Model pattern, an object model of the domain that incorporates both behavior and data (1). *(slides 84, 90)*

### Q7(b) (4)

- **Single Table Inheritance:** the whole hierarchy is stored in a single table with columns for all the fields of the various classes (1). **Advantage, any one:** only one table to worry about; no joins when retrieving data; refactoring fields up or down the hierarchy does not change the database (1). *(slides 97–98)*
- **Class Table Inheritance:** one table for each class, linked by foreign keys (1). **Advantage, any one:** all columns are relevant for every row so tables are easier to understand and waste no space; the relationship between the domain model and the database is straightforward (1). *(slides 99–100)*
