# Data-entry-desktop-application
A desktop application built with Python . Here's a breakdown of its functionalities:

**Data Entry with Validation:**

* The application allows users to enter information about sales or services provided.
* Fields include:
    * Service type (dropdown menu)
    * Product code
    * Customer name
    * Phone number
    * Property type (dropdown menu)
    * Detailed address
    * Village/town name
    * Invoice number
    * Supply status (dropdown menu)
    * Supply date
    * Employment date
    * Installation date
    * Total amount
    * Total paid
    * Notes


**Data Storage and Management:**

* The application uses pandas, a Python library for data analysis, to store the entered data in a format likely  a DataFrame.
* It saves this DataFrame to a pre-defined Excel file (`THE NAME OF THE EXCEL FILE.xlsx`) on the user's system.
* A new sheet (`Sheet1`)  is used by default

**Graphical User Interface (GUI):**

* The application uses PyQt, a set of Python bindings for the Qt GUI toolkit, to create the user interface. 
* The interface is likely divided into sections:
    * A title section displaying the company name ('ANYNAME') and potentially a date.
    * An information section where users enter details about the sale/service.
    * A results section displaying a table, possibly showing previously entered data.
    * A function section with buttons for potentially adding, editing, or clearing data.

**Additional Notes:**

* The code uses global variables (`df`, `filename`, `sheetname`), which is generally discouraged in larger applications due to potential maintainability issues.



Overall, this application provides a user-friendly way for TAQA Company to collect, validate, and store data related to sales or services. 
![Screenshot (564)](https://github.com/user-attachments/assets/3cf23958-4b88-47b4-a7d3-c879b61bdc20)
![Screenshot (563)](https://github.com/user-attachments/assets/fd94333c-2d62-4d34-9ff0-4ef264171436)
![Screenshot (562)](https://github.com/user-attachments/assets/355ac49e-dc3b-4833-b9f1-1214b03438b0)
![Screenshot (561)](https://github.com/user-attachments/assets/5ff0a7ca-4336-4c86-9f74-eb0c48ff4da1)
![Screenshot (560)](https://github.com/user-attachments/assets/04b93b14-ed22-4411-9155-e5f8f2f7127d)
![Screenshot (559)](https://github.com/user-attachments/assets/464a6391-6f29-4856-9a04-f038a9525cec)
![Screenshot (558)](https://github.com/user-attachments/assets/9712018f-73d5-4762-ba38-37343105c5e3)
![Screenshot (557)](https://github.com/user-attachments/assets/3c999607-e013-4a52-9660-28c7cc13b282)
![إرشادات استخدام البرنامج](https://github.com/user-attachments/assets/946c769b-7c4e-49f8-8ef4-9fc3596cabb9)
![Screenshot (569)](https://github.com/user-attachments/assets/e114e825-1b1c-424f-9a74-4c79a9d39545)
![Screenshot (568)](https://github.com/user-attachments/assets/96477cd9-8b16-49b0-82f5-1014c63f0758)
![Screenshot (567)](https://github.com/user-attachments/assets/5f047c6c-9438-4242-84d0-a72ea13d6cdd)
![Screenshot (566)](https://github.com/user-attachments/assets/887f1483-7b0f-42d5-ad7b-be0b9bf41f4e)
![Screenshot (565)](https://github.com/user-attachments/assets/305c1f6d-29cf-4188-9f1b-9e397603a18a)
