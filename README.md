# Simple Web Browser in C# – Industrial Programming Project

This repository contains the source code and documentation for a Simple Web Browser application developed for the F21SC: Industrial Programming course at Heriot-Watt University.

## 🔍 Project Overview

- Built a functional web browser using C# and .NET
- Implemented HTTP requests and responses with `HttpClient`
- Displayed raw HTML content and HTTP status codes (200, 400, 403, 404)
- Extracted page titles and the first 5 URLs from each page using regular expressions
- Implemented homepage management, bookmarks, and browsing history
- Used SQLite for persistent storage of history, bookmarks, and user settings

## 🧱 Main Features

- **HTTP Communication**
  - Send requests to user-entered URLs
  - Display response content and status codes
  - Show page titles

- **Bookmarks**
  - Add, edit, and delete bookmarks
  - Click bookmarks to navigate
  - Store bookmarks per user in SQLite

- **History**
  - Record visited pages with timestamps
  - Navigate back/forward
  - Avoid consecutive duplicate history entries

- **Homepage**
  - User can set and update a homepage
  - Homepage loads automatically on startup

- **GUI**
  - Windows Forms interface
  - Toolbar buttons + keyboard shortcuts
  - Side panel for extracted URLs

## 🛠 Technologies Used

- C# / .NET
- Windows Forms
- SQLite
- System.Net.Http (`HttpClient`)
- Regular Expressions
- Object-Oriented Design and Layered Architecture

## 📄 Documentation

Full written report: `WebBrowserProjectReport.docx`  
Includes design decisions, architecture, and reflections.

## ▶️ How to Run

1. Clone or download this repository.
2. Open `SimpleWebBrowser.sln` in Visual Studio.
3. Restore NuGet packages if required.
4. Build and run the solution.

---

**Author:** Yash Sandesh Pawar – MSc Data Science, Heriot-Watt University
