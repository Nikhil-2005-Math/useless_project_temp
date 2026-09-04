<img width="1280" height="640" alt="git (1)" src="https://github.com/user-attachments/assets/8920b256-2ba8-4988-b824-5351134eb4bd" />



# ChronoSense🎯


## Basic Details
### Team Name: SEKIRO


### Team Members
- Team Lead: Adithyan A - College of Engineering Kallooppara
- Member 2: Nikhil Mathew - College of Engineering Kallooppara

### Project Description
ChronoSense is an over-engineered optical digitizer that allows users to photograph an analog wristwatch, routes the image through simulated computer vision pipelines to compute the time, and then violently roasts them on a full-screen display for not simply glancing at their wrist.

### The Problem (that doesn't exist)
For centuries, humans have suffered the unbearable cognitive strain of having to interpret rotating mechanical sticks on a small dial. Glancing downward at one's wrist requires up to 0.15 seconds of biological effort and basic spatial geometry—an archaic, exhausting ritual that modern society has inexplicably failed to automate.

### The Solution (that nobody asked for)
Instead of looking at your arm, you take out an expensive smartphone (which already shows the exact digital time), photograph your analog watch, upload the multi-megabyte image to a local computer, wait through four seconds of faux-neural trigonometric laser scanning, and receive a giant comic-style readout accompanied by synthetic text-to-speech shouting: "JUST LOOK AT YOUR WRIST!"

# Technical Details
# Technologies/Components Used
# For Software:

Languages used: Python 3.10+, JavaScript (ES6+), HTML5, CSS3

Frameworks used: Python Built-in ThreadingHTTPServer / SimpleHTTPRequestHandler

Libraries used: Web Speech API (window.speechSynthesis), HTML5 Canvas API (Client-side downscaling & compression), Web Storage API (localStorage), Google GenAI Vision API (Gemini multimodal endpoint)

Tools used: Visual Studio Code, VS Code Live Server, Git, PowerShell / Bash terminal

# For Hardware:

List main components: Modern Smartphone (Camera source) and Laptop / PC (Host server & display)

List specifications: Minimum 4 GB RAM, Web camera / smartphone camera with minimum 1080p capture capability, modern Chromium/WebKit-based web browser

List tools required: Wi-Fi Local Area Network router or mobile Wi-Fi hotspot for local client-server pairing]

### Implementation
For Software:
# Installation
# Clone the repository
git clone https://github.com/your-username/chronosense-neural-dial.git

# Navigate into the project folder
cd chronosense-neural-dial

# Run
# Option 1: Using Python's built-in local server (Zero external dependencies)
python -m http.server 8000

# Option 2: Using Node.js
npx serve .

# Open your browser and navigate to:
# http://localhost:8000

### Project Documentation
For Software:

# Screenshots 
Screenshot 1
<img width="1600" height="900" alt="image" src="https://github.com/user-attachments/assets/b5c4280a-b409-401e-b9ba-e2b2e1b0298b" />
The ChronoSense main portal—a clean, enterprise-grade dark dashboard presenting the drag-and-drop optical upload zone and mock neural system notes.

Screenshot 2
<img width="1600" height="900" alt="image" src="https://github.com/user-attachments/assets/3f6a46d4-d981-4618-a6e8-7c545a3e4c2a" />
The pre-flight inspection panel showing client-side telemetry toggles, voice feedback controls, and the disabled recovery trigger awaiting image input.

Screenshot 3
<img width="1600" height="900" alt="image" src="https://github.com/user-attachments/assets/3e5f6409-1369-4183-bdd4-b228120f5018" />
Watch image successfully ingested and downscaled via HTML5 Canvas, unlocking the primary "Initiate Optical Time Recovery" trigger.

Screenshot 4
<img width="1600" height="900" alt="image" src="https://github.com/user-attachments/assets/31311cda-d9eb-4bb1-990f-1c20d42ad3b0" />
The deceptive triumph stage—rendering the recovered digital time in oversized comic font with an absurd "99.8% Neural Confidence" metric.

Screenshot 5
<img width="1600" height="900" alt="image" src="https://github.com/user-attachments/assets/aa34a7d5-3ad5-490a-a4cf-596a7b02c2b3" />
The final punchline sequence—stamping "OR JUST LOOK AT IT" over the screen, shouting "JUST LOOK AT YOUR WRIST!", and computing a 99.9% effort waste metric

# Diagrams
[User Device / Phone]
           │
           │ 1. Uploads High-Res Analog Watch Photo
           ▼
  [Client-Side HTML5 Canvas]
           │
           │ 2. Downscales image to max 1200px (Prevents browser lag)
           ▼
  [Stage 1: Neural Inspection HUD]
           │
           │ 3. Sweeping laser animation + 3 fake debug telemetry logs (2.5s)
           ▼
  [Stage 2: Faux Triumph Readout]
           │
           │ 4. Displays real local digital time in bold font (350ms bait)
           ▼
  [Stage 3: The Comic Roast Switch]
           ├──> 5a. Screen glitch animation shakes overlay
           ├──> 5b. Typewriter engine pops comic text: "JUST LOOK AT YOUR WRIST!"
           ├──> 5c. Web Speech API triggers deadpan voice roast aloud
           └──> 5d. Saves scan latency & wasted seconds to localStorage

For Hardware:

# Schematic & Circuit
N/A (Pure Software Application — No custom circuits or physical microcontrollers required).


![Schematic](Add your schematic diagram here)
*Add caption explaining the schematic*

# Build Photos
N/A (Pure Software Application — No custom circuits or physical microcontrollers required).

Build Photos
N/A (Pure Software Application — Developed entirely within VS Code).

### Project Demo
# Video
[(https://drive.google.com/file/d/15LijM1hgrmwALVDtVLxC9jCy0nv2gaWr/view?usp=drivesdk)](https://drive.google.com/drive/folders/1IePAWfOLMPDagw46_Ca5JYJP_wjfd7ex?usp=sharing)
This video demonstrates the complete user journey of ChronoSense: starting from the temporal lock screen to the optical recovery workspace, selecting and locally downscaling a high-resolution luxury analog watch photo, running the simulated radial computer-vision laser sweep, transitioning through the fleeting digital time reveal, and hitting the user with the satirical comic roast ("USE YOUR EYES, NOT AN AI!") alongside the 99.9% wasted-effort telemetry and automated scan archive logging.

## Team Contributions
Nikhil Mathew: Core web architecture, stage animation choreography (inspection → triumph → roast), offscreen <canvas> downscaling logic, and window.speechSynthesis voice roast implementation.

Adithyan A: Responsive CSS layout, typography scaling (fitPunchline logic), and local storage history engine , UI copy, comedic punchline creation, sample watch test dataset curation, and documentation.

---
Made with ❤️ at TinkerHub Useless Projects 

![Static Badge](https://img.shields.io/badge/TinkerHub-24?color=%23000000&link=https%3A%2F%2Fwww.tinkerhub.org%2F)
![Static Badge](https://img.shields.io/badge/UselessProjects--26-26?link=https%3A%2F%2Ftinkerhub.org%2Fevents%2F1M8ORET9A1%2Fuseless-projects-3.0)



