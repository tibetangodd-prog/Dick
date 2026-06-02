# ⚔️ Blade & Spell

A 3D third-person action game built with Three.js.

## 🎮 Controls

### Desktop
| Key | Action |
|-----|--------|
| WASD / Arrow Keys | Move |
| Shift | Sprint |
| Space | Jump |
| J | Sword Attack (Outward Slash) |
| K | Sword Attack (Inward Slash) |
| L | Cast Spell (Laser Beam) — costs 25 MP |
| R / Ctrl | Roll / Dodge |
| Mouse Drag | Rotate Camera |
| Scroll | Zoom |

### Mobile (Landscape)
- **Left joystick** — Move
- **↑** — Jump
- **⚔️** — Attack 1
- **🗡️** — Attack 2
- **✨** — Spell
- **🔄** — Roll
- **Drag center** — Rotate camera

## 🚀 Deploy to GitHub Pages

1. Create a new GitHub repository
2. Upload all files (keeping folder structure)
3. Go to **Settings → Pages**
4. Set Source to **Deploy from branch → main → / (root)**
5. Your game will be live at `https://yourusername.github.io/your-repo-name`

## 📁 File Structure
```
index.html          ← main game
models/
  character.glb     ← character mesh
  Idle.glb
  Walking.glb
  Running.glb
  Sprint.glb
  Attack1.glb
  Attack2.glb
  CastSpell.glb
  Roll.glb
```
