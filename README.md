<p align="center">
  <img src="./img.png" alt="Project Banner" width="100%">
</p>

# Saath 🎯
### Quietly caring, always with you 🌿

## Basic Details
A gentle, companion-based approach to health management and disease diagnosis discovery.

### Team Name: []

### Team Members
- Member 1: Ameena Nasrin VK - [PPTM ARTS AND SCIENCE COLLEGE]
- Member 2: Suhaila Nasrin K - [PPTM ARTS AND SCIENCE COLLEGE]

### Hosted Project Link
https://nasrinabdurahmandraco-maker.github.io/tink-her-hack-temp/

### Project Description
Saath is a personal health companion web application designed to make healthcare management less clinical and more human. It acts as a supportive partner ("Saathiya") that helps users manage their medical reports, appointments, and lifestyle habits through a calm, reassuring, and aesthetically pleasing interface.

### The Problem statement
Traditional medical applications are often cold, complex, and anxiety-inducing. Patients, especially those dealing with chronic conditions or general health anxiety, feel overwhelmed by clinical jargon, cluttered interfaces, and the stress of managing dispersed health records and appointments. There is a lack of emotional support in digital health tools.

### The Solution
Saath bridges the gap between medical utility and emotional well-being. By using a "Calm UI" philosophy with soft colors, gentle animations, and conversational language, it reduces health anxiety. It provides a centralized, timeline-based history for reports, a human-centric doctor finder, and gentle lifestyle nudges, making the user feel cared for rather than just "managed."

---

## Technical Details

### Technologies/Components Used

**For Software:**
- **Languages used:** HTML5, CSS3, JavaScript (Vanilla)
- **Design System:** Custom "Saathiya" Design System (CSS Variables, Glassmorphism, Animations)
- **Fonts:** Outfit (Sans-serif) & Playfair Display (Serif)
- **Tools used:** VS Code, Git

---

## Features

- **🌿 Warm Onboarding:** A conversational, step-by-step introduction that collects basic health data (Bio, Age, Blood Group) in a non-intrusive way.
- **📂 Story-based Health Timeline:** display of medical reports and prescriptions arranged as a life story rather than a database list, with clear summaries.
- **🩺 Compassionate Doctor Discovery:** Find doctors filtered by specialty, emphasizing their human traits (e.g., "Good Listener", "Patient") alongside medical qualifications.
- **🗓️ Smart Appointments:** Booking system for Online/Offline visits with built-in logic for slot availability and gentle reminders.
- **🧘 Lifestyle Nudges:** A simple, switch-based tracker for Hydration, Sleep, Nutrition, and Mindfulness, accompanied by daily motivational quotes.
- **🛡️ Privacy-First Design:** Encourages users to share only what they are comfortable with.

---

## Implementation

### For Hardware:

#### Components Required
[List all components needed with specifications]

#### Circuit Setup
[Explain how to set up the circuit]

---

## Project Documentation

### For Software:

#### Screenshots (Add at least 3)

