# Expense Tracker

## Project Overview
The Expense Tracker is a user-friendly web application designed to help individuals manage their financial expenses efficiently. It provides functionality to add, view, and analyze expenses while offering a visual representation of spending habits through charts. The application stores data locally, ensuring that user information persists across sessions.
it is hosted on avpthegreat.site
---

## Features

### 1. **Add Expenses**
- Users can log their expenses by entering:
  - Expense Name
  - Amount (in INR)
  - Date (with a shortcut to set "Today")
  - Category (e.g., Food, Travel, Others)
  - Optional notes
- Form validations ensure all required fields are filled correctly before submission.

### 2. **View Expenses**
- Expenses are displayed in a neatly styled list format with:
  - Name, amount, and date
  - Category-specific color indicators:
    - **Food**: Pink border
    - **Travel**: Blue border
    - **Others**: Purple border
  - Notes, if provided

### 3. **Visualize Spending**
- A chart section provides a graphical representation of expenses using a bar chart or pie chart powered by the Chart.js library.
- Filters allow users to narrow down their analysis by:
  - Specific day (date picker)
  - Specific month (month picker)

### 4. **Navigation**
- Simple navigation buttons to toggle between sections:
  - **Show Expenses**: Displays the list of all recorded expenses.
  - **Show Chart**: Switches to the chart view for analysis.
  - **Export Expenses**: (Future feature placeholder) Intended for exporting expenses as files.

### 5. **Data Persistence**
- Expenses are saved in the browser's local storage, ensuring data remains available even after refreshing the page.

---

## Technologies Used

### Frontend
- **HTML**: For structuring the application
- **CSS**: For styling and responsive design
  - Custom styles for navigation, form, and list items
  - Category-specific color indicators
  - Popup animations for user feedback
- **JavaScript**: For dynamic interactions and data management
  - Event-driven form handling
  - Local storage integration for saving and retrieving expenses
  - Chart rendering with Chart.js

### External Libraries
- **Google Fonts**: Fonts used include Exo 2, Jersey 15, and Sixtyfour
- **Chart.js**: For creating interactive and visually appealing charts

---

## Code Structure

### HTML
- Defined a clean structure with semantic tags
- Form elements include proper `aria-labels` for accessibility
- Responsive layout with container elements and flexbox styling

### CSS
- Organized styles for:
  - General layout (body, container)
  - Navigation bar and buttons
  - Expense form and list
  - Chart and popup components
- Applied media queries for responsiveness on smaller devices

### JavaScript
- Modular functions to:
  - Handle form submissions and validations
  - Render the expense list dynamically
  - Toggle visibility between sections
  - Filter and render the expense chart
- Integrated local storage for saving and loading expenses

---

## Installation & Setup
1. Clone the repository to your local machine:
   ```bash
   git clone https://github.com/your-repo/expense-tracker.git
   ```
2. Open the project folder:
   ```bash
   cd expense-tracker
   ```
3. Open the `index.html` file in a web browser to run the application.

---

## Usage
1. Navigate to the application in your browser.
2. Use the **Add Expense** form to log expenses.
3. View all expenses in the **Expenses** section.
4. Analyze your spending using the **Spending Chart**.
5. Data is saved automatically and persists across sessions.

---

## Demo
- **Expense Form**: Log details of each expense, including category and optional notes.
- **Expense List**: View all expenses with category-specific indicators.
- **Chart Section**: Visualize spending patterns with filter options.

---

## External Dependencies
- [Chart.js CDN](https://cdn.jsdelivr.net/npm/chart.js): For chart rendering
- [Google Fonts](https://fonts.google.com): For typography

---

## License
This project is licensed under the MIT License. Feel free to use and modify it as needed.
