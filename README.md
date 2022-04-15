# Bicopter Project
### Setup
1. Initializing Communication
2. Initializing PORT
3. Setup IMU
4. Calibrating IMU
5. Check motors can move full range
6. ESC Calibration(change output signal max speed to min speed)
7. global variable initialize

### Loop
1. Read and Calculate IMU
2. Read RF Receiver input
3. Calculate with PID algorithm
4. Calculate ESC & servo values
5. Set ESC & servo speed

#### Interrupt
- RF Receiver input 4 or 6 CH
- IMU interrupt signal