Hello there, and thanks for taking the time to read my code!

**Sumamry**
This is a roster, using the names of Black artists, inventors, educators, and other public figueres, to represent fictional students with IEPs (Individualized Education Programs or Plans).
It holds special education related information to help with compliance, particulary dates of important documents.
The spreadsheet displays pop-up messages about the type and number of IEPs due and their general timeframe. 
The messages pop up whenever the spreadsheet is opened, refreshed, and when activated from the custom menu. 
There are 3 types of IEPs: initial, reevaluation (reeval), and annual, and due dates vary. 
To support the tracking of due dates, color coding is used. 
Red rows means overdue and orange or pink rows, that means the reeval or annual IEP is in 30 calendar days or 14 calendar days, respectfully 

**Successes**
- using a datedif formula to automatically calculate the age of the ficticious students based on the DOB (date of birth) entry
- incorporating drop down buttom option in order to select students' grade level
- labeling 2 types of IEPs (reeval and annual) correctly based on their date and IDEA laws
- color coding works for the following colors and IEP types: red for both reevals and annuals, orange for reevals
- running the script using triggers
- including a custom menu button to manual run the pop-up messages

**Challenges**
- maintaining the initial label for IEPs...instead the label is changed over to "annual" (remedy: for now, users are to rely on the "Initial_IEP" column for confirmation of an initial IEP or not)
- color coding for the following color and IEP type: pink for annuals

**Sources & Tools used**
- chatGPT
- Google Apps Script
