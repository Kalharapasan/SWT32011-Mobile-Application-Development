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

#### Session Progression Overview
- **Week 1-2 (Days 1-5):** Android fundamentals, UI basics, event handling
- **Week 3-4 (Days 6-10):** Advanced widgets, custom views, input validation
- **Week 5-6 (Days 11-15):** Lists, adapters, navigation patterns
- **Week 7-10 (Days 16-20):** Database integration, CRUD operations, authentication
- **Week 11-14 (Days 21-26):** Advanced features, web integration, menus, multimedia

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

## 🌟 Project Highlights

### Featured Projects

**Calculator Application (Day 18)**
- Complete arithmetic calculator with expression parsing
- Clean, intuitive Material Design interface
- Error handling and edge case management
- Demonstrates advanced UI state management

**SQLite Login & CRUD System (Day 22)**
- Full user authentication system
- Complete database lifecycle management
- Secure password handling techniques
- Real-world application architecture
- Demonstrates industry-standard patterns

**RecyclerView Implementation (Days 19-20)**
- Modern list handling with optimal performance
- Multiple layout manager implementations
- Custom view holders and adapters
- Efficient memory management

**WebView Integration (Day 26)**
- Seamless web content integration
- JavaScript bridge implementation
- Custom WebViewClient for navigation control
- Hybrid app development techniques

### Technical Achievements

**Database Management**
- Implemented relational database schemas
- Complex SQL queries with JOINs and aggregations
- Transaction management for data integrity
- Database versioning and migration strategies

**UI/UX Excellence**
- Responsive layouts for multiple screen sizes
- Material Design principles implementation
- Smooth animations and transitions
- Accessibility considerations

**Code Quality**
- Clean, maintainable code structure
- Proper separation of concerns
- Comprehensive error handling
- Code documentation and comments

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

## 🏗️ Architecture & Design Patterns

### Architectural Patterns Used

**Activity-Based Architecture**
- Each screen represented by an Activity
- Lifecycle-aware component management
- Intent-based navigation between screens
- Back stack management for navigation flow

**Database Layer Pattern**
- `DBHelper` class extending `SQLiteOpenHelper`
- Singleton pattern for database instance management
- DAO (Data Access Object) pattern for CRUD operations
- Separation of database logic from UI layer

**Adapter Pattern**
- Custom ArrayAdapters for ListView
- RecyclerView.Adapter with ViewHolder pattern
- Efficient view recycling for performance
- Data binding between model and view

### Design Patterns Implemented

**ViewHolder Pattern**
```java
// Efficient view recycling in RecyclerView
public class MyViewHolder extends RecyclerView.ViewHolder {
    TextView titleText;
    ImageView itemImage;
    
    public MyViewHolder(View itemView) {
        super(itemView);
        titleText = itemView.findViewById(R.id.title);
        itemImage = itemView.findViewById(R.id.image);
    }
}
```

**Singleton Pattern**
```java
// Database helper singleton
public class DBHelper extends SQLiteOpenHelper {
    private static DBHelper instance;
    
    public static synchronized DBHelper getInstance(Context context) {
        if (instance == null) {
            instance = new DBHelper(context.getApplicationContext());
        }
        return instance;
    }
}
```

**Observer Pattern**
- OnClickListener for button events
- OnSeekBarChangeListener for progress updates
- OnCheckedChangeListener for radio/checkbox state
- Custom callbacks for data updates

### Project Structure

```
app/
├── src/
│   ├── main/
│   │   ├── java/
│   │   │   └── com.example.app/
│   │   │       ├── activities/      # Activity classes
│   │   │       ├── adapters/        # List adapters
│   │   │       ├── database/        # DB helpers and DAOs
│   │   │       ├── models/          # Data models
│   │   │       └── utils/           # Utility classes
│   │   ├── res/
│   │   │   ├── layout/              # XML layouts
│   │   │   ├── drawable/            # Images and drawables
│   │   │   ├── values/              # Strings, colors, styles
│   │   │   └── menu/                # Menu resources
│   │   └── AndroidManifest.xml      # App configuration
│   └── test/                        # Unit tests
└── build.gradle                     # Dependencies
```

