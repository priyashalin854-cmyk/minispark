# MiniSparkRDD

A lightweight implementation of the **Spark RDD (Resilient Distributed Dataset)** concept in Python. This project demonstrates how basic distributed data processing works by implementing common RDD transformations and actions without using Apache Spark.

## 📌 Project Overview

MiniSparkRDD is an educational project designed to help understand the internal working of Apache Spark's RDD model. It provides a simplified framework for loading data, performing transformations, executing actions, and building a Directed Acyclic Graph (DAG) for processing.

The project processes an Amazon product dataset and demonstrates filtering and transforming data using RDD operations.

---

## 🚀 Features

- Load CSV datasets
- Custom RDD implementation
- Lazy evaluation
- DAG-based execution model
- Filter and Map transformations
- Collect action
- Simple execution engine
- Clean and modular project structure

---

## 📂 Project Structure

```
MiniSparkRDD/
│
├── Data/
│   └── amazon.csv
│
├── src/
│   ├── dag.py
│   ├── executor.py
│   ├── loader.py
│   ├── rdd.py
│   └── ...
│
├── main.py
├── README.md
└── requirements.txt (optional)
```

---

## 🛠 Technologies Used

- Python 3.x
- Object-Oriented Programming (OOP)
- CSV File Handling
- Custom Data Processing Framework

---

## ⚙️ Installation

### 1. Clone the repository

```bash
git clone https://github.com/your-username/MiniSparkRDD.git
```

### 2. Navigate to the project

```bash
cd MiniSparkRDD
```

### 3. Run the project

```bash
python main.py
```

or

```bash
py main.py
```

---

## 📊 Dataset

The project uses an Amazon product dataset stored in:

```
Data/amazon.csv
```

The dataset contains information such as:

- Product Name
- Category
- Rating
- Price
- Other product details

---

## 🔄 Workflow

1. Load the CSV dataset.
2. Create an RDD from the data.
3. Apply transformations such as filtering and mapping.
4. Build a DAG representing the operations.
5. Execute the DAG.
6. Display the final results.

---

## 📷 Sample Output

```
Loading dataset...

Applying Filter:
Category == Electronics

Applying Filter:
Rating > 4

Collecting Results...

Apple AirPods Pro
Sony WH-1000XM5
Samsung Galaxy Buds
...
```

*(Output may vary depending on the dataset.)*

---

## 💡 Learning Objectives

This project helps understand:

- What is an RDD?
- Lazy Evaluation
- Transformations vs Actions
- Directed Acyclic Graph (DAG)
- Data Processing Pipeline
- Spark Programming Concepts

---

## 🔮 Future Improvements

- Reduce operation
- FlatMap transformation
- Parallel processing
- Multiple partitions
- Performance optimization
- Support for additional file formats

---

## 👩‍💻 Author

**Priya Shalin**

---

## 📄 License

This project is created for educational and learning purposes.
