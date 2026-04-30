# Crystal, Glass, and Vesicle Ternary Diagram

**Interactive ternary plot for visualizing volcanic rock classification based on normalized Crystal, Glass, and Vesicle components.**

[![GitHub Pages](https://img.shields.io/badge/View%20Live-GitHub%20Pages-informational)](https://tdisando.github.io/CGV_ternary/)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)

---

## 🌋 About

This tool provides an interactive web-based ternary diagram for classifying and visualizing volcanic rocks according to their normalized proportions of:
- **Crystal** (solid phases or differentiation signatures)
- **Glass** (amorphous phase of solidified melt)
- **Vesicle** (exsolved volatile or porosity)

The classification scheme is inspired by seminal work in volcanology and petrology:
- **Fisher** (1966) — Foundational ternary classification framework
- **Schmid** (1981) — Refinements in volcanic rock nomenclature
- **Pettijohn et al.** (1975) — Sedimentary rock classification principles adapted for volcanic materials

---

## ✨ Features

- **Interactive Ternary Plotting**: Add sample points with real-time visualization
- **Natural Field Boundaries**: Pre-defined classification fields for common volcanic rock types:
  - Obsidian, Dense Lavas, Scoriae, Pumices, Reticulites
  - Tachylite/Sideromelane, Vitrophyres, Porphyritic Lavas
  - Hyaloclastites/Palagonite, Cumulates
- **Dynamic Validation**: Automatic sum validation (must equal 100%)
- **Normalized Input Sliders**: Easy adjustment of Crystal, Glass, and Vesicle percentages
- **Sample Management**: Add, delete, and track multiple sample points
- **Export Capabilities**:
  - Download plots as **PNG** images
  - Export sample data as **CSV**
- **Dark Theme UI**: Professional, publication-ready dark interface
- **Responsive Design**: Works on desktop and tablet displays
- **Hover Tooltips**: Quick access to sample composition details

---

## 🚀 Quick Start

1. **Visit the app**: https://tdisando.github.io/CGV_ternary/
2. **Add a sample**:
   - Enter a sample name (e.g., "BAS-01", "PUM-03")
   - Adjust sliders for Crystal, Glass, and Vesicle percentages
   - Ensure total = 100%
   - Click **"▸ Plot Sample"**
3. **Visualize**: Points appear on the ternary diagram, color-coded and labeled
4. **Manage**: Delete individual samples or clear all
5. **Export**: Download PNG or CSV for further analysis

---

## 📊 Classification Fields

The diagram includes 10 natural volcanic rock classification fields (rough estimation):

| Field | Characteristics |
|-------|-----------------|
| **Obsidian** | High glass (>90%), minimal crystals/vesicles |
| **Dense Lavas** | Crystalline basalt/andesite; low vesicularity |
| **Scoriae** | Moderate crystal + vesicle; intermediate porosity |
| **Pumices** | High vesicularity (>60%); low crystal |
| **Reticulites** | Extreme vesicularity (>85%); minimal other phases |
| **Tachylite/Sideromelane** | High glass with minor vesicles; deep-water basalt |
| **Vitrophyres** | Crystalline with glassy matrix; transitional |
| **Porphyritic Lavas** | Significant crystals in glassy groundmass |
| **Hyaloclastites/Palagonite** | Mixed glass + vesicles; alteration products |
| **Cumulates** | Highly crystalline (>80%); crystal-rich phases |

---

## 📐 Mathematical Basis

The ternary diagram uses an **equilateral triangle** where:
- **Bottom-left corner** = 100% Crystal
- **Bottom-right corner** = 100% Glass
- **Top corner** = 100% Vesicle

Coordinates are normalized such that **Crystal + Glass + Vesicle = 100%**.

---

## 📚 References

1. **Fisher, R. V.** (1966). "Geology of the Crater Lake Caldera, Oregon." *U.S. Geological Survey Professional Paper*, 513. https://doi.org/10.1016/0012-8252(66)90010-9

2. **Schmid, R.** (1981). "Descriptive nomenclature and classification of pyroclastic deposits and fragments: Recommendations of the IUGS Subcommission on the Systematics of Igneous Rocks." *Journal of Volcanology and Geothermal Research*, 8(3-4). https://doi.org/10.1007/BF01822152

3. **Pettijohn, F. J., Potter, P. E., & Siever, R.** (1975). *Sand and Sandstone* (2nd ed.). Springer-Verlag. https://doi.org/10.1007/978-1-4612-1066-5

---

## 📝 License

This project is licensed under the **MIT License** — see [LICENSE](LICENSE) file for details.

**You are free to:**
- Use commercially and privately
- Modify the source code
- Distribute copies

**You must:**
- Include the license and copyright notice

---

## 🙏 Acknowledgments

- Inspired by classic volcanology literature and the IUGS nomenclature system
- Built for geologists, volcanologists, and petrology researchers
- Special thanks to all contributors and users providing feedback
