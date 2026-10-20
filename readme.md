# Building the Perpetual Electromagnetic Eddy Art Display

### Overview & Concept
This project is a mesmerizing desktop kinetic art installation inspired by retro drawing toys but driven by modern physics. Instead of physical pins or obstacles[cite: 1], an invisible grid of magnetic eddy points[cite: 1] continuously swirls and orbits ferromagnetic sand particles forever in perpetual fluid-like motion[cite: 1]. The user controls particle spawning via an X-Y gantry funnel and modulates the vortex field intensity and global drift using tactile rotary controls.

---

### Materials & Components Needed

#### 1. Enclosure & Display
* **Shadow Box Frame:** A sealed, double-paned transparent acrylic display box (to keep the magnetic sand safely enclosed).
* **Backlight Panel:** An addressable RGB LED matrix or diffuse edge-lit panel to give the background a glowing digital aesthetic.

#### 2. Mechanics & Electronics
* **Microcontroller:** An Arduino Nano, ESP32, or Raspberry Pi Pico to handle field calculations and motor controls.
* **X-Y Gantry System:** Two miniature stepper motors (NEMA 17 or smaller) with timing belts and linear rails to drive the top sand-dispensing hopper.
* **Electromagnet Matrix:** A grid of small iron-core solenoid coils or neodymium electromagnets mounted to the rear panel behind the display screen.
* **Control Interface:** Four high-precision rotary encoder knobs for the front panel.

---

### Step-by-Step Assembly Instructions

* **Step 1: Construct the Sealed Frame:** Build your shadow box enclosure using clear acrylic sheets. Ensure the interior display cavity is completely airtight so the magnetic sand particles cannot escape or jam the mechanical components.
* **Step 2: Install the X-Y Dispenser Gantry:** Mount a micro-servo hopper at the top of the frame. Attach it to a Cartesian gantry rail system driven by your stepper motors so the sand release nozzle can traverse smoothly across both X and Y axes[cite: 1].
* **Step 3: Wire the Electromagnet Matrix:** Arrange your grid of electromagnetic coils along the rear board. Wire them through MOSFET transistor driver circuits connected to your microcontroller so you can dynamically shift polarity and generate swirling eddy fields[cite: 1].
* **Step 4: Mount the Control Knobs:** Install four rotary encoders onto the front control console. Program your microcontroller to map these knobs to the X-Y nozzle coordinates, magnetic pulse intensity, and directional drift angle[cite: 1].
* **Step 5: Calibrate & Test:** Load your custom-colored ferromagnetic micro-grains into the hopper, power up the system, and use the knobs to release continuous streams of particles into the invisible vortex matrix[cite: 1]!