# Fortuna Tracker
## Introduction
Our application, FortunaTracker, serves as an income and expense tracker designed to assist users in managing their finances effectively. It offers a user-friendly interface for easy money management and provides comprehensive data visualization through swing charts, allowing users to track their finances on a monthly, daily, and categorical basis. By empowering users with detailed financial information, our app enables them to make informed decisions and avoid financial hardships.

## SDG (No Poverty)
Fortuna Tracker aligns with - [Sustainable Development Goal No. 1: No Poverty](https://sdgs.un.org/goals/goal1) by providing various features and functionalities aimed at empowering users to manage their finances effectively.

## Here are the features of Fortuna Tracker:

### Expense Tracker
Allows users to record and categorize their expenses, providing insight into where money is being spent and facilitating budgeting to prevent overspending.

### Income Tracker
Enables users to log their income sources, helping them understand their earning patterns and ensuring a balanced financial inflow.

### Data Visualization
Utilizes visual representations such as charts and graphs to present financial data in an easily understandable format, aiding users in identifying trends, setting financial goals, and making informed decisions to improve their financial stability.

By offering these features, Fortuna Tracker serves as a proactive tool for individuals to take control of their financial situation, ultimately contributing to the global effort to eradicate poverty.

## Application GUI
### DashBoard

<img src="screenshot/LIGHT THEME DASHBOARD.png" alt="sample light full" width="400"/>&nbsp;
<img src="screenshot/DARK THEME DASHBOARD.png" alt="sample dark full" width="400"/>

### Tracker
<img src="screenshot/EXPENSE LIGHT.png" alt="sample light full" width="400"/>&nbsp;
<img src="screenshot/INCOME LIGHT.png" alt="sample light full" width="400"/>&nbsp;
<img src="screenshot/EXPENSE DARK.png" alt="sample dark full" width="400"/>&nbsp;
<img src="screenshot/INCOME DARK.png" alt="sample dark full" width="400"/>

### Drawer
<img src="screenshot/DRAWER LIGHT.png" alt="sample light full" width="400"/>&nbsp;
<img src="screenshot/DRAWER DARK.png" alt="sample light full" width="400"/>&nbsp;

## Class Summaries
### Class Application
This is the class that sets up the application with a custom look and feel by utilizing FlatLaf and custom fonts. Within this class, it initializes a main window with a background and shows the DashboardForm, which is the initial form displayed after running the application.

## Components Package 
### Class Background
This class is designed to serve as a background for the application's main window which extends JPanel. It also makes the window a rounded rectangle.
### Class MainForm
This class serves as the main form of the application, containing a header with buttons for menu and refresh functionality, as well as a scrollable panel for displaying content.
### Class SimpleForm
The class serves as a template or base class for creating forms in the application. This where it provides basic functionality of the forms such as initializing, opening, refreshing, and closing forms.

## Forms Package
### Class DashboardForm
This class represents the dashboard of the application, containing various financial charts such as pie, bar, and line charts for visualizing the financial data inputted by the user such as daily, monthly, and categorical income and expenses.
### Class ExpenseForm & IncomeForm
This class represents the form for tracking income and expenses. This allows users to input and track their income and expenses by providing fields for entering the date, description, amount, and category of an expense. This also allows users to add new expenses, delete existing ones, and view their balance.

## Menu Package
### Class FormManager
This class manages the navigation and display of forms within the application, including the transition animations, and UI updates.

### Class Menu & MyDrawerBuilder
The Menu class is responsible for the functionality of the main menu panel in the application.

While the MyDrawerBuilder extends the Menu which is responsible for the customization of the drawer menu of the application, including its content and behavior.

### Class ThemesChange
This class is responsible for handling theme changes in the application.

## Highlights
### Flatlaf
FlatLaf is a modern and versatile look and feel library for Java Swing applications. It provides a flat and clean design aesthetic, inspired by modern UI design trends. FlatLaf offers various themes and styles, allowing easy customization of the application’s appearance.

### Mysql Database
The data inputted by the users is stored in a MySQL database which is a powerful and versatile database system used for managing and manipulating data. Additionally, SQLite Studio was used to edit the databases.

<img src="screenshot/DB BALANCE.png" alt="sample light full" width="400"/>&nbsp;
<img src="screenshot/DB EXPENSES.png" alt="sample light full" width="400"/>&nbsp;
<img src="screenshot/DB INCOME.png" alt="sample dark full" width="400"/>

