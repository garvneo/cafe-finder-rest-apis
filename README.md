# cafe-finder-rest-apis

## Coffee & Wifi - Find Your Perfect Work Spot

This Flask application allows users to discover cafes in their area that are suitable for remote work by providing information about coffee quality, wifi strength, and power outlet availability.

### Tools Used

* **Flask:** A lightweight web framework for building Python web applications. 
* **Flask-Bootstrap:** A Flask extension that integrates the Bootstrap CSS framework for easy styling and responsiveness.
* **Flask-WTF:** A Flask extension that simplifies working with web forms and validation.
* **WTForms:** A library for creating and validating forms in web applications.
* **CSV (comma-separated values):** A simple file format used to store tabular data, suitable for storing cafe information.

### Running the Application

1. **Install dependencies:** Ensure you have Python 3 and `pip` installed. Then, run the following command in your terminal:

   ```bash
   pip install -r requirements.txt
   python wificafe_main.py

### Learning from This Project

Building this application provided an opportunity to:

* **Learn Flask fundamentals:** Understand how Flask facilitates routing, templating, form handling, and database interactions (not directly implemented in this project).
* **Integrate form validation:** Utilize WTForms and Flask-WTF to ensure user-submitted data is valid before processing.
* **Work with CSV files:** Read and write data from a CSV file for persistent cafe information storage.
* **Implement basic CRUD operations (Create, Read, Update, Delete):** While not fully implemented here (only Create is included), the foundation is laid for future enhancements.
* **Leverage Bootstrap for styling:** Rapidly style the application using Bootstrap components and classes.

### Next Steps

Will implement the following and upgrading the project in upcoming time:

* **Implement full CRUD operations:** Allow users to edit or delete existing cafe entries.
* **Search functionality:** Enable users to search for cafes based on location keywords, wifi rating, etc.
* **User accounts and authentication:** Create a user system to personalize experiences and allow for potentially adding favorite cafes.
* **Deployment:** Deploy the application to a production server to make it publicly accessible.
   