## 💡 Best Practices Implemented

### Code Organization
- **Meaningful naming conventions:** Variables and methods use descriptive names
- **Consistent code formatting:** Following Java coding standards
- **Modular design:** Separating concerns into different classes
- **Reusable components:** Creating utility classes for common functionality

### Android Best Practices

**Lifecycle Management**
- Proper handling of Activity lifecycle methods
- Saving and restoring instance state
- Releasing resources in onDestroy()
- Handling configuration changes (rotation)

**Memory Management**
- Closing database connections properly
- Releasing bitmap resources
- Avoiding memory leaks with listeners
- Using weak references where appropriate

**User Experience**
- Providing immediate feedback for user actions
- Loading indicators for long operations
- Input validation with clear error messages
- Graceful error handling and recovery

**Security Practices**
- Input sanitization to prevent SQL injection
- Secure password handling (though basic for learning)
- Validating user input before processing
- Proper permission handling

### Database Best Practices
- **Parameterized queries:** Using placeholders to prevent SQL injection
- **Transaction management:** Grouping operations for data integrity
- **Index optimization:** Adding indexes on frequently queried columns
- **Proper cursor management:** Always closing cursors after use

### UI/UX Best Practices
- **Responsive layouts:** Using ConstraintLayout for flexible designs
- **Material Design compliance:** Following Android design guidelines
- **Accessibility:** Providing content descriptions for images
- **Keyboard handling:** Proper IME options and input types

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

## � Development Workflow

### Standard Development Process

1. **Planning Phase**
   - Review lab requirements and specifications
   - Design UI mockup or wireframe
   - Plan database schema (if applicable)
   - Identify required components and libraries

2. **Implementation Phase**
   - Create XML layout files for UI
   - Implement Activity classes with logic
   - Set up database helpers (if needed)
   - Implement event handlers and listeners
   - Add input validation and error handling

3. **Testing Phase**
   - Test on emulator with different API levels
   - Test on physical device (if available)
   - Verify edge cases and error scenarios
   - Check for memory leaks and performance issues

4. **Refinement Phase**
   - Code cleanup and optimization
   - Add comments and documentation
   - Refactor for better maintainability
   - Final testing and verification

### Git Workflow

```bash
# Check current status
git status

# Stage changes
git add .

# Commit with descriptive message
git commit -m "Day XX: Implemented [feature description]"

# Push to repository
git push origin main
```

### Common Development Tasks

**Creating a new Activity:**
```java
// 1. Create Activity class
public class NewActivity extends AppCompatActivity {
    @Override
    protected void onCreate(Bundle savedInstanceState) {
        super.onCreate(savedInstanceState);
        setContentView(R.layout.activity_new);
    }
}

// 2. Register in AndroidManifest.xml
<activity android:name=".NewActivity" />
```

**Implementing a ListView:**
```java
// 1. Prepare data source
ArrayList<String> items = new ArrayList<>();

// 2. Create adapter
ArrayAdapter<String> adapter = new ArrayAdapter<>(this,
    android.R.layout.simple_list_item_1, items);

// 3. Set adapter to ListView
ListView listView = findViewById(R.id.listView);
listView.setAdapter(adapter);
```

**Database Operations:**
```java
// Create
ContentValues values = new ContentValues();
values.put("name", "John Doe");
db.insert("users", null, values);

// Read
Cursor cursor = db.query("users", null, null, null, null, null, null);

// Update
ContentValues values = new ContentValues();
values.put("name", "Jane Doe");
db.update("users", values, "id = ?", new String[]{"1"});

// Delete
db.delete("users", "id = ?", new String[]{"1"});
```

## 🧪 Testing & Quality Assurance

### Testing Strategies

