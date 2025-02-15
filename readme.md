# PETROBOTS Dustbin Monitoring System

The **PETROBOTS Dustbin Monitoring System** is a web-based application designed to track and display real-time dustbin progress and monitoring dustbin data. This system includes an interactive user interface with features such as dustbin progress tracking and user-friendly dashboards.

## Features

### Key Functionalities

- **Real time dustbin monitoring**: Tracks and updates dustbin status dynamically.
- **Progress Bar**: Displays the capacity progress of dustbin.
- **Dashboard:** Displays dustbin status and analytics.

## Project Structure

```
PETROBOTS/
├── PETROBOTS/
│   ├── README.md              # Project documentation
│   ├── app.py                 # Main application script (Flask-based)
│   ├── config.py              # Configuration settings
│   ├── static/                # Static files (CSS, JS, images)
│   │   ├── css/
│   │   ├── js/
│   │   ├── images/
│   ├── templates/             # HTML templates
│   │   ├── base.html
│   │   ├── index.html
│   │   ├── dashboard.html
│   ├── models.py              # Database models
│   ├── requirements.txt       # Required dependencies
│   ├── database/
│   │   ├── petro_db.sqlite3   # SQLite database
│   ├── utils/                 # Utility scripts
│   ├── tests/                 # Testing scripts
│   ├── .gitignore             # Git ignore file
```

## Installation and Setup

1. **Clone the Repository**
   ```sh
   git clone <repository-url>
   ```
2. **Navigate to the Project Directory**
   ```sh
   cd PETROBOTS-main
   ```
3. **Run on a Local Server**
   - Open `index.html` in a browser.
   - Use a local server such as XAMPP or a simple Python HTTP server:
     ```sh
     python -m http.server 8000
     ```

## Usage

- Open the home page to learn about rubbish accumulation.
- Navigate to Dustbin Track for monitoring dustbin progress.
- Navigate to Progress Bar to monitor the dustbin capacity progress.

## Contributing

Contributions are welcome! Fork the repository, make changes, and submit a pull request.

## License

This project is licensed under [].


