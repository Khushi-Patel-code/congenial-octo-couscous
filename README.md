# 🧮 PyBaseConverter

**PyBaseConverter** is a Python-based command-line tool that converts numbers between **Binary (Base 2)**, **Decimal (Base 10)**, and **Hexadecimal (Base 16)** systems.  
It supports both **integer and fractional numbers**, along with **negative values**, and ensures accurate conversions through detailed validation checks.

## 🚀 Features

- Converts between:
  - Binary → Decimal / Hexadecimal  
  - Decimal → Binary / Hexadecimal  
  - Hexadecimal → Decimal / Binary
- Supports fractional numbers (e.g., `10.5`, `A.F`, `101.1`)
- Handles negative numbers gracefully (e.g., `-101`, `-1A`)
- Includes strong input validation to prevent invalid entries
- Interactive CLI with options to perform multiple conversions in one session

## 🧩 How It Works

The program first validates user input based on the source and target bases.  
Depending on the conversion type, it uses modular conversion functions such as:

- `decimal_to_binary()`
- `decimal_to_hex()`
- `binary_to_decimal()`
- `binary_to_hex()`
- `hex_to_decimal()`
- `hex_to_binary()`

Each function follows mathematical principles for base conversion, including fractional part handling with up to **20-bit precision** for non-integer conversions.


## ▶️ Usage

1. Clone or download this repository:
   ```bash
   git clone https://github.com/<your-username>/PyBaseConverter.git
   
2. Navigate to the project directory:
   ```bash
   cd PyBaseConverter
   
3. Run the Python script:
   ```bash
   python pybaseconverter.py
   
4. Follow the on-screen prompts:
    ```bash
    Please enter the number to convert: 101.1
    The source base (i.e., the base to convert from): 2
    The target base (i.e., the base to convert to): 10
    ```
    ✅ Output:
    
      ```bash
    The result of converting the number 101.1 from base 2 to base 10 is: 5.5
    ```
## 🏗️ Project Structure

```bash
PyBaseConverter/
│
├── pybaseconverter.py     # Main program file
└── README.md              # Documentation

```
## 💡 Future Enhancements

- GUI-based version using **Tkinter** or **Flask**  
- Support for **Octal (Base 8)**  
- **Unit testing** and **code optimization**  
- Web deployment through **Streamlit** or **Flask API**

## ✨ Author

**Khushi Patel**  
Software Engineering Student @ Ontario Tech University  
📫 [Connect on LinkedIn](http://www.linkedin.com/in/khushi-patel-85a994274)  |  🌐 [Portfolio Website](https://khushi-patel-code.github.io/KhushiPatelPortFolio/)
