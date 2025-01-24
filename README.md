
# Google-Spread-Sheets

Project Title Google Spreadsheets

Project Overview

This project replicates the functionality of a spreadsheet application like Google Sheets. It provides a grid-based interface, supports mathematical formulas, drag-and-drop functionality, data validation, and allows users to save and load their spreadsheets. Built using HTML, CSS, and JavaScript, it demonstrates the use of front-end technologies and data structures to create an interactive and robust web application.

Features Grid-based spreadsheet interface with editable cells. Support for basic mathematical functions like SUM, AVERAGE, MAX,MIN,COUNT,TRIM,UPPER,LOWER,REMOVE_DUPLICATES,FIND_AND_REPLACE etc. Drag-and-drop functionality for rearranging rows, columns, and resizing. and allow users to save and load their spreadsheets Data validation and conditional formatting for quality assurance. Save and load functionality using JSON.

SpreadSheet Interface Dynamic grid: a dynamic spreadsheet grid with editable cells. Headers:Column and row headers to navigate celss easily. Cell Interaction: Supports adding,deleting, and resizing rows and columns. Formatting options:Apply bold italic,underline and text colour formatting to cells.

Technical Stack and Justification

HTML (Structure) Purpose: Provides the basic structure of the application, including the grid layout and user interface elements like buttons and headers.
Reason for Use:

Semantic and easy-to-use markup language. Ensures cross-browser compatibility. Works seamlessly with CSS and JavaScript for web development.

CSS (Styling) Purpose: Enhances the visual presentation of the spreadsheet, ensuring a user-friendly interface.
Reason for Use:

Allows precise control over cell layout, grid alignment, and user interaction styles. Enables responsive design for different screen sizes. Supports animations for smoother drag-and-drop interactions.

JavaScript (Functionality) Purpose: Implements the dynamic behaviors, including mathematical functions, drag-and-drop, and save/load functionality.
Reason for Use:

Native support for browser-based applications. Provides tools for DOM manipulation to handle user interactions. Facilitates formula parsing, mathematical calculations, and event-driven programming. 4. JSON (Data Management) Purpose: Manages data persistence by saving and loading spreadsheet data.

Reason for Use:

Lightweight and easy to parse with JavaScript. Supports hierarchical data, making it ideal for storing spreadsheet structures, formulas, and values. Allows users to download and share spreadsheet data.

Testing Frameworks (Optional) Purpose: Ensures the application performs as expected under various scenarios.
Reason for Use:

Frameworks like Jest or Mocha streamline unit and integration testing. Helps verify the accuracy of mathematical calculations, drag-and-drop behavior, and save/load operations.

Data Structures Used and Their Roles

2D Array Purpose: Represents the spreadsheet grid where each cell corresponds to an element in the 2D array.
Reason for Use:

Provides an intuitive mapping of rows and columns. Easy to access and update specific cell data using indices.

HashMap (or JavaScript Object) Purpose: Stores formulas and their relationships to dependent cells.
Reason for Use:

Efficient lookup for formula evaluations and updates. Enables quick identification of cells affected by changes in dependent values.

Queue Purpose: Handles dependencies for recalculating formulas.
Reason for Use:

Ensures proper order of recalculations when cells have dependencies (e.g., A1 depends on B1, which depends on C1).

Event Listeners (JavaScript Objects) Purpose: Manage user interactions like clicks, drags, and cell edits.
Reason for Use:

Native to JavaScript, providing efficient handling of user-triggered actions. Allows dynamic updates to the interface in real time.

Why This Stack and Data Structures? Simplicity and Compatibility:

The HTML, CSS, and JavaScript stack is universally supported by all modern web browsers without additional plugins. Scalability:

The combination of a 2D array for grid representation and a HashMap for formula management ensures the application scales well with larger datasets. Efficiency:

JSON enables lightweight and efficient data storage. Event-driven programming in JavaScript ensures the application responds quickly to user inputs.

Modularity:

The separation of structure (HTML), style (CSS), and behavior (JavaScript) ensures clean and maintainable code.

Flexibility:

The use of queues and hashmaps supports complex dependencies, making the application robust for advanced features.

Installation and Usage

Clone the repository to any IDE(VS code,Eclipse etc)

Open index.html in a web browser.

Edit cells, use formulas, drag rows/columns, and save/load spreadsheets.
