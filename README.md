# CSV Question Answering and Visualization App

This repository contains a Python-based interactive web app that allows users to upload a CSV file, ask questions about its data, and visualize relationships between columns. The app is built using Gradio and integrates a language model from Ollama to generate data-driven answers.

## Features

- **CSV Upload & Validation:** Users can upload a CSV file, which gets validated upon submission.
- **Question Answering:** Using the Ollama language model, the app answers questions based on the contents of the uploaded CSV.
- **Data Visualization:** Users can select two columns from the CSV to generate a simple line plot.
- **Interactive Interface:** Powered by Gradio for an easy-to-use web interface.

## Requirements

- Python 3.8+
- Gradio
- Pandas
- Matplotlib
- Ollama
- Pydantic

You can install the necessary libraries with the following commands:

```bash
pip install gradio pandas matplotlib ollama pydantic
```

## How to Run the App

1. Clone this repository:

```bash
git clone <repository-url>
cd <repository-folder>
```

2. Launch the Gradio app:

```bash
python Assign.ipynb
```

3. Open the Gradio interface in your browser and interact with the app.

## Usage

- **Upload CSV:** Click the upload button and choose your CSV file.
- **Ask a Question:** Type a natural language question related to the data.
- **Choose Columns:** Provide the column names for the X and Y axes of the graph.
- **Get Results:** View the answer generated by the LLM and see a plot of the chosen data.

## Example

1. Upload a CSV containing sales data.
2. Ask: "What were the highest sales months?"
3. Choose `Month` as the X-axis and `Sales` as the Y-axis.
4. See the answer and the sales trend plotted.

## Contributing

Feel free to submit issues or pull requests with improvements or feature suggestions.

