# SKILL LAB PRATICAL HACKATHON

## Final Project README

> **Project Weight:** 100%  
> **Team Size:** 4/3 students  
> **Project Duration:** 8 hours  
> **Total Time Available:** 32 effort-hours per team  
> **Project Type:** Playful, interactive, technology-based experience

---

# Before you begin

## Fork and rename this repository

After forking this repository, rename it using the format:

 SKILLLAB_PROR-2026-TeamName 

### Example

 SKILLLAB_PROR-2026-AuroWizards 

Do not keep the default repository name.

---

# How to use this README

This file is your team’s **working project document**.

You must keep updating it throughout the build period.  
By the final review, this README should clearly show:

- your idea,
- your planning,
- your design decisions,
- your technical process,
- your build progress,
- your testing,
- your failures and changes,
- your final outcome.

## Rules

- Fill every section.
- Do not delete headings.
- If something does not apply, write  `Not applicable`  and explain why.
- Add images, screenshots, sketches, links, and videos wherever useful.
- Update task status and weekly logs regularly.
- Use this file as evidence of process, not only as a final report.

---

# 1. Team Identity

## 1.1 Studio / Group Name

Team STOPPABLE

## 1.2 Team Members

| Name           | Primary Role                    | Secondary Role | Strengths Brought to the Project |
| -------------- | ------------------------------- | -------------- | -------------------------------- |
| Saumitra Bata |  Hardware / Coding   |  [Documentation]   |  Documentation, Gift of Gab  |
| Anish Deodhar |  Hardware / Fabrication]    |  [Coding]      |  Material Handling, Gift of Gab     |
|  Virat Dhoot  |  Documentation/ Hardware  ]  |  [Coding]   |  Documentation, Material Handling  |
|  Nitisha Dung   |  Fabrication/Harware]    |  [Coding]      |  Material Handling, Hardware     |

<img width="813" height="700" alt="image" src="https://github.com/ViratDhoot/SKILLLAB__PROR-2026-STOPPABLE/blob/main/images/Team%20Photograph.jpeg" />

## 1.3 Project Title

 ### Sync-Box 
 

<img width="813" height="900" alt="image" src="https://github.com/ViratDhoot/SKILLLAB__PROR-2026-STOPPABLE/blob/main/images/Project%20Image.png" />

---

## 🎥 Demo Video

