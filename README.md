# HTML Code Preview PWA

## Description
HTML Code Preview PWA is an offline-capable web app that allows you to write HTML code and see a live preview of the rendered output below.  
It includes Copy, Clear, and Install buttons for a smooth user experience and is optimized for mobile devices.

## Features
- **Live HTML Code Preview**: Instantly see how your HTML code renders as you type.  
- **Copy Button**: Easily copy the previewed HTML code to your clipboard.  
- **Clear Button**: Clear all the code to start fresh.  
- **Install Button**: Install the app as a Progressive Web App (PWA) on mobile and desktop devices.  
- **Offline Support**: Thanks to Service Worker caching, the app works without internet connection.  
- **Responsive Design**: Works well on phones, tablets, and desktops.

---

## How to Use
1. Type your HTML code into the textarea.  
2. The rendered preview will appear live below the code box.  
3. Click the Copy button to copy the previewed code to your clipboard.  
4. Click the Clear button to erase all code and start over.  
5. Use the Install button to add the app to your device for offline use.

---

## Technologies Used
- HTML, CSS, JavaScript  
- Service Worker for offline support (PWA)  
- Fully client-side, no backend required  

---

## Installation
Clone or download the GitHub repository, or use the app directly via GitHub Pages.  
Click the Install button to add the app to your device as a PWA.

---

## Important Notice About Browser Cache and Offline Usage

This Progressive Web App (PWA) relies heavily on both **Service Worker cache** and **Browser cache** to deliver a seamless offline experience.

**Please be aware:**

- Clearing your **browser cache** will remove essential files (JavaScript, CSS, HTML) cached by the browser.
- While the Service Worker manages its own cache (Cache Storage), clearing the browser cache can cause some assets to become temporarily unavailable.
- This may result in errors or prevent the app from working properly when offline.
- For the best offline experience, **avoid clearing the browser cache** while using this app.
- When updates are made, the app uses cache versioning and prompts users to refresh, ensuring you always have the latest version.

If you experience issues after clearing your browser cache, try refreshing the page or reopening the app with an active internet connection.

Thank you for understanding!

---

## License
MIT License

---

## Author 
Created With Khin Maung Win
