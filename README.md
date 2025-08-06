# 🌊 Family Photo Water Pool

A beautiful Three.js water simulation featuring a swimming pool with your family photo displayed on the bottom. This project combines sophisticated water physics with personal touches to create a unique interactive experience.

## ✨ Features

- **Family Photo Pool Bottom**: Your family portrait appears as a beautiful mosaic on the pool floor
- **Clean Pool Design**: Light gray walls for a realistic swimming pool appearance
- **Advanced Water Physics**: Sophisticated water simulation with realistic ripples and waves
- **Interactive Water**: Click and drag to create water drops and ripples
- **Sky Reflections**: Beautiful reflections of the sky on the water surface
- **Caustics**: Realistic underwater light patterns
- **Responsive Design**: Works on desktop and mobile devices

## 🚀 Quick Start for Collaborators

### What You Need
- A modern web browser (Chrome, Firefox, Safari, Edge)
- Python 3 (usually pre-installed on Mac/Linux)

### Get Started in 3 Steps

1. **Download the project**:
   ```bash
   git clone https://github.com/delamarifer/family-photo-water-pool.git
   cd family-photo-water-pool
   ```

2. **Start the server**:
   ```bash
   python3 -m http.server 8080
   ```

3. **Open in your browser**:
   ```
   http://localhost:8080
   ```

That's it! You should see a beautiful water pool with interactive physics.

### Optional: Add Your Own Family Photo
- Replace `tiles.jpg` with your family photo (under 1MB recommended)
- The photo will appear on the pool bottom
- Refresh the browser to see changes

## 🎮 How to Use

- **Click and Drag**: Create water ripples by clicking and dragging on the water surface
- **Watch the Physics**: Observe realistic water wave propagation
- **Enjoy the Reflections**: See beautiful sky reflections on the water
- **Admire Your Family**: Your family photo creates a unique pool bottom design

## 🛠️ Technical Details

This project is built with:
- **Three.js**: 3D graphics and rendering
- **WebGL Shaders**: Custom GLSL shaders for water simulation
- **Real-time Physics**: GPU-accelerated water wave simulation
- **Responsive Design**: Works across different screen sizes

## 📁 Project Structure

```
family-photo-water-pool/
├── index.html          # Main HTML file
├── index.js            # Main JavaScript application
├── tiles.jpg           # Family photo (add your own!)
├── shaders/            # GLSL shader files
│   ├── water/          # Water surface shaders
│   ├── pool/           # Pool container shaders
│   ├── simulation/     # Water physics simulation
│   ├── caustics/       # Underwater light effects
│   └── utils.glsl      # Shared shader utilities
└── *.jpg               # Skybox textures
```

## 🔧 Troubleshooting

**Port 8080 already in use?**
```bash
python3 -m http.server 8081
# Then go to http://localhost:8081
```

**Python not found?**
- On Mac: `python3 -m http.server 8080`
- On Windows: `python -m http.server 8080`

**Page not loading?**
- Make sure you're in the correct directory
- Check that all files are present
- Try a different browser

## 🎨 Customization

### Changing the Family Photo
Replace `tiles.jpg` with your own family photo to personalize the pool bottom.

### Modifying Pool Colors
Edit `shaders/utils.glsl` to change the pool wall colors.

### Adjusting Water Physics
Modify the simulation parameters in `index.js` to change water behavior.

## 🤝 Contributing

This is a personal project, but feel free to fork and create your own variations!

## 📄 License

This project is based on the original [threejs-water](https://github.com/martinRenou/threejs-water) repository by Martin Renou, with modifications for the family photo feature.

## 🙏 Acknowledgments

- Original water simulation by [Martin Renou](https://github.com/martinRenou)
- Three.js community for the amazing 3D graphics library
- Your family for the beautiful photo that makes this pool special!

---

**Enjoy your personalized family photo water pool!** 🌊👨‍👩‍👧‍👦 