# GNSS–IMU Fusion for Resilient Navigation

## Overview  
This project investigates **GNSS–IMU fusion** as a strategy to reduce drift in navigation systems.  
The immediate focus is on developing a **hardware prototype** that integrates a GNSS receiver and an IMU onto a custom board, providing the foundation for future fusion and algorithmic work.  

Once hardware is operational, the project will move toward verifying drift reduction through GNSS–IMU fusion. If time permits, an adaptive **switching algorithm** will be explored to further improve robustness under degraded GNSS conditions.  

---

## Motivation  
- **GNSS** → Accurate absolute positioning, but unreliable in GNSS-denied environments.  
- **IMU** → Continuous relative motion data, but suffers from drift over time.  
- **Fusion** → Combining the two enables more reliable, resilient navigation.  

This project delivers both **hardware integration** and **algorithm development**, aiming to demonstrate a full stack approach from sensor board design to fusion strategy evaluation.  

---

## Project Goals  
- **Short-term deliverable:** Build and validate a prototype board with GNSS + IMU.  
- **Core contribution:** Implement and test fusion algorithms to reduce IMU drift.  
- **Stretch goal:** Explore a switching algorithm to optimize trust between GNSS and IMU.  
- **Optional bonus:** Demonstrate embedded real-time performance on the prototype.  

---

## Planned Steps  
1. **Hardware Prototype**  
   - Design and assemble a GNSS + IMU board.  
   - Validate sensor outputs and communication interfaces.  

2. **Data Collection**  
   - Gather synchronized GNSS and IMU data from test runs.  
   - Store datasets for repeatable testing.  

3. **Fusion Algorithm Implementation**  
   - Implement baseline GNSS–IMU fusion (e.g., Extended Kalman Filter).  
   - Compare standalone IMU vs. fused performance.  

4. **(Stretch) Switching Algorithm**  
   - Develop criteria for adaptively weighting GNSS and IMU.  
   - Benchmark against baseline fusion.  

5. **Evaluation & Documentation**  
   - Analyze drift reduction and navigation accuracy.  
   - Document hardware design, algorithms, and results.  

---

## Deliverables  
- **Hardware prototype**: GNSS + IMU board with working data streams.  
- **Fusion results**: Quantified drift reduction compared to standalone IMU.  
- **(Stretch) Switching algorithm**: Adaptive trust allocation between sensors.  
- **(Optional) Real-time demo**: Embedded hardware implementation.  

---

## Why This Matters  
Navigation in **GNSS-degraded or denied environments** is a critical challenge for autonomous platforms, robotics, and mobile systems. By tackling both the **hardware integration** and the **fusion algorithms**, this project aims to deliver insights into practical, resilient localization systems that balance accuracy and efficiency.  

