# LLM-Powered Document Generator with HTML Rendering

This project demonstrates how to generate realistic sample documents (Invoices, Resumes, or KYC Forms) using OpenAI’s API. The generated content is rendered into an HTML template with enhanced formatting (including a header with a simulated logo and custom CSS) and then converted to PDF using WeasyPrint.

## Features
- **Interactive UI**: Select document type and region, then generate documents with a single click.
- **Customizable Themes**: Multiple CSS themes for professional and creative designs.
- **Dynamic Logos**: Generate SVG logos dynamically based on company names.
- **PDF Generation**: Convert HTML documents to PDF using WeasyPrint.
- **Error Handling**: Fallback mechanisms ensure functionality even if API calls fail.

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/WasanthaK/sample-gen.git
   cd sample-gen
   ```

2. Create and activate a virtual environment:
   ```bash
   python -m venv venv
   .\venv\Scripts\activate
   ```

3. Install the required dependencies:
   ```bash
   pip install -r requirements.txt
   ```

4. Set up your `.env` file with the following content:
   ```env
   OPENAI_API_KEY=your_openai_api_key
   ```

## Usage

1. Open the Jupyter Notebook:
   ```bash
   jupyter notebook invoices.ipynb
   ```

2. Follow the instructions in the notebook to generate documents.

## Project Structure
- `invoices.ipynb`: Main notebook for generating documents.
- `invoices/`: Folder containing generated invoices.
- `requirements.txt`: List of dependencies.

## Dependencies
- `openai`: For interacting with OpenAI’s API.
- `weasyprint`: For converting HTML to PDF.
- `ipywidgets`: For creating interactive widgets in Jupyter Notebooks.
- `python-dotenv`: For managing environment variables.

## License
This project is licensed under the MIT License. See the `LICENSE` file for details.

## Contributing
Feel free to submit issues or pull requests for improvements or bug fixes.