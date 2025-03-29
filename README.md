📝 About

This Python script searches for a telephone number formatted as ###-###-#### within text files located in a specific directory. It utilizes regular expressions (re) and the os module to scan files automatically.

🚀 Features

Uses regex to identify phone numbers.

Recursively searches through files inside the Extracted_content folder.

Prints the first found phone number along with the file name.

Works dynamically in the current working directory.

📥 Installation & Usage

📌 Prerequisites

Ensure you have Python installed on your system.

📌 How to Run

Clone the repository:

git clone https://github.com/yourusername/phone-number-finder.git

Navigate to the project directory:

cd phone-number-finder

Run the script:

python find_phone_number.py

📂 Folder Structure

project-folder/
│── Extracted_content/    # Folder where text files are stored
│── find_phone_number.py  # Python script

🎯 How It Works

The script walks through the Extracted_content/ folder.

It opens each text file and searches for a pattern matching ###-###-####.

If a phone number is found, it prints the number and the filename.

The script stops searching after the first match is found.

📜 License

This project is licensed under the MIT License.

