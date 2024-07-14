# Text Extraction App Using Python

## Steps to Run the Application Locally:

**Step 1:** Create a copy of the project.

**Step 2:** Open the command prompt and navigate to the folder where you can find the 'app.py' file.

**Step 3:** Create a new environment using the following command:

```
conda create -n <environment_name>
```

**Step 4:** Activate the environment using the following command:

```
conda activate <environment_name>
```

**Step 5:** Install Tesseract OCR by following the instructions provided in the [Windows Installer](https://github.com/UB-Mannheim/tesseract/wiki).

**Step 6:** Note the installation path of Tesseract. The default installation path at the time of this edit was: `C:\ProgramFiles\Tesseract-OCR`. Please verify the installation path as it may vary.

**Step 7:** Set the Tesseract path in `pytesseract.pytesseract.tesseract_cmd` variable. Use the following code snippet:

```python
pytesseract.pytesseract.tesseract_cmd = r'C:\ProgramFiles\Tesseract-OCR\tesseract.exe'
```

**Step 8:** Install the required dependencies using the following command:

```
python -m pip install -r requirements.txt
```

**Step 9:** Run the application using the following command:

```
python app.py
```

Copy the URL displayed in the command prompt and paste it into your web browser.

**Step 10:** The `sample_data` folder contains images that you can use for testing.

Feel free to reach out if you have any questions or encounter any issues.