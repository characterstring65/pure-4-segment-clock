Pure 4-Segment Fluid Design Clock
An elegant, minimalistic desktop clock built in Python. It uses a custom, fluid 4-segment numeric matrix to display time.
Unlike traditional boxy or geometric 4-segment attempts (like the V6 or Hourglass designs), this concept uses a unique combination of organic curves, calligraphic strokes, and an italic shear transformation. It achieves legibility with the absolute mathematical minimum number of segments required to distinguish 10 digits.

The Core Concept (The Matrix)
A 4-segment display represents the theoretical minimum needed to map the digits 0 through 9. This project achieves this using four specifically engineered segments:
S1: The fluid lower-left curve.
S2: The fluid upper-left curve.
S3: The shortened top horizontal bar with dynamic design accents.
S4: The sharp right-side vertical stem featuring handwritten detail artifacts.
Digit Mapping Definitions
Digit 0: Uses segment S1 (Solo lower curve)
Digit 1: Uses segment S4 (Solo right stem)
Digit 2: Uses segments S1 and S3 (Top bar + lower curve)
Digit 3: Uses segments S1, S3, and S4 (Top bar + lower curve + right stem)
Digit 4: Uses segments S2 and S4 (Upper curve + right stem)
Digit 5: Uses segments S1, S2, and S3 (Closed left side + top bar)
Digit 6: Uses segments S1 and S2 (Complete fluid left-side profile)
Digit 7: Uses segments S3 and S4 (Top bar + right stem)
Digit 8: Uses segments S1, S2, S3, and S4 (All segments active)
Digit 9: Uses segments S2, S3, and S4 (Upper curve + top bar + right stem)

Features
Borderless Floating UI: Completely borderless and streamlined window layout.
Click and Drag: Left-click anywhere on the canvas to seamlessly reposition the clock on your desktop.
Always-on-Top: Stays pinned above other application windows for easy tracking.
Per-Pixel Transparency: Transparent background blending perfectly with your desktop wallpaper.
Quick Close: Right-click anywhere on the clock to exit instantly.

Installation and Running
Make sure you have Python installed. Tkinter comes pre-installed with standard Python distributions.
1.Clone this repository or download the script:
git clone github.com
2.Go into the folder:
cd pure-4-segment-clock
3.Run the clock application:
python clock.py

License
This project is licensed under the MIT License. Feel free to use, modify, and build upon this matrix for your own hardware or software display projects!
