## Project Description

### Objective:

The "Book Management System" project aims to provide users with a tool for monitoring their progress with reading books, storing notes and files related to books, and inputting data about books and their authors. The application facilitates efficient management of reading materials and helps organize information about books and their creators.

### Feature Description:

- **Reading Progress Monitoring:** Users can track their reading progress by specifying the currently read pages or chapters of each book.
- **Notes and Files Storage:** Ability to add notes and upload files (e.g., images, documents) related to the books being read, aiding in information organization and retention of important content.
- **Inputting Book Data:** Users can input information about books, such as title, author, genre, publisher, etc.
- **Inputting Author Data:** Ability to add data about book authors, including name, surname, biography, publication list, etc.

## Requirements Analysis

### Functional Requirements:

- **Reading Progress Monitoring:** Users can specify the currently read pages or chapters of each book.
- **Notes and Files Storage:** The application allows users to add and view notes and files related to the books being read.
- **Inputting Book Data:** Users can input information about books, such as title, author, genre, publisher, etc.
- **Inputting Author Data:** Ability to add data about book authors, including name, surname, biography, publication list, etc.

### Non-functional Requirements:

- **Data Confidentiality:** Ensure the security of user data, especially when storing notes and files.
- **Interface Responsiveness:** Provide smooth operation of the application on different devices and screen sizes.
- **User-friendly Interface:** Create a clear and easy-to-use interface that enables users to quickly find the necessary functions.

## Interface Design

### Interface Sketches/Visualizations:

- _Home Page:_ Control panel with options for monitoring reading progress, adding notes and files, inputting book and author data.
- _Book Adding Form:_ Space for inputting data about a new book.
- _Author Adding Form:_ Space for adding data about a new author.
- _Book Details Page:_ Viewing detailed information about a specific book, including reading progress, notes, files, author information.

### Site Map:

- _Home Page_
  - Control panel
  - Reading progress monitoring options
  - Adding notes and files
  - Inputting book and author data
- _Book Adding Form_
  - Fields for inputting book data
  - "Add Book" button
- _Author Adding Form_
  - Fields for inputting author data
  - "Add Author" button
- _Book Details Page_
  - Book information (title, author, genre, etc.)
  - Notes and uploaded files
  - Author information

## System Architecture

### Data Structure Description:

The application stores data related to books and authors, including:

- **Books:** Contains information such as title, author, genre, publisher, reading progress, notes, and uploaded files.
- **Authors:** Stores data about authors, including name, surname, biography, publication list.

### Architecture Diagrams:

The architecture is based on a layered structure, where:

- **Model:** Responsible for managing book and author data logic.
- **View:** Presents the user interface.
- **Controller:** Manages communication between the model and the view.

## Implementation

### Technology Description:

- **Frontend:** HTML, CSS, JavaScript (React.js).
- **Backend:** Flask (Python), SQLite (database).
- **Authorization and Authentication:** JWT (JSON Web Tokens) to ensure user data security.

### Code Structure:

- _Directories/Files_: Separate files for data management logic, interface, user control.
- _Coding Style_: Utilize modularity, readability, and comments in the code.

## Testing

### Testing Plan:

- **Unit Tests:** Verify the correctness of book and author data management functions.
- **Integration Tests:** Ensure that components cooperate correctly.
- **User Interface Tests:** Check user interaction on different devices.
- **Security Tests:** Evaluate application security, especially regarding user data storage.

### Testing Procedures:

- Develop a set of test cases for each application function.
- Establish procedures for reporting and fixing discovered bugs.

## Deployment and Maintenance

### Deployment Plan:

- **Deployment Stages:** Testing, corrections, publication on platforms available to users.
- **Deadlines:** Determine dates for planned stages.

### Maintenance Procedures:

- **Technical Support:** Establish communication channels with users for issue reporting.
- **Updates:** Plan regular updates based on user feedback and needs.

## Schedule

### Project Plan:

- **Implementation Stages:** Divide work into specific tasks (e.g., implementing reading progress monitoring, adding notes and files, inputting book and author data).
- **Deadlines:** Determine the time needed for each stage.

## Budget

### Estimated Costs:

- **Application Development:** Based on hours of work or team of developers.
- **Maintenance Costs:** Servers, potential fees for external services, technical support.

---

[Polish](<Documents/README(PL).md>)
