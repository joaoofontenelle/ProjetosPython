````markdown
# 🐍 Python Projects  

This repository gathers several projects and exercises developed during my studies in Python 3, focusing on object-oriented programming, list manipulation, loops, functions, and best practices.  

Each project represents a step in the learning journey and can serve as a foundation for study, review, or future improvements.  

---

## 📂 Projects and Algorithms  

### 1. 🎬 Streaming Clients and Plans Management  
File: `clientes.py`  

- `Clientes` class with attributes name, email, and plan.  
- Available plans: `Gold` and `Platinum`.  
- Features:  
  - Change plan.  
  - Validate selected plan.  
  - Watch a movie (restricted by the client’s plan).  

➡️ Example:  
```python
cliente1 = Clientes('João', 'joao@email.com', 'Platinum')
cliente1.mudar_plano('Gold')
cliente1.ver_filme('Star Wars', 'Platinum')
````

---

### 2. 🏪 Inventory Control System

File: `estoque.py`

* Console-based interactive menu with options:

  1. Add product to inventory
  2. Check inventory
  3. Remove product from inventory (partial or total)
  4. Exit system

* Data structure: list of dictionaries (`{'Product': name, 'Quantity': value}`)

* Usage of **loops, validations, and error handling**.

---

### 3. 👨‍💼 Employee Registration and Management System

File: `funcionarios.py`

* Functions for:

  * Registering new employees (with data such as SSN, ID, address, role, salary, etc.).
  * Listing active employees.
  * Updating employee information.
  * Blocking and unblocking employees.

* Highlights:

  * Helper functions for **formatting SSN, IDs, and dates**.
  * **Status control (Active/Inactive)** for employees.
  * Strong user input validations.

---

## 🛠️ Technologies Used

* **Python 3.x**
* Native libraries: `time`, `os`

---

## ▶️ How to Run

1. Clone the repository:

```bash
git clone https://github.com/joaoofontenelle/ProjetosPython.git
```

2. Navigate into the project folder:

```bash
cd ProjetosPython
```

3. Run any script:

```bash
python file_name.py
```

---

## 🎯 Purpose

This repository aims to:

* Consolidate knowledge acquired during Python studies.
* Gather practical projects that simulate **real-world systems**.
* Serve as a portfolio of learning and programming practice.

---

## 👨‍💻 Author

Developed by **João Victório Dos Santos Fontenelle**
📧 Contact: [joaofontenelle12570@gmail.com](mailto:joaofontenelle12570@gmail.com)

---
