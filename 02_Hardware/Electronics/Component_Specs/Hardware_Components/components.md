
# Plantastic Hardware Components Specification
## Version 2.0 - Hydroponic/Aeroponic System
## Target Age: 6-15 years | Date: December 2024

---

## 1. FOG GENERATION SYSTEM (Primary Watering Method)

### 1.1 Ultrasonic Fogger Module
- **Type**: 24V ultrasonic disc fogger (1.7MHz frequency)
- **Output**: 200-400ml/hour mist generation
- **Power**: 15W consumption
- **Disc size**: 20mm diameter
- **Particle size**: 1-5 microns
- **Lifetime**: 3000-5000 hours
- **Safety features**: 
  - Auto-shutoff when water level low
  - Temperature monitoring (<30°C)
  - Fully enclosed housing
- **Child-safe alternative**: 5V piezoelectric misting disc for younger users

### 1.2 Fog Distribution Components
- **Fog chamber**: Separate 200ml capacity chamber
- **Distribution manifold**: 4-way splitter for multiple plants
- **Tubing**: Food-grade silicone, 6mm OD, 4mm ID
- **Anti-drip valves**: Prevent water accumulation
- **Timing control**: 15 min ON / 45 min OFF cycles

---

## 2. WATER RESERVOIR SYSTEM

### 2.1 Dual-Chamber Smart Reservoir
- **Dimensions**: 200mm x 150mm x 120mm
- **Total capacity**: 2L (1.5L main + 0.5L nutrient)
- **Chamber A (Main water)**:
  - Clear body with graduated markings
  - Child-friendly volume graphics
  - Float sensor for level monitoring
  - Quick-fill port with splash guard
  - Overflow protection at 90% capacity
- **Chamber B (Nutrient concentrate)**:
  - Pod-based nutrient system (like coffee pods)
  - Color-coded by plant type
  - Childproof lock mechanism
  - Peristaltic micro-pump for dosing
  - One-button operation

### 2.2 Water Level Monitoring
- **Primary sensor**: Non-contact ultrasonic sensor
- **Backup**: Magnetic float switch
- **Visual indicator**: 5-LED level display
- **Alert system**: Audio/visual low water warning

---

## 3. GROWING CHAMBERS

### 3.1 Beginner Chamber (Ages 6-10)
- **Dimensions**: 100mm diameter x 150mm height
- **Capacity**: 3 plants maximum
- **Features**:
  - Pre-assembled net pot system
  - 30mm and 50mm net pot sizes
  - Color-changing LED growth indicator ring
  - Clear observation windows (3 sides)
  - Seed pod system (no loose seeds)
  - Picture-based plant identification labels

### 3.2 Advanced Chamber (Ages 11-15)
- **Dimensions**: 150mm diameter x 200mm height
- **Capacity**: 5-6 plants
- **Features**:
  - Modular net pots (30mm, 50mm, 75mm)
  - pH test strip holder
  - Root observation chamber with magnification window
  - Fog/drip mode selector switch
  - Data logging port (3.5mm jack)
  - Graduated measurement markings

### 3.3 Growing Media Options
- **Clay pebbles**: Reusable, pH neutral
- **Rockwool cubes**: Sterile, good water retention
- **Coconut coir**: Sustainable, beginner-friendly
- **Perlite**: Lightweight, excellent drainage

---

## 4. STRUCTURAL SYSTEM (LEGO® COMPATIBLE)

### 4.1 Base Platforms
- **Starter size**: 16x16 studs (128mm x 128mm x 40mm)
- **Standard size**: 32x32 studs (256mm x 256mm x 40mm)
- **Expansion size**: 48x32 studs (384mm x 256mm x 40mm)
- **Material**: PETG or ABS plastic
- **Features**:
  - Drainage channels integrated
  - Cable management grooves
  - Reinforcement ribs underneath
  - Anti-slip rubber feet

### 4.2 Modular Components
- **Vertical supports**: Technic-compatible beams (various lengths)
- **Connector joints**: 
  - Straight connectors
  - 90-degree elbows
  - T-joints
  - Flexible joints (30° bend radius)
- **Mounting brackets**: For sensors, lights, camera
- **Tool-free assembly**: All snap-fit or twist-lock

