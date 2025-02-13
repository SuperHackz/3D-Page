# tri.js

## Overview
`tri.js` is a JavaScript bookmarklet that applies a **3D transformation effect** to web pages using perspective and rotation. It allows dynamic interaction through **mouse movement** or **device orientation** and includes a settings menu for customization.

## Features
- **Mouse-controlled 3D rotation**
- **Gyroscope-based interaction** (for mobile devices)
- **Customizable settings** via a floating menu:
  - Rotation limit
  - Depth gap between elements
  - Tilt adjustment (sag)
  - Field of view (FOV)
  - Enable/disable transformations
- **Toggle and Quit buttons** to control the effect

## Usage
### 1. Add as a Bookmarklet
1. Copy the following JavaScript code:
   ```javascript
   javascript:(function(){var js=document.body.appendChild(document.createElement("script"));js.onerror=function(){alert("Sorry, the script could not be loaded.")};js.src="https://rawgit.com/Krazete/bookmarklets/master/tri.js"})(); 
   ```
2. Open your browser's **Bookmarks Manager**.
3. Create a **new bookmark** and paste the copied code into the **URL field**.
4. Click the bookmark on any webpage to activate the effect.

### 2. Run Directly in Console
1. Open the **browser developer console** (`F12` or `Ctrl + Shift + I` → Console tab).
2. Paste the script and press **Enter**.

## Controls
- `≡` Button: Toggle the settings menu.
- **Sliders & Checkboxes**: Adjust depth, rotation, field of view, etc.
- **Quit Button**: Remove the effect.
