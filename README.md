# FaceLog – Real-Time Face Recognition Attendance System

FaceLog is a lightweight, offline-capable attendance management system that automatically detects and recognizes employee faces through a webcam and records daily attendance.
Built with Python, OpenCV (using Haar Cascade & LBPH algorithms) and MySQL, it prevents duplicate entries and offers an intuitive Tkinter-based GUI.

# Key Features

Real-time face detection using Haar Cascade

Face recognition with LBPH (Local Binary Pattern Histogram)

Attendance logging into MySQL and CSV files

Prevents duplicate daily entries

Tkinter-based GUI for adding employees and viewing logs

Works offline, lightweight and doesn’t need GPU or deep learning

# Technologies & Libraries Used

Face detection - OpenCV Haar Cascade	(Fast, CPU-friendly; avoids GPU-heavy deep models)

Face recognition - OpenCV LBPH	(Works with small datasets; robust without deep learning)

GUI - Tkinter	(Lightweight and built-in; avoids heavier PyQt)

Database - MySQL + mysql-connector	(Relational and scalable; better than SQLite for multi-user)

CSV logs - CSV module	(Easy human-readable backup)

Image handling - Pillow, OpenCV	(For capturing and displaying images)
