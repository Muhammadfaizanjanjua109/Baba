# Interactive 3D Sculpture Effect

An immersive WebGL-based 3D sculpture visualization featuring dynamic particle effects and interactive distortion. This project showcases a responsive 3D model that reacts to user cursor movements with stunning particle-based disintegration and reformation effects.

## ✨ Features

- **Real-time Particle Effects**: Dynamic particle system with physics-based animations
- **Interactive Distortion**: Cursor-based model manipulation with smooth transitions
- **Custom Shaders**: GLSL shaders for advanced lighting and distortion effects
- **3D Model Support**: GLB/GLTF model loading capability
- **Orbital Controls**: Full 360° model viewing with zoom functionality
- **Responsive Design**: Adapts to different screen sizes and devices
- **Performance Optimized**: Efficient rendering for smooth interactions

## 🛠️ Tech Stack

- Three.js - 3D rendering engine
- Custom GLSL Shaders
- JavaScript ES6+
- WebGL
- HTML5/CSS3

## 🚀 Getting Started

### Prerequisites

- Modern web browser with WebGL support
- Local development server
- Basic knowledge of Three.js (for customization)

### Installation

1. Clone the repository:
```bash
git clone https://github.com/yourusername/interactive-3d-sculpture
cd interactive-3d-sculpture
```

2. Add your 3D model:
- Place your .glb file in the project root
- Rename it to `model.glb` or update the path in the code

3. Start a local server:
```bash
# Using Python 3
python -m http.server

# Using Node.js
npx http-server

# Using PHP
php -S localhost:8000
```

4. Open your browser and navigate to:
```
http://localhost:8000
```

## 🎮 Usage

- **Move**: Hover your cursor around the model to trigger particle effects
- **Rotate**: Click and drag to rotate the view
- **Zoom**: Use mouse wheel or pinch gestures to zoom in/out
- **Reset**: Double-click to reset the view

## ⚙️ Customization

### Particle System
```javascript
const particleCount = 1000; // Adjust particle density
const particleSize = 0.02;  // Adjust particle size
```

### Distortion Effect
```javascript
// In shaderMaterial uniforms
intensity: { value: 2.0 }    // Adjust effect intensity
mouseInfluence: { value: 1.2 } // Adjust mouse influence radius
```

### Colors
```javascript
const pointLight = new THREE.PointLight(0x00ffff, 1); // Adjust light color
// In fragment shader
vec3 baseColor = vec3(0.0, 1.0, 1.0); // Adjust model color
```

## 📝 Configuration

The project includes several configurable parameters:

- Camera position and field of view
- Particle system properties
- Distortion effect intensity
- Color schemes and lighting
- Model scaling and positioning

## 🔧 Troubleshooting

Common issues and solutions:

1. **Model not loading**
   - Ensure the model path is correct
   - Check if the model format is supported (.glb)
   - Verify the server is running correctly

2. **Performance issues**
   - Reduce particle count
   - Adjust render quality
   - Check browser WebGL support

## 🤝 Contributing

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request



## 🙏 Acknowledgments

- 3D Model: ["Human Face Sculpting Practice"](https://skfb.ly/orWvB) by 441670420 is licensed under [Creative Commons Attribution 4.0](http://creativecommons.org/licenses/by/4.0/)
- Three.js community for their excellent documentation
- WebGL and GLSL shader resources
- 3D modeling tools and resources

## 📮 Contact

Muhammad Faizan - (https://www.linkedin.com/in/follow-muhammadfaizan)
Project Link: [https://github.com/Muhammadfaizanjanjua109/Baba](https://github.com/Muhammadfaizanjanjua109/Baba)

---

Made with ❤️ by Muhammad Faizan
