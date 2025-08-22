# Product Madness UGUI Art Test

This repository contains my implementation of the **Product Madness UGUI Art Test**.  
The task was to demonstrate skills in Unity UI (UGUI), responsive layouts, optimization, and animation.

---

## Part One — Level Up Popup

### Features:
- **Responsive UI**  
  - Canvas set to *Scale with Screen Size* (base resolution: iPad).  
  - Popup scales and repositions correctly across multiple aspect ratios (16:9, 4:3, 19.5:9).  

- **Dynamic buttons layout**  
  - Supports 1, 2, 3, or more buttons.  
  - No duplicated prefabs — buttons reposition automatically inside a flexible RectTransform layout.  

- **Optimization**  
  - Assets prepared into atlases to keep draw calls around **5 or less**.  

- **Animation**  
  - "Appear" animation (~5 seconds).  
  - Includes scaling, fade-in, and celebratory effects (particles + motion).  
  - Starts from an empty screen → ends with the final popup layout.  

---

## Part Two — Character Integration

### Features:
- Character imported into Unity.  
- Idle animation created (breathing, subtle movements, blinking).  
- Rigged for reuse and future animation cycles.  
- Gives the character a sense of personality and life.  

---

## Tools & Technologies
- **Unity** (UGUI, Animator, Particle System)  
- **Photoshop** (asset optimization, UI preparation)  
- **Git** (version control)  

---

## How to Run
1. Clone or download this repository.  
2. Open the project in **Unity [version you used, e.g. 2022.3 LTS]**.  
3. Load the scene: `Scenes/LevelUpPopup.unity`.  
4. Play the scene to view the popup and animation.  

---

## 👤 Author
**Oleh Kosenko**  
Technical Artist / Technical Designer  
- [LinkedIn](https://www.linkedin.com/in/kosenkooleh/)  
- [Behance](https://www.behance.net/kosenkooleh)  
- [Dribbble](https://dribbble.com/kosenkooleh)
