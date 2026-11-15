#  **Vertical Take-Off and Landing (VTOL) Radio Controlled (RC) Drone**

This project aims to create a sub $250 VTOL RC Drone using widely available components. To better define the aim of this project, I have set a list of targets to be attained, and certain benchmarks that **must** be fulfilled in order to call this project a success

### **Targets**

1. Highly maneuverable when hovering and during horizontal flight.
2. Be able to carry payload in excess of 250 grams with minimal loss of flight characteristics.
3. Stay airborne for more than 20 minutes in horizontal flight mode.

### **Benchmarks**

1. Maximum weight should not exceed 1.1 kilograms, excluding payload.
2. It should be able to change hovering height.
3. The transition from hovering to horizontal flight must be smooth and fully autonomous.
4. The control algorithm must be able to keep the drone hovering or flying with longitudinal and lateral stability in gusts up to 5 m/s.

### **Technical Branches**

1. **Mechanical Branch**: Concerning the central structural frame of the drone; load bearing sections; wing spar, box, and ribs; and tail boom.
2. **Aerodynamics Branch**: Concerning the low-Reynolds number airfoil design; propeller optimization; longitudinal and lateral stability calculations during horizontal flight; cyclic and collective pitch control during hovering; and control surface design.
3. **Electronics Branch**: Concerning motor efficiency; high current wire magnetic field control; wiring; and battery discharge optimization.
4. **Control Branch**: Concerning PID algorithm creation, tuning and testing; automated hovering to horizontal flight transition control algorithm; IMU drift cancellation and tuning; and control surface control loop creation.

This project has been split into its separate branches in separate folders in the _documentation_ folder of this project. All code, CAD, FEA, theoretical calculations, and data logs are present in their respectively named folders in the main branch.

   



