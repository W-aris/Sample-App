# 🚀 Ruby on Rails Tutorial – Sample Application

This repository contains the **sample application** built while following  
**_Ruby on Rails Tutorial: Learn Web Development with Rails_** by **Michael Hartl**.

The project demonstrates real-world Rails development practices including MVC architecture, authentication & authorization, session management, automated testing, and production-ready conventions.

---

## 📘 About the Tutorial

The **Ruby on Rails Tutorial** teaches Rails by building a complete application from scratch, with a strong emphasis on **best practices**, **clean code**, and **test-driven development**.

- 🌐 Website: https://www.railstutorial.org  
- 👤 Author: https://www.michaelhartl.com  

---

## ✨ Features Covered

- User signup and authentication
- Login, logout, and persistent sessions (“Remember Me”)
- Authorization and admin privileges
- MVC architecture and RESTful routing
- Secure passwords and model validations
- Automated testing with Rails test framework
- Professional-grade Rails application structure

---

## 🛠️ Getting Started

Follow the steps below to run the application locally.

### ✅ Prerequisites

- Ruby (compatible with the tutorial version)
- Rails
- Bundler
- SQLite3 (default database)

---

# Clone the repository
git clone <repository-url>
cd sample_app

# Install required Bundler version
gem install bundler -v 2.3.14

# Configure Bundler and install dependencies
bundle _2.3.14_ config set --local without 'production'
bundle _2.3.14_ install

# Set up the database
rails db:migrate

# Run the test suite
rails test

# Start the Rails server
rails server
