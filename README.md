# ChatGPT CSS Sidebar Horizontal Scrollbar 🚀✨

Welcome to **ChatGPT-CSS-Sidebar-Horizontal-Scrollbar**! This repository provides a pure CSS solution to improve the ChatGPT sidebar by enabling a horizontal scrollbar so you can view all hidden text.

## 🎯 Overview

This project focuses on:
- **Pure CSS Only:** No JavaScript required!
- **Enhanced ChatGPT Sidebar:** Fixes hidden text issues by adding a horizontal scrollbar.
- **Top Scrollbar Issue:** The default implementation places the horizontal scrollbar at the top, which may get hidden during vertical scrolling.

## 🔧 Features & Options

- **Top Horizontal Scrollbar:**  
  By default, the CSS creates a top horizontal scrollbar.  
  **Issue:** It can be hidden when vertical scrolling occurs.

- **Extra Flipping Options:**  
  An additional CSS snippet is provided (commented out) that flips extra options to the bottom.  
  Use this if you’d prefer the scrollbar or extra options to remain visible even during vertical scrolling (note that some elements will flip).

## 📦 How to Use with Stylus

If you use the [Stylus extension](https://add0n.com/stylus.html) to inject custom CSS:
1. **Install Stylus** for your browser.
2. **Create a New Style** and paste in the CSS code below.
3. Set the style to apply on the ChatGPT Domain (e.g., `chatgpt.com`).
4. **Save and Refresh** your ChatGPT page to see the effect.

## ⚠️ Known Issue

- **Top Horizontal Scrollbar Hidden on Vertical Scroll:**  
  The default top horizontal scrollbar may get hidden when you scroll vertically.  
  **Workarounds:**  
  - Increase bottom padding (as shown above).  
  - Uncomment the "Extra Option" block to flip extra options to the bottom. Keep in mind this may change the order of some elements.

## 🤝 Contributing

Contributions, suggestions, and improvements are welcome! Feel free to open an issue or submit a pull request if you have any ideas to enhance this solution.

## 📄 License

This project is licensed under the [MIT License](LICENSE).

---
