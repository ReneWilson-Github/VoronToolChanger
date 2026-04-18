💾 Voron 2.4 StealthChanger (5-Tool) Configs

This repository contains the Klipper configuration files for my Voron 2.4 300mm build, featuring a 5-tool StealthChanger system. These configs are optimized for high-speed tool changes, precision bed leveling, and content creation.
🛠 Hardware Specifications

    System: StealthChanger Tool-Changing System (5 Docks)

    Toolheads: 5x Anthead (Low-mass, high-speed optimized)

    Extruders: WristWatch Galileo 2 (WWG2) with 9:1 gear ratio

    Probing: Beacon Rev H (Contact Mode) + Voron OptoTap on every toolhead

    Electronics: * Mainboard: [Your Mainboard, e.g., BTT Octopus]

        Toolboards: Nitehawk-36 on all 5 toolheads

        Display: Knomi mini-display integrated into the toolhead

    Hotends: [E.g., Phaetus Rapido / Dragon UHF]

🚀 Performance Targets

    Max Velocity: 600 mm/s

    Max Acceleration: 4000 mm/s²

    Z-Acceleration: 800 mm/s² (Tuned for StealthChanger dock reliability)

    Probing Precision: Typical Beacon standard deviation of 0.0006 mm

📂 Config Highlights

    ktc-easy Integration: Utilizing the latest klipper-toolchanger-easy fork for seamless tool management and crash detection.

    Per-Tool Calibration: Custom macros for TOOL_BED_MESH_CALIBRATE and automated XYZ offset adjustments.

    Social Media Ready: Includes full Hyperlapse and Timelapse macro suites optimized for TikTok and YouTube content.

⚠️ Notes for Comparison

If you are using these configs as a reference for your own build, please note:

    Rotation Distance: My WWG2 extruders are currently tuned to 42.619; yours may vary based on tension.

    Beacon Offsets: The Beacon model_coefficients in my printer.cfg are specific to my bed's thermal profile.

    Dock Coordinates: X/Y docking positions in T0.cfg through T4.cfg are specific to my rail alignment.
