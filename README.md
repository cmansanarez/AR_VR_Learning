# AR_VR_Learning

A lightweight sandbox for learning AR/VR on the web. This repo is intentionally minimal so I can iterate quickly while exploring WebXR concepts and interaction patterns.

## What’s in here

- **`index.html`**: The main learning playground page.
- **`style.css`**: UI styling, including an “Enter AR” floating button and a night mode variant.
- **`ARVR_Learning_Background.png`**: Background / visual texture used by the page.

> Note: WebXR is the browser API layer for AR/VR, but it does not render 3D by itself. You typically pair it with WebGL or a framework (A-Frame, three.js, Babylon, etc.).  
> Sources: MDN WebXR fundamentals, and the WebXR spec session modes.  
> (See links in **References**.) 

## Running locally

Because browsers restrict some XR features on `file://`, run this with a local server:

### Option A: VS Code Live Server
1. Open the folder in VS Code
2. Install **Live Server**
3. Right-click `index.html` → **Open with Live Server**

### Option B: Python simple server
```bash
python3 -m http.server 8000
