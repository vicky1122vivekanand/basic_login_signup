# Basic Login & Signup Project

A simple and straightforward login and signup application built with HTML, CSS, and JavaScript. This project provides user authentication functionality with form validation for registration and login processes.

## 🌟 Features

- **User Registration**: Create new user accounts with validation
- **User Login**: Authenticate existing users
- **Form Validation**: 
  - Name validation (no numbers allowed)
  - Email validation (must be in @gmail.com format)
  - Password strength requirements (minimum 6 characters)
  - Password confirmation matching
  - Duplicate account prevention
  - Required field checking
- **User-Friendly Interface**: Simple and intuitive design
- **Data Storage**: In-memory storage using arrays for user data

## 🛠️ Technologies Used

- **Frontend**: HTML, CSS, JavaScript
- **Architecture**: Client-side validation and authentication

## 📋 Requirements

- Modern web browser (Chrome, Firefox, Safari, Edge)
- No external dependencies required

## 🚀 Getting Started

### Installation

1. Clone the repository:
```bash
git clone https://github.com/vicky1122vivekanand/basic_login_signup.git
cd basic_login_signup
```

2. Open the project in your browser:
   - Simply open the HTML file in your web browser
   - Or visit the live demo: [https://vicky-project-beta.vercel.app](https://vicky-project-beta.vercel.app)

## 📝 Usage

### Registration
1. Fill in your name (no numbers allowed)
2. Enter a valid email address (must end with @gmail.com)
3. Create a password (minimum 6 characters)
4. Confirm your password
5. Submit the form

### Login
1. Enter your registered email address
2. Enter your password
3. Submit the form to authenticate

## 📁 Project Structure

```
basic_login_signup/
├── README.md           # Project documentation
├── first.js           # Main JavaScript file with authentication logic
├── index.html         # HTML structure
└── style.css          # Styling (if present)
```

## 🔐 Validation Rules

| Field | Rules |
|-------|-------|
| Name | No numbers allowed |
| Email | Must be in format: user@gmail.com |
| Password | Minimum 6 characters |
| Password Confirmation | Must match the password |
| Duplicate Accounts | Not allowed |

## ⚙️ How It Works

The application uses JavaScript arrays to store user data:
- `username[]` - Stores registered usernames
- `data_email[]` - Stores registered email addresses
- `pass[]` - Stores registered passwords

### Registration Process
1. Validates all input fields
2. Checks for existing accounts
3. Verifies password confirmation
4. Stores user data in arrays

### Login Process
1. Validates email and password fields
2. Searches for matching credentials
3. Displays welcome message on successful login

## 🔄 Future Enhancements

- [ ] Backend database integration (MongoDB, Firebase)
- [ ] Secure password hashing
- [ ] Session management
- [ ] Email verification
- [ ] Password recovery feature
- [ ] User profile management
- [ ] Responsive design improvements
- [ ] Remember me functionality

## 📝 Notes

**Important**: This project stores data in memory only. All data will be lost when the browser is refreshed. For production use, implement proper backend authentication with secure database storage.

## 👤 Author

**Vivekanand Mehta** (@vicky1122vivekanand)

## 📄 License

This project is open source and available under the MIT License.

## 🤝 Contributing

Contributions are welcome! Feel free to:
1. Fork the repository
2. Create a feature branch
3. Commit your changes
4. Push to the branch
5. Open a Pull Request

## 📞 Support

For issues or questions, please open an issue on the [GitHub repository](https://github.com/vicky1122vivekanand/basic_login_signup/issues).

---

**Last Updated**: 2026-04-26 09:49:07