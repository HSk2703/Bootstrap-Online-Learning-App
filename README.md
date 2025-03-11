# Bootstrap Online Learning App

This project is a **responsive online learning platform** developed using Bootstrap, HTML, CSS, and JavaScript. It offers users access to a variety of courses, interactive lessons, and a seamless learning experience across devices.

## Features

- **Responsive Design** – Ensures optimal viewing and interaction across desktops, tablets, and mobile devices.
- **Course Catalog** – Browse and search through a wide range of courses.
- **Interactive Lessons** – Engage with multimedia content, quizzes, and assignments.
- **User Authentication** – Secure login and registration system.
- **Profile Management** – Users can view and edit their profiles.

## Technologies Used

- **Bootstrap** – For responsive and modern UI components.
- **HTML5 & CSS3** – Structure and styling of the web pages.
- **JavaScript** – Interactive elements and functionality.
- **Python & Django** – Backend development and server-side logic.
- **SQLite** – Database management.

## Project Structure

```
Bootstrap-Online-Learning-App/
├── myproject/          # Main project settings and configurations
├── onlinecourse/       # Core application handling courses and lessons
├── static/             # Static files (CSS, JavaScript, images)
├── templates/          # HTML templates
├── db.sqlite3          # SQLite database
├── manage.py           # Django management script
├── requirements.txt    # Project dependencies
├── runtime.txt         # Python runtime environment
```

## Getting Started

To set up the project locally:

### 1. Clone the Repository

```bash
git clone https://github.com/HSk2703/Bootstrap-Online-Learning-App.git
cd Bootstrap-Online-Learning-App
```

### 2. Create and Activate a Virtual Environment

```bash
python -m venv env
```

#### On Windows:
```bash
env\Scripts\activate
```

#### On macOS/Linux:
```bash
source env/bin/activate
```

### 3. Install Dependencies

```bash
pip install -r requirements.txt
```

### 4. Apply Migrations

```bash
python manage.py migrate
```

### 5. Run the Development Server

```bash
python manage.py runserver
```

### 6. Access the Application

Open your web browser and navigate to:

👉 [http://127.0.0.1:8000/](http://127.0.0.1:8000/)

## Contributing

Contributions are welcome! To contribute:

1. **Fork the repository**.
2. **Create a new branch** for your feature or bug fix.
3. **Commit your changes** with clear and descriptive messages.
4. **Push your changes** to your forked repository.
5. **Submit a pull request** detailing your changes.

## License

This project is licensed under the **MIT License**. See the `LICENSE` file for more information.

