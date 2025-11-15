# ⚡ PowerPulse 360° - Power System Simulator

A modern, visually immersive educational website designed to help Electrical Engineering students understand the complete power system lifecycle - from generation, transmission, distribution, to final consumption.

## 🌟 Features

### 1. **Home Page - Welcome to PowerPulse 360°**
- Interactive 3D animated power grid visualization using Three.js
- Particle effects and rotating geometric shapes
- Smooth navigation to different sections

### 2. **Generation Section**
Interactive exploration of different power generation methods:
- 🔥 **Thermal Power** - Coal, gas, oil combustion
- 💧 **Hydro Power** - Dam-based generation
- ☀️ **Solar Power** - Photovoltaic systems
- 💨 **Wind Power** - Turbine-based generation
- ☢️ **Nuclear Power** - Nuclear fission
- 🌋 **Geothermal** - Earth's internal heat

Each plant includes:
- Interactive 3D-style cards
- Process flow diagrams (Fuel → Turbine → Generator)
- Hover animations and effects

### 3. **Transmission Section**
- Animated high-voltage transmission lines
- Interactive substations with pulse effects
- Visual representation of power flow
- Information on step-up transformers and transmission infrastructure

### 4. **Distribution Section**
- Real-time monitoring gauges for:
  - Distribution voltage (11 kV)
  - Load balance (75%)
  - Voltage drop indicators
  - Power quality metrics (98%)
- Animated meters and indicators
- Color-coded voltage level visualization

### 5. **Consumer Side - Interactive Smart Home**
- Click appliances to turn them ON/OFF:
  - 💡 LED Lights (100W)
  - ❄️ Air Conditioner (1500W)
  - 🧊 Refrigerator (150W)
  - 🚿 Water Heater (2000W)
  - 📡 Microwave (1200W)
  - 📺 Television (300W)
  - 🌀 Washing Machine (800W)
  - 📶 WiFi Router (50W)
- Real-time power consumption meter
- Cost calculation ($0.12/kWh)
- ☀️ **Solar Net Metering** - Shows power generation and grid feedback

### 6. **Simulation Lab**
Drag & drop power system builder with:
- Components: Generator, Transformer, Transmission Line, Load, Circuit Breaker
- Interactive circuit building canvas
- **Run Simulation** - Validates circuit and shows power flow
- **Fault Test** - Simulates short circuits and overcurrent conditions
- Real-time feedback and analysis

### 7. **About / Contact / Feedback**
- Platform information and features
- Educational benefits
- Contact form for feedback
- Feature highlights

## 🎨 Design & Aesthetics

### Theme
Futuristic, industrial-tech, inspired by smart grids and real-time control centers

### Color Palette
- **Background**: `#0E1117` (Dark industrial)
- **Accent**: `#00FFD1` (Neon green-blue glow)
- **Highlight**: `#FFB100` (Warning yellow for alerts and flow highlights)

### Typography
- **Headings**: Orbitron (Techno-style font)
- **Body**: Inter (Clean sans-serif)

## 🛠️ Technologies Used

- **3D Graphics**: Three.js for immersive 3D visualizations
- **Animations**: GSAP (GreenSock Animation Platform) with ScrollTrigger
- **Styling**: Modern CSS with custom properties and animations
- **Fonts**: Google Fonts (Orbitron, Inter)
- **JavaScript**: Vanilla JS for interactivity

## 🚀 Getting Started

### Installation

Simply open the `index.html` file in a modern web browser. No build process required!

```bash
# Clone the repository
git clone https://github.com/Rsmk27/Power-system-simulator-.git

# Navigate to the directory
cd Power-system-simulator-

# Open in browser
open index.html  # macOS
start index.html # Windows
xdg-open index.html # Linux
```

### Hosting Options

1. **GitHub Pages**: 
   - Enable GitHub Pages in repository settings
   - Select the main branch
   - Your site will be live at `https://Rsmk27.github.io/Power-system-simulator-/`

2. **Vercel**:
   ```bash
   # Install Vercel CLI
   npm i -g vercel
   
   # Deploy
   vercel
   ```

3. **Netlify**: Drag and drop the folder to Netlify dashboard

## 📚 How to Use

1. **Navigation**: Use the top navigation bar to jump to different sections
2. **Generation**: Hover over power plant cards to see effects, click for details
3. **Transmission**: Watch the animated power flow through transmission lines
4. **Distribution**: Observe real-time meter readings and gauges
5. **Consumer**: Click appliances to simulate power usage and see consumption
6. **Simulation**: 
   - Drag components from the palette to the canvas
   - Click "Run Simulation" to validate your circuit
   - Click "Fault Test" to simulate failures
   - Click "Clear" to start over

## 🎯 Educational Value

This platform provides:
- **Visual Learning**: 3D animations make abstract concepts concrete
- **Interactive Exploration**: Hands-on experience with power systems
- **Real-time Feedback**: Instant results from simulations
- **Comprehensive Coverage**: All stages from generation to consumption
- **Engaging Interface**: Modern design keeps students interested

## 📱 Responsive Design

The website is fully responsive and works on:
- Desktop computers
- Tablets
- Mobile phones

## 🔒 Browser Compatibility

Tested and working on:
- Chrome 90+
- Firefox 88+
- Safari 14+
- Edge 90+

## 🤝 Contributing

Contributions are welcome! Feel free to:
- Report bugs
- Suggest new features
- Submit pull requests
- Improve documentation

## 📄 License

This project is open source and available for educational purposes.

## 👨‍💻 Developer

Created for Electrical Engineering education

## 🙏 Acknowledgments

- Three.js community for excellent 3D graphics library
- GSAP for smooth animations
- Google Fonts for typography

---

**⚡ PowerPulse 360° - Making Power Systems Education Interactive and Fun!**
