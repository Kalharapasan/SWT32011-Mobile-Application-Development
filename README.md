# SWT32011 - Mobile Application Development

This repository contains lab work and projects for the Mobile Application Development course (SWT32011), covering Android development fundamentals and advanced concepts.

## 📚 Course Overview

This repository documents hands-on learning through practical Android applications, organized by day and topic. The course covers the complete Android development lifecycle, from basic UI components to complex database-driven applications with authentication systems.

### Learning Objectives
- Master Android application architecture and lifecycle
- Implement responsive and interactive user interfaces
- Handle user input, validation, and event-driven programming
- Work with local data storage using SQLite databases
- Navigate between activities and pass data efficiently
- Integrate web content and multimedia components
- Apply best practices in mobile application development

## 📂 Repository Structure

### Lab Work Sessions
The `00.LabWork/` directory contains organized lab sessions from September 2025 to February 2026, covering the progression of Android development concepts across 26+ sessions.

### Projects

#### Basic UI Components
- **01.GitUpload** - Initial project setup and Git integration
  - Project structure setup
  - Version control basics
  - Gradle configuration

- **02.Add_Tow_Number** - Basic input handling and arithmetic operations
  - EditText input fields
  - Type conversion (String to Number)
  - Basic arithmetic operations
  - Result display with TextView

- **03Onclick_Button** - Button click events and event handling
  - OnClickListener implementation
  - Event handling patterns
  - UI interaction feedback

- **04SeekBar** - Progress and seek bar implementation
  - SeekBar widget usage
  - OnSeekBarChangeListener
  - Real-time value updates
  - Progress tracking

- **05Checkbox** - Checkbox component usage
  - Multiple selection handling
  - Checkbox state management
  - CompoundButton.OnCheckedChangeListener

- **06RadioButton** - Radio button implementation
  - Single selection from options
  - Radio button state handling
  - User preference selection

- **07RadioGroup** - Radio group management
  - Grouped radio button handling
  - Automatic mutual exclusion
  - OnCheckedChangeListener for groups

- **08RatingBar** - Rating bar component
  - Star rating interface
  - Rating value retrieval
  - User feedback collection

#### Interactive Applications
- **09DiscountApplication** - Application with discount calculation logic
  - Percentage calculations
  - Original price and discount rate inputs
  - Final price computation
  - Business logic implementation

- **10Validation_in_textEditer** - Input validation techniques
  - Email validation
  - Phone number format checking
  - Required field validation
  - Pattern matching with regex
  - Error message display

- **14.Discount_App** - Enhanced discount calculator
  - Improved UI/UX design
  - Multiple discount types
  - Tax calculation integration
  - Result formatting

- **15.BackgruondColorChangerApp** - Dynamic UI color manipulation
  - Color picker implementation
  - Real-time UI updates
  - RGB/Hex color handling
  - View background modification

- **18.Calculater** - Full-featured calculator application
  - Basic arithmetic operations (+, -, ×, ÷)
  - Decimal number support
  - Clear and delete functions
  - Expression evaluation
  - Error handling for division by zero

#### Advanced UI Components
- **11ListView** - List view implementation
  - Custom ArrayAdapter creation
  - List item click handling
  - Dynamic data population
  - Scrollable list views

- **12AlertDialog** - Dialog boxes and alerts
  - Confirmation dialogs
  - Custom dialog layouts
  - Positive/Negative button actions
  - User decision prompts

- **13ImageView** - Image handling and display
  - Loading images from resources
  - Image scaling and positioning
  - ScaleType attributes
  - Basic image manipulation

- **25.ImageView** - Advanced image view techniques
  - Dynamic image loading
  - Image gallery implementation
  - Bitmap processing
  - Memory management for images

- **26.WebView** - Web content integration
  - Loading URLs in WebView
  - JavaScript enablement
  - WebViewClient configuration
  - Local HTML rendering
  - Web navigation controls

- **27.TimePicker** - Time selection component
  - 12/24 hour format support
  - Time selection dialogs
  - TimePickerDialog implementation
  - Selected time retrieval

#### Navigation & Data Passing
- **16.OpenOtherWindow** - Activity navigation
  - Intent creation and usage
  - startActivity() method
  - Activity lifecycle management
  - Back stack navigation

- **17.PassDataforOtherWindow** - Inter-activity data transfer
  - Intent extras (putExtra/getExtra)
  - Passing primitive data types
  - Passing complex objects
  - Data retrieval in target activity

#### Lists & RecyclerView
- **19.RECYCLERVIEW** - RecyclerView basics
  - RecyclerView setup and configuration
  - ViewHolder pattern implementation
  - LayoutManager (LinearLayoutManager)
  - Basic adapter creation

- **20.RecyclerView** - Advanced RecyclerView implementation
  - Custom ViewHolder design
  - Click listeners for items
  - GridLayoutManager and StaggeredGridLayoutManager
  - Item animations
  - Performance optimization techniques

#### Database & Storage
- **21.SQLite** - SQLite database basics
  - SQLiteOpenHelper implementation
  - Database creation and versioning
  - Table schema definition
  - Basic SQL query execution

- **21SQLite_Text** - SQLite text operations
  - Text data insertion
  - Query and retrieval methods
  - Cursor handling
  - Data type management

- **22SQLiteLoginRegistryandCURDoperation** - Complete CRUD operations with login/registration system
  - User registration with validation
  - Secure login authentication
  - Create, Read, Update, Delete operations
  - Password management
  - Session handling
  - User profile management

- **23.SQLite** - Advanced SQLite operations
  - Complex queries (JOIN, GROUP BY)
  - Database transactions
  - Data migration strategies
  - Query optimization

#### Menus & Toolbars
- **24.TOOLBARMENUS** - Toolbar and menu implementation
  - ActionBar/Toolbar setup
  - Menu resource files
  - Options menu creation
  - Menu item click handling
  - Context menus
  - Action icons and overflow menu

### Utility Files
- `DBHelper.java` - Database helper class
- `main_activity_java.java` - Main activity template
- `Other/` - Miscellaneous resources and utilities

## 🛠️ Technologies & Tools

### Development Environment
- **IDE:** Android Studio
- **Language:** Java (JDK 8+)
- **Build System:** Gradle (Kotlin DSL)
- **Version Control:** Git

### Android Components
- **Platform:** Android SDK (API Level 21+)
- **UI Framework:** Android XML Layouts
- **Architecture:** Activity-based navigation
- **Database:** SQLite with SQLiteOpenHelper

### Key Libraries & Components
- **UI Components:** 
  - Native Android Views (TextView, EditText, Button)
  - RecyclerView with ViewHolder pattern
  - WebView for web content
  - AlertDialog for user prompts
  - Custom adapters for lists
- **Data Storage:** SQLite database engine
- **Layout Managers:** LinearLayout, RelativeLayout, ConstraintLayout
- **Input Components:** EditText, SeekBar, CheckBox, RadioButton, TimePicker

## 📱 Key Concepts Covered

1. **Basic Android Components**
   - Activities and Layouts
   - UI Components (Buttons, TextViews, EditTexts)
   - Event Handling

2. **Intermediate Concepts**
   - List Views and Adapters
   - RecyclerView with ViewHolders
   - Custom Dialogs
   - Input Validation

3. **Advanced Topics**
   - SQLite Database Integration
   - CRUD Operations
   - Navigation Between Activities
   - Data Persistence
   - WebView Integration
   - Toolbar and Menu Systems

4. **Application Development**
   - User Authentication
   - Form Validation
   - Calculator Logic
   - Dynamic UI Updates

## 🚀 Getting Started

### Prerequisites
- Android Studio (Latest stable version recommended)
- JDK 8 or higher
- Android SDK (API Level 21 or higher)
- Android Virtual Device (AVD) or physical Android device
- Git for version control

### Installation Steps

1. **Clone the repository**
   ```bash
   git clone <repository-url>
   cd GitUpload
   ```

2. **Open a project in Android Studio**
   - Launch Android Studio
   - Select "Open an existing project"
   - Navigate to any project folder (e.g., `02.Add_Tow_Number/`)
   - Click OK

3. **Sync Gradle files**
   - Android Studio will automatically prompt to sync
   - Click "Sync Now" in the notification bar
   - Wait for dependencies to download

4. **Configure an emulator or device**
   - For emulator: Tools → Device Manager → Create Virtual Device
   - For physical device: Enable Developer Options and USB Debugging

5. **Run the application**
   - Click the Run button (▶) or press Shift+F10
   - Select target device
   - Wait for build and installation

### Troubleshooting

**Gradle sync fails:**
- Check internet connection
- Update Gradle version in `gradle-wrapper.properties`
- Invalidate caches: File → Invalidate Caches / Restart

**App crashes on startup:**
- Check LogCat for error messages
- Verify minimum SDK version compatibility
- Clean and rebuild project: Build → Clean Project

**Database errors:**
- Uninstall app from device/emulator to clear old database
- Check DBHelper version number for migrations
- Verify SQL syntax in database operations

## 📝 Course Timeline

- **Start Date:** September 9, 2025
- **Latest Session:** February 3, 2026
- **Total Sessions:** 26+ days of lab work
- **Duration:** ~5 months of intensive hands-on training
- **Format:** Progressive learning from basic to advanced concepts

## 📊 Project Statistics

- **Total Projects:** 27+ Android applications
- **Lab Sessions:** 26+ documented sessions
- **Technologies Mastered:** Java, Android SDK, SQLite, XML Layouts
- **Concepts Covered:** UI Components, Navigation, Database, Web Integration

## 🎯 Skills Developed

By completing this course, students gain proficiency in:
- Designing and implementing Android user interfaces
- Handling user interactions and event-driven programming
- Managing application state and lifecycle
- Implementing local data persistence with SQLite
- Creating responsive and adaptive layouts
- Debugging and troubleshooting Android applications
- Following Android development best practices
- Version control with Git

## 📚 Additional Resources

- **Android Developer Documentation:** https://developer.android.com/
- **Java Documentation:** https://docs.oracle.com/en/java/
- **Gradle Build Tool:** https://gradle.org/
- **Material Design Guidelines:** https://material.io/design

## 🤝 Contributing

This is an educational repository for course work. If you're a student in this course:
- Follow the lab instructions for each session
- Document your code with clear comments
- Test thoroughly before committing
- Use meaningful commit messages

## 📧 Course Information

- **Course Code:** SWT32011
- **Course Name:** Mobile Application Development
- **Focus:** Android Development with Java
- **Level:** Intermediate to Advanced

## 📄 License

Educational project for SWT32011 - Mobile Application Development course.

---

*Last Updated: February 3, 2026*
