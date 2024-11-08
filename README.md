# String Reassembly from Fragments

## Description
This project explores the computational challenges of **reassembling strings from fragments**, a problem central to areas like **genome sequencing** and **dendrochronology**. The program implements a greedy algorithm to combine overlapping fragments of a string into a single sequence. While the solution is not always optimal, it demonstrates the foundational techniques used in real-world computational biology, such as those applied in the Human Genome Project.

Additionally, this project includes **JUnit tests** to validate the functionality of each method, ensuring correctness and reliability.

---

## Objectives
1. **Practice with Set objects**:
   - Use sets to manage and manipulate fragments.
2. **Write JUnit test cases**:
   - Validate the correctness of the implemented methods.
3. **Explore sequence reassembly**:
   - Understand the challenges of reassembling long strings from overlapping fragments.

---

## Features
### 1. String Reassembly
- Reassembles a string from overlapping fragments using a greedy approach.
- Handles cases where:
  - Some fragments do not perfectly overlap.
  - The solution is not guaranteed to be optimal.

### 2. File Input
- Reads text files containing string fragments for reassembly.
- Handles input files with over 1000 fragments (though execution time increases).

### 3. Unit Testing with JUnit
- **StringReassemblyTest**: Includes test cases to validate individual methods in `StringReassembly.java`.

---

## Technologies Used
- **Java** for implementing the reassembly algorithm.
- **JUnit** for writing and running unit tests.
- **Set** objects for managing string fragments.

---

## How to Run
### Prerequisites
- Java Development Kit (JDK)
- Eclipse IDE or any Java-compatible IDE

### Steps
1. Clone the repository:
   ```bash
   git clone [repository URL]
