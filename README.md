# JSON Refiner Advanced Edition

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/abishavid-coder/html-quick-styler-ai/blob/main/html_quick_styler.ipynb)

JSON Refiner Advanced Edition is an intelligent JSON processing platform built using **Python** and **Gradio**.
The tool converts raw key-value text into clean, structured, and production-ready JSON data through an interactive web interface.

The system automatically detects data types, standardizes key naming conventions, validates JSON structure, and performs multiple transformations like flattening and null removal.

---

## Features

* Automatic JSON **type inference**
* Key **case conversion**

  * snake_case
  * camelCase
  * kebab-case
  * PascalCase
* **Remove null values**
* **Flatten nested JSON**
* **JSON statistics generation**
* Interactive **Gradio UI**
* Easy deployment using **Google Colab**

---

## Technologies Used

* Python
* Gradio
* JSON5
* JSON Schema
* Pydantic
* Google Colab

---

## Installation

Install required dependencies:

```
pip install gradio json5 jsonschema python-dotenv pydantic transformers
```

---

## How to Run

1. Open the project notebook in **Google Colab** using the button above.
2. Run all notebook cells sequentially.
3. A **Gradio interface link** will be generated.
4. Open the link in the browser.
5. Enter key-value data and generate structured JSON.

---

## Example Input

```
Name: John
Age: 28
Active: true
Score: 95.5
Country: USA
Phone: null
```

---

## Example Output

```
{
  "name": "John",
  "age": 28,
  "active": true,
  "score": 95.5,
  "country": "USA"
}
```

Statistics:

```
Total Keys: 6
Top Level Keys: 6
Nested Keys: 0
Has Nested Objects: False
```

---

## Use Cases

* CSV to JSON data migration
* API response normalization
* Configuration file management
* JSON schema validation
* Data transformation for analytics


---

## License

This project is created for educational purposes.