**Manual Testing Checklist**
- [ ] App launches without crashes
- [ ] All buttons and UI elements are responsive
- [ ] Input validation works correctly
- [ ] Database operations complete successfully
- [ ] Navigation between activities functions properly
- [ ] App handles screen rotation gracefully
- [ ] Error messages display appropriately
- [ ] Back button behavior is correct

**Edge Cases to Test**
- Empty input fields
- Invalid data formats (letters in number fields)
- Very large numbers or long strings
- Rapid repeated button clicks
- Low memory conditions
- No internet connection (for WebView)
- Database full or corrupted

### Debugging Tools

**Logcat Usage**
```java
// Add logging statements
Log.d("TAG", "Debug message");
Log.i("TAG", "Info message");
Log.w("TAG", "Warning message");
Log.e("TAG", "Error message");

// View in Android Studio: View → Tool Windows → Logcat
```

**Common Debugging Commands**
```bash
# View device logs
adb logcat

# Clear logs
adb logcat -c

# Filter by tag
adb logcat -s TAG

# Install APK manually
adb install app-debug.apk

# Uninstall app
adb uninstall com.example.app
```

### Performance Testing

**Memory Profiling**
- Use Android Studio Profiler
- Monitor memory usage during runtime
- Check for memory leaks
- Optimize bitmap loading

**Performance Optimization Tips**
- Use ViewHolder pattern in adapters
- Lazy load images and data
- Minimize database queries
- Use background threads for heavy operations
- Cache frequently accessed data

## �📝 Course Timeline

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

## ❓ Frequently Asked Questions (FAQ)

### General Questions

**Q: What is the minimum Android version required for these projects?**
A: API Level 21 (Android 5.0 Lollipop) or higher. Most projects are compatible with Android 5.0+.

**Q: Can I use these projects as reference for my own work?**
A: Yes! These are educational projects designed for learning. Feel free to study the code and adapt concepts for your own projects.

**Q: Do I need a physical Android device to test?**
A: No, the Android Emulator in Android Studio works perfectly for all projects. However, testing on a real device can provide better performance insights.

**Q: How long does it take to complete each project?**
A: Simple projects (Days 1-8): 1-2 hours; Intermediate projects (Days 9-20): 2-4 hours; Advanced projects (Days 21-27): 4-6 hours.

### Technical Questions

**Q: Why does my app crash when rotating the screen?**
A: This happens when Activity state isn't saved. Implement `onSaveInstanceState()` and `onRestoreInstanceState()` to preserve data:
```java
@Override
protected void onSaveInstanceState(Bundle outState) {
    super.onSaveInstanceState(outState);
    outState.putString("key", value);
}
```

**Q: How do I fix "Cannot resolve symbol 'R'" errors?**
A: Try these solutions in order:
1. Clean and rebuild: Build → Clean Project → Rebuild Project
2. Sync Gradle files: File → Sync Project with Gradle Files
3. Invalidate caches: File → Invalidate Caches / Restart
4. Check for XML layout errors

**Q: Why is my ListView not scrolling smoothly?**
A: Implement the ViewHolder pattern to recycle views efficiently:
```java
static class ViewHolder {
    TextView textView;
}

@Override
public View getView(int position, View convertView, ViewGroup parent) {
    ViewHolder holder;
    if (convertView == null) {
        convertView = inflater.inflate(R.layout.item, parent, false);
        holder = new ViewHolder();
        holder.textView = convertView.findViewById(R.id.text);
        convertView.setTag(holder);
    } else {
        holder = (ViewHolder) convertView.getTag();
    }
    holder.textView.setText(data.get(position));
    return convertView;
}
```

**Q: How do I pass complex objects between activities?**
A: Make your object implement `Parcelable` or `Serializable`:
```java
// Sending activity
Intent intent = new Intent(this, TargetActivity.class);
intent.putExtra("user", userObject);
startActivity(intent);

// Receiving activity
User user = (User) getIntent().getSerializableExtra("user");
```

