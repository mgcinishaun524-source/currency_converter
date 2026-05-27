```python
# Define the content for the README.md
readme_content = """# Currency Converter V1

A minimalist, high-contrast currency converter built with **React.js**. This project was developed with a "Deep Obsidian" aesthetic, prioritizing sharp lines, dark backgrounds, and a professional, aggressive design language.

## 🚀 Features
- High-Contrast UI: Deep obsidian and pure black theme for maximum focus.
- Bi-directional Conversion: Handles USD to ZAR and ZAR to USD.
- Precision Formatting: Ensures all financial outputs are capped at 2 decimal places.
- Beginner-Friendly Architecture: Uses explicit state management and modular component structure.

## 🛠 Tech Stack
- Frontend: React.js
- Styling: Inline CSS-in-JS (Monochromatic)
- State Management: React Hooks (`useState`)

## 📂 Project Structure
```text
src/
├── components/
│   └── CurrencyConverter.js  # Core logic and styling
├── App.js                    # Main application entry
└── index.js                  # React DOM rendering

```

## ⚙️ Logic Breakdown

The application uses a standard `if/else` logic flow within the `handleConvert` function to determine the exchange rate based on the selected state:

USD to ZAR: Amount  18.45
ZAR to USD: Amount  0.054

## 📖 How to Run

1. Clone the repository.
2. Install dependencies:
```bash
npm install

```


3. Start the development server:
```bash
npm start
