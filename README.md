# Prompt-Engineering-for-Business-Intelligence
Prompt Engineering Project for Business Intelligence

# 📊 Prompt Engineering for Business Intelligence

This is an interactive Python tool (designed for Google Colab) that helps generate high-quality prompts for Business Intelligence tasks, using data from Excel files.

It allows users to select from various prompt templates such as data summary, KPI extraction, forecasting, and more, and fill in the required details interactively.

---

## 🚀 Features

- ✅ Mount and read Excel files directly from Google Drive
- ✅ View a snapshot of your dataset
- ✅ Choose prompt types by **number** or **exit anytime**
- ✅ Supports various prompt templates:
  - Summary
  - Visual Chart Creation
  - Data Comparison
  - KPI Extraction
  - Prediction
  - Business Insights
- ✅ Interactive input for placeholders
- ✅ Easily extendable with your own prompt templates

---

## 📁 Example Prompt Templates

| Prompt Type     | Description                                      |
|-----------------|--------------------------------------------------|
| Summary         | Summarizes the main trends in the dataset        |
| Visual          | Creates chart prompts based on selected metrics  |
| Comparison      | Compares two elements over the fiscal year       |
| KPI Extraction  | Extracts key KPIs from a department              |
| Prediction      | Forecasts future metrics based on trends         |
| Insights        | Extracts business insights from the dataset      |

---

## 🛠️ How to Use

1. **Open with Google Colab**
2. **Mount Google Drive**:
   - The script will automatically mount your Drive.
3. **Make sure your Excel file is uploaded to** `MyDrive/Colab Notebooks/`
4. **Run the notebook and follow the interactive menu**
5. **Select a prompt type by number**
6. **Enter values for each placeholder**
7. **Get your custom-generated prompt!**

---

## 📦 Requirements

This tool is built for **Google Colab**, and uses:

- `pandas`
- `openpyxl` (for reading Excel files)
- Google Colab’s `drive` module

No additional installation needed on Colab.

---

## 🧩 Extending the Tool

You can easily add new prompt types by modifying the `prompt_templates` dictionary:

```python
"NewPrompt": {
    "template": "Your custom prompt with {placeholder1} and {placeholder2}",
    "placeholders": ["placeholder1", "placeholder2"]
}