![Home Screen](https://github.com/nasrinabdurahmandraco-maker/tink-her-hack-temp/blob/main/Screenshot%202026-02-14%20215413.png))
*The welcoming home screen with the core philosophy.*

![Dashboard](docs/dashboard.png)
*Central dashboard with quick actions and daily motivation.*

![Health Timeline](docs/reports.png)
*Medical history presented as a timeline.*

![Lifestyle](docs/lifestyle.png)
*Gentle habit tracking and mindfulness.*

### Diagrams

**Application Workflow:**

![Workflow](docs/workflow.png)
*Add caption explaining your workflow*

---
(https://github.com/nasrinabdurahmandraco-maker/tink-her-hack-temp/blob/main/Screenshot%202026-02-14%20215413.png)

### For Hardware:

#### Schematic & Circuit

![Circuit](Add your circuit diagram here)
*Add caption explaining connections*

![Schematic](Add your schematic diagram here)
*Add caption explaining the schematic*

#### Build Photos

![Team](Add photo of your team here)

![Components](Add photo of your components here)
*List out all components shown*

![Build](Add photos of build process here)
*Explain the build steps*

![Final](Add photo of final product here)
*Explain the final build*

---

## Additional Documentation

### For Web Projects with Backend:

#### API Documentation

**Base URL:** `https://api.yourproject.com`

##### Endpoints

**GET /api/endpoint**
- **Description:** [What it does]
- **Parameters:**
  - `param1` (string): [Description]
  - `param2` (integer): [Description]
- **Response:**
```json
{
  "status": "success",
  "data": {}
}
```

**POST /api/endpoint**
- **Description:** [What it does]
- **Request Body:**
```json
{
  "field1": "value1",
  "field2": "value2"
}
```
- **Response:**
```json
{
  "status": "success",
  "message": "Operation completed"
}
```

[Add more endpoints as needed...]

---

### For Mobile Apps:

#### App Flow Diagram

![App Flow](docs/app-flow.png)
*Explain the user flow through your application*

#### Installation Guide

**For Android (APK):**
1. Download the APK from [Release Link]
2. Enable "Install from Unknown Sources" in your device settings:
   - Go to Settings > Security
   - Enable "Unknown Sources"
3. Open the downloaded APK file
4. Follow the installation prompts
5. Open the app and enjoy!

**For iOS (IPA) - TestFlight:**
1. Download TestFlight from the App Store
2. Open this TestFlight link: [Your TestFlight Link]
3. Click "Install" or "Accept"
4. Wait for the app to install
5. Open the app from your home screen

**Building from Source:**
```bash
# For Android
flutter build apk
# or
./gradlew assembleDebug

# For iOS
flutter build ios
# or
xcodebuild -workspace App.xcworkspace -scheme App -configuration Debug
```

---

### For Hardware Projects:

#### Bill of Materials (BOM)

| Component | Quantity | Specifications | Price | Link/Source |
|-----------|----------|----------------|-------|-------------|
| Arduino Uno | 1 | ATmega328P, 16MHz | ₹450 | [Link] |
| LED | 5 | Red, 5mm, 20mA | ₹5 each | [Link] |
| Resistor | 5 | 220Ω, 1/4W | ₹1 each | [Link] |
| Breadboard | 1 | 830 points | ₹100 | [Link] |
| Jumper Wires | 20 | Male-to-Male | ₹50 | [Link] |
| [Add more...] | | | | |

**Total Estimated Cost:** ₹[Amount]

#### Assembly Instructions

**Step 1: Prepare Components**
1. Gather all components listed in the BOM
2. Check component specifications
3. Prepare your workspace
![Step 1](images/assembly-step1.jpg)
*Caption: All components laid out*

**Step 2: Build the Power Supply**
1. Connect the power rails on the breadboard
2. Connect Arduino 5V to breadboard positive rail
3. Connect Arduino GND to breadboard negative rail
![Step 2](images/assembly-step2.jpg)
*Caption: Power connections completed*

**Step 3: Add Components**
1. Place LEDs on breadboard
2. Connect resistors in series with LEDs
3. Connect LED cathodes to GND
4. Connect LED anodes to Arduino digital pins (2-6)
![Step 3](images/assembly-step3.jpg)
*Caption: LED circuit assembled*

**Step 4: [Continue for all steps...]**

**Final Assembly:**
![Final Build](images/final-build.jpg)
*Caption: Completed project ready for testing*

---

### For Scripts/CLI Tools:

#### Command Reference

**Basic Usage:**
```bash
python script.py [options] [arguments]
```

**Available Commands:**
- `command1 [args]` - Description of what command1 does
- `command2 [args]` - Description of what command2 does
- `command3 [args]` - Description of what command3 does

**Options:**
- `-h, --help` - Show help message and exit
- `-v, --verbose` - Enable verbose output
- `-o, --output FILE` - Specify output file path
- `-c, --config FILE` - Specify configuration file
- `--version` - Show version information

**Examples:**

```bash
# Example 1: Basic usage
python script.py input.txt

# Example 2: With verbose output
python script.py -v input.txt

# Example 3: Specify output file
python script.py -o output.txt input.txt

# Example 4: Using configuration
python script.py -c config.json --verbose input.txt
```

#### Demo Output

**Example 1: Basic Processing**

**Input:**
```
This is a sample input file
with multiple lines of text
for demonstration purposes
```

**Command:**
```bash
python script.py sample.txt
```

**Output:**
```
Processing: sample.txt
Lines processed: 3
Characters counted: 86
Status: Success
Output saved to: output.txt
```

**Example 2: Advanced Usage**

**Input:**
```json
{
  "name": "test",
  "value": 123
}
```

**Command:**
```bash
python script.py -v --format json data.json
```

**Output:**
```
[VERBOSE] Loading configuration...
[VERBOSE] Parsing JSON input...
[VERBOSE] Processing data...
{
  "status": "success",
  "processed": true,
  "result": {
    "name": "test",
    "value": 123,
    "timestamp": "2024-02-07T10:30:00"
  }
}
[VERBOSE] Operation completed in 0.23s
```

---

## Project Demo

### Video
[Add your demo video link here - YouTube, Google Drive, etc.]

*Explain what the video demonstrates - key features, user flow, technical highlights*

### Additional Demos
[Add any extra demo materials/links - Live site, APK download, online demo, etc.]

---

## AI Tools Used (Optional - For Transparency Bonus)

If you used AI tools during development, document them here for transparency:

**Tool Used:** [e.g., GitHub Copilot, v0.dev, Cursor, ChatGPT, Claude]

**Purpose:** [What you used it for]
- Example: "Generated boilerplate React components"
- Example: "Debugging assistance for async functions"
- Example: "Code review and optimization suggestions"

**Key Prompts Used:**
- "Create a REST API endpoint for user authentication"
- "Debug this async function that's causing race conditions"
- "Optimize this database query for better performance"

**Percentage of AI-generated code:** [Approximately X%]

**Human Contributions:**
- Architecture design and planning
- Custom business logic implementation
- Integration and testing
- UI/UX design decisions

*Note: Proper documentation of AI usage demonstrates transparency and earns bonus points in evaluation!*

---

## Team Contributions
- **Ameena Nasrin VK**: [Specific contributions, e.g., UI/UX Design, Dashboard Implementation, Lifestyle Module]
- **Suhaila Nasrin K**: [Specific contributions, e.g., Onboarding Flow, Doctor Search Logic, Report Timeline]

---

## License

This project is licensed under the [LICENSE_NAME] License - see the [LICENSE](LICENSE) file for details.

**Common License Options:**
- MIT License (Permissive, widely used)
- Apache 2.0 (Permissive with patent grant)
- GPL v3 (Copyleft, requires derivative works to be open source)

---

Made with ❤️ at TinkerHub
