# 🔍 Copescope – Offline Source Code Search Engine

Copescope is an **offline source code search engine** that allows users to search across all files in a given directory. It scans source files based on user input (keywords or patterns) and returns relevant matches, making it easy to explore large codebases **without internet access**.

---

## 🚀 Features

* 🔎 Search across **all files** in a user-specified directory
* 📁 Supports recursive search through sub-folders
* ⚡ Fast keyword-based lookup
* 📴 Works completely **offline**
* 🧠 Designed for developers, students, and code reviewers
* 🖥️ Simple and user-friendly interface (CLI / GUI – as applicable)

---

## 🛠️ How It Works

1. User provides:

   * Directory path
   * Search keyword or query
2. Copescope scans all files in the directory
3. Matches are identified line-by-line
4. Results are displayed with:

   * File name
   * Matched content
   * Location (line number, if applicable)

---

## 📂 Project Structure

```
copescope/
│
├── src/                # Source code files
├── search/             # Search logic and algorithms
├── utils/              # Helper functions
├── README.md           # Project documentation
└── requirements.txt    # Dependencies (if any)
```

---

## 🧪 Example Usage

```bash
Enter directory path: /projects/sample-code
Enter search keyword: binarySearch
```

**Output:**

```
Found in: src/search.java (Line 24)
Found in: utils/helper.py (Line 10)
```

---

## 🧑‍💻 Technologies Used

* Programming Language: **(Java / Python / C++ – update this)**
* File Handling & Directory Traversal
* String Matching / Pattern Search
* Data Structures for efficient lookup

---

## 🎯 Use Cases

* Exploring large offline codebases
* Searching code during exams or interviews
* Reviewing legacy projects
* Learning and debugging source code

---

## 📈 Future Enhancements

* Regex-based advanced search
* File type filtering (e.g. `.java`, `.py`)
* GUI version
* Search result ranking
* Code snippet preview

---

## 📄 License

This project is open-source and available under the **MIT License**.

---

## 🙋‍♂️ Author

**Himank Goel**
💻 Computer Science Student
📫 GitHub: *your-github-username*

---

### ⭐ If you like this project, don’t forget to star the repo!
