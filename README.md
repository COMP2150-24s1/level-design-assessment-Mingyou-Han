# COMP2150  - Level Design Document
### Name: [Mingyou Han]
### Student number: [46991808] 

This document discusses and reflects on the design of your platformer level for the Level Design assessment. It should be 1500 words. Make sure you delete this and all other instructional text throughout the document before checking your word count prior to submission. Hint: You can check word count by copying this text into a Word or Google doc.

Your document must include images. To insert an image into your documentation, place it in the "DocImages" folder in this repo, then place the below text where you want the image to appear:


```
![Place any alt text here](DocImages/<IMAGE NAME AND FILE EXTENSION>)
```

Example:

![This is the alt text for an image!](DocImages/exampleimage.png)

## 1. Player Experience (~700 words)
Outline and justify how your level design facilitates the core player experience goals outlined in the assignment spec. Each section should be supported by specific examples and screenshots of your game encounters that highlight design choices made to facilitate that particular experience.

Jump and melee dash to increase the distance covered, introduced by the breakable structure at the start right next to a jump that is too far for normal jumping.

### 1.1. Discovery
What does the player learn? How does your encounter and broader level design facilitate learning in a way that follows good design practice?

The map is circular where advanced mechanics such as jump melee dash need to be hit perfectly to jump from the start to the "end" of the tail. 
This allows players who choose to have a challenge, especially a more experimental and experimental player with more skill levels. 
The gun provided later adds to the challenge.

I chose a circular design to fit the narrative of a hero`s journey where the end is a return to the beginning allowing for a sense of progression and reward. Introducing multiple mechanics such as dash jump and using spikes to wall jump. Discovery is facilitated through experimenting with different controls, discovering more dynamics created.


### 1.2. Drama
What is the intensity curve? How does your design facilitate increasing yet modulating intensity, with moments of tension and relief? 

The centre room provides both the function of an overlook point to the entire level and a break room to create a "safety" This box uses negative space to crave out the centre of the map emphasising the importance of space and creating a "home" base.


### 1.3. Challenge
What are the main challenges? How have you designed and balanced these challenges to control the difficulty curve and keep the player in the flow channel?

The main challenge is controlling the dash jump as players already learnt the basic movements. Requires intuitive understanding of jump distance and patience to pass the final Room 3. 

### 1.4. Exploration
How does your level design facilitate autonomy and invite the player to explore? How do your aesthetic and layout choices create distinct and memorable spaces and/or places?

Although the rewards is limited due to lack of collectables and upgrades, 
I have decided to use the geometry of letters to spell the word ‘Hero’ as player exploration around the letter should form to puzzle together the final word, creating a desire to explore and find out what the letter spelt. I have also added shortcuts via breakable obstacles which players can keep an eye out for.

## 2. Core Gameplay (~400 words)
A section on Core Gameplay, where storyboards are used to outline how you introduce the player to each of the required gameplay elements in the first section of the game. Storyboards should follow the format provided in lectures.

Storyboards can be combined when multiple mechanics are introduced within a single encounter. Each section should include a sentence or two to briefly justify why you chose to introduce the mechanic/s to the player in that sequence.

You should restructure the headings below to match the order they appear in your level.

### 2.1. Acid

### 2.2. Checkpoints

### 2.3. Chompers

### 2.4. Health Pickups

### 2.5. Keys

### 2.6. Moving Platforms

### 2.7. Passthrough Platforms

### 2.8. Spikes

### 2.9. Spitters

### 2.10. Weapon Pickup (Gun)

### 2.11. Weapon Pickup (Staff)

## 3. Spatiotemporal Design
 
### 3.1. Molecule Diagram
![Game design sequence](https://github.com/COMP2150-24s1/level-design-assessment-Mingyou-Han/assets/153143368/50f79fb8-e445-48d5-86d5-c692149258cb)

### 3.2. Level Map – Section 1
![level 1](https://github.com/COMP2150-24s1/level-design-assessment-Mingyou-Han/assets/153143368/4014559b-b945-4492-8438-6b6246fb4394)

### 3.3.	Level Map – Section 2
![room of pain](https://github.com/COMP2150-24s1/level-design-assessment-Mingyou-Han/assets/153143368/0d91ef5c-9ac2-4841-a275-892baf8f4dc9)

### 3.4.	Level Map – Section 3
![level 3](https://github.com/COMP2150-24s1/level-design-assessment-Mingyou-Han/assets/153143368/eb9b703a-ddeb-49ad-90d8-84bfd954f1da)
## Level Map Compiled
![Overall Map Compiled](https://github.com/COMP2150-24s1/level-design-assessment-Mingyou-Han/assets/153143368/d56363f5-49a9-4e13-a782-d902361983a4)

## 4. Iterative Design (~400 words)
Reflect on how iterative design helped to improve your level. Additional prototypes and design artefacts should be included to demonstrate that you followed an iterative design process (e.g. pictures of paper prototypes, early grey-boxed maps, additional storyboards of later gameplay sequences, etc.). You can also use this section to justify design changes made in Unity after you drew your level design maps shown in section 3. 

You should conclude by highlighting a specific example of an encounter, or another aspect of your level design, that could be improved through further iterative design.

<br /> Throw away prototyping 

### scrapbook Map design
![HERO_map topology](https://github.com/COMP2150-24s1/level-design-assessment-Mingyou-Han/assets/153143368/6201fb7e-5a1e-4ddc-ae0b-476ecd455c2a)

### E to H join room concept
![E_H-room concept topology](https://github.com/COMP2150-24s1/level-design-assessment-Mingyou-Han/assets/153143368/fcf11c27-1f36-4ac1-b7c3-fe91f6bce70e)

### R stairway with moving platforms
![R_room Concept topology](https://github.com/COMP2150-24s1/level-design-assessment-Mingyou-Han/assets/153143368/87a61132-1515-49ec-927c-6db9e15c91aa)

<br />
E to H join room feasibility check
![Uploading RoomOfPain needed hill spikes to block melee dash and bHops<img width="430" alt="TryingIfGameIdea is fesible 1 moving platform horonzital " src="https://github.com/COMP2150-24s1/level-design-assessment-Mingyou-Han/assets/153143368/089eb7fd-1b51-4e7f-94b1-0d0759bc9aaa">

<img width="608" alt="RoomOfPainTrial 1" src="https://github.com/COMP2150-24s1/level-design-assessment-Mingyou-Han/assets/153143368/3ade0c57-d656-4157-8b12-94bc933e4e2d">
 Found the need to constrain the player for the intended experience.

 feasibility check for "R stairway with moving platforms" <img width="564" alt="RoomOfPain needed hill spikes to block melee dash and bHops to constrain the player to intented experience" src="https://github.com/COMP2150-24s1/level-design-assessment-Mingyou-Han/assets/153143368/fc6aca43-f503-4c3d-adf3-3c887e4ee7f1">




