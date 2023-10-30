---
layout: page
title: "Technical Experience"
---
**Note: Respecting my previous employers and NDAs, I will refrain from describing certain details of my experiences.**  

# D-Wave  
Electrical Design Engineer, May 2023 – Aug 2023   
![rs](https://raw.githubusercontent.com/carterkowel/carterkowel.github.io/master/assets/images/Logo_dwave.png)  
**Projects**  
* QPU (Quantum Processing Unit) Power Supply Redesign  
	* Custom designed a multifaceted prototype, reducing lead time by 85% and form factor by 50%
	* Implemented communications infrastructure by developing a UART to RS232 communications converter PCB in KiCAD that integrates with a python GUI
	* Designed high voltage safety covers, venting, routing, and electrical components to comply with CSA electrical equipment standards (CAN/CSA-C22.2 No. 61010-1)  
 	* Designed an electronics enclosure using sheet metal design in Solidworks, incorporated PEMs and brackets for mounting and fastening, baffles for ideal air flow for sufficient cooling, and safety covers for electrical safety
  	* Demonstrated thorough attention to detail by designing an enclosure with extremely tight clearances where accounting for uncertainties in manufacturing is crucial
  	* Drafted engineering drawings to accompany Solidworks design, following D-Waves Mechanical Engineering Drafting Guidelines, ensuring

* High Precision Quality Control Jigs
	* Integrated 3D printed jigs in Solidworks with low noise PCBs to improve usability and repeatability  
 	* Collaborated with colleagues through iterative feedback to ensure ergonomic and efficient designs  

**Skills**  
* Project Management
* KiCAD  
* Solidworks
* Python

# Solidigm  
Firmware Development Engineer, May 2022 – Dec 2022   
![rs](https://raw.githubusercontent.com/carterkowel/carterkowel.github.io/master/assets/images/solodigm-logo-2_678x452.png)  
**Projects**  
* Command Line Remote Debugger Script  
 ![rs](https://raw.githubusercontent.com/carterkowel/carterkowel.github.io/master/assets/images/debugtoolgif.gif)  	 		
	* Designed a python script that automates the connection process of using ARM and GDB to debug remote systems  
	* Integrated GDB with VSCode IDE for efficient and convenient debugging by configuring launch files 
	* Documented the script using diagrams, requirments.txt, and step-by-step instructions to streamline the setup process
	* Through continuous feedback and communication with my team, I incorporated their desired features:
		* Implemented both argparse and InquirerPy to allow for providing arguments or getting prompted for them
		* Smart file searching the ensures the script onlys prompts the user with valid and functional options
		* Automatically selects an option when there is only one available
		* Utilized a json file that stores the last ran parameters and allows users to customize their defaults
	
* Log Page Regression Testing Framework
	* Automated a log page retrieval testing framework for an embedded system using C and C++
	* Designed a verification API that interacts with a console menu through wrapper functions
	* Followed high quality error handling practices by implementing a test result data type and enums 
	* Modified a console menu data type, enhancing an interactive testing menu experience

* Various Firmware Features
	* Interacted with register reads, writes, and masks
	* Consulted documentation and legacy code to further understand the intricacies of the task
	* Extensive troubleshooting and debugging

**Skills**  
* LINUX environment  
* Scripting with python and bash  
* Version controls such as github, gitlab, and bitbucket  
* Writing firmware with C and C++  

# Accelovant  
Product Development Engineer, Jan 2021 – Apr 2021  
![rs](https://raw.githubusercontent.com/carterkowel/carterkowel.github.io/master/assets/images/accelovant.PNG)  

[Accelovant](https://www.accelovant.com/) is start-up company located in North Vancouver that is pushing the boundaries on innovative fiber-optic temperature solutions. My technical responsibilities included: 

**Design**  
* 4-Layer PCB Cost Reduction Redesign
	* Redesigned a 4-layer PCB in Altium, replacing an upstream transformer for a BUCK converter and a downstream digital isolator to reduce production cost by 20%
	* Routed sensitive SPI signals, utilizing multi-layer ground planes to protect the signals
	* Collaborated with colleagues to ensure accessible debugging pins and precise mechanical integration of components such as the grounding contact with the housing
* PCB Calibration Pogo Pin Jig
	* Designed a 3D printed jig in Solidworks that probes the DUT with pogo pins, introducing usability and repeatability to the calibration process
	* Developed a via stitched PCB in Altium with a coaxial cable to achieve optimal signal immunity
	* Manufactured a close-fitting carriage and selected self-aligning bushings for smooth functionality
	* Wrote detailed assembly and calibration procedures for use of the production team
* Statistical Process Control Python Code
	* Conducted statistical process control on electrical products by interpreting voltage readings
	* Designed a csv generation code in python which organizes data into graphical and analyzable form
* Force Analysis Production Jig
	* Designed an apparatus of 3D printed parts, a load cell, an Arduino, and a precision linear stage, that measures the reaction force from a given displacement
* 3D modeling products in SOLIDWORKS and Fusion360  
	* Used the CAM tool in Fusion360 for CNC milling 

**Documentation**   
* Made engineering drawings for clients and manufacturers  
* Followed Engineering Change Order protocol to release and revise designs into production  
* Wrote user manuals, safety documents, and procedures for client use  
* Designed step-by-step Manufacturing Assembly Instructions for various products  
* Maintained Bill Of Materials for several projects, tracking inventory and budgeting  


# UBC Solar Car Design Team  
Electrical and Mechanical Team Member, Sept 2019 – Mar 2021  
![rs](https://raw.githubusercontent.com/carterkowel/carterkowel.github.io/master/assets/images/UBCSolar.jpg)  

[UBC Solar](https://ubcsolar.com/) is a student team focused on the design and manufacturing of solar-powered race cars. Their core values include sustainability, education, and proffesionalism. My technical responsibilities included: 

**Projects**  
* Car Cabling Schematic
	* Designed an organized wiring schematic of the car’s electrical systems using Altium
	* Purchased cabling based on gauge, shielding, length, and number of conductors
* Steering Wheel PCB
	* Designed a steering wheel board to efficiently house steering wheel controls, optimizing usability and reducing messy wiring
	* Integrated the circuit schematic and routing using Eagle, minimizing electrical noise using low pass filters
	* Placed surface mount components using a laser cut stencil and reflow oven, hand soldered through hole components
* 3D Modeling Mounts
	* Designed 3D mounts on Solidworks, optimizing structural integrity and weight
	* Selected components such as hinges, latches, and screws based on required specifications
	* Manufacturing a sheet metal mount using a waterjet cutter and a plastic mount using a 3D printer
