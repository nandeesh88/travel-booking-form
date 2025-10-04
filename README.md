✈️ Travel Trip Requirements Form
A beautiful, responsive web form for collecting travel requirements from travelers. Built with pure HTML, CSS, and JavaScript - no frameworks required!
🌐 Live Demo
Visit the live form here: (https://nandeesh88.github.io/travel-booking-form/)

📋 Features
✨ Form Sections

👤 Personal Information - Collect customer details (name, email, phone, country)
🌍 Trip Details - Trip type, destination, dates, budget, and number of travelers
🏨 Accommodation - Hotel rating and room type preferences
✈️ Flight Preferences - Flight class and departure city
🎯 Additional Services - Car rental, tour guide, insurance, visa assistance, activities
📝 Special Requirements - Dietary restrictions, accessibility needs, custom requests

🎨 Design Features

Modern gradient design with smooth animations
Fully responsive (mobile, tablet, desktop)
Interactive hover effects
Form validation with visual feedback
Success/error messages
Clean, intuitive user interface

🔧 Technical Features

Pure HTML, CSS, and JavaScript (no dependencies)
Client-side form validation
Date validation (end date must be after start date)
Dynamic minimum date (cannot book past dates)
JSON data output to browser console
Easy to integrate with backend services


🚀 Quick Start
View the Form
Simply visit: https://YOUR-USERNAME.github.io/travel-booking-form/
Test the Form

Fill out all required fields (marked with *)
Click "Submit Trip Requirements"
Open browser console (F12)
View submitted data in JSON format

## 📩 Form Handling & Data Storage

Currently, the form logs user submissions directly to the **browser console** for testing purposes.  
To save form submissions in a persistent way, you’ll need to connect a backend or third-party service.  
Some recommended options include:

- **Formspree** → Simple form backend service, just add an endpoint to your `<form>` tag.  
- **Google Sheets API** → Store submissions directly into a Google Sheet.  
- **Firebase** → Use Firebase Realtime Database or Firestore to save form data securely.  
- **Custom Backend** → Build your own API with Node.js, Python, or any framework of your choice.

💻 Local Development
Option 1: Direct File Opening

Download index.html
Double-click to open in your browser
Start testing!

Option 2: Local Server
bash# Clone the repository
git clone https://github.com/YOUR-USERNAME/travel-booking-form.git

# Navigate to directory
cd travel-booking-form

# If you have Python installed
python -m http.server 8000

# Or using Node.js
npx serve

# Open browser to http://localhost:8000
