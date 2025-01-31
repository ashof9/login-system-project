# README for Login System Project

## Project Overview
This project implements a simple login system with different user roles (admin and staff) using Python. It provides a user-friendly interface for both roles to access their respective functionalities.

## Features
- User authentication for admin and staff roles.
- Admin functionalities include viewing statistics and managing users.
- Staff functionalities include viewing reports and submitting requests.

## Project Structure
```
login-system-project
├── src
│   ├── __init__.py
│   ├── app.py
│   ├── auth
│   │   ├── __init__.py
│   │   ├── login.py
│   │   └── roles.py
│   ├── views
│   │   ├── __init__.py
│   │   ├── admin_view.py
│   │   └── staff_view.py
│   └── utils
│       ├── __init__.py
│       └── helpers.py
├── requirements.txt
└── README.md
```

## Installation
1. Clone the repository:
   ```
   git clone <repository-url>
   ```
2. Navigate to the project directory:
   ```
   cd login-system-project
   ```
3. Install the required dependencies:
   ```
   pip install -r requirements.txt
   ```

## Usage
1. Run the application:
   ```
   python src/app.py
   ```
2. Access the application in your web browser at `http://localhost:5000`.

## Contributing
Contributions are welcome! Please submit a pull request or open an issue for any enhancements or bug fixes.

## License
This project is licensed under the MIT License. See the LICENSE file for details.