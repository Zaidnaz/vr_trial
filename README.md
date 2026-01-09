# Cyberpunk VR Shooter

A minimal A-Frame demo: a neon, physics-enabled VR shooter that works with mouse (desktop) and VR controllers.

**Features:**
- Simple `shooter` component: fires neon bullets with sound (mouse click or VR trigger).
- `keyboard-look` component: desktop arrow-key camera rotation; `wasd-controls` for movement.
- Uses `aframe-environment-component` and `aframe-physics-system` for scene and physics.

**Run:**
1. Serve the project over HTTP (recommended). Example commands:

```powershell
python -m http.server 8000
# or
npx serve .
```

2. Open http://localhost:8000 and load [index.html](index.html).
3. For VR mode use a WebXR-capable browser and a secure context (HTTPS) or a local server/workflow that enables WebXR.

**Controls:**
- Desktop: Click to shoot; Arrow keys to rotate view; WASD to move.
- VR: Use controller trigger to shoot; laser-controls provided for right hand.

**Notes:**
- External libraries are loaded from CDNs; an internet connection is required.
- Bullets are created as dynamic physics bodies and removed after a short timeout.
- If you want me to expand this README with build/deploy steps, testing, or credits, tell me which details to add.
