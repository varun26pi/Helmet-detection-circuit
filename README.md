🪖 Helmet Detection for Bikes

A **Digital Electronics–based safety system** that ensures a motorcycle can start **only when the rider is wearing a valid helmet with the strap properly fastened**.
This project focuses on improving **road safety** using **sequential logic circuits** and **state-based control**.

📌 Project Overview

Road safety remains a major global concern, especially for two-wheeler riders. Although helmet laws exist, **non-compliance is still widespread**, leading to severe injuries and fatalities.

This project proposes an **automated helmet detection system** that integrates with a bike’s ignition mechanism.
The system verifies:

* Helmet presence
* Helmet type validity
* Strap fastening

Only after all conditions are satisfied, the **bike ignition is enabled**.

The entire system is designed using **digital electronics principles**, making it cost-effective, energy-efficient, and scalable.

🎯 Objectives

* Enforce helmet compliance automatically
* Prevent bike ignition without helmet confirmation
* Apply **sequential logic circuit design**
* Demonstrate real-world application of **Digital Electronics**
* Reduce road accident risks


🧠 System Concept

The system works as a **finite state machine (FSM)** with multiple states such as:

* Idle
* Key Inserted
* Helmet Detection
* Helmet Type Validation
* Strap Check
* Start Allowed / Start Blocked

State transitions are controlled using **D Flip-Flops and logic gates**.

🛠️ Components Used
Hardware / Logic Components

* D Flip-Flop (IC 7474)
* AND Gate (IC 7408)
* OR Gate (IC 7432)
* Clock source
* Connecting wires
* Input & Output pins

### Software

* Logisim – for simulation and verification

📊 Core Design Elements

* **State Table** defining present state, inputs, next state, and outputs
* **State Diagram** representing system flow
* **Boolean Equations** for:

  * Start Allowed
  * Start Blocked
  * Flip-Flop excitation (D2, D1, D0)
  Sequential Logic Circuit implementation

🔄 Working Principle

1. Key is inserted
2. Helmet presence is detected
3. Helmet type is validated
4. Strap lock is checked
5. If all conditions are satisfied → Start Allowed
6. If any condition fails → Start Blocked

The ignition system remains disabled until all safety checks pass.

✅ Simulation & Verification

* Designed and tested using Logisim
* Verified correct state transitions
* Ensured reliable output for all valid and invalid conditions
* Eliminated manual intervention

🧪 Results

* Accurate helmet compliance detection
* Correct ignition control behavior
* Efficient state transitions
* Fully functional sequential logic implementation

 📌 Advantages

* Improves rider safety
* Reduces helmet law violations
* Cost-effective design
* Energy efficient
* Scalable for real-world integration
* Demonstrates practical use of digital electronics

🚀 Future Enhancements

* Integration with real-time sensors
* Camera-based helmet detection using ML
* Wireless communication with vehicle systems
* Smart traffic monitoring integration
