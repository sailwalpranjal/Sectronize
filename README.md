# This project is under development
---
# Sectronize

**Sectronize** is a Python-based application designed to distribute students into different sections based on their academic performance and skills. This project ensures fair and balanced section allocation within the university, taking into account various factors such as semester grades, overall grades, and programming skills.

## Table of Contents

- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [Screenshots](#screenshots)
- [Technologies Used](#technologies-used)
- [Contributing](#contributing)
- [License](#license)

## Features

- **Data Import:** Easily upload student data from CSV or Excel files.
- **Column Mapping:** Automatic recognition and mapping of column names from different formats.
- **Section Assignment:** Allocate students to sections based on their academic performance, ensuring fairness.
- **Model Training:** Train a machine learning model to predict sections using student data.
- **Section Shuffling:** Shuffle and reassign sections as needed, based on updated data.
- **Result Export:** Save results to Excel and PDF formats.
- **Developer Mode:** Hidden developer access for advanced functionalities, accessible with a secret key.
- **Scroll and Hover Effects:** Enhanced UI with smooth scrolling and hover effects.
- **Performance Optimization:** Efficient handling of large datasets with reduced lag.

## Installation

1. **Clone the repository:**
   ```bash
   git clone https://github.com/sailwalpranjal/sectronize.git
   ```

2. **Navigate to the project directory:**
   ```bash
   cd sectronize
   ```

3. **Install the required dependencies:**
   ```bash
   pip install -r requirements.txt
   ```

4. **Run the application:**
   ```bash
   python sectronize.py
   ```

## Usage

1. **Upload Student Data:**
   - Click on the "Upload File" button to select a CSV or Excel file containing student data.

2. **Train the Model:**
   - Once the data is loaded, click on "Train Model" to train the machine learning model.

3. **Shuffle Sections:**
   - After training, click on "Shuffle Sections" to assign students to sections based on their performance.

4. **Save Results:**
   - Click on "Save Results" to export the shuffled sections to an Excel or PDF file.

5. **Developer Mode:**
   - Activate hidden developer features by pressing `Shift+2` three times and entering the developer password.

## Screenshots

## Technologies Used

- **Python:** Backend logic and machine learning.
- **Tkinter:** GUI framework for building the application interface.
- **Pandas:** Data manipulation and analysis.
- **scikit-learn:** Machine learning model training and predictions.
- **FPDF:** Exporting results to PDF.
- **Joblib:** Model saving and loading.

## Contributing

Contributions are welcome! If you have any ideas, improvements, or bug fixes, feel free to submit a pull request.

1. Fork the repository.
2. Create your feature branch: `git checkout -b feature/your-feature-name`
3. Commit your changes: `git commit -m 'Add some feature'`
4. Push to the branch: `git push origin feature/your-feature-name`
5. Open a pull request.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
