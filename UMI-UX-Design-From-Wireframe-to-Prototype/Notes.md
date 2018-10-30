[Design-UX-UI Home](https://github.com/coolinmc6/design-ux-ui)

<a name='top'></a>
# UX Design: From Wireframe to Prototype

## Table of Contents

- [Course Documents](https://github.com/coolinmc6/design-ux-ui/tree/master/UMI-UX-Design-From-Wireframe-to-Prototype/Course-Documents)
- [Course Summary and Key Take-aways](#course-summary-and-key-take-aways)
	+ [Basic Summary](#course-summary)
	+ [Most Interesting Parts](#my-key-takeaways)
- [Course Syllabus](#course-syllabus-and-learning-objectives)
- [Building Blocks of User Interaction](https://github.com/coolinmc6/design-ux-ui/blob/master/UMI-UX-Design-From-Wireframe-to-Prototype/Notes.md#building-blocks-of-user-interaction)
	+ [Course Introduction](https://github.com/coolinmc6/design-ux-ui/blob/master/UMI-UX-Design-From-Wireframe-to-Prototype/Notes.md#l1-course-introduction)
	+ [Elements of User Interaction: Data Input](https://github.com/coolinmc6/design-ux-ui/blob/master/UMI-UX-Design-From-Wireframe-to-Prototype/Notes.md#l2-elements-of-user-interaction-data-input)
	+ [Elements of User Interaction: Output, State, and Mode](https://github.com/coolinmc6/design-ux-ui/blob/master/UMI-UX-Design-From-Wireframe-to-Prototype/Notes.md#l3-elements-of-user-interaction-output-state-and-mode)
	+ [Introduction to Prototyping](https://github.com/coolinmc6/design-ux-ui/blob/master/UMI-UX-Design-From-Wireframe-to-Prototype/Notes.md#l4-introduction-to-prototyping)
- [Low to Hi-Fidelity Prototyping](https://github.com/coolinmc6/design-ux-ui/blob/master/UMI-UX-Design-From-Wireframe-to-Prototype/Notes.md#low-to-hi-fidelity-prototyping)
	+ [Wireframes](https://github.com/coolinmc6/design-ux-ui/blob/master/UMI-UX-Design-From-Wireframe-to-Prototype/Notes.md#l5-wireframes)
	+ [Low-Fidelity Interactive Prototypes](https://github.com/coolinmc6/design-ux-ui/blob/master/UMI-UX-Design-From-Wireframe-to-Prototype/Notes.md#l6-low-fidelity-interactive-prototypes)
	+ [Testing Lo-Fi Prototypes](https://github.com/coolinmc6/design-ux-ui/blob/master/UMI-UX-Design-From-Wireframe-to-Prototype/Notes.md#l7-testing-lo-fi-prototypes)
	+ [Adding Realism to Prototypes](https://github.com/coolinmc6/design-ux-ui/blob/master/UMI-UX-Design-From-Wireframe-to-Prototype/Notes.md#l8-adding-realism-to-prototypes)
- [Conceptual Issues in Prototyping and Design](https://github.com/coolinmc6/design-ux-ui/blob/master/UMI-UX-Design-From-Wireframe-to-Prototype/Notes.md#conceptual-issues-in-prototyping-and-design)
	+ [Key Design Concepts](https://github.com/coolinmc6/design-ux-ui/blob/master/UMI-UX-Design-From-Wireframe-to-Prototype/Notes.md#l9-key-design-concepts)

## Course Summary and Key Take-aways

### Course Summary

### My Key Takeaways

[back to top](#top)

## Course Syllabus and Learning Objectives

- Learning Objectives:
	+ Analyze factors that influence the design of user input and feedback in an interactive system
	+ Describe different types of prototype, and what kinds of questions each type of prototype is intended to answer
	+ Create and evaluate low-fidelity prototypes
	+ Recognize the importance of good choice of defaults
	+ Reason critically about the broader impacts of the systems that they are designing

[back to top](#top)

## Building Blocks of User Interaction

### L1: Course Introduction

- Prototyping can be wireframes, lo-fi prototypes, mock-ups, mid-fi prototypes
- Prototyping translates findings from formative work into concrete designs that can be tested, revised, and refined prior to implementation of the final system

[back to top](#top)

### L2: Elements of User Interaction: Data Input

- Input: data that needs to be entered into the program to enable it to perform desired tasks
- Two types of input:
	+ user-entered input
		* GUI elements => buttons, icons, menus, switches
		* Self-report data => free-text, structured forms, voice input, taking a picture
	+ passive input
		* sensor readings => location, camera, microphone, accelerometer
		* Data from other applications => calendar, pictures, health data
		* Information from internet => web app data (FitBit, Yelp, etc.), Weather, RSS feeds
- Input Design Considerations
	+ what granularity of data is needed?
	+ When / how often is the data needed?
	+ In what state is the user when input is needed? (Driving? loud environment?)
	+ what is the value vs. the burden of obtaining the data
- Consequences of Input Design
	+ format, granularity, and frequency of input set limits on what application can do
	+ User experience greatly affected by input design

[back to top](#top)

### L3: Elements of User Interaction: Output, State, and Mode

- Output: information that the system presents to the user in order to accomplish its indended funciton
- Output structure: the format in which it is presented
- Output content: what information is presented
- Output Structure
	+ Modality
		* visual (screen-based, ambient)
		* Audio
		* Haptic
	+ Format
		* Number
		* text
		* list
		* graph
		* push notification
	+ Location
		* in-app
		* wearable
		* phone lock screen
- Output Design Considerations
	+ What exactly does the user need to know to perform the task?
	+ When/how often will the user interact with the information?
	+ In what state will the user be when presented with the information?
	+ What is the user's current knowledge base?
- State: current values of system inputs and the set of rules that determine what kind of output the system will produce
- Mode: element of state, usually user-controllable, that consistently determines how information is presented
	+ sustem-wide modes: ringer on/off, airplane mode, do not disturb, night shift
- Summary
	+ UX design involves designing inputs, outputs, and rules that translate inputs to desired outputs
	+ Design of both inputs and outputs must consider when, where, and how user will need to interact with the system
	+ Visibility of state help users understand why the system behaves the way it does


[back to top](#top)

### L4: Introduction to Prototyping

- Interaction design prototype: a representation of a design, made before the final solution exists
- Why Prototype?
	+ you often don't know exactly how the system should work
	+ engineering and software development are expensive and time-consuming
- Prototyping enables testing of and receiving feedback on:
	+ overall design concepts
	+ functionality of different components of a system
	+ user interactions
	+ layouts
	+ fine-grain design details like fonts and color schemes
- Each protoype is intended to answer one or more questions to help designers make decisions needed to advance their design
- Types of Prototype
	+ storyboard
	+ sketch
	+ wireframe - visual representation of individual screens of the system
	+ interactive prototype - captures multiple states of a design, transitions among them
- Prototype Fidelity
	+ more polished prototypes make users feel like it's already set in stone and that they are commenting on smaller things like font sizes, colors, etc.
- Prototyping maximizes the number of times you get to revise and refine your design before committing to code

[back to top](#top)

## Low to Hi-Fidelity Prototyping

### L5: Wireframes

- Wireframe: a visual representation of the screens of an interactive application that shows layout, types of information that are displayed, and elements of pointer-based navigation
- Questions Wireframes can Answer
	+ Do screens capture right chunks of system functionality?
	+ Are the components of a wireframe the right things to have on a single screen?
	+ Does the screen capture the right way those components should be presented to the user?
	+ Does the overall layout of components make sense?
	+ Do screens provide the right navigational elements?
- Questions Wireframes Do Not Answer
	+ What is the state required to generate this output?
	+ How should content be ordered?
	+ How does the user transition among multiple screens?
	+ What is the right visual design for the screen?
	+ What non-visual output is the system producing?
- How to Wireframe
	+ sketching on pen and paper
	+ Desktop and Web Apps
		* Balsamiq
- When to Create Wireframes?
	+ When the designer understands a chunk of functionality and wants to get feedback
	+ When there are several ways somethign can be presented to users and the designer needs to choose among them
	+ When developers need to start planning system backend
- Summary
	+ wireframes are basic building blocks of UX prototypes
	+ they can test early concepts of functionality, rpesentation of interactive components, and layout
	+ They support gathering of feedback before full system has been thought through
	+ They are fast to create and cheap to discard
- 

[back to top](#top)

### L6: Low-Fidelity Interactive Prototypes

[back to top](#top)

### L7: Testing Lo-fi Prototypes

[back to top](#top)

### L8: Adding Realism to Prototypes

[back to top](#top)

## Conceptual Issues in Prototyping and Design

### L9: Key Design Concepts

[back to top](#top)

### L10: Defaults

[back to top](#top)

### L11: Reflective Design

[back to top](#top)

### L12: New Direction in UX Design

[back to top](#top)