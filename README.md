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
| Saumitra Bata |  [Hardware / Coding ]  |  [Documentation]   |  Documentation, Gift of Gab  |
| Anish Deodhar |  [Hardware / Fabrication]    |  [Coding]      |  Material Handling, Gift of Gab     |
|  Virat Dhoot  |  [Documentation/ Hardware  ]  |  [Coding]   |  Documentation, Material Handling  |
|  Nitisha Dung   |  [Fabrication/Harware]    |  [Coding]      |  Material Handling, Hardware     |

<img width="813" height="700" alt="image" src="https://github.com/ViratDhoot/SKILLLAB__PROR-2026-STOPPABLE/blob/main/images/Team%20Photograph.jpeg" />

## 1.3 Project Title

 "Sync-Box" 

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

 It is a RFID-based personalized dispensing. Instead of just releasing pills at a fixed time, this system ensures the right person is taking the right medicine, which solves a real-world problem in multi-user environments. On top of that, features like dose verification (via sensors), alerts system turn it from a basic dispenser into a connected healthcare assistant that works according to individual needs. 

---

# 4. Project Intent

## 4.1 User Journey 

 It’s 8:00 AM in an old-age home, and the **Sync Box** gently lights up and indicates it's medication time. Residents walk up one by one on their own. Mr. Sharma taps his RFID card, the system recognizes him instantly, and only his assigned compartment opens to dispense his specific pills. He takes the medicine and taps the confirm sensor, and the system logs his dose as “taken.” A few minutes later, another resident comes, taps their card, and receives a completely different set of medicines—all from the same shared device, without confusion or assistance. 

 Meanwhile, the caregiver doesn’t need to be physically present. On a local web dashboard, they can see live updates: who has taken their medicine, who is late, and who hasn’t shown up yet. When one resident misses their dose, the system marks it and updates the dashboard in real time. The caregiver can quickly identify the issue remotely and decide whether to intervene. By the end of the day, the Sync Box provides a complete adherence report, making medication management efficient, independent for residents, and easy to monitor for caregivers. 

---

# 5. Definition of Success

## 5.1 Definition of “Usable”

 A product is usable if it allows its intended users to achieve their goals easily, efficiently, and without confusion or error, in real-world conditions. 

 A device can be functional but still not usable.
Example: your medicine box project could dispense pills correctly—but if an old person can’t understand the interface, it’s useless in practice. 

## 5.2 Minimum Usable Version 

 The smallest version of this project that still delivers the core experience is a simple, single-user medicine reminder system that ensures the patient takes their medication on time and allows a caregiver to know whether it was taken. This can be achieved using a microcontroller Raspberry Pico Pi 2, a buzzer or LED for alerts, and a single push button for user confirmation. At the scheduled time, the device gives an audible or visual alert prompting the user to take the medicine from a basic compartment. Once the medicine is taken, the user presses the button to confirm, and this status is sent over Wi-Fi to a simple webpage or dashboard for the caregiver to monitor remotely. This minimal setup removes complex features like RFID, multiple users, or automated dispensing, yet still fulfills the essential goal of timely medication intake and remote awareness, which defines the core value of the system. 

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

- [x] App-connected

- [x] Motorized

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
|  [Raspberry Pi Pico 2]    |  1       |  [Main controller]                    |
|  [Touch Sensor]           |  5       |  [Verification]                       |
|  [RFID (RC522)]            |  1       |  [Individual Detection]              |
|  [LED]                    |  8       |  [Indication]                         |
|  [Buzzer]                 |  2       |  [Alert]                              |


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
 [Upload image and link here] 
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

| Tool / Platform                | Purpose                                        |
| ------------------------------ | ---------------------------------------------- |
|  [Aurdino ID]                  |  Code into Raspberry Pi Pico                   |
|  [Python/PyGame/OpenCV]        |  Track markers, game logic, create projection  |
|  [Fusion/Blender/Illustrator]  |  [Prototyping structure]                       |

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

Write how your team will work together.

Include:

- how tasks are divided,
- how decisions are made,
- how progress will be checked,
- what happens if a task is delayed,
- how documentation will be maintained.

**Response:**  


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

