# Plagiarism-Checker
Java tool for detecting plagiarism in text using multiple similarity algorithms and generating detailed reports.
A simple Java application to detect text similarity between files using a basic word-by-word matching approach. The project includes both a command-line interface (CLI) and a Java Swing-based GUI for ease of use.

# 📌 Features

- Compare two text files for similarity

- Calculates percentage similarity based on matching words

- Supports .txt files

- Graphical interface with file selection dialogs

- Command-line mode for quick comparisons

# 🛠️ How It Works

- File Processing
  FileProcessor reads each file, splits the text into words, and stores them in lists.

- Similarity Calculation
  SimilarityChecker compares word lists from both files and calculates the percentage of words that match.

- GUI Interface
  PlagiarismCheckerGUI allows users to select two files and view the similarity result in a pop-up dialog.

- CLI Mode
  Run the program from the terminal with two file paths as arguments.

# 📌 Requirements

- Java 8 or later

- Works on Windows, macOS, and Linux
