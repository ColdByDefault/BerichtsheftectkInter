
![1](https://github.com/ColdByDefault/BerichtsheftectkInter/assets/155304740/95caa3b2-1444-42ab-8849-cdb6e1b9c5e7)
![2](https://github.com/ColdByDefault/BerichtsheftectkInter/assets/155304740/8bdbcbb8-7074-45c0-9ff0-3dec287e0c3b)
Welcome to beRich.py 
Berichtsheft Application Documentation


 

### Introduction
The Berichtsheft Application is a Python-based GUI tool designed to streamline the creation and management of training reports. Utilizing `tkinter` and `customtkinter`, it offers a user-friendly interface for entering training details and generating corresponding documentation.

### Features
- **Dark Mode Interface**: A sleek, dark-themed UI that is easy on the eyes, enhancing user experience, especially during extended use.
- **Tabbed Navigation**: Easily switch between "General Information" and "Daily Notes" to input respective details.
- **Word Document Integration**: Automates the process of updating a Word document template with input data, facilitating the generation of standardized report files.

### Setup
1. **Dependencies**: Ensure Python is installed on your system. The application requires `tkinter`, `customtkinter`, and `python-docx`. Install these packages using pip if not already installed.
   ```bash
   pip install customtkinter python-docx
   ```
2. **Running the Application**: Download `mainctk.py` and run it using Python.
   ```bash
   python mainctk.py
   ```

### Usage
#### General Information Tab
- Input fields for personal and training session details.
- Option to select training module numbers from a dropdown menu.

#### Daily Notes Tab
- Text boxes for entering notes or observations for each weekday.
- Inputs are designed to be captured for document generation.

### Generating Reports
- The "Submit" button processes the entered information, updating a specified Word document template with the provided data. This feature requires a `.docx` file with predefined placeholders corresponding to the input fields.

### Contributing
We welcome contributions to the Berichtsheft Application! Whether it's feature suggestions, bug reports, or code contributions, please feel free to open an issue or pull request on our GitHub repository.

### Support
For any questions or issues, please open an issue on the GitHub repository, and we'll get back to you as soon as possible.

### License
None

---

