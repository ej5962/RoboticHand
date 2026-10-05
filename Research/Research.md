# Research Overview

## Issues with the current finger design:
- Lack of feedback of position to the microcontroller due to continuous motor only controlling speed input
- Finger position has erratic control when closing, i.e. the different joints will close in a different sequence depending on speed, initial finger position, hand position
  and object to be held
- Finger CANNOT contort to different shapes. It is currently best suited to hold maleable, soft objects
- Inability to move all five fingers at a given time
- Power issues with the arm and the hand
- Size of all compenents is large, adding more moment on the whole arm
- If to use a force sensor: size on cheap force sensors are large, requiring threading into finger and are affected by the finger closures.


## Potential Ideas
- Use a standard 180 degree servo motor with changed gear head to provide full feedback of finger position. This prevents whole hand redesign
- Use a mechanical finger closure design that limits dof for finger joints, allowing controlled motion when paired with servo.
- Use silicon grippers on the finger
- Completely remove servo housing to fit motors in a more confined space, reducing weight + size
- Create simple pcb board for microcontroller attachments

## Research links:

### Rigid Body Mechanisms
- **[Becosplay Finger Mechanism](https://www.youtube.com/watch?v=iwQB7wnxnU0)**
  
  <img height="100" alt="image" src="https://github.com/user-attachments/assets/04a1e8c8-824c-4647-a605-13d22312d097" />
  
- **[Research Paper](https://www.sciencedirect.com/science/article/pii/S2468067220300092)**

  <img height="100" alt="image" src="https://github.com/user-attachments/assets/ab7179e3-820c-49fa-b01e-f32ba12b51f1" />

- **[Pinterest Mechanism](https://kr.pinterest.com/pin/735283076703856330/)**
  
  <img height="100" alt="image" src="https://github.com/user-attachments/assets/9750feb4-95ec-4db3-8b15-cb4f1a86d5b1" />

- **[Finger Mechanism](https://www.instagram.com/reels/DQy_6XpiD2J/)**
  
  <img height="100" alt="image" alt="image" src="https://github.com/user-attachments/assets/813bf73b-f0ad-4dfd-ad7f-ef5764a25d38" />

- **[Simplified Finger Mechanism](https://www.youtube.com/watch?v=g_bBMMDn82Q)**
  
  <img height="100" alt="image" src="https://github.com/user-attachments/assets/95b31951-a50a-467b-9f9d-07a4b281e10a" />

