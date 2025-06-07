# Student Enrollment Form Using JsonPowerDB

### A simple web-based student enrollment form integrated with JsonPowerDB to perform CRUD operations on the STUDENT-TABLE relation of SCHOOL-DB database.

---

## Description

This project demonstrates the basics of **JsonPowerDB (JPDB)** by creating a fully functional **Student Enrollment Form**. The form allows users to enter, save, update, and reset student records with fields such as Roll No (Primary Key), Full Name, Class, Birth Date, Address, and Enrollment Date.

The form dynamically interacts with JsonPowerDB’s REST API to check if the Roll No exists and accordingly enables the appropriate controls for creating or updating records. The application also includes form validation to ensure no empty inputs before database operations.

---

## Benefits of Using JsonPowerDB

- **Serverless and REST API based** — no complex backend setup required.
- **Schema-free JSON document storage** — ideal for flexible student data.
- **High performance and real-time database engine** — powered by PowerIndeX.
- **Simplifies CRUD operations** using simple JSON requests and commands.
- **Lightweight and easy to integrate** with frontend applications.
- **Supports multi-mode database features** like document DB, RDBMS, key-value, geospatial, and time series.
- **Helps reduce development time and cost** by offering nimble APIs.

---

## Table of Contents

- [Description](#description)
- [Benefits of Using JsonPowerDB](#benefits-of-using-jsonpowerdb)
- [Scope of Functionalities](#scope-of-functionalities)
- [Examples of Use](#examples-of-use)
- [Project Status](#project-status)
- [Release History](#release-history)
- [Sources](#sources)
- [Additional Information](#additional-information)

---

## Scope of Functionalities

- Input and validation of student data fields.
- Check if a student record exists by Roll No.
- Save new student records if Roll No is not present.
- Update existing student records if Roll No exists.
- Reset form to initial state.
- Enable/disable form fields and buttons contextually based on user actions.
- Uses JsonPowerDB commands: `GET_BY_KEY`, `PUT`, and `UPDATE`.

---

## Examples of Use

- Enter a Roll No and press Enter or leave the field.
- If the Roll No is new, fill in other details and click **Save**.
- If the Roll No exists, form fields populate automatically and you can modify and click **Update**.
- Use **Reset** to clear and start over.

---

## Project Status

This project is currently **stable and functional** for basic CRUD operations on JsonPowerDB. Further enhancements can include:

- Better error handling.
- Support for asynchronous operations.
- UI/UX improvements.
- Integration with other JsonPowerDB features like advanced queries.

---

## Release History

- **v1.0** - Initial release with complete student enrollment form, validation, and JsonPowerDB integration.

---

## Sources

- JsonPowerDB Documentation: [http://login2explore.com/jpdb/docs.html](http://login2explore.com/jpdb/docs.html)
- JsonPowerDB Commons JS: [https://login2explore.com/jpdb-commons.js](https://login2explore.com/jpdb-commons.js)

---

## Illustrations

Dashboard of JsonPowerDB:

![Dashboard](https://github.com/BeAgarwal/JsonPowerDB/blob/master/Assets/Screenshots/Dashboard.PNG)

Student Enrollment Form (Example UI):

![Student Form Example](https://user-images.githubusercontent.com/yourusername/yourprojectpath/student-form-screenshot.png)  

---

## Additional Information

If you want to contribute or suggest improvements, please feel free to fork the repository and create a pull request.

---

### Acknowledgments

- Thanks to the JsonPowerDB team for providing an easy-to-use NoSQL database platform.
- Inspired by the official JsonPowerDB sample projects.

---

**Give this project a star if you find it useful!**

---

