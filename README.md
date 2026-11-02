# The-Emotional-Archive
An interactive browser-based experience designed to help urban youth and students process daily worries and anxiety through a mindful digital ritual.

## 🌟 Live Demo & Preview
* **Project Type**: Interactive Web Experience
* **Screenshot**: 
  *(You can add a screenshot of your running app here if needed)*

## 💡 Concept & Intended User
* **Intended User**: Students and young adults experiencing academic stress or daily fatigue who need a private, low-friction space to clear their minds.
* **Core Idea**: Users write down a fleeting worry or thought and "seal" it. The text transforms into a floating visual capsule that dissolves into a calm background archive, giving a physical metaphor of letting go.

## 🕹️ Main Interaction Loop
1. **Input**: Type text into the text area.
2. **Response**: Click **"Seal & Release"** to trigger a smooth rising capsule animation and a randomized supportive message.
3. **Feedback**: The daily archived counter increases, and the input field clears, offering a clean slate.

## 🛡️ Error Handling
* **Empty Input**: If a user clicks "Seal & Release" without typing anything, the input box shakes with a red border (`.shake` animation) and a subtle error message appears ("Nothing is written here yet. Type something to archive."), preventing accidental empty submissions.

## 🚀 How to Run Locally
No complex installation or external dependencies (like Python `uv` or Node.js npm) are required.
1. Download or clone this repository.
2. Locate the `index.html` file.
3. Double-click `index.html` to open it directly in any modern web browser (Chrome, Safari, Edge, Firefox).

## 🛠️ Known Limitations
* Data is stored temporarily in the browser's local state during the session; entries are not saved to a persistent backend database.
