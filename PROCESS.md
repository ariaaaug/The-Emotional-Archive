# Process & Reflection

## 1. Initial Idea & Evolution
* **Starting Idea**: I wanted to create a lightweight tool that turns abstract psychological weight into visual motion, drawing inspiration from minimalist design interfaces and micro-interactions.
* **Evolution**: Initially, I considered a heavy database-backed journal, but to keep the scope manageable and testable within the timeline, I narrowed it down to a single-session "Emotional Archive" focusing purely on the core interaction loop: input, animation feedback, and error handling.

## 2. Design & Code Changes
* **UI Refinement**: Styled the interface using a dark-mode glassmorphism aesthetic (`backdrop-filter: blur`, subtle borders) to create a calm, focused atmosphere suitable for reflection.
* **Animation Logic**: Implemented keyframe animations (`floatUp` and `shake`) using pure CSS combined with event-driven JavaScript to ensure smooth 60fps performance without external animation libraries.

## 3. User Trial & Iteration
* **Observation**: I invited a peer to test the prototype without explaining it first. They immediately understood the text box and button, but hesitated when they clicked with an empty box initially because there was no immediate visual cue.
* **Design Decision**: Based on this observation, I added the **shake animation and error warning text** when submitting empty input, making it instantly clear why the action didn't go through.

## 4. AI Tool Usage
* **AI Tool Used**: AI assistant was utilized to help structure the single-file HTML/CSS/JS architecture, refine the CSS keyframe animations, and draft the initial project documentation structure.
* **Kept vs. Changed**: 
  * *Kept*: The clean, modular separation of CSS styles and vanilla JavaScript event listeners.
  * *Changed*: Customized the error-handling behavior and adjusted the aesthetic styling to better align with a dark, minimalist, high-contrast visual tone.

## 5. Credits
* Built entirely with vanilla HTML5, CSS3, and JavaScript. No external third-party frameworks or media assets were used.
