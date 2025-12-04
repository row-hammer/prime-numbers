Prime Number Spiral

A visualization of prime numbers arranged in a spiral pattern on a 2D plane. This project allows you to explore the distribution of prime numbers with interactive controls for navigation and analysis.

Features

Interactive Navigation: Move around the 2D plane to explore different regions of the spiral.

Zoom Controls: Zoom in to see details or zoom out to see the larger pattern.

Filtering: Toggle visibility for prime numbers and composite numbers independently.

Visual Customization: Increase or decrease the size of the dots for better visibility.

Prerequisites

To run this project, you need the Processing IDE.

Download Processing for your operating system (Windows, macOS, or Linux) from processing.org/download.

Install and open the application.

Installation & Setup

1. Clone or Download

Clone the repository or download the ZIP file.

git clone [https://github.com/row-hammer/prime-numbers.git](https://github.com/row-hammer/prime-numbers.git)


2. Fix Directory Structure (Important)

The current repository structure is deeply nested. To make it runnable in Processing, the .pde file must be inside a folder with the exact same name.

Manual Fix:

Navigate into Pirminiu skaiciu spirale-master/Prime-Number-Spiral-master/.

Move the Prime_Numbers_Spiral folder to your main workspace (e.g., your Documents/Processing folder).

Automatic Fix (Mac/Linux/Git Bash):
Run the included fix_project_structure.sh script or run this command in the root of the repo:

mv "Pirminiu skaiciu spirale-master/Prime-Number-Spiral-master/Prime_Numbers_Spiral" ./
rm -rf "Pirminiu skaiciu spirale-master"


How to Run

Open Processing.

Go to File > Open.

Navigate to the Prime_Numbers_Spiral folder.

Select Prime_Numbers_Spiral.pde and click Open.

Click the Run button (Play icon) in the top-left corner.

Controls

Note: Exact key bindings are defined in the source code. Based on standard Processing sketches, try the following keys:

Movement: Arrow Keys or W, A, S, D.

Zoom: Mouse Scroll, + / -, or Z / X.

Toggle Views: Check the void keyPressed() function in the code to see which keys toggle Primes vs. Composites.

Project Structure

Prime_Numbers_Spiral.pde: The main source code file containing the setup, draw loop, and logic for the spiral generation.
