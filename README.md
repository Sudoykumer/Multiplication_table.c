


```markdown
# 📘 Multiplication Table Generator (C Program)

This is a simple C program that prints the **multiplication table** (নামতা)
of any integer up to a user-defined positive range.

---

## 🔍 What does this program do?

- Asks the user for a number (e.g., 5)
- Asks for the range (how far to go, e.g., 10)
- Validates that the range is a **positive integer**
- Then it prints the multiplication table like this:

```

5 \* 1 = 5

5 \* 2 = 10

......

5 \* 10 = 50

````


## 🛠 How to Compile and Run

### ✅ Requirements:
- A C compiler (like `gcc`)
- Terminal or Command Prompt

### 🧪 Compilation:

```bash
gcc table.c -o table
````

> Make sure your file is named `table.c`. You can rename it if needed.

### ▶️ Run the program:

```bash
./table
```

Or on Windows:

```bash
table.exe
```

---

## 📥 Sample Input / Output:

```
Enter an integer: 7
Enter the range (positive integer): 10
```

```
7 * 1 = 7
7 * 2 = 14
7 * 3 = 21
...
7 * 10 = 70
```

---

## 💡 Learning Purpose

This program is great for:

* Beginners learning C language
* Understanding loops and input validation
* Practicing how to use `for` loop and `do-while` in C
* Building command-line utilities

---

## 🧾 Code Structure

```c
int n, i, range;
printf("Enter a number: ");
scanf("%d", &n);

// Ensures range is positive
do {
    printf("Enter the range (positive integer): ");
    scanf("%d", &range);
} while (range <= 0);

// Prints the table
for (i = 1; i <= range; ++i) {
    printf("%d * %d = %d\n", n, i, n * i);
}
```

---

## 📂 Project Files

```
multiplication-table/
├── table.c       # Main C source code
└── README.md     # Instructions and project overview
```

---

## 🧑‍💻 Author

**Your Name**
GitHub: [@Sudoykumer](https://github.com/your-username)

---

## 🆓 License

This project is open-source and free to use under the [MIT License](LICENSE).

---

## 🤝 Contributions

Pull requests are welcome! If you want to add new features (like reverse table, Bengali output, or range checking), feel free to fork and send a PR.