| Week   | Planned Goal   | What Actually Happened | What Changed   | Next Steps     |
| ------ | -------------- | ---------------------- | -------------- | -------------- |
| Week 1 |  [Write here]  |  [Write here]          |  [Write here]  |  [Write here]  |
| Week 2 |  [Write here]  |  [Write here]          |  [Write here]  |  [Write here]  |
| Week 3 |  [Write here]  |  [Write here]          |  [Write here]  |  [Write here]  |
| Week 4 |  [Write here]  |  [Write here]          |  [Write here]  |  [Write here]  |

---

# 14. Risks and Unknowns

## 14.1 Risk Register

| Risk                                                            | Type         | Likelihood | Impact   | Mitigation Plan                                                                       | Owner                |
| --------------------------------------------------------------- | ------------ | ---------- | -------- | ------------------------------------------------------------------------------------- | -------------------- |
| WiFi connection between laptop and ESP32 becomes unstable       |  Technical   |  Medium    |  High    | Keep ESP32 close, ensure stable power supply, reduce network load, add fail-safe stop |  [Gopal]            |


## 14.2 Biggest Unknown Right Now

What is the single biggest uncertainty in your project at this stage?

**Response:**  


---

# 15. Testing 

## 15.1 Technical Testing Plan

| What Needs Testing     | How You Will Test It                                                                 | Success Condition                                                                                    |
| ---------------------- | ------------------------------------------------------------------------------------ | ---------------------------------------------------------------------------------------------------- |
|  [Wifi connection]     |  [Check if motor spins via app button]                                               |  [Both motors accurately respond to wifi signals]                                                    |
                       |
## 15.2 Testing and Debugging Log

| Date          | Problem Found                         | Type         | What You Tried                                | Result               | Next Action                                    |
| ------------- | ------------------------------------- | ------------ | --------------------------------------------- | -------------------- | ---------------------------------------------- |
|  18th April   |  Car not balancing properly           |  Mechanical  |  Add low-friction caster support to one side  |  Worked              |  improve caster structure                      |


## 15.3 Playtesting Notes

| Tester      | What They Did                        | What Confused Them                    | What They Enjoyed                         | What You Will Change                          |
| ----------- | ------------------------------------ | ------------------------------------- | ----------------------------------------- | --------------------------------------------- |
|  Gopal  |  Tried navigating through obstacles  |  Some obstacles ewren't clear enough  |  Liked projection + real car interaction  |  Add a slight red highlight around obstacles  |


---

# 16. Build Documentation

## 16.1 Fabrication Process

Describe how the project was physically made.

Include:

- cutting,
- 3D printing,
- assembly,
- fastening,
- wiring,
- finishing,
- revisions.

**Response:**  
 The fabrication process involved designing, manufacturing, assembling, and refining both the physical structure and electronic integration of the system. 

 Design (CAD Modeling):
The initial model was created using CAD software, where components were designed based on the actual dimensions of the electronic parts. This ensured accurate fitting and minimized errors during assembly.
Cutting (Laser Cutting):
The designed parts were fabricated using laser cutting techniques. Sheets were cut precisely according to the CAD model to create the structural base and mounts for components. 

 Components were fixed using adhesives and mechanical supports. Certain parts were intentionally kept modular (not permanently fixed) to allow easy replacement and modification of electronics.
Surface Finishing:
Some parts were sanded to smooth rough edges after cutting. Sawdust mixed with adhesive was used to fill gaps and uneven edges, improving structural finish. The final structure was then painted for better aesthetics and durability. 

 Environment Setup (Dark Room Fabrication):
To enhance projection visibility, a controlled dark environment was created using Z-boards, paper sheets, and bedsheets. This minimized external light interference and improved projection clarity.
Revisions and Iterations:
Multiple adjustments were made throughout the process, including refining alignment, improving structural stability, repositioning components, and optimizing the interaction between the physical car and projected environment. 

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

Describe the final version of your project.

**Response:**  


## 17.2 What Works Well



## 17.3 What Still Needs Improvement


## 17.4 What Changed From the Original Plan

How did the project change from the initial idea?

**Response:**  


---

# 18. Reflection

## 18.1 Team Reflection

What did your team do well?  
What slowed you down?  
How well did you manage time, tasks, and responsibilities?

**Response:**  


## 18.2 Technical Reflection

What did you learn about:

- electronics,
- coding,
- mechanisms,
- fabrication,
- integration?

**Response:**  


## 18.3 Design Reflection

What did you learn about:

- designing ,
- delight,
- clarity,
- physical interaction,
- understanding,
- iteration?

**Response:**  


## 18.4 If You Had One More hour

What would you improve next?

**Response:**  

   

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


