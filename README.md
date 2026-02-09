# budgetTracker
Budget tracker mainly for students to calculate their spendings with a professional, full-featured budget tracking web application with dark/light mode support, analytics

## Features

### 🔐 User Authentication
- Welcome screen with user registration
- Persistent user sessions using localStorage
- Logout functionality

### 💰 Financial Management
- Track income and expenses with categories
- Real-time balance calculation
- Savings rate tracking
- Transaction history with filtering options

### 📊 Analytics & Visualizations
- **Weekly Spending Chart**: Bar chart showing daily expenses for the past 7 days
- **Category Breakdown**: Doughnut chart displaying top 5 spending categories
- Visual insights into spending patterns

### 🎨 Professional UI/UX
- Dark mode (default) with light mode toggle
- Sharp, professional design with minimal curves
- Responsive layout for desktop, tablet, and mobile
- Smooth navigation with sidebar menu
- Auto-scroll to sections when clicking sidebar items

### 🗂️ Sidebar Navigation
- **Main**: Dashboard, Transactions, Analytics
- **Categories**: Income, Expenses, Savings
- **Settings**: Profile, Preferences

### 💵 Transaction Features
- Add income or expenses
- Categorize transactions (Salary, Freelance, Food, Transport, etc.)
- Filter transactions by type (All, Income, Expenses)
- Delete individual transactions
- Amount displayed in Indian Rupees (₹)

## Technology Stack

- **HTML5**: Structure and markup
- **CSS3**: Styling with CSS variables for theming
- **JavaScript (ES6+)**: Application logic and interactivity
- **Chart.js**: Data visualization library
- **LocalStorage API**: Data persistence

## Installation

1. Download the `budget-tracker.html` file
2. Open it in any modern web browser (Chrome, Firefox, Safari, Edge)
3. No server or installation required - runs entirely in the browser

## Usage

### First Time Setup
1. Open the application
2. Enter your name on the welcome screen
3. Click "Get Started"

### Adding Transactions
1. Navigate to the "Add Transaction" section
2. Select transaction type (Income/Expense)
3. Enter description and amount
4. Choose a category
5. Click "Add Transaction"

### Viewing Analytics
- Click "Analytics" in the sidebar to view charts
- Weekly spending chart shows last 7 days
- Category breakdown shows top spending categories

### Switching Themes
- Click the sun/moon icon in the top-right corner
- Theme preference is saved automatically

### Logging Out
- Click the "Logout" button in the header
- Confirm logout in the dialog
- Your data remains saved for next login

## Data Persistence

All data is stored locally in your browser using localStorage:
- **User Information**: Username
- **Transactions**: All income and expense records
- **Theme Preference**: Dark or light mode selection

**Note**: Data is browser-specific. Clearing browser data will delete all stored information.

## Categories

### Income Categories
- Salary
- Freelance
- Investment

### Expense Categories
- Food & Dining
- Transportation
- Utilities
- Entertainment
- Shopping
- Healthcare
- Other

## Browser Compatibility

- ✅ Chrome (recommended)
- ✅ Firefox
- ✅ Safari
- ✅ Edge
- ✅ Opera

**Minimum Requirements**: Any modern browser with JavaScript enabled and localStorage support.

## Features Breakdown

### Summary Cards
- **Total Income**: All-time earnings in rupees
- **Total Expenses**: All-time spending in rupees
- **Balance**: Current balance (Income - Expenses)
- **Savings Rate**: Percentage of income saved

### Charts
- **Weekly Spending**: Visual representation of daily expenses
- **Category Breakdown**: Pie chart showing expense distribution by category

### Transaction Management
- Real-time transaction list
- Filter by type (All/Income/Expenses)
- Delete unwanted transactions
- Automatic balance updates

## Keyboard Shortcuts

- **Tab**: Navigate through form fields
- **Enter**: Submit forms
- **Escape**: Close dialogs (if applicable)

## Tips for Best Experience

1. **Regular Updates**: Add transactions regularly for accurate tracking
2. **Categorization**: Use appropriate categories for better insights
3. **Review Analytics**: Check weekly spending and category breakdown regularly
4. **Backup**: Export or note down important data periodically (browser-dependent)

## Privacy & Security

- All data is stored locally on your device
- No data is sent to external servers
- No account creation or personal information required beyond a display name
- Clear browser data to completely remove all stored information

## Troubleshooting

### Data Not Saving
- Ensure cookies/localStorage is enabled in browser settings
- Check if browser is in private/incognito mode
- Try refreshing the page

### Charts Not Displaying
- Ensure JavaScript is enabled
- Check browser console for errors
- Verify internet connection (for loading Chart.js library)

### Theme Not Switching
- Try clearing browser cache
- Check if localStorage is enabled
- Refresh the page after theme change

## Future Enhancements (Potential)

- Export data to CSV/Excel
- Budget goals and alerts
- Recurring transactions
- Multiple currency support
- Monthly/yearly reports
- Custom categories
- Data backup and restore

## Credits

- **Chart.js**: For beautiful, responsive charts
- **Design**: Professional dark/light theme with sharp edges
- **Icons**: SVG icons for clean, scalable graphics

## License

This project is free to use and modify for personal and commercial purposes.

## Support

For issues or questions:
1. Check the troubleshooting section
2. Ensure you're using a modern browser
3. Clear cache and try again

---

**Version**: 1.0.0  
**Last Updated**: 2025 
**Author**: Ajmal

Enjoy tracking your finances! 💰📊

<img width="1917" height="878" alt="Screenshot 2026-02-09 202317" src="https://github.com/user-attachments/assets/fe25a958-2ba4-48c9-a193-e555b33e349b" />
<img width="1531" height="894" alt="Screenshot 2026-02-09 202450" src="https://github.com/user-attachments/assets/1f6f5c39-1724-4a35-9641-b2b42288d8ac" />

