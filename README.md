# 🤖 TutorAI - Automated Study Assistance System

TutorAI is an innovative technological ecosystem designed to automate, optimize, and transform the English evaluation process within the classroom. The system combines a physical educational robot powered by an IoT microcontroller, a Python-based backend server, a real-time web control panel for teachers, and cloud-based AI processing focused on active learning.

---

## 📂 Project Directory Structure

The repository is organized as follows:

* **📁 /esp32_robot_code**: Contains the C++ firmware (Arduino environment) for the ESP32-CAM that manages the robot's network connectivity and local quiz flows.
* **📁 /backend_server**: Contains the Python scripts managing the API endpoints, cloud database integration, and communication with the AI models.
* **📁 /web_panel**: Contains the teacher's dashboard user interface (`index.html`) featuring a modern layout (CSS Grid/Flexbox) and DOM manipulation logic in JavaScript.
* **📁 /docs**: Additional documentation, wiring guides, and project schematics.

---

## ⚙️ Operating Modes

The robot operates under two distinct software architectures depending on the classroom needs:

* **📝 Quiz Mode (Strict Evaluation):** A local, linear evaluation system. The C++ code directly validates student answers against predefined templates for fast, offline-compatible scoring.
* **💡 Assistant Mode (Socratic Method):** The ESP32 utilizes its Wi-Fi connection as a bridge to delegate natural language processing to a cloud AI. Guided by a strict system prompt, the AI interacts with the student using clues, analogies, and guiding questions instead of giving away answers, forcing them to think and deduce the solution by themselves.

---

## 🚀 Key Features

* **🌐 IoT Connectivity:** Automatic local Wi-Fi connection management handled by the ESP32 chip for real-time remote communication.
* **🐍 Python Backend Integration:** A robust server layer built in Python to handle data routing, secure API connections, and smart logic management.
* **📊 Analytics Dashboard:** A GitHub-style dark mode web interface that allows teachers to deploy questions, manage a global question bank, and read automated AI group diagnostic reports.
* **🧠 Smart Analytics:** The system channels accumulated classroom grades through the cloud AI to generate strategic feedback for the teacher, highlighting common group mistakes.

---

## 🛠️ Technologies Used

* **🔧 Hardware & Firmware:** C++ (Control structures, stream handling with `cin.ignore()`, and nested conditionals) within the Arduino environment for ESP32.
* **🐍 Backend Development:** Python (handling API requests, processing JSON data payload, and managing server-side connectivity).
* **💻 Web Development:** HTML5, CSS3 (Responsive layouts, modern dark theme), and Vanilla JavaScript (Dynamic node manipulation and asynchronous events).
* **🤖 AI & Methodology:** Strategic utilization of Artificial Intelligence (Copilot/LLMs) as a development assistant to optimize repetitive tasks, build UI styles, and generate the question bank, prioritizing logical architecture and manual hardware integration.

---

## 🔒 Security Notes (Deployment)

> ⚠️ **IMPORTANT:** For security and privacy reasons, the network credentials (`ssid` and `password`) in the ESP32 source code have been completely omitted from this public repository. Please ensure you configure your own credentials locally before compiling the firmware.

---

## ✍️ Author

* **SEBAS-CODE** - *Software Development, ZG SISTEM* - Colombia