[![Watch the video](https://img.youtube.com/vi/KGYOpVLvnqs/0.jpg)](https://www.youtube.com/watch?v=KGYOpVLvnqs)

---

## 1.4 One-Line Pitch

 A Time synced automated medicine box with unique tags for individuals to take precise medication at right time catered to every individual. 

## 1.5 Expanded Project Idea
 
A time-synced automated medicine box with unique RFID tags ensures each person receives the correct medication at the right time. The system alerts the user when a dose is due, verifies their identity using an RFID tag, and then dispenses the medicine, reducing errors like missed or incorrect doses.
It combines technologies like an Raspberry Pi Pico 2, RFID module, motors for dispensing, and sensors for verification.This creates a smart, reliable system that improves medication adherence and patient safety.
 

---


# 2. Philosophy Fit

## 2.1 Experience, Not Social Problem

This module does **not** require your project to solve a large social problem.

You are allowed to build:

- toys,
- games,
- interactive objects,
- playful machines,
- kinetic artifacts,
- humorous devices,
- strange but delightful experiences,
- things that are entertaining to use or watch.



# 3. Inspiration

## 3.1 References

List what inspired the project.

| Source Type | Title / Link                                                        | What Inspired You                                                                         |
| ----------- | ------------------------------------------------------------------- | ----------------------------------------------------------------------------------------- |
|  [Scientific Report]  |  https://www.ncbi.nlm.nih.gov/books/NBK225187/  |  Medication errors are a major cause of preventable deaths in healthcare systems.  |
|  [Encyclopedia article]  |  https://en.wikipedia.org/wiki/Overmedication  |  Managing multiple medicines and dosage is one of the biggest challenges in elderly care.   |
|             |                                                                     |                                                                      |



## 3.2 Original Twist

The system operates as a personalized medication guidance system which uses RFID technology. The system uses RFID cards to verify which person should receive which medications at the correct schedule instead of dispensing pills automatically. The system uses touch sensors to verify drug intake while specific LEDs display which medications should be taken according to the current time. The system offers personalized solutions through its user-friendly design which includes double-dose prevention and separate alert systems for missed doses.


---

# 4. Project Intent


## 4.1 User Journey 

The Sync Box shows visual cues for medication time at 8:00 AM. The residents use their RFID cards to approach the device. The system identifies Mr. Sharma when he taps his card which triggers specific LEDs that show his required medicines. He follows the LED indications to take his medicines while using touch sensors to confirm each one. The system registers the dose complete after the user provides all required inputs.

Another resident scans their card after a few minutes which leads to different LED indications that match their scheduled times. The system prevents users from taking their medication at the same time while creating a system that makes it clear who the current user is. A dedicated buzzer alert system activates when a resident fails to take their medicine within their scheduled time and continues until the dose is completed. The system creates a straightforward system that guides users to manage their medications independently without needing outside help or complicated systems.


---


# 5. Definition of Success



## 5.1 Definition of “Usable”

 A product is usable if it allows its intended users to achieve their goals easily, efficiently, and without confusion or error, in real-world conditions. 

 A device can be functional but still not usable.
Example: your medicine box project could dispense pills correctly—but if an old person can’t understand the interface, it’s useless in practice. 



## 5.2 Minimum Usable Version 

The smallest version of this project that still delivers the core experience is a simple, single-user medication guidance system that ensures the patient takes their medicine on time. The system can be built with a Raspberry Pi Pico and two LEDs for status display and one touch sensor for user verification. The system uses an LED light to notify users about their scheduled medication time. After the user takes their medicine, they press the touch sensor to confirm their action, which causes the system to record the event and reset for the upcoming cycle. This basic configuration maintains essential functions for confirming medication intake at scheduled times, but it eliminates features such as RFID and multiple user access and alert systems.



## 5.3 Stretch Features

 1.Automatic pill dispensing (motors, mechanisms)
Sounds impressive, but introduces mechanical failure points. A simple box works fine for the core function. 
 2. Mobile app instead of simple webpage
A full app feels professional, but a basic web interface already solves the caregiver visibility problem. 
 3. Voice assistant integration (Alexa, Google Assistant)
Cool demo feature, but doesn’t improve reliability or usability significantly. 

---



# 6. System Overview



## 6.1 Project Type

Check all that apply.

- [x] Electronics-based

- [ ] Mechanical

- [x] Sensor-based

- [ ] App-connected

- [ ] Motorized

- [ ] Sound-based

- [x] Light-based

- [x] Screen/UI-based

- [x] Fabricated structure

- [x] Game logic based

- [x] Installation

- [ ] Other:

## 6.2 High-Level System Description

 The system works as an automated medicine management unit designed to ensure that patients take the correct medicines at the right time. It begins with the input stage, where the system receives three types of inputs. First, an RFID card is scanned using an RC522 RFID Module, which identifies the patient based on a unique UID. Second, the system internally tracks time using a programmed timer to divide the day into different slots, determining when medicines should be taken. Third, touch sensors act as confirmation inputs, allowing the patient to indicate that they have taken the required medicines. 

 Once the inputs are received, the system moves to the processing stage, where the microcontroller acts as the brain. It compares the scanned RFID UID with stored patient data to identify the user, checks the current time slot, and decides which medicines are scheduled for that patient at that time. It also verifies whether the medicine has already been taken in that slot to prevent overdosing. If the slot has already been used, the system blocks further action; otherwise, it activates the appropriate outputs and waits for confirmation through touch sensors before marking the medicines as taken. 

 In the output stage, the system communicates its decisions through LEDs and alerts. Specific LEDs glow to indicate which medicine compartments should be accessed, guiding the patient visually. A Green LED is used as a warning indicator when an invalid action occurs, such as attempting to take medicine twice in the same time slot. Additionally, the system sends messages like “Patient 1 | Slot 0” through serial communication, which can later be used for monitoring or data logging. 

 Physically, the system is structured as a compact medicine box containing multiple compartments, each associated with an LED and a touch sensor. The RFID reader is placed on the exterior for easy access, allowing patients to scan their cards before taking medicines. Inside the box, a microcontroller connects all components, including LEDs, sensors, and the RFID module, forming a complete embedded system that interacts with the user in a simple and guided manner. 


## 6.3 Input / Output Map

| System Part                              | Type            | What It Does                                                               | 
| ---------------------------------- | ------------------- | ------------------------------------------------------------------------------ |
|  RFID Reader (MFRC522)               | Input               | Reads RFID card UID to identify which patient is accessing the system        |
|  Touch Sensors (TOUCH_1 to TOUCH_5)  | Input               | Detect user interaction to confirm that each medicine has been taken         |
|  Time Slot Logic (millis())        | Input (Virtual)     | Generates time-based slots to decide which medicines should be dispensed       |
|  Patient UID Data                    | Input (Stored Data) | Matches scanned RFID UID with predefined patient identities                  |
|  LEDs (LED_1 to LED_5)              | Output              | Indicate which medicine compartments should be accessed for current slot      |
|  Red LED (LED_RED)                 | Output              | Alerts user if medicine already taken or invalid action                        |
|  Serial Monitor (Serial.print )    | Output              | Displays system status, UID, patient info, and slot data for debugging/logging |
|  Medicine Logic (giveMedicine() )  | Process             | Decides which medicines to activate based on patient and time slot             |
|  Touch Confirmation Loop             | Process             | Ensures all required medicines are taken before marking slot complete        |

---

# 7. Sketches and Visual Planning

## 7.1 Concept Sketch

<img width="813" height="700" alt="image" src="https://github.com/ViratDhoot/SKILLLAB__PROR-2026-STOPPABLE/blob/main/images/non%20labled.png" />

## 7.2 Labeled Build Sketch

<img width="813" height="700" alt="image" src="https://github.com/ViratDhoot/SKILLLAB__PROR-2026-STOPPABLE/blob/main/images/labled.png" />

## 7.3 Approximate Dimensions

| Dimension        | Value   |
| ---------------- | ------- |
| Length           |  16 cm  |
| Width            |  16 cm  |
| Height           |  8 cm   |
| Estimated weight |  400 g  |

---

# 8. Electronics Planning

## 8.1 Electronics Used

| Component                 | Quantity | Purpose                               |
| ------------------------- | --------:| ------------------------------------- |
|  Raspberry Pi Pico 2    |  1       |  Main controller                    |
|  Touch Sensor           |  5       |  Verification                       |
|  RFID (RC522)            |  1       |  Individual Detection             |
|  LED                    |  8       |  Indication                         |
|  Buzzer                 |  2       |  Alert                              |


## 8.2 Wiring Plan

Describe the main electrical connections.

**Response:**  
 The **RP2040 Pico** is the central controller. It communicates with the **RC522 RFID module** over the SPI bus using five wires: GPIO 17 (CS), GPIO 20 (RST), plus the shared MOSI, MISO, and SCK lines. The CS pin selects the RC522 on the SPI bus, and the RST pin allows hardware reset of the module.
The **five medicine LEDs** are each connected directly from their respective GPIO output pins (10, 11, 14, 15, 21) to GND, with no resistors in the circuit. The **sixth alert LED** (also green) follows the same direct connection on GPIO 22 — it lights up as a warning when a patient attempts to scan their card after already completing that time slot's dose.
The **five capacitive touch sensors** are each wired with one terminal to a dedicated GPIO input pin (26, 27, 28, 6, 7) and the other terminal to GND. When the patient's finger touches the sensor pad, the pin reads HIGH; when untouched, it reads LOW.
All components — the RFID module, LEDs, and touch sensors — share a **common GND rail** connected to the Pico's GND pin to ensure a stable voltage reference across the entire circuit. The system is powered via the Pico's **Micro-USB port** at 5V, which the onboard regulator steps down to 3.3V to supply the RC522 module and all logic-level signals. 

## 8.3 Circuit Diagram

Insert a hand-drawn or software-made circuit diagram.

**Insert image below:**  
<img width="867" height="1156" alt="" src="" />


# 9. Power Plan

| Question         | Response                                                                                                                                          |
| ---------------- | ------------------------------------------------------------------------------------------------------------------------------------------------- |
| Power source     |  Device(Laptop)                                                                                                                            |
| Voltage required |  3.3V for Circuit                                                                   |
| Current concerns |  Possibilty of reduction in LED's Brightness due to lot of LEDs being turned on simultaneously                                        |
| Safety concerns  |  Not Applicable  |

---

# 10. Software Planning

## 10.1 Software Tools


| Tool / Platform                               | Purpose                                                                 |
| --------------------------------------------- | ----------------------------------------------------------------------- |
| Arduino IDE                                   | Writing and uploading code to Raspberry Pi Pico                         |
| Raspberry Pi Pico (RP2040) Board Package      | Enables Arduino IDE to program the Pico microcontroller                 |
| MFRC522 Library                               | Used for interfacing with the RFID module and reading UID data          |
| SPI Library                                   | Handles communication between Pico and RFID module                      |
| Serial Monitor (Arduino IDE)                  | Debugging and viewing system outputs like UID, patient, and slot data   |



## 10.2 Software Logic

Describe what the code must do.

Include:

- startup behavior,
- input handling,
- sensor reading,
- decision logic,
- output behavior,
- communication logic,
- reset behavior.


**Startup behavior:**
The system initializes LEDs, touch sensors, buzzers, and the RFID reader using the MFRC522 RFID Module. All outputs are turned OFF, timers are set, and the system becomes ready for operation.

**Input handling:**
It reads RFID cards to identify patients and ignores repeated scans using a cooldown. Invalid cards are rejected.

**Sensor reading:**
Touch sensors detect medicine confirmation, and internal timing (millis) determines the current time slot.

**Decision logic:**
The system checks patient ID and slot, prevents duplicate intake, and selects required medicines. It waits until all required touches are completed.

**Output behavior:**
LEDs indicate medicines, a red LED shows errors, and buzzers alert if a dose is missed.

**Communication logic:**
Serial output sends data like patient and slot, which can be extended using an ESP32 for web monitoring.

**Reset behavior:**
LEDs and alerts reset automatically after use, and the system continuously runs for the next cycle.

## 10.3 Code Flowchart

Insert a flowchart showing your code logic.

Suggested sequence:

- start,
- initialize,
- wait for input,
- read input,
- decision,
- trigger output,
- repeat or reset,
- error handling.

**Insert image below:**  
<img width="1600" height="1200" alt="image" src="" />
<img width="1600" height="1200" alt="image" src="" />




# 11. Bill of Materials

## 11.1 Full BOM

| Item                             | Quantity | In Kit? | Need to Buy? | Estimated Cost | Material / Spec               | Why This Choice?          |
| -------------------------------- | --------:| ------- | ------------ | --------------:| ----------------------------- | ------------------------- |
| Raspberry Pi Pico                |  1       |  Yes    |  No          |  0             |  38 Pin ESP32                 |  [To control components]  |
| Touch sensor                     |  5       |  [Yes]  |  [No]        |  0             |  [LN296]                      |  [To drive both motors]   |
| Buzzer                           |  2       |  [No]   |  [Yes]       |  [150]         |  [BO Motors and 6 cm wheels]  |  [high torque motors]     |
| Led                              |  8       |  [No]   |  [Yes]       |  [75]          |                               |                           |
| RFID RC522                       | 1        |  [No]   |  [Yes]       |  [200]         |                               |                           |

## 11.2 Material Justification

Explain why you selected your main materials and components.

The RP2040 Pico was chosen as the microcontroller because it has sufficient GPIO pins to handle all five LEDs, five touch sensors, the RFID module's SPI bus, two buzzers, and one alert LED simultaneously without needing a port expander. Its onboard 3.3V regulator also directly powers the RC522 module, removing the need for an external voltage regulator.
The RC522 RFID module was chosen over a keypad or fingerprint sensor for identity input because it requires zero physical effort from the patient — especially important for elderly or post-surgery users who may have limited dexterity. A card tap is faster and more reliable than typing a PIN, and each card carries a hardcoded unique UID that cannot be accidentally duplicated.
LEDs were chosen as the output indicator instead of an OLED or LCD display because they are universally understood regardless of literacy or language. A glowing compartment is unambiguous — no reading required. This makes the device accessible to elderly patients or those unfamiliar with digital interfaces.
Capacitive touch sensors (red round cap type) were chosen over mechanical push buttons because they require only a light touch with no physical force, which matters for patients with weak grip or joint pain. They also have no mechanical parts that can wear out over repeated use.
Buzzers were added as a missed-dose alert mechanism because a purely visual LED reminder is easy to miss, especially if the patient is in another room or asleep. Two separate buzzers (one per patient) allow the system to alert each individual independently without disturbing the other.

## 11.3 Items You chose
Here's your **Section 11.2 — Material Justification** and **Section 11.3 — Items You Chose:**

---

**11.2 Material Justification**

The **RP2040 Pico** was chosen as the microcontroller because it has sufficient GPIO pins to handle all five LEDs, five touch sensors, the RFID module's SPI bus, two buzzers, and one alert LED simultaneously without needing a port expander. Its onboard 3.3V regulator also directly powers the RC522 module, removing the need for an external voltage regulator.

The **RC522 RFID module** was chosen over a keypad or fingerprint sensor for identity input because it requires zero physical effort from the patient — especially important for elderly or post-surgery users who may have limited dexterity. A card tap is faster and more reliable than typing a PIN, and each card carries a hardcoded unique UID that cannot be accidentally duplicated.

**LEDs** were chosen as the output indicator instead of an OLED or LCD display because they are universally understood regardless of literacy or language. A glowing compartment is unambiguous — no reading required. This makes the device accessible to elderly patients or those unfamiliar with digital interfaces.

**Capacitive touch sensors** (red round cap type) were chosen over mechanical push buttons because they require only a light touch with no physical force, which matters for patients with weak grip or joint pain. They also have no mechanical parts that can wear out over repeated use.

**Buzzers** were added as a missed-dose alert mechanism because a purely visual LED reminder is easy to miss, especially if the patient is in another room or asleep. Two separate buzzers (one per patient) allow the system to alert each individual independently without disturbing the other.

---

**11.3 Items You Chose**

|    Component    |   Model / Type              |    Quantity   |           Purpose                              |
| Microcontroller | RP2040 Pico                 |     1         | Central logic, GPIO control, SPI communication |
| RFID Readerm    | RC522                       |     1         | Reads patient identity via card UID            |
| RFID Cards      | Passive MIFARE 13.56 MHz    |     2         | One per patient — unique identity token        |
| Medicine LEDs   | Standard 5mm LED (green)    |     5         | Indicate which medicines to take               |
| Alert LED       | Standard 5mm LED (green)    |     1         | Overdose / already-taken warning on GPIO 22    |
| Touch Sensors   | Capacitive round cap module |     5         | Patient confirmation of each medicine taken    |
| Buzzers         | Active buzzer module        |     2         | Missed-dose alert, one per patient             |
| Breadboard      | Full-size 830-point         |     1         | Prototyping and component mounting             |
| Jumper wires    | Male-to-male&male-to-female |    ~40        | All electrical connections                     |
| USB cable       | Micro-USB                   |     1         | Power supply from laptop / adapter             |
  

## 11.4 Budget Summary

| Budget Item           | Estimated Cost              |
| --------------------- | ---------------------------:|
| Electronics           |  [400]                      |
| Mechanical parts      |  [200]                      |
| Fabrication materials |  [0 (Available on campus)]  |
| Purchased extras      |  [0]                        |
| Contingency           |  [300]                      |
| **Total**             |  [900]                      |

## 11.5 Budget Reflection

If your cost is too high, what can be simplified, removed, substituted, or shared?

**Response:**  

---

# 12. Planning the Work

## 12.1 Team Working Agreement

We divided tasks according to our individual strengths in work performance. Anish operated in the hardware domain because he managed wiring tasks and solved technical issues while recording the complete demonstration. Saumitra managed the coding and WiFi installation tasks whereas Nitisha constructed the physical structure and led both the presentation and documentation work. Virat established the initial phase of our project by creating the first documentation framework and report templates.

The team maintained collaborative work processes because all significant technical decisions required group input. The team maintained progress through short unplanned meetings and active testing sessions in which team members demonstrated their operational results. The team solved problems by redistributing tasks and providing support to complete the assignment. We maintained our notes by updating them throughout the project and then we worked together to create a unified final report which represented our work as one complete project.


## 12.2 Task Breakdown

| Task ID | Task                    | Owner    | Estimated Hours | Deadline     | Dependency | Status |
| ------- | ----------------------- | -------- | ---------------:| ------------ | ---------- | ------ |
| T1      |  [Finalize concept]     |  [Both]  |  2              |  1st April   |  None      |  Done  |


## 12.3 Responsibility Split

| Area                 | Main Owner | Support Owner |
| -------------------- | ---------- | ------------- |
| Concept              |  [Gopal]   |  [Kader]      |
| Electronics          |  []        |  []           |
| Coding               |  []        |  []           |
| Mechanical build     |  []        |  []           |
| Testing              |  []        |  []           |
| Documentation        |  []        |  []           |

---

# 13. 2 hour Milestones

## 13.1 8-hour Plan

### Bi Hour 1 — Plan and De-risk

Expected outcomes:

- [x] Idea finalized
- [x] Core interaction decided
- [x] Sketches made
- [x] BOM completed
- [x] Purchase needs identified
- [ ] Key uncertainty identified
- [x] Basic feasibility tested

### Bi Hour 2 — Build Subsystems

Expected outcomes:

- [x] Electronics tests completed
- [ ] CAD / structure planning completed
- [ ] App UI started if needed
- [x] Mechanical concept tested
- [x] Main subsystems partially working

### Bi Hour 3 — Integrate

Expected outcomes:

- [x] Physical body built
- [x] Electronics integrated
- [x] Code connected to hardware
- [ ] App connected if required
- [x] First playable version exists

### Bi Hour 4 — Refine and Finish

Expected outcomes:

- [x] Technical bugs reduced
- [x] Playtesting completed
- [x] Improvements made
- [x] Documentation completed
- [x] Final build ready

## 13.2  Update Log


| Hour       | Planned Goal                                        | What Actually Happened                                                         | What Changed                                                                   | Next Steps                                   |
| ---------- | --------------------------------------------------- | ------------------------------------------------------------------------------ | ------------------------------------------------------------------------------ | -------------------------------------------- |
| Hour 2     | Finalize idea, decide components, basic wiring plan | Project idea finalized, RFID and LED testing started                           | Simplified design by focusing on core functionality instead of full automation | Complete basic circuit and test RFID reading |
| Hour 4     | Build circuit with sensors and RFID, start coding   | RFID working, LEDs responding, initial touch sensor issues faced               | Added debounce logic and improved wiring for stable sensor readings            | Integrate touch confirmation with LED logic  |
| Hour 5     | Implement full system logic and testing             | Time-slot logic and buzzer system implemented, faced issues with blocking code | Switched to non-blocking `millis()` based logic for better stability           | Final integration and system testing         |
| Hour 7     | Final testing, debugging, documentation             | System working reliably, buzzer and LED logic stable, documentation completed  | Removed complex features like motors and WiFi to ensure system reliability     | Prepare final demo and presentation          |

---

# 14. Risks and Unknowns

## 14.1 Risk Register


| Risk                                               | Type        | Likelihood | Impact | Mitigation Plan                                                          | Owner |
| -------------------------------------------------- | ----------- | ---------- | ------ | ------------------------------------------------------------------------ | ----- |
| Incorrect RFID reading or failure to detect card   | Technical   | Medium     | High   | Ensure proper wiring, maintain optimal scan distance, use stable power   | Team  |
| Touch sensors giving unstable or false readings    | Technical   | Medium     | Medium | Use INPUT_PULLDOWN, proper grounding, and debounce logic                 | Team  |
| Loose wiring or poor connections                   | Technical   | High       | High   | Secure connections, use quality jumper wires, and check continuity       | Team  |
| Power fluctuations affecting components            | Technical   | Medium     | Medium | Use stable power source and maintain common ground across components     | Team  |
| LED or buzzer failure                              | Hardware    | Low        | Medium | Pre-test components and keep spare parts ready                           | Team  |
| Logic errors causing incorrect medicine indication | Software    | Medium     | High   | Debug using Serial Monitor and test all edge cases                       | Team  |
| User confusion in interaction                      | Usability   | Low        | Medium | Design clear LED indicators and keep interaction simple and intuitive    | Team  |

## 14.2 Biggest Unknown Right Now

What is the single biggest uncertainty in your project at this stage?

The biggest question mark left is whether the servo motor can actually behave itself. While the identification and alert logic are solid, moving from "telling" to "dispensing" introduces a lot of mechanical chaos—things like perfect alignment, consistent rotation, and the constant threat of a pill jamming the gears. The real challenge for the next stage is making sure that adding these moving parts doesn't break the reliability we worked so hard to build. 


---

# 15. Testing 

## 15.1 Technical Testing Plan


| What Needs Testing       | How You Will Test It                          | Success Condition                                              |
| ------------------------ | --------------------------------------------- | -------------------------------------------------------------- |
| RFID card detection      | Scan multiple RFID cards repeatedly           | Correct user is identified accurately every time               |
| LED indication logic     | Trigger different time slots and scan RFID    | Correct LEDs activate based on user and time slot              |
| Touch sensor response    | Press each touch sensor during active session | Corresponding LED turns OFF reliably upon confirmation         |
| Double dosage prevention | Scan same RFID twice in the same slot         | System blocks access and warning LED turns ON                  |
| Buzzer alert system      | Do not scan RFID for a set time (e.g., 2 min) | Buzzer activates as a reminder                                |
| Buzzer reset             | Scan RFID and complete medicine intake        | Buzzer turns OFF immediately after confirmation                |
| Serial output            | Monitor Serial during operation               | Correct user ID and time slot data displayed consistently      |
| Overall system flow      | Perform full cycle (scan → take → confirm)    | System operates smoothly without errors or unexpected behavior |


## 15.2 Testing and Debugging Log

| Date       | Problem Found                       | Type           | What You Tried                                         | Result | Next Action                     |
| ---------- | ----------------------------------- | -------------- | ------------------------------------------------------ | ------ | ------------------------------- |
| 18th April | RFID not detecting cards properly   | Hardware       | Checked wiring, reduced distance, reinitialized module | Worked | Improve mounting stability      |
| 19th April | Touch sensors giving false triggers | Hardware       | Used INPUT_PULLDOWN and added debounce logic           | Worked | Fine-tune sensitivity           |
| 20th April | LEDs not turning OFF consistently   | Logic          | Fixed mapping between LED and touch sensors            | Worked | Test across all slots           |
| 21st April | System freezing during operation    | Software       | Removed blocking loops and used millis()               | Worked | Optimize code structure         |
| 22nd April | Buzzer triggering incorrectly       | Logic          | Switched from slot-based to time-based logic           | Worked | Improve independence of buzzers |
| 23rd April | One buzzer not working properly     | Hardware/Logic | Separated buzzer timing logic                          | Worked | Final testing of alerts         |



## 15.3 Playtesting Notes

| Tester      | What They Did                        | What Confused Them                    | What They Enjoyed                         | What You Will Change                          |
| ----------- | ------------------------------------ | ------------------------------------- | ----------------------------------------- | --------------------------------------------- |
|  Gopal  |  Tried navigating through obstacles  |  Some obstacles ewren't clear enough  |  Liked projection + real car interaction  |  Add a slight red highlight around obstacles  |


---

# 16. Build Documentation

## 16.1 Fabrication Process

The fabrication process of the smart medication management system included designing, assembling, wiring, and refining both the hardware structure and electronic components. 

The initial design was based on the sizes of the components like the Raspberry Pi Pico, RFID module, LEDs, touch sensors, and buzzers. This ensured proper placement and accessibility. The base structure was created using a simple enclosure or mounting board, where slots and positions for each component were marked and adjusted by hand.

Basic cutting and shaping were done to make openings for the LEDs, RFID scanner, and touch sensors. The components were then attached to the structure with adhesives and basic fastening methods. Some parts remained modular for easy debugging and replacement.

Wiring connected all components to the microcontroller. This ensured proper power distribution, common grounding, and stable signal connections. Care was taken to organize the wires to prevent loose connections and interference.

Minor finishing steps involved securing loose components, properly aligning sensors, and making sure the LEDs were clearly visible for user interaction. Throughout the process, multiple revisions were made to resolve issues like incorrect connections, unstable sensor readings, and component placement. This resulted in a stable and functional prototype.

 
## 16.2 Build Photos

- early sketch,
<img width="960" height="1280" alt="WhatsApp Image 2026-04-24 at 9 46 02 AM (1)" src="" />
- Initial Build ,
<img width="960" height="1280" alt="WhatsApp Image 2026-04-24 at 9 46 02 AM (1)" src="https://github.com/ViratDhoot/SKILLLAB__PROR-2026-STOPPABLE/blob/main/images/Basic%20Build.jpeg" />
- Build testing,
<img width="960" height="1280" alt="WhatsApp Image 2026-04-24 at 9 46 02 AM (1)" src="https://github.com/ViratDhoot/SKILLLAB__PROR-2026-STOPPABLE/blob/main/images/Build%20Testing.jpeg" />
- final build.
- <img width="960" height="1280" alt="WhatsApp Image 2026-04-24 at 9 46 02 AM (1)" src="" />



# 17. Final Outcome

## 17.1 Final Description

The final version of the project is a fully functional smart medication management system designed to ensure accurate and timely medicine intake for multiple users. The system uses RFID cards to uniquely identify patients and, based on predefined time slots, activates specific LEDs to indicate the medicines to be taken. Touch sensors allow users to confirm intake, after which the system records completion and turns off the corresponding indicators. It includes a safety mechanism that prevents repeated access within the same time slot to avoid double dosage. Additionally, each patient has an independent buzzer alert that activates if a dose is missed and continues until the medication is taken. The system is built on a Raspberry Pi Pico with a clean, non-blocking logic architecture, ensuring stable and continuous operation.


## 17.2 What Works Well

The system's main parts and functions are all working as they should. The RFID-based identification system correctly tells different patients apart. The LED lights clearly show which medicines need to be taken, and the time-based logic correctly sets up the medication schedules. The touch sensors always work, which makes it easy to confirm that the medicine was taken. The system works well to stop people from taking the same dose twice in the same time slot. The independent buzzer alert system also works for each patient, only sending reminders when a dose is missed. The hardware and software work well together overall, and the system runs smoothly without any problems or delays.


## 17.3 What Still Needs Improvement

The integration of the servo motor for automatic medicine dispensing still needs work. The core system for identification, indication, and confirmation is working fine, but the servo mechanism isn't fully in sync with the system logic yet. There needs to be more work on issues like precise control, consistent movement, and making sure that the medicine slots are lined up correctly. Also, the mechanical design for dispensing needs to be better calibrated to make sure it works reliably without getting stuck or lost. More work needs to be done to make sure that the servo works perfectly with the current system so that automatic dispensing is smooth and reliable.


## 17.4 What Changed From the Original Plan

Our original vision for the Smart Medicine Dispenser was ambitious: a fully automated system featuring servo-driven dispensing, real-time cloud alerts via the Pico W, and a dedicated LCD interface. However, as development progressed, we encountered the classic "mechanical hurdle." Precise pill alignment, servo synchronization, and the constant risk of jamming posed a threat to the system's most important job: reliability.

Reimagining the Approach
To ensure a rock-solid prototype, we strategically shifted our focus. We moved away from the mechanical risks of automatic dispensing and instead developed a Guided Medication System. By swapping servos for high-visibility LEDs and touch sensors, we transformed the device into an intuitive assistant:

Visual Guidance: LEDs clearly indicate exactly which medication needs to be taken.

Tactile Confirmation: Capacitive touch sensors allow the user to confirm they’ve taken their dose, closing the feedback loop without the risk of a mechanical failure.

Streamlined Logic: We replaced the external RTC and IoT dependencies with a robust software-based timer. This eliminated "network anxiety" and simplified the hardware footprint, ensuring the device works every time, regardless of Wi-Fi stability.

The Result
This pivot allowed us to master the core fundamentals: accurate identification, clear indication, and persistent missed-dose alerts. What we have now isn't just a simplified version of the original plan; it’s a stable, fully functional foundation. By removing the "moving parts" that often lead to failure in early-stage prototypes, we’ve created a more dependable device that is easier to demonstrate and perfectly positioned for future upgrades like remote monitoring or mechanical automation.

Essentially: We traded a "cool" motorized feature for a "critical" guarantee of performance. It’s better to have a system that reliably tells you what to take than an automated one that accidentally crushes a pill or loses its Wi-Fi connection.


---

# 18. Reflection

## 18.1 Team Reflection

The team worked really well together, syncing up during coding and wiring to build a system that actually works. We were at our best when things went sideways—quickly spotting bugs and making the tough call to pivot to a more reliable design when the original plan stalled.

That said, the "hardware tax" hit us hard. We lost quite a bit of momentum troubleshooting finicky wiring, stubborn servos, and jumpy sensor data, which required way more trial and error than we expected. While we shared the load fairly, we definitely underestimated how much time hardware debugging eats up. Luckily, we adapted by stripping the project down to its core essentials, which is the only reason we crossed the finish line with a working prototype on time.  


## 18.2 Technical Reflection

This project was a crash course in bridging the gap between theory and reality. On the electronics side, we moved past the basics to learn how sensors, RFID modules, and buzzers actually behave when wired together—specifically the "fun" of managing grounding and stable signals. On the software front, we leveled up from simple loops to non-blocking code with millis(), allowing us to juggle multiple real-time interactions without the system freezing up.

The mechanical side was a reality check; working with servos taught us that alignment and precision are much harder to achieve in practice than on paper. We also got our hands dirty with fabrication, figuring out how to actually layout and assemble a device that someone could easily use. Ultimately, the biggest takeaway was the art of integration—troubleshooting that final 10% where hardware and software meet to turn a mess of wires into a cohesive, functional prototype.


## 18.3 Design Reflection

We learned that great design isn't just about making things work; it’s about making them make sense. We focused on clarity, using LEDs as simple visual cues so there’s never a doubt about which pill is which. We found that "delight" actually comes from simplicity—creating a "scan, see, confirm" flow that feels satisfying rather than confusing.

The physical build taught us that placement is everything; we had to put the RFID, LEDs, and sensors exactly where they felt most natural to reach. This was especially true when considering elderly users, where every bit of reduced complexity makes a massive difference. Ultimately, it took a lot of trial and error to get there, but each iteration helped us strip away the friction to build something that isn't just functional, but genuinely user-friendly.


## 18.4 If You Had One More hour

With just one more hour, we would have dived back into the servo motor integration to make automatic dispensing a reality. The main goal would be syncing the motor’s movement perfectly with the system logic, ensuring each trigger results in a precise delivery. We’d spend that time calibrating the exact angles for smooth, consistent rotation and carefully aligning the mechanism with the compartments to finally solve the jamming issues. A quick round of stress-testing after RFID confirmation would have been the final touch, bringing the prototype one big step closer to being a truly "hands-free" automated dispenser.
   

---

# 19. Final Submission Checklist

Before submission, confirm that:

- [x] Team details are complete
- [x] Project description is complete
- [x] Inspiration sources are included
- [x] Sketches are added
- [x] BOM is complete
- [x] Purchase list is complete
- [x] Budget summary is complete
- [x] Mechanical planning is documented if applicable
- [ ] App planning is documented if applicable
- [x] Code flowchart is added
- [x] Task breakdown is complete
- [x] Weekly logs are updated
- [x] Risk register is complete
- [x] Testing log is updated
- [x] Playtesting notes are included
- [x] Build photos are included
- [x] Final reflection is written
<img width="1131" height="1600" alt="image" src="" />

---


---