### 4.3 Design Specifications
- **Stud spacing**: 8mm x 8mm (Lego® standard)
- **Stud height**: 5mm
- **Wall thickness**: 2mm minimum
- **Tolerance**: ±0.1mm for proper fit
- **Corner radius**: 3mm (safety requirement)

---

## 5. ELECTRONICS & CONTROL SYSTEM

### 5.1 Main Control Board Options

#### Option A: Arduino-based (Budget)
- **MCU**: Arduino Nano or Uno
- **Cost**: ~$5-10
- **Features**: Basic automation, sensor reading
- **Connectivity**: Optional WiFi module (+$10)
- **Programming**: Simplified block coding

#### Option B: Raspberry Pi-based (Premium)
- **MCU**: Raspberry Pi Zero W or Pi 4
- **Cost**: ~$15-35
- **Features**: AI plant recognition, web interface
- **Connectivity**: Built-in WiFi/Bluetooth
- **Programming**: Python, Scratch, full Linux OS

### 5.2 User Interface

#### Young Makers Interface (Ages 6-10)
- **Display**: 16x2 character LCD with backlight
- **Controls**: 
  - 3 large buttons (Water/Food/Light)
  - Rotary encoder for menu navigation
- **Feedback**: Buzzer for audio alerts
- **Indicators**: 5 RGB LEDs for system status

#### STEM Explorer Interface (Ages 11-15)
- **Display**: 2.8" color TFT touchscreen (320x240)
- **Features**:
  - Real-time sensor graphs
  - Experiment logging
  - Settings customization
  - Data export via SD card
- **Connectivity**: Bluetooth for smartphone app

### 5.3 Sensor Suite
- **Water level**: HC-SR04 ultrasonic sensor
- **pH monitoring**: 
  - Digital pH probe (±0.1 accuracy)
  - Color-changing indicator strips
- **EC/TDS meter**: Measure nutrient concentration
- **Temperature**: Waterproof DS18B20 probe
- **Humidity/Air temp**: DHT22 sensor
- **Light intensity**: Photoresistor with lux calculation
- **All sensors include**: Protective housing, color-coded wires

---

## 6. POWER SYSTEM

### 6.1 Battery Specifications
- **Type**: LiFePO4 (Lithium Iron Phosphate)
- **Voltage**: 12V
- **Capacity**: 10Ah (120Wh)
- **Safety**: Won't catch fire, safe chemistry
- **Charging**: USB-C PD input (15V/2A)
- **Runtime estimates**:
  - Fog mode: 16-20 hours
  - Drip only: 3-5 days
  - Standby: 7+ days

### 6.2 Power Management
- **Solar ready**: 10-20W panel connection
- **Backup**: 4x AA batteries for sensors only
- **Power modes**:
  - Normal: Full fog operation
  - Eco: Reduced fog, extended battery
  - Emergency: Drip only, maximum runtime
- **Indicators**: 5-LED battery gauge
- **Protection**: Over-charge, over-discharge, short circuit

### 6.3 Power Distribution
- **Voltage rails**: 
  - 24V: Fogger
  - 12V: Pumps, main system
  - 5V: MCU, sensors
  - 3.3V: Some sensors
- **Regulation**: Buck converters for efficiency

---

## 7. LIGHTING SYSTEM (OPTIONAL)

### 7.1 LED Grow Light Module
- **Dimensions**: 160mm x 40mm x 20mm
- **Power**: 10W, dimmable
- **Spectrum**: Full spectrum (400-700nm)
- **Red:Blue ratio**: 3:1 optimal for most plants
- **Mounting**: Adjustable height on rails
- **Control**: Timer function, intensity adjustment
- **Heat management**: Aluminum heat sink

### 7.2 Light Scheduling
- **Seedling**: 14-16 hours/day
- **Vegetative**: 12-14 hours/day
- **Flowering**: 10-12 hours/day
- **Auto mode**: Based on plant selection

---

## 8. CAMERA SYSTEM (TIME-LAPSE)

### 8.1 Camera Module
- **Type**: 8MP camera (Raspberry Pi camera or USB webcam)
- **Lens**: Wide-angle for full plant coverage
- **Features**:
  - Auto white balance
  - Fixed focus at 30cm
  - IR filter for true colors
  - Optional: Night vision capability

