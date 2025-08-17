# **FlexTime Tracker 9000**

A retro, 8-bit styled timekeeping web application designed to help you track your work hours and manage your flex time with precision and a bit of fun. Built with vanilla HTML, JavaScript, and Tailwind CSS, this app runs entirely in your browser and saves all data locally.

## **Features**

FlexTime Tracker 9000 is packed with features to give you full control over your time tracking:

* **Classic Time Punching**: Simple, one-click buttons for **Clock In**, **Clock Out**, **Lunch In**, and **Lunch Out**.  
* **Flex Bank Calculator**: Automatically calculates your time worked against a configurable workday length and tracks your total accrued flex time in a "Flex Bank."  
* **Interactive Calendar**: A full calendar view to navigate through different days, weeks, and months. Easily select any day to view or edit its punches.  
* **Complete Punch Management**:  
  * **Manual Punch Entry**: Forgot to clock in? Manually add any type of punch to any day.  
  * **Edit Timestamps**: Click "Edit" on any punch to adjust its timestamp.  
  * **Delete Punches**: Remove incorrect punches with a confirmation step.  
  * **Clear Entire Day**: Wipe a day's log clean to start over.  
* **Bulk Copy/Paste Functionality**:  
  * **Copy Day**: Duplicate a single day's punches to another date.  
  * **Copy Week**: Copy an entire week's schedule (Sun-Sat) and paste it starting on a new date.  
  * **Copy Month**: Copy an entire month's data to a new month.  
* **Undo/Redo System**: Made a mistake? Easily undo and redo your last actions.  
* **Detailed Audit Log**: Every action—from punches and edits to undos and copies—is recorded in a timestamped log for each day, ensuring complete transparency.  
* **Customizable Workday**: In the **Settings**, you can define the length of your standard workday (e.g., 7.5 hours) to ensure accurate flex time calculations.  
* **Data Portability**:  
  * **Export**: Export all your time data to **JSON** (for backup/restore) or **CSV** (for spreadsheets).  
  * **Import**: Restore your data from a JSON backup file.  
* **Timezone Toggling**: Instantly switch all timestamps between your **local timezone** and **UTC**.  
* **Persistent Local Storage**: All your data is saved in your browser's local storage, so your time log is waiting for you every time you open the app.

## **How to Use**

This is a standalone web application that requires no server or build process.

1. **Download the Code**: Clone or download the index.html file from this repository.  
2. **Open in Browser**: Open the index.html file in any modern web browser (like Chrome, Firefox, or Edge).  
3. **Start Tracking\!**: That's it\! The app is ready to use.

## **Technology Stack**

* **HTML**: For the core structure of the application.  
* **Tailwind CSS**: For all styling, loaded via a CDN for simplicity.  
* **Vanilla JavaScript (ES6+)**: For all application logic, state management, and DOM manipulation. No frameworks or libraries needed\!  
* **Google Fonts**: For the 'Press Start 2P' retro font.
