# 🧮 GUI Calculator by Zohair Ahmed

A sleek and functional calculator application built with Python and Tkinter. Perform basic arithmetic operations with an easy-to-use graphical interface.

---

## 🚀 Features

- ✅ Basic Operations: Addition, Subtraction, Multiplication, Division
- 🧼 Clear Button to reset input
- 🔢 Real-time input updates
- ✔️ Result shown instantly using `eval()`
- 🖱️ Interactive buttons with hover effects (cursor change)

---

## 🖼️ GUI Preview

> A simple, clean layout that mimics standard calculator design with responsive buttons.

![gui](https://media.discordapp.net/attachments/1265694796308283515/1362916430999191582/image.png?ex=68042256&is=6802d0d6&hm=78d4dc65d0c9652c7f7f4338d342c907ea90f5446b108fad571e92af6965a243&=&format=webp&quality=lossless&width=242&height=306)
---

## 📦 Requirements

- Python 3.x
- Tkinter (comes pre-installed with Python)

---

## 🛠️ How to Run

1. **Clone the Repository:**

```bash
git clone https://github.com/your-username/tkinter-calculator.git
cd tkinter-calculator
```

2. **Run the App:**

```bash
python calculator.py
```

---

## 🧑‍💻 How It Works

- Press buttons to enter numbers or operators.
- Press **`=`** to evaluate the expression.
- Press **`C`** to clear the input field.

The logic is handled using Python’s built-in `eval()` function, and a global expression string tracks current user input.

---

## 📌 Example

| Expression | Result |
|------------|--------|
| `8 + 2 * 5` | `18` |
| `10 / 2` | `5.0` |
| `3.5 + 2.1` | `5.6` |

---

## 📁 File Structure

```
calculator.py     # Main script
README.md         # You're here!
```

---

## ⚠️ Warning

> This calculator uses Python's `eval()` function, which can be risky if the input comes from untrusted sources. Since this is a standalone GUI app for personal use, it's safe — but be cautious if adapting for web or multi-user systems.

---

## 👨‍💻 Author

Developed by [Zohair Ahmed](https://github.com/zohair-ahmed-nadeem)

---

## 📄 License

This project is open-sourced under the [MIT License](LICENSE).
