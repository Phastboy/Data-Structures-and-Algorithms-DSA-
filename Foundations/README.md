# Foundation of Data Structures and Algorithms

## What is a Data Structure?
It is a way of organizing and storing data in a way that enables efficient access, modification and management.

## Characteristics of Data Structure
1. **Organization:** How data is arranged.
2. **Storage:** How data is stored.
3. **Memory Usage:** It uses memory, though it must be minimized to ensure optimal performance.
4. **Operations:** They define possible operations on the data they contain.
5. **Size:** They are either flexible or fixed in size.
6. **Access methods:** Different Data structures have different access methods.
7. **Complexity:** Different Data structures have different time and space complexities for different operations.

## Goals of Data structures
1. **Efficiency:** Aims to optimize operations.
2. **Reusability:** Quality data structures can be reused across different software.
3. **Correctness:** Mechanism to enforce criteria ensures correctness and consistency.
4. **Scalability:** Continue to perform efficiently with varying amount of data.

## Need for Data Structures
1. **Organize Data Efficiently**: Data structures help in organizing data at various levels, making it easier to manage and retrieve information.
2. **Storage and Access**: They define how data can be stored and accessed, even at the most basic level, ensuring systematic data management.
3. **Data Operations**: Data structures provide methods for performing operations on data, such as adding, removing, and updating data or groups of data.
4. **Manage Data Volume**: They offer ways to handle varying amounts of data efficiently, accommodating growth and changes in data size.
5. **Enhance Performance**: Data structures improve the efficiency of data operations, optimizing the performance of algorithms and applications.

## Basic Terminologies

- **Data**: Elementary value or collection of values.
- **Group Items**: Data items that have subordinate data items. For example, a student’s name can have first and last name.
- **Record**: Collection of various data items grouped together.
- **File**: A collection of various records of one type of entity.
- **Attribute**: Represents a particular property of an entity.
- **Entity**: Represents a class of certain objects and contains various attributes.
- **Field**: A single elementary unit of information representing the attribute of an entity.

## Basic Factors to consider when designing a data structure 
1. Data type 
2. Operations required 
3. Performance 
4. Flexibility 
5. Maintainability
6. Memory Usage
7. Ease of implementation 

## Classification

``` mermaid
graph TD;
  DS --> Primitive;
  DS --> Non-primitive;
  P["`int
  char
  boolean`"]
  Primitive --> P;
  Non-primitive --> Linear;
  L["`Arrays
  Linked list 
  Stacks 
  Queues`"]
  Linear --> L;
  Non-primitive --> Non-linear;
  NL["`trees
  graphs`"]
  Non-linear --> NL;
```

## Abstraction 

**Abstraction** involves simplifying complex systems by breaking them down into smaller parts and hiding the unnecessary details.

### Characteristics 
1. **Encapsulation:** Bundles data with method that operate on the data, and restrict direct access to some object's components.

2. **Simplification:** Omits unnecessary details to ensure reduced complexity, making it easy to focus on high level operations.

3. **Modularity:** Divides program into smaller, manageable, and reusable parts (modules), each responsible for a specific functionality.

### Advantages

1. **Improve code usability:** Simplifies understanding of code.

2. **Enhances Maintainability:** Make codes easier to modify and extend, since changes are localized within modules.

3. **Promotes Reusability:** Enables the reuse of modules in different programs without modification.

## Abstract Data Structures (ADS)

They are theoretical models designed to define, and organize data along with operations that can be performed on the data.

### Key Components 

1. **Interface:** Set of operations that can be performed on the data.

2. **Behavior:** How it should respond to operations without specifying the underlying mechanics.

### Common Types 

1. Linked list
2. Stack
3. Queue
4. Tree
5. Graph
