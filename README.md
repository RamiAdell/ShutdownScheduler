## Screenshot
![image](https://github.com/RamiAdell/ShutdownScheduler/assets/80486564/128307b8-c253-4e73-a9ad-b11cb8b497ca)

# Timer Setter

This is a simple Java GUI application created in **2021**. It was my first Java GUI project, designed to schedule a computer shutdown after a specified time (in minutes).

## Features

- Set a timer (in minutes) to automatically shut down the computer.
- Cancel/reset the timer if needed.
- Simple user interface built with Swing.
- Generates and runs a `.bat` file to handle shutdown and cancellation commands.

## How to Use

1. Run the application. Or open jar file directly from /dist directory
2. Enter the number of minutes you want before shutdown.
3. Click **Set Timer** to schedule the shutdown.
4. To cancel the scheduled shutdown, click **Reset**.

## Notes

- The app creates a temporary `filename.bat` file to execute the shutdown/cancel command.
- This tool is intended for Windows systems because it uses `shutdown -s -t` and `shutdown -a` commands.

## Author

**Ramy Adel**  
Instagram: [ramy.exe](https://www.instagram.com/ramy.exe)

---

> ✨ Created in 2021 as my first project with Java GUI development.
