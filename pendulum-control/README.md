# Inverted Pendulum GNC Project — Project Board

##  Backlog
- [ ] Read control theory book (linear systems, observability, controllability)
- [ ] Review Lyapunov stability methods
- [ ] Learn LQR fundamentals
- [ ] Sketch inverted pendulum physical concept
- [ ] Decide actuation method (belt / lead screw)
- [ ] Research encoder and IMU options

---

## ✅ Phase 0 — Control Foundations (Dec–Jan)

- [ ] Read control theory book daily
- [ ] Work example problems
- [ ] Simulate linear systems
- [ ] Prove basic system stability
- [ ] Create inverted pendulum state definitions

---

## ✅ Phase 1 — Dynamics & Simulation

- [ ] Derive nonlinear equations of motion
- [ ] Define state variables
- [ ] Symbolically model system
- [ ] Linearize at upright equilibrium
- [ ] Build linear model in code
- [ ] Simulate LQR controller
- [ ] Tune Q and R matrices

---

## ✅ Phase 2 — Sensing & Estimation

- [ ] Select position and angle sensors
- [ ] Model sensor noise
- [ ] Add noise to simulation
- [ ] Implement basic state estimator
- [ ] Validate estimator accuracy
- [ ] Log estimation performance

---

## ✅ Phase 3 — Mechanical System

- [ ] Finalize rail/cart/pendulum mechanical layout
- [ ] Build linear sliding track
- [ ] Mount motor and drive mechanism
- [ ] Verify smooth mechanical motion
- [ ] Install pendulum arm and pivot
- [ ] Mount sensors and verify signals

---

## ✅ Phase 4 — Embedded Control

- [ ] Set up embedded development environment
- [ ] Implement PWM motor control
- [ ] Implement encoder reading
- [ ] Test open-loop motor control
- [ ] Close speed control loop
- [ ] Close position control loop

---

## ✅ Phase 5 — LQR on Hardware

- [ ] Port LQR controller to embedded system
- [ ] Test balance control
- [ ] Log failures and behavior
- [ ] Implement pendulum swing-up routine
- [ ] Test swing-up → balance transition

---

## ✅ Phase 6 — Motor Control PCB

- [ ] Draft PCB system architecture
- [ ] Create motor driver schematic
- [ ] Choose MOSFETs and gate drivers
- [ ] Design current sensing circuit
- [ ] Complete PCB layout
- [ ] Export Gerbers and order board

---

## ✅ Phase 7 — Advanced Estimation

- [ ] Implement EKF in simulation
- [ ] Simulate IMU + encoder fusion
- [ ] Port EKF to embedded system
- [ ] Profile real-time performance
- [ ] Optimize estimator timing

---

## ✅ Phase 8 — System Integration

- [ ] Assemble custom PCB
- [ ] Power-up and smoke test
- [ ] Replace dev board with custom PCB
- [ ] Run baseline tests
- [ ] Tune LQR gains on real hardware

---

## ✅ Phase 9 — Reliability & Polishing

- [ ] Implement error handling
- [ ] Test fault recovery
- [ ] Reduce electrical noise sensitivity
- [ ] Optimize real-time loop timing

---

## ✅ Phase 10 — Documentation & Demo

- [ ] Record demonstration videos
- [ ] Capture telemetry logs
- [ ] Create plots of system performance
- [ ] Write technical report
- [ ] Clean wiring and improve enclosure

---

## ✅ Final Milestones

- [ ] Full autonomous balancing achieved
- [ ] Swing-up to balance working
- [ ] EKF running in real time
- [ ] Custom PCB fully operational
- [ ] Project archived and documented

