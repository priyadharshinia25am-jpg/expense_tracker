# expense_tracker
💰 Expense Tracker PWA

A modern, feature-rich Progressive Web App for tracking your daily expenses with a vibrant orange and cyan theme.

🌟 Features
✅ Add & Track Expenses - Log your spending with amount, category, date, and description
📊 Dashboard Analytics - View total expenses, monthly totals, averages, and highest expenses
📈 Visual Charts - Beautiful pie charts (spending by category) and line charts (expenses over time)
🏷️ 8 Categories - Food, Transport, Entertainment, Shopping, Bills, Health, Education, Other
🔍 Filter & Search - Filter expenses by category or month
📱 Mobile Responsive - Fully responsive design for phones, tablets, and desktops
🌈 Vibrant Theme - Stunning orange and cyan design
💾 Offline Support - Works completely offline, data saved locally
⚡ PWA Installation - Install as a native app on iOS and Android
🔒 Privacy First - All data stored locally, nothing uploaded to servers
⚙️ Auto-Save - Expenses automatically saved in browser storage
🚀 Getting Started
Option 1: Use Online (Easiest)

Open in your browser:

https://priyadharshinia25am-jpg.github.io/expense_tracker
Option 2: Run Locally
Download expense_tracker.html
Double-click the file to open in your browser
Start tracking expenses!
Option 3: Host Your Own
Clone/fork this repository
Upload the HTML file to your web server
Access via your domain
📲 Install as Mobile App
Android (Google Chrome)
Open the app in Chrome browser
Tap the "Install App" button that appears
Tap "Install" to confirm
App will appear on your home screen
iOS (Safari)
Open the app in Safari browser
Tap the Share button (bottom menu)
Select "Add to Home Screen"
Tap "Add" to confirm
App will appear on your home screen
💡 How to Use
Adding an Expense
Go to "Add Expense" tab
Enter the amount you spent
Select a category
Choose the date
Add optional description
Click "Add Expense"
Viewing Expenses
Go to "View Expenses" tab
See all your expenses in reverse chronological order
Filter by category or month using dropdowns
Delete expenses as needed
Dashboard & Analytics
Go to "Dashboard" tab
View statistics:
Total expenses
This month's total
Average per expense
Highest expense
See pie chart of spending by category
See line chart of daily expenses (last 30 days)
🎨 Customization
Change Theme Colors

Edit the CSS variables in the <style> section:

css
:root {
    --primary: #ff6b35;        /* Orange */
    --secondary: #00d4ff;      /* Cyan */
    --bg-light: #0a0e27;       /* Dark blue */
    --text-primary: #e8f0fe;   /* Light blue */
    /* ... other colors ... */
}
Popular Color Combinations

Feel free to experiment with these combinations:

Purple & Pink:

css
--primary: #a855f7;
--secondary: #ec4899;
--bg-light: #1a1a2e;

Green & Teal:

css
--primary: #10b981;
--secondary: #06b6d4;
--bg-light: #0f2f2f;

Red & Yellow:

css
--primary: #ef4444;
--secondary: #fbbf24;
--bg-light: #1a1a1a;
Change Currency

Find this line in the HTML and replace ₹ with your currency:

html
<div class="stat-value" id="totalExpenses">₹0.00</div>
Add/Remove Categories

Edit the category options in both forms:

html
<option value="Food">🍔 Food & Dining</option>
<option value="Transport">🚗 Transport</option>
<!-- Add more or remove as needed -->
🛠️ Technical Stack
HTML5 - Structure
CSS3 - Styling with CSS variables
JavaScript (Vanilla) - All functionality
Chart.js - Data visualization
Service Worker - Offline support
LocalStorage - Data persistence
📊 Data Storage

All your expenses are stored in your browser's LocalStorage:

✅ Data stays on your device
✅ No server uploads
✅ No tracking or analytics
✅ Complete privacy

Warning: Clearing browser data will delete your expenses. Back up important data regularly.

🔄 Export Data

To backup your expenses, open browser console (F12) and run:

javascript
console.log(JSON.stringify(expenses));

Copy the output and save to a text file for backup.

🌐 Browser Support
✅ Chrome/Edge 88+
✅ Firefox 87+
✅ Safari 14.1+
✅ Mobile browsers (Android Chrome, iOS Safari)
📱 Offline Usage

The app works 100% offline once loaded:

All data stored locally
Charts and analytics work offline
Add/edit/delete expenses without internet
When online, service worker keeps app cached
🚀 Deployment
Deploy to GitHub Pages (Free)
Fork this repository
Upload expense_tracker.html as index.html
Enable GitHub Pages in settings
Access at: https://YOUR-USERNAME.github.io/expense_tracker
Deploy to Netlify (Free)
Drag and drop the HTML file
Get instant live link
Optional: connect custom domain
Deploy to Vercel (Free)
Create Vercel account
Upload HTML file
Get instant deployment
Deploy to Heroku (Free tier deprecated)

Use GitHub Pages or Netlify instead for best free hosting.

📦 Project Structure
expense_tracker/
├── index.html              # Main app file
├── README.md               # This file
└── expense_tracker_black_gold.html  # Alternative black & gold theme
🎯 Features Roadmap

Future improvements:

 Export to CSV/PDF
 Import expenses from file
 Budget limits & alerts
 Recurring expenses
 Multi-user support
 Cloud backup (with Firebase)
 Advanced reports & insights
 Multiple currencies
 Dark/Light mode toggle
 Expense tags
 Search functionality
🐛 Troubleshooting

App not saving expenses:

Check if localStorage is enabled in browser settings
Try clearing cache and reloading
Check if you're in private/incognito mode

Charts not showing:

Refresh the page
Make sure you have expenses added (at least 2)
Check browser console (F12) for errors

PWA install button not showing:

Use Chrome/Edge browser (Safari has different installation method)
Make sure app is loaded from HTTPS (GitHub Pages is secure)
Try clearing cache and reloading

Expenses disappearing:

Browser storage might be cleared
Check if private mode is enabled
Some browsers limit storage in private mode

Can't filter by month:

Add expenses first
Make sure dates are set correctly
Try refreshing the page
🌍 Themes Available

This project includes two built-in themes:

Orange & Cyan (Default) - expense_tracker.html
Vibrant, modern, energetic
Great contrast, easy to read
Black & Gold - expense_tracker_black_gold.html
Premium, elegant, professional
Perfect for luxury feel

You can easily create more themes by modifying the CSS variables!

💬 Support

Having issues? Here are some common solutions:

Clear Browser Cache
Ctrl+Shift+Delete (Windows)
Cmd+Shift+Delete (Mac)
Then reload the page
Check Browser Console
Press F12 to open Developer Tools
Check Console tab for error messages
Try Different Browser
If app doesn't work, try Chrome, Firefox, or Safari
Update Your Browser
Make sure you have the latest version
📄 License

Free to use and modify for personal and commercial purposes. No attribution required.

✨ Credits

Made with ❤️ for better expense management.

Uses Chart.js for beautiful visualizations
Built with vanilla JavaScript (no frameworks)
Progressive Web App standards compliant
🚀 Quick Tips
Keyboard Shortcuts:
Tab to navigate between form fields
Enter to submit forms
Escape to cancel
Mobile Tips:
Landscape mode shows better on tablets
Install as home screen app for fullscreen
Pinch to zoom on charts
Best Practices:
Add expenses daily for accurate tracking
Use consistent category names
Review dashboard monthly
Backup data regularly
Privacy Tips:
All data stored locally - share URL safely
No tracking or telemetry
Works on public WiFi safely
Consider password-protecting your device