**Q: Why is my SQLite database not updating?**
A: Common issues:
- Not incrementing database version in DBHelper constructor
- Not calling `db.close()` after operations
- SQL syntax errors (check Logcat)
- Forgetting to call `db.execSQL()` for schema changes

**Q: How do I handle runtime permissions?**
A: For Android 6.0+ (API 23+), request permissions at runtime:
```java
if (ContextCompat.checkSelfPermission(this, Manifest.permission.CAMERA)
        != PackageManager.PERMISSION_GRANTED) {
    ActivityCompat.requestPermissions(this,
        new String[]{Manifest.permission.CAMERA}, REQUEST_CODE);
}
```

### Database Questions

**Q: How do I view my SQLite database?**
A: Use Android Studio's Database Inspector:
1. Run app on emulator
2. View → Tool Windows → App Inspection
3. Select Database Inspector tab
4. Browse tables and execute queries

**Q: How do I reset my database during development?**
A: Easiest method: Uninstall the app from device/emulator and reinstall. Or increment database version in DBHelper.

**Q: Should I close the database after every operation?**
A: It's better to keep one instance open and close it in `onDestroy()`. Use singleton pattern for DBHelper.

### UI Questions

**Q: How do I create a custom dialog?**
A: Use AlertDialog.Builder with custom layout:
```java
AlertDialog.Builder builder = new AlertDialog.Builder(this);
View view = getLayoutInflater().inflate(R.layout.custom_dialog, null);
builder.setView(view);
AlertDialog dialog = builder.create();
dialog.show();
```

**Q: How do I change app icon?**
A: Replace files in `res/mipmap-*/` folders with your icon images (ic_launcher.png) in various resolutions.

**Q: How do I support multiple screen sizes?**
A: Use ConstraintLayout and avoid hardcoded dp values. Use `match_parent`, `wrap_content`, and constraints.

## 🎯 Skills Developed

- **Android Developer Documentation:** https://developer.android.com/
- **Java Documentation:** https://docs.oracle.com/en/java/
- **Gradle Build Tool:** https://gradle.org/
- **Material Design Guidelines:** https://material.io/design

## 🔧 Common Challenges & Solutions

### Challenge 1: Activity Lifecycle Management
**Problem:** Data loss when app goes to background or screen rotates.

**Solution:**
```java
@Override
protected void onSaveInstanceState(Bundle outState) {
    super.onSaveInstanceState(outState);
    outState.putString("userInput", editText.getText().toString());
}

@Override
protected void onRestoreInstanceState(Bundle savedInstanceState) {
    super.onRestoreInstanceState(savedInstanceState);
    String userInput = savedInstanceState.getString("userInput");
    editText.setText(userInput);
}
```

### Challenge 2: Null Pointer Exceptions
**Problem:** App crashes with NullPointerException.

**Solution:** Always check for null before using objects:
```java
if (textView != null && textView.getText() != null) {
    String text = textView.getText().toString();
    // Process text
}
```

### Challenge 3: Database Cursor Not Closing
**Problem:** Memory leaks from unclosed cursors.

**Solution:** Always use try-with-resources or close manually:
```java
Cursor cursor = null;
try {
    cursor = db.query("users", null, null, null, null, null, null);
    while (cursor.moveToNext()) {
        // Process data
    }
} finally {
    if (cursor != null) {
        cursor.close();
    }
}
```

### Challenge 4: Intent Data Not Received
**Problem:** Passed data not showing in target activity.

**Solution:** Verify key names match exactly:
```java
// Sender
intent.putExtra("USERNAME", username);

// Receiver - use same key
String username = getIntent().getStringExtra("USERNAME");
if (username != null) {
    // Use username
}
```

### Challenge 5: RecyclerView Not Displaying
**Problem:** RecyclerView shows blank screen.

**Solution:** Ensure all components are set:
```java
recyclerView.setLayoutManager(new LinearLayoutManager(this));
recyclerView.setAdapter(adapter);
adapter.notifyDataSetChanged();
```

### Challenge 6: Button Click Not Working
**Problem:** Button click listener not triggering.

