# Basilisk Simulation Documentation

This repository contains tutorials and documentation for spacecraft simulations using the [Basilisk](https://hanspeterschaub.info/basilisk/) astrodynamics framework.

## 📚 Documentation Site

Visit the live documentation: **[https://pagrossi91.github.io/basilisk-quarto-marimo-test/](https://pagrossi91.github.io/basilisk-quarto-marimo-test/)**

*(Replace with your actual GitHub Pages URL after publishing)*

## 🚀 Tutorials

- **Basic Orbit Scenario** - Fundamental orbital mechanics simulation demonstrating:
  - Spacecraft orbital dynamics
  - Gravity modeling (point mass and spherical harmonics)
  - Multiple orbit types (LEO, GEO, GTO)
  - Earth and Mars simulations

## 🛠️ Setup

### Prerequisites

- Python 3.11+
- [Basilisk](https://github.com/AVSLab/basilisk) installed

### Installation

1. Clone this repository:
```bash
git clone https://github.com/pagrossi91/basilisk-quarto-marimo-test.git
cd basilisk-simulations
```

2. Create and activate a virtual environment:
```bash
python3 -m venv .venv
source .venv/bin/activate  # On Windows: .venv\Scripts\activate
```

3. Install Basilisk following the [official instructions](https://hanspeterschaub.info/basilisk/Install/installOnMacOS.html)

4. Install Python dependencies:
```bash
pip3 install jupyter nbformat nbclient ipykernel matplotlib numpy pandas
```

## 📝 Contributing

Feel free to open issues or submit pull requests with improvements or additional tutorials.

## 📖 Resources

- [Basilisk Documentation](https://hanspeterschaub.info/basilisk/)
- [Basilisk GitHub](https://github.com/AVSLab/basilisk)
- [AVS Lab](http://hanspeterschaub.info/AVSlab.html)

## 📄 License

This documentation is provided for educational purposes. Basilisk is licensed under the ISC License.
