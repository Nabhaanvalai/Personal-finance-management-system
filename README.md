# Personal Finance Management System

A web-based application for managing personal finances, tracking expenses, setting budgets, and monitoring financial goals.

## Features

- **Dashboard Overview**: View financial summaries, balance, expenses, savings, and investments at a glance
- **Financial Tracking**: Update and monitor your income, expenses, savings, and investments
- **Budgeting Tools**: Create and manage budget categories with customizable limits
- **Expense Tracking**: Log and categorize your expenses
- **Financial Goals**: Set and track progress towards your financial goals
- **Investment Tracking**: Monitor your investment portfolio and returns
- **Reports**: Generate financial reports and visualizations

## Technologies Used

- HTML5
- CSS (Tailwind CSS)
- JavaScript
- Chart.js for data visualization
- Firebase Authentication (configured but requires API keys)

## Getting Started

### Prerequisites

- A modern web browser
- Internet connection (for CDN resources)

### Installation

1. Clone this repository:
   ```
   git clone https://github.com/yourusername/personal-finance-management-system.git
   ```

2. Open any of the HTML files in your web browser:
   - `dashboard.html` - Main application dashboard
   - `auth.html` - Login page
   - `signup.html` - Registration page

### Firebase Configuration

To enable authentication features:

1. Create a Firebase project at [https://firebase.google.com/](https://firebase.google.com/)
2. Obtain your Firebase configuration (API keys, etc.)
3. Update the Firebase configuration in `signup.html`:

```javascript
const firebaseConfig = {
  apiKey: "YOUR_API_KEY",
  authDomain: "YOUR_AUTH_DOMAIN",
  projectId: "YOUR_PROJECT_ID",
  storageBucket: "YOUR_STORAGE_BUCKET",
  messagingSenderId: "YOUR_MESSAGING_SENDER_ID",
  appId: "YOUR_APP_ID"
};
```

## Usage

1. Create an account using the Sign Up page
2. Log in with your credentials
3. Use the sidebar navigation to access different features:
   - Overview: View financial summaries and recent transactions
   - Update Info: Enter your financial information
   - Budgeting: Create and manage budget categories
   - Goals: Set and track financial goals
   - Reports: Generate financial reports

## Project Structure

- `dashboard.html` - Main application interface with all features
- `auth.html` - User login page
- `signup.html` - New user registration page

## Future Enhancements

- Data persistence with a backend database
- Mobile-responsive design improvements
- Export/import functionality for financial data
- Multi-currency support
- Financial advice and recommendations based on spending patterns

## License

This project is licensed under the MIT License - see the LICENSE file for details.

## Acknowledgments

- Tailwind CSS for the UI framework
- Chart.js for data visualization components 