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


