# Smart File Organizer & Analyzer (C++)

## Overview
Smart File Organizer is a C++17 application that automatically organizes files in a directory based on file type and generates logs for all operations.

## Features
- Organizes files into categories: Images, Documents, Videos, Music
- Handles unknown file types
- Auto-creates directories
- Logging with timestamps
- Exception-safe and cross-platform

## Technologies Used
- C++17
- STL (map, vector, filesystem, algorithms)
- File I/O
- Exception handling

## How to Run
1. Compile using:
   g++ -std=c++17 main.cpp -o organizer
2. Run:
   ./organizer
3. Enter the directory path when prompted

## Output
- Files are organized into folders
- log.txt records all actions


