This repository contains solutions to fundamental algorithmic problems implemented in **Python** using **Jupyter Notebook**.

Each problem includes:
- A clear problem description
- An explanation of the approach
- The Python implementation
- Executed output results

The purpose of this repository is to strengthen algorithmic thinking, improve problem-solving skills, and analyze time complexity.

---

## Problems Included

### 1. Longest Substring Without Repeating Characters

Given a string, find the longest substring consisting of consecutive characters with no repeated characters.

Example:

Input:
```
ABCABCFKAB
```

Output:
```
5
```

Approach:
- Sliding Window technique
- Hash set to track visited characters

Time Complexity: O(n)  
---

### 2. Four Consecutive 1s in a Circular Binary String

Given a 7-digit binary string, determine whether there are four consecutive `1`s.
The string is considered circular, meaning the end connects to the beginning.

Example:

Input:
```
1010111
```

Output:
```
True
```

Approach:
- Simulate circular behavior
- Check for consecutive occurrences of "1111"

Time Complexity: O(n)

---

## Technologies Used

- Python 3.12 or higher 
- Jupyter Notebook / JupyterLab

---

## How to Run Locally

1. Clone the repository:

```
mkdir project-name
cd project-directory
git clone https://github.com/pedram12dev/algorithm-challenge-backend-sanaap
```

2. (Optional but recommended) Create a virtual environment:

```
python -m venv venv
source venv/bin/activate   # macOS / Linux
venv\Scripts\activate      # Windows
```

3. Install requirements (jupyter notebook):

```
pip install -r requirement.txt
```

4. Run Jupyter:

```
jupyter notebook
```

