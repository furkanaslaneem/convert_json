Hello!!!


We have a Python script specially crafted to convert your files to JSON format quickly and error-free. 
This script detects and automatically processes PDF, DOCX and XLSX file formats, so you don't have to search for different scripts to convert your files.


Here is a more detailed explanation of how our script works:

1 - File Detection: The user enters the path to the file they want to convert. The script knows what type of file it is by looking at its extension.

2 - Conversion Operations: The script calls an appropriate function based on the type of file. For example, if it is an Excel file, a function that 
converts Excel data into a data frame is called. Likewise, if it is PDF, it processes PDF data, and if it is DOCX, it processes DOCX data.

3 - JSON Output: The processed data is converted into a pandas data frame and then translated into JSON format. This ensures that the data is stored in a structurally organized way.

4 - Saving to File: The JSON data is saved in a new JSON file with the name of the original file. This allows you to easily access the converted data.

5 - User Feedback: When the operation is complete, the script displays a message that the successfully converted data has been saved to file.

