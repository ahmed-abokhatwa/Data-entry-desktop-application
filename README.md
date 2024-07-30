# Data-entry-desktop-application
A desktop application built with Python for TAQA Company. Here's a breakdown of its functionalities:

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

* It seems likely that the application validates the data entered by the user. This could involve checking formats (e.g., date format) and ranges (e.g., total amount cannot be negative).

**Data Storage and Management:**

* The application uses pandas, a Python library for data analysis, to store the entered data in a format likely  a DataFrame.
* It saves this DataFrame to a pre-defined Excel file (`taqa.xlsx`) on the user's system.
* A new sheet (`Sheet1`)  is used by default

**Graphical User Interface (GUI):**

* The application uses PyQt, a set of Python bindings for the Qt GUI toolkit, to create the user interface. 
* The interface is likely divided into sections:
    * A title section displaying the company name (TAQA) and potentially a date.
    * An information section where users enter details about the sale/service.
    * A results section displaying a table, possibly showing previously entered data.
    * A function section with buttons for potentially adding, editing, or clearing data.

**Additional Notes:**

* The code uses global variables (`df`, `filename`, `sheetname`), which is generally discouraged in larger applications due to potential maintainability issues.
* The UI seems to be designed for a right-to-left layout based on the `setLayoutDirection` settings.


Overall, this application provides a user-friendly way for TAQA Company to collect, validate, and store data related to sales or services. 
