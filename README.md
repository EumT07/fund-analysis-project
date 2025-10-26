# Fund Data Analysis Project

A comprehensive Python project for web scraping financial fund data and performing detailed analysis with visualizations. This project demonstrates modern Python development practices including web automation, data processing, and visualization.

## 📹 Project Demo

* insert video:

*Click the image above to watch the project demonstration*

## 📁 Project Structure

project/
├── scrap.ipynb # Web scraping automation
├── data.ipynb # Data analysis and visualization
├── files/
│ └── Funds.xlsx # Collected fund data
├── assets/ # Screenshots and demo video
├── requirements.txt # Python dependencies
└── README.md # Project documentation

## 🚀 Project Overview

This project consists of two main components:

1. **Web Scraper** (`scrap.ipynb`) - Automated data collection from CEF Connect
2. **Data Analysis** (`data.ipynb`) - Statistical analysis and visualization of fund performance

## 🛠️ Technical Stack

- **Python 3.8+**
- **Selenium** - Web automation and scraping
- **Pandas** - Data manipulation and analysis
- **Matplotlib & Seaborn** - Data visualization
- **BeautifulSoup** - HTML parsing
- **Jupyter Notebook** - Interactive development

## 📊 Features

### Web Scraping Module
- Automated navigation and data extraction from CEF Connect
- Cookie consent handling
- Dynamic date range selection
- Robust error handling and logging
- Type-annotated code for better maintainability

### Data Analysis Module
- Data cleaning and transformation
- Monthly statistical analysis (mean, median, min, max)
- Interactive visualizations
- Fund performance comparison
- Professional chart generation

## 🖼️ Screenshots

### Data Collection Process
<p align="center">
  <img src="" width="650" height="400"  alt="home" />
</p>
*Automated data collection from financial website*

### Statistical Analysis
<p align="center">
  <img src="" width="650" height="400"  alt="home" />
</p>
*Monthly performance statistics for ACP fund*

### Visualization Output
<p align="center">
  <img src="" width="650" height="400"  alt="home" />
</p>
*Monthly average share price visualization*

## ⚙️ Option 1: Using UV (Recommended)

1. **Clone the repository**
   ```bash
   git clone https://github.com/EumT07/fund-analysis-project.git
   cd fund-analysis-project

2. **Install dependencies**

# Create virtual environment
uv venv

# Activate virtual environment
# On Windows:
.venv\Scripts\activate
# On macOS/Linux:
source .venv/bin/activate

# Install all dependencies
uv pip install -r pyproject.toml

3. **Set up Chrome WebDriver**

* Download ChromeDriver from https://chromedriver.chromium.org/
* Ensure it's in your system PATH

## 📝 License
This project is open source and available under the MIT License.

## 👨‍💻 Author
Your Eublan Mata
Junior Python Developer