**Solution:** Verify findViewById returns non-null and listener is set:
```java
Button button = findViewById(R.id.myButton);
if (button != null) {
    button.setOnClickListener(new View.OnClickListener() {
        @Override
        public void onClick(View v) {
            // Handle click
        }
    });
}
```

## 📈 Learning Outcomes

By the end of this course, students will have:

### Technical Competencies
- ✅ Built 27+ functional Android applications
- ✅ Mastered Android Studio IDE and development tools
- ✅ Implemented complex UI layouts with multiple components
- ✅ Created and managed SQLite databases with CRUD operations
- ✅ Developed user authentication and registration systems
- ✅ Integrated web content using WebView
- ✅ Implemented navigation between multiple activities
- ✅ Handled user input validation and error management

### Soft Skills
- ✅ Problem-solving through debugging and testing
- ✅ Code organization and project structure
- ✅ Documentation and code commenting
- ✅ Version control with Git
- ✅ Independent learning and research
- ✅ Attention to detail in UI/UX design

### Portfolio Projects
Students can showcase these projects:
1. **Calculator App** - Demonstrates UI design and logic implementation
2. **CRUD Application** - Shows database management skills
3. **Authentication System** - Proves security awareness
4. **RecyclerView App** - Displays modern Android practices

## 🤝 Contributing

This is an educational repository for course work. If you're a student in this course:
- Follow the lab instructions for each session
- Document your code with clear comments
- Test thoroughly before committing
- Use meaningful commit messages

## � Project Dependencies

### Common Dependencies (build.gradle)

```gradle
dependencies {
    // Core Android libraries
    implementation 'androidx.appcompat:appcompat:1.6.1'
    implementation 'com.google.android.material:material:1.9.0'
    implementation 'androidx.constraintlayout:constraintlayout:2.1.4'
    
    // RecyclerView
    implementation 'androidx.recyclerview:recyclerview:1.3.1'
    
    // Testing libraries
    testImplementation 'junit:junit:4.13.2'
    androidTestImplementation 'androidx.test.ext:junit:1.1.5'
    androidTestImplementation 'androidx.test.espresso:espresso-core:3.5.1'
}
```

### Minimum SDK Configuration

```gradle
android {
    compileSdk 34
    
    defaultConfig {
        applicationId "com.example.app"
        minSdk 21
        targetSdk 34
        versionCode 1
        versionName "1.0"
    }
    
    buildTypes {
        release {
            minifyEnabled false
            proguardFiles getDefaultProguardFile('proguard-android-optimize.txt'),
                    'proguard-rules.pro'
        }
    }
    
    compileOptions {
        sourceCompatibility JavaVersion.VERSION_1_8
        targetCompatibility JavaVersion.VERSION_1_8
    }
}
```

### Required Permissions (AndroidManifest.xml)

```xml
<!-- For WebView with internet access -->
<uses-permission android:name="android.permission.INTERNET" />

<!-- For external storage (if needed) -->
<uses-permission android:name="android.permission.READ_EXTERNAL_STORAGE" />
<uses-permission android:name="android.permission.WRITE_EXTERNAL_STORAGE" />
```

## 🎓 Course Completion

### Assessment Criteria
- **Code Quality:** 30% - Clean, well-organized, documented code
- **Functionality:** 40% - All features work as specified
- **UI/UX Design:** 15% - Intuitive, attractive interface
- **Best Practices:** 15% - Following Android conventions

### Final Project Expectations
- Incorporate multiple concepts learned throughout the course
- Implement at least 3 different UI components
- Include database operations (CRUD)
- Demonstrate proper error handling
- Provide user-friendly interface
- Include comprehensive code comments

## �📧 Course Information

- **Course Code:** SWT32011
- **Course Name:** Mobile Application Development
- **Focus:** Android Development with Java
- **Level:** Intermediate to Advanced

## 📄 License

Educational project for SWT32011 - Mobile Application Development course.

---

*Last Updated: February 3, 2026*
