# Recipe Management System 🍴

A web application for managing recipes, built using **HTML**, **CSS**, **Bootstrap**, **JavaScript**, **Spring Boot**, and **MySQL**. The Recipe Management System allows users to securely manage, view, add, and edit recipes with ease.

---

## Features ✨

- **User Authentication:** 🔒 Secure login and registration with real-time form validation.
- **Recipe Management:**
  - 📋 View a list of recipes dynamically.
  - 📖 Access detailed information about each recipe.
  - ✏️ Add and edit recipes, including images and multiple ingredients.
- **Responsive Design:** 📱 Built with Bootstrap for consistent and responsive user experience across devices.
- **CRUD Operations:** 🛠️ Full Create, Read, Update, and Delete functionality for recipes.
- **Image Uploads:** 🖼️ Supports adding images for recipes.
- **Database Integration:** 🗄️ Data is securely stored and retrieved using MySQL.

---

## Technologies Used 💻

### Frontend
- **HTML5**
- **CSS3**
- **Bootstrap**
- **JavaScript**

### Backend
- **Spring Boot Framework**
- **MySQL Database**
- **RESTful APIs**

---

## Installation 🛠️

Follow these steps to set up the project locally:

1. **Clone the Repository:**
   ```bash
   git clone https://github.com/your-username/recipe-management-system.git
   cd recipe-management-system
   ```

2. **Backend Setup:**
   - Ensure Java (JDK 17+) and Maven are installed.
   - Navigate to the backend folder:
     ```bash
     cd backend
     ```
   - Configure your MySQL database credentials in `application.properties`:
     ```properties
     spring.datasource.url=jdbc:mysql://localhost:3306/recipe_db
     spring.datasource.username=your_username
     spring.datasource.password=your_password
     ```
   - Run the Spring Boot application:
     ```bash
     mvn spring-boot:run
     ```

3. **Frontend Setup:**
   - Open the frontend folder:
     ```bash
     cd frontend
     ```
   - Open the `index.html` file in your browser or serve the static files using a web server.

---

## Usage 🍽️

1. **Register:** Create a new user account through the registration page.
2. **Login:** Access the application using your credentials.
3. **Manage Recipes:**
   - ➕ Add new recipes with images and multiple ingredients.
   - ✏️ Edit or ❌ delete existing recipes.
   - 🔍 View recipe details dynamically.

---

## Folder Structure 📂

```plaintext
recipe-management-system/
├── backend/             # Backend code (Spring Boot)
│   ├── src/             # Source code for controllers, services, models
│   ├── pom.xml          # Maven configuration
│   └── application.properties  # Database configurations
├── frontend/            # Frontend code
│   ├── index.html       # Main HTML file
│   ├── assets/          # CSS, JS, and image assets
├── README.md            # Project documentation
```

---



## Contributing 🤝

Contributions are welcome! Please fork the repository and submit a pull request.

---

## License 📜

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

---

## Acknowledgments 🙌

- Built with Spring Boot and MySQL.
- Frontend styled with Bootstrap.

---

