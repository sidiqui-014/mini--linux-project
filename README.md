# 🐧 Mini Linux Web Server Project

## 📄 Project Overview

This mini project simulates a simple web server using Linux command-line tools.  
It demonstrates basic web server setup using Python's built-in HTTP server module.

---

## 📁 Project Structure
myweb/  |----index.html |___
start.server.sh
## 💡 File Descriptions

### index.html

This is the main HTML file shown when someone opens your server in a browser.  
Content example:

```html
Welcome to my server


---

start_server.sh

Shell script to start the web server:

echo "Starting simulated server"
python3 -m http.server 8080


---

🚀 How to Run

1️⃣ Open terminal and go to project directory:

cd myweb

2️⃣ Make sure the script is executable (only first time):

chmod +x start_server.sh

3️⃣ Start the server:

./start_server.sh

4️⃣ Open your browser and visit:

http://localhost:8080

5️⃣ You will see your index.html content saying: "Welcome to my server".


---

✅ Requirements

Python 3

Linux shell or any bash-compatible terminal



---

💬 Author

Created as part of a Linux mini-project exercise.