### 8.2 Mounting System
- **Type**: Telescoping mount
- **Height**: 200-400mm adjustable
- **Movement**: 360° pan, 180° tilt
- **Base**: 4x4 Lego® studs
- **Cable**: Internal cable routing

### 8.3 Time-lapse Features
- **Interval**: Adjustable (5min - 24hr)
- **Storage**: SD card or cloud upload
- **Processing**: Auto-compilation to video
- **Sharing**: Direct social media integration

---

## 9. SAFETY COMPONENTS

### 9.1 Electrical Safety
- **Voltage**: Maximum 24V DC (safe low voltage)
- **Isolation**: Water and electronics separated
- **Fuses**: Resettable PTC fuses
- **Connectors**: Waterproof, polarized
- **Cables**: Silicone insulated, strain relief

### 9.2 Mechanical Safety
- **Edges**: All corners rounded (3mm radius)
- **Materials**: Food-safe, BPA-free plastics
- **Small parts**: Secured, not removable by children
- **Stability**: Wide base, low center of gravity
- **Spill protection**: Contained water areas

### 9.3 Chemical Safety
- **Nutrients**: Pre-measured pods, childproof
- **pH adjusters**: Locked compartment
- **Growing media**: Non-toxic, dust-free
- **Labels**: Clear warnings, age-appropriate

---

## 10. ACCESSORIES & CONSUMABLES

### 10.1 Starter Kit Includes
- **Seeds**: 5 varieties (lettuce, basil, tomato, mint, flowers)
- **Nutrient pods**: 3-month supply
- **pH test kit**: Strips and color chart
- **Growing media**: 1kg clay pebbles
- **Net pots**: Assorted sizes (10 pieces)
- **Labels**: Waterproof plant markers

### 10.2 Optional Add-ons
- **Solar panel kit**: 20W panel with mounting
- **Advanced sensor pack**: CO2, dissolved oxygen
- **Expansion chambers**: Additional growing spaces
- **Decorative elements**: Lego® compatible decorations
- **Science journal**: Printed experiment workbook

---

## 11. PACKAGING COMPONENTS

### 11.1 Main Package
- **Box dimensions**: 400mm x 300mm x 200mm
- **Weight**: Approximately 3kg
- **Materials**: Recycled cardboard, biodegradable padding
- **Design**: Colorful, educational graphics
- **Window**: Clear view of main components

### 11.2 Internal Organization
- **Component trays**: Organized by assembly step
- **Hardware bags**: Numbered, resealable
- **Documentation pocket**: Manuals, stickers
- **Protection**: Foam inserts for electronics

---

## 12. MATERIAL SPECIFICATIONS

### 12.1 Plastics
- **Structural parts**: PETG or ABS
- **Transparent parts**: Clear PETG or acrylic
- **Flexible parts**: TPU or silicone
- **Food contact**: FDA-approved materials only

### 12.2 Hardware
- **Screws**: Stainless steel, Phillips head
- **Magnets**: Neodymium, nickel-plated
- **Springs**: Stainless steel
- **O-rings**: Food-grade silicone

### 12.3 Electronics
- **PCB**: Lead-free HASL finish
- **Wires**: 22-26 AWG, silicone insulation
- **Connectors**: JST-XH, JST-PH series
- **Displays**: Industrial temperature range

---

## COMPONENT COST BREAKDOWN

| Component Category | Budget Version | Premium Version |
|-------------------|----------------|-----------------|
| Fog System | $25 | $40 |
| Reservoir | $15 | $25 |
| Growing Chambers | $20 | $35 |
| Structure (3D printed) | $15 | $20 |
| Electronics | $25 | $60 |
| Power System | $30 | $40 |
| Sensors | $20 | $30 |
| Accessories | $10 | $20 |
| Packaging | $10 | $15 |
| **TOTAL MFG COST** | **$170** | **$285** |
| **Suggested Retail** | **$299** | **$499** |

---

## QUALITY STANDARDS

- **ISO 9001**: Quality management
- **RoHS**: Restriction of hazardous substances
- **REACH**: Chemical safety
- **ASTM F963**: Toy safety standard
- **IP54**: Water resistance rating

---

*Document Version: 2.0*  
*Last Updated: December 2024*  
*Next Review: After prototype testing*