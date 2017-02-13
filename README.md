## Stoga Underwater Robotics Team Tech Report:

#### Table of Contents
* [Abstract](Abstract)
* [Images ](Images)
* [Budget](Budget)
* [System Interconnection Diagram](SID)
* [Software diagram]()
* [Design rationale]()
* [Safety](Safety)
* [Challenges](Challenges)
* [Future Improvements:]()
* [Acknowledgements	](Acknowledgements)
* [References](References)



Specifics can be found [here](http://www.marinetech.org/files/marine/files/ROV%20Competition/2017%20competition/Missions/2017_RANGER_Manual_FINAL_cover.pdf):
Click “COMPANY SPEC SHEET (ONE PAGE ONLY)” or “TECHNICAL DOCUMENTATION” on the table of contents.

#### Spec Sheet (1pg):
* COMPANY (MATT C)
* Company and school, club, or community organization name  
* Home state and/or country  
* Distance required to travel to the international competition  
* History of MATE ROV competition participation. Be sure to specify if your company and/or the members of your company are “new” or “returning.”
* Company photo and caption indicating members’ names and roles (e.g. CEO, CFO, Design Engineer, Pilot, etc.). This photo should include all of the members of your company.
* (John Lee)  
* Range of grade/college levels represented by the members of your company: Grades 9-12
* Think picture, name and job, and grade (John Lee)

ROV (MATT C)
* ROV name if applicable  
* Total cost. You must include the approximate cost of any donated items.  (MARK AND SEB)
* Size and weight measurements  
* Total student-hours to design and build. This should include the number of hours that each and every member of the company worked on the vehicle.  
* Safety features  
* Special features  
* Photo of the vehicle

**Technical Documentation (new name for tech report):**
* Title page must include: (Carolyn)
	* Your company's name
	* School, club, or community organization’s name, city, and state or province, and country.
	* COMPLETE list of the members of your company and their role (CEO, CFO, Design Engineer, Pilot, etc.). You may also include degree/area of study (or what you plan to major in at college) and expected graduation date.
	* Names of your instructor(s) and/or mentor(s).  

## Abstract
* (no more than 250 words) that is concise and clearly summarizes the project. (MATT C)
* draft 1 (wordcount: 228/250):
* The ROBOTNAME System is the culmination of the past four years of Pioneer Robotics. Drawing on the skills learned and resources gained throughout their years on the team, the Pioneers have built a small, lightweight, and powerful ROV that improves upon all previous designs. Special attention has been payed to waterproofing and data transmission systems, as those areas have proved problematic in the past. The ROV cost $X to build. Some of that value was donated or reclaimed from previous years’ materials, and we could most likely build another one for under $Y. The ROBOTNAME System runs on a combination of Java and Arduino programs using an intuitive control system. Using two prebuilt boards, the Arduino Mega on the ROV is capable of communicating with a laptop on the surface. As this communication is done through ethernet, the ROBOTNAME System can have a relatively thin and flexible tether. The ROV’s body is made from PVC plastic, a watertight enclosure, and several custom 3D-printed parts. This is not only financially convenient, but allowed for several of its pieces to more easily fit together. We were also able to keep our ROV small, agile, and powerful in order to complete the tasks we were presented with. While the ROBOTNAME System is Pioneer Robotics’ best system yet, with more time, its buoyancy calibrations, modularity, and overall polish could be improved.
* Photograph(s) of your completed ROV: Include photo(s) of your completed vehicle and other photos or sketches that capture the vehicle’s design features. You are permitted to make modifications that may change the look of your vehicle between the time you submit your report and the competition; however, in your technical documentation you must include at least one photo(s) of your completed, assembled vehicle, in addition to any photos of individual systems and/or payload.
* John Lee (Taking photos with camera)

##  Images
* All photographs, figures, graphs, diagrams, and tables must include captions. Images and text should work together to describe your design and answer readers’ questions. Graphs and technical diagrams should include labels for things like data axes, signal paths, and components.
(Cameron Celebuski with the 3D model)

## Budget
* At the beginning of the project, companies should establish a budget. A budget is different than a project costing sheet (see the next bullet) in that it is a projection of the cost of the project. Companies should create categories and realistically estimate what they think that they will spend in each. If well-thought through, the project costing will align with the budget (i.e., the amount budgeted for a certain category will be the actual amount spent!). The budget can be included as an appendix. (Seb U.)
* Project costing: Project costing is an accounting of your income, donations, and expenditures. Items must be listed as one of the following: purchased, reused, parts donated, or cash donated. For reused or donated items, report the item’s current market value and note the source or organization that made the donation. See the project costing sheet located here for an example.  (Seb U.)

## System Interconnection Diagram (SID)
* A SID (also called a block diagram) is a system-level diagram showing how major system (electrical, mechanical, hydraulic/fluid) components are connected. The SID provides readers with a graphical map of the major components and signals needed to understand the design at a high level. It should make clear which parts of the system operate above and below the surface. It should answer the questions “What and where are major parts of the system?” and “What main signals (power, data, electrical, fluid, mechanical) flow between the components?” The SID will be evaluated on how well it shows the relationship between major system components at an appropriate level of detail (not too much, not too little).  (MARK W.)
* Requirements
	* The SID must be drawn using a computer drawing tool (e.g. OpenOffice (free), Inkscape (free) Power Point, Word, Paint, Visio, Omni Graffle, etc.)
	* Components and signals (power, control, data) must be labeled
	* Industry standard symbols and drawing conventions (ANSI, NEMA, IEC) must be used
* Recommendations
	* Read the VEHICLE DESIGN & BUILDING SPECIFICATIONS for more information about the SID.  

## Software diagram
* If your design uses software, it must include a block diagram and flow chart. Like the SID, a software block diagram graphically describes the connections between major software components (functional blocks, i.e., what and where the software parts are). A flow diagram graphically describes the major steps (process) that your software uses to fulfill its role (what the software does). These diagrams should represent the software subsystems at a high level, rather than listing every line of code. They show the judges what software runs where in the system, and demonstrates that you understand how it works. If you are purchased control system that uses software or use software written outside your company (libraries), you should learn about its operation and describe it in a diagram.  (MATT C.)


## Design rationale
* presented in a clear and logical manner. This section should comprise the bulk of your report. It must fo3cus on the technical aspects of your vehicle and how your ROV was built to perform the specific tasks. It must include information about the new vs. used as well as the original vs. commercial components you used and why you made the design choices that you did. See the questions under Product Presentation below for an example of information that you should cover.  (Alex Martorano is willing to do some but not all because I only know build crew stuff) (Matt C can help)
* The ROBOTNAME System was built with the specific needs of our client in mind, but also focuses on modularity, versatility, and compactness. The body of the ROV was built out of PVC pipes due to the ability of PVC pipes to be easily cut and assembled along with being lightweight. A 4” Watertight Enclosure by Blue Robotics was secured by 8 zip ties allowing for us to suspend the enclosure in a nonpermanent but secure manner.  We used 2 NAME OF SPECIFIC SERVOS to … which were waterproofed by covering the circuitry in marine epoxy and filling the gearbox with mineral oil.  The ROV is kept upright underwater due to the rectangular piece of foam secured on the top of the PVC frame. Easily attachable and detachable dive weights help keep the ROBOTNAME System neutrally buoyant and balanced at any depth. Powerful brushless motors are mounted to the ROV using strong, versatile, and easily replaceable 3D printed parts.
* It was important to us that the ROBOTNAME System have intuitive controls. To that extent, the ROV’s software is compatible with most USB gamepads and uses a simple first person control scheme similar to that of many video games. The ROV’s software also gives it analog control of its motors and allows it to turn in place using differential drive. The design of the ROBOTNAME System offers a core structure that allows the user to complete various tasks in a simple manner, without significant changes being necessary.

## Safety
* This section must describe the steps that your company has taken to identify and address any safety concerns regarding the design, construction, maintenance, and operation of your vehicle. Safety is paramount! Your company should reflect that within this section.  (Mark W.)

## Challenges
* Designs tested, pitfalls encountered, and lessons learned during the design and building process: This section should describe the technical challenges that your company faced during the design and building process and the lessons learned and skills gained that allowed you to overcome them. In addition to technical challenges, you may include descriptions of challenges related to project management, working as a team, understanding business practices, etc.  (Alex, but he can give that to others on build team)

## Future Improvements:
* In this case, the MATE Center is your “client” and has defined both the problem to be resolved and the products and services you need to provide. Consider the needs of potential future clients; these could include research institutions, private companies, and government agencies. A synopsis of ideas for future improvements to designs, processes, and practices is essential to any entrepreneurial organization.  (Matt C)

## Acknowledgements
* Please list your sponsors (companies, organizations (including the MATE Center), professionals from industry, and/or mentors) and the type of support that they provided (funds, building supplies, equipment, site visits to facilities, time, and/or technical expertise). You may also include organizations and/or individuals that provided logistical and/or moral support (e.g. your parents, siblings, or pets). Regional competition companies should also acknowledge regional contest supporters. (Matt C, Mark W.)
* We would like to thank the MATE Center for giving us the opportunity to participate in this competition. All of us, especially our graduating members, appreciate the opportunity to make, learn, and grow, individually and as a team. We would also like to thank the WHOEVER IT FINALLY IS for providing us with a pool in which to test the buoyancy, waterproofing, and mechanical systems. We thank Mr. Gregory Chodaczek, the father of one of our CEOs, for providing some of the funds necessary to build the ROBOTNAME System. Most importantly, we would like to thank our Conestoga faculty sponsor, Mr. John Kim, for giving us the space and time we needed to complete our product, as well as having the patience to put up with amateur teenage engineers in his room for the past seven years.

## References
* All reference materials such as books, journal articles, magazines, trade publications, software, web sites, and professional advice that you used for your project must be acknowledged. The references should be noted and numbered in the body of the text then listed here. You should use the Chicago Manual of Style (http://www.chicagomanualofstyle.org/home.html) format for the reference list. Web sites like the Citation Machine (http://www.citationmachine.net/) make it easy to generate citations in the correct format. (MATT C)
	* "Arduino - Reference." Arduino - Reference. Accessed February 05, 2017. https://www.arduino.cc/en/Reference/HomePage.
	* "Blue Robotics Documentation." Blue Robotics. Accessed February 05, 2017. http://docs.bluerobotics.com/.
	* "Free flowchart maker and diagrams online." Draw.io. Accessed February 06, 2017. https://www.draw.io/.
	* "How to Build a Robot Tutorials - Society of Robots." ACTUATORS - HOW TO WATERPROOF A SERVO. Accessed February 06, 2017. http://www.societyofrobots.com/actuators_waterproof_servo.shtml.
	* Martak, Michael, Jeff Kesselman, and Thomas Daniel. "JInput." Jinput. May 19, 2016. Accessed February 05, 2017. https://github.com/jinput/jinput.
	* "RXTX for Java." RXTX for Java. Accessed February 05, 2017. http://fizzed.com/oss/rxtx-for-java.
