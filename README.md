# Employee Time Card App

## Introduction
The Digital Timecard Recorder is a Python program designed to automate the process of recording clock-in and clock-out times for employees, particularly inspired by the traditional punch card systems still prevalent in many companies, especially in Japan. This program aims to streamline the time-tracking process, reducing manual effort and potential errors associated with traditional methods.

## Features
- **User-Friendly Interface**: The program provides a simple interface for employees to clock in and out using graphical buttons.
- **Individual Time Tracking**: Each staff member has their own designated button and corresponding sheet in the Excel file for accurate time tracking.
- **Automated Recording**: Clock-in and clock-out times are automatically recorded in an Excel file, eliminating the need for manual data entry.
- **Customizable**: The program is easily customizable to accommodate up to 20 individual staff members, making it suitable for small to medium-sized teams.

## How It Works
1. **Interface**: Upon launching the program, users are presented with a graphical interface displaying buttons for each staff member.
2. **Clocking In/Out**: Employees simply click their designated button to clock in or out, triggering the recording of the timestamp.
3. **Data Recording**: The program automatically updates an Excel file, with each staff member having their own sheet for time records.
4. **Real-Time Updates**: The interface displays the current date and time, providing real-time feedback to users.

## Installation
1. Clone the repository to your local machine.
2. Ensure you have Python installed (version 3.6 or higher).
3. Install the required dependencies using pip:
   ```
   pip install pygame openpyxl
   ```
4. Run the program by executing the main Python script:
   ```
   python digital_timecard_recorder.py
   ```

## Customization
- **Adding/Removing Staff**: Modify the `staff_list` variable to include or exclude staff members. Each member should be instantiated as a `Member` object with a unique name, button location, and Excel sheet name.
- **Interface Layout**: Adjust the button positions (`Button_X`) as desired to fit your interface layout preferences.
- **Excel File Handling**: Ensure the program is configured to save data to the correct Excel file for each month, and customize the file structure as needed.

## Future Enhancements
- **Email Integration**: Implement functionality to automatically send the Excel file to the accounting department via email for streamlined payroll processing.
- **User Authentication**: Add user authentication features to ensure only authorized personnel can access and modify time records.
- **Reporting**: Generate summary reports or analytics from the time records to provide insights into employee attendance patterns.

## License
This project is licensed under the [MIT License](LICENSE).

## Acknowledgements
- Special thanks to the staff at IKS International Kindergarten & School for their input throughout the development process.
- Credits to the developers of the Pygame and openpyxl libraries for their contributions to the Python ecosystem.
