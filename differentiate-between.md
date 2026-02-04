# Differentiate Between Tables

## 1. Hardware vs. Software (Chapter 1)

| Feature  | Hardware                                       | Software                                          |
| :------- | :--------------------------------------------- | :------------------------------------------------ |
| **Nature** | Physical components, tangible.                 | Set of instructions/programs, intangible.         |
| **Function** | Performs the actual computation and tasks.     | Instructs the hardware what to do.                |
| **State** | Can be seen and touched.                       | Cannot be physically touched.                     |
| **Example** | CPU, Monitor, Keyboard, RAM.                   | Operating System, Python Interpreter, MS Word.    |

## 2. RAM vs. ROM (Chapter 1)

| Feature      | RAM (Random Access Memory)                 | ROM (Read Only Memory)                         |
| :----------- | :----------------------------------------- | :--------------------------------------------- |
| **Nature**   | Volatile (data lost when power is off).    | Non-volatile (data retained when power is off). |
| **Purpose**  | Used for active, temporary working memory. | Stores firmware/boot instructions.             |
| **Writeability** | Data can be read from and written to.      | Data is primarily for reading (pre-written).   |
| **Speed**    | Generally faster than ROM.                 | Slower than RAM.                               |

## 3. Binary vs. Decimal Number System (Chapter 2)

| Feature  | Binary (Base 2)                      | Decimal (Base 10) |
| :------- | :----------------------------------- | :---------------- |
| **Base** | 2                                    | 10                |
| **Digits** | 0 and 1                              | 0 through 9       |
| **Usage** | Used internally by all computer hardware. | Used by humans for counting. |
| **Example** | $(101)_2$                            | $(5)_{10}$        |

## 4. String vs. List (Chapter 10 & 11)

| Feature      | String (`str`)                            | List (`list`)                                      |
| :----------- | :---------------------------------------- | :------------------------------------------------- |
| **Mutability** | Immutable (Cannot be changed in place).   | Mutable (Can be changed in place).                 |
| **Content**  | Sequence of characters.                   | Sequence of any data type.                         |
| **Representation** | Enclosed in quotes (e.g., `"hello"`). | Enclosed in square brackets (e.g., `[1, 'a']`).    |
| **Manipulation** | Methods return a new string (e.g., `.upper()`). | Methods modify the list directly (e.g., `.append()`). |

## 5. List vs. Tuple (Chapter 11 & 12)

| Feature      | List (`list`)                                     | Tuple (`tuple`)                                     |
| :----------- | :------------------------------------------------ | :-------------------------------------------------- |
| **Mutability** | Mutable (Elements can be changed).                | Immutable (Elements cannot be changed).             |
| **Syntax**   | Square brackets `[ ]`.                            | Parentheses `( )`.                                  |
| **Performance** | Generally slower due to overhead for mutability. | Generally faster and more memory efficient.         |
| **Usage**    | Storing collections of data that will change.     | Storing collections of data that should not change (e.g., coordinates). |

## 6. `for` vs. `while` loop (Chapter 9)

| Feature      | `for` loop                                           | `while` loop                                           |
| :----------- | :--------------------------------------------------- | :----------------------------------------------------- |
| **Usage**    | Used when the number of iterations is known (e.g., iterating through a list). | Used when the number of iterations is unknown or dependent on a condition. |
| **Structure** | Iterates over a sequence (`range`, list, string).    | Executes as long as a condition remains `True`.        |
| **Termination** | Ends automatically after the sequence is finished.   | Requires an update to the condition to eventually become `False`. |

## 7. Virus vs. Trojan Horse (Chapter 14)

| Feature      | Virus                                               | Trojan Horse                                       |
| :----------- | :-------------------------------------------------- | :------------------------------------------------- |
| **Replication** | Replicates itself by attaching to other files.      | Does not replicate itself.                         |
| **Disguise** | Often hides in files/executables.                   | Disguised as legitimate, useful software.          |
| **Goal**     | To damage files, corrupt systems, and spread.       | To provide a 'backdoor' for remote access or deliver a payload. |

## 8. Copyright vs. Patent (Chapter 15)

| Feature      | Copyright                                             | Patent                                             |
| :----------- | :---------------------------------------------------- | :------------------------------------------------- |
| **Subject**  | Original works of authorship (e.g., literature, art, code). | Inventions (e.g., processes, machines, designs).   |
| **Protection** | Protects the *expression* of an idea.                 | Protects the *idea* and how it works.              |
| **Process**  | Generally automatic upon creation.                    | Requires an application and approval process.      |
