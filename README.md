# 🧱 Lego Paglu 

3D Browser-Based Lego Builder A browser-based 3D Lego builder using **Three.js** and **Tailwind CSS**. Build, rotate, drag, and save Lego structures in real-time. 

<img width="400" height="212" alt="Screen Recording 2026-04-29 at 9 14 32 PM" src="https://github.com/user-attachments/assets/c307baa8-94b7-4464-8574-0261c6808da7" /> 


--- 

## ✨ Features 
- **Place & Build** - Click to place multiple brick types (1x1, 2x2, 2x4, etc.) 
- **Rotate** - Press `R` or use arrow keys to rotate bricks 
- **Delete & Drag** - Toggle modes with `D` (delete) and `M` (drag)
- - **Grid Alignment** - Auto-snap to grid for precision 
- **Reference Images** - Upload guide images for building 
- **Blueprints** - Pre-designed shapes (pyramid, heart, etc.) 
- **Save/Load** - Persist designs via localStorage 
- **Orbit Controls** - Rotate, zoom, and pan the camera 


### Advanced Features v2 
- **Reference Image Overlay** - Upload and position guide images 
- **Blueprint System** - Pre-designed shapes including pyramids and hearts 
- **Save/Load System** - Persist your creations using browser localStorage 
- **Live Brick Counter** - Real-time display of placed bricks 
- **Smooth Animations** - Pop-in effect and damped camera movement 


### Installation 
1. **Clone the repository**
   ```bash git clone https://github.com/VIDHISHAK15/Lego-Editor.git cd Lego-Editor ``` 
   2. **Open in browser** - Simply open `lego.html` in your web browser - Or serve locally using a simple HTTP server: ```bash # Python 3 python -m http.server 8000 # Node.js (http-server) npx http-server # PHP php -S localhost:8000 ``` 
   3. **Access the application** - Navigate to `http://localhost:8000/lego.html` - Start building! 
--- 

## 🎮 Usage
 
1. **Select brick type** from the tool panel
2. **Choose color** from palette
3. **Click** to place (ghost preview shows placement)
4. **Rotate** with `R` or arrow keys
5. **Delete** - Press `D`, hover, and click to remove
6. **Drag** - Press `M` to move bricks
7. **Save** - `Ctrl+S` to persist


## ⌨️ Keyboard Shortcuts
 
| Key | Action |
|-----|--------|
| `R` | Rotate brick 90° |
| `↑↓←→` | Fine-tune rotation |
| `D` | Toggle Delete Mode |
| `M` | Toggle Drag Mode |
| `Ctrl+S` | Save |

## 🛠️ Tech Stack
 
- **Three.js** - 3D rendering, OrbitControls, Raycasting
- **Tailwind CSS** - UI styling
- **Vanilla JavaScript** - No dependencies
- **LocalStorage** - Data persistence
- **WebGL** - Hardware-accelerated 3D
    

### Customization

```javascript
const brickTypes = {
  '1x1': { width: 1, height: 1, depth: 1 },
  '2x2': { width: 2, height: 1, depth: 2 },
};
```
 
### Add Colors
```javascript
const colors = {
  red: new THREE.MeshStandardMaterial({ color: 0xFF0000 }),
};
```
 
## 🐛 Troubleshooting
 
| Issue | Solution |
|-------|----------|
| 3D not rendering | Enable WebGL, check browser console |
| Bricks not snapping | Verify grid size in code |
| Slow performance | Reduce brick count, disable shadows |
| Save not working | Enable localStorage in browser |

 ## 🤝 Contributing
 
1. Fork and clone
2. Create feature branch: `git checkout -b feature/name`
3. Commit changes: `git commit -m 'Add feature'`
4. Push: `git push origin feature/name`
5. Open Pull Request
## 📄 License
 
MIT License - see [LICENSE](LICENSE) file
    
## 👨‍💻 Author **VIDHISHAK15** - [@VIDHISHAK15](https://github.com/VIDHISHAK15) 
## 🙏 Credits 
- Three.js - 3D library 
- Tailwind CSS - Styling 
- LEGO - Inspiration and design philosophy
