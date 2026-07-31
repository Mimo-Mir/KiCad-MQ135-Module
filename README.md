# MQ135 Module KiCad Library

A custom KiCad library for the popular **MQ135 Gas Sensor Module**, including a schematic symbol, PCB footprint, and an aligned 3D model.

This library was created to make it easy to use the MQ135 module in KiCad projects without having to recreate the footprint or symbol.

---

## Features

- ✅ Custom schematic symbol
- ✅ Custom PCB footprint
- ✅ Integrated 3D STEP model
- ✅ Accurate mounting holes
- ✅ Through-hole header footprint
- ✅ Fabrication (F.Fab) and Silkscreen layers
- ✅ Ready for PCB design in KiCad 9

---

## Repository Structure

```
KiCad-MQ135-Module/
│
├── 3DModels/
│   └── MQ135_Module.step
│
├── Footprints/
│   └── MQ135_Module.pretty/
│       └── MQ135_Module.kicad_mod
│
├── Symbols/
│   └── MQ135_Module.kicad_sym
│
├── LICENSE
├── CHANGELOG.md
└── README.md
```

---

## Pinout

| Pin | Name | Description |
|-----|------|-------------|
| 1 | VCC | Power Supply (5V) |
| 2 | GND | Ground |
| 3 | DO | Digital Output |
| 4 | AO | Analog Output |

---

## 3D Model

The repository includes a STEP model for realistic PCB visualization inside KiCad.

---

## Compatibility

- KiCad 9
- Windows, Linux, macOS

---

## Installation

### Symbol Library

1. Open **Preferences → Manage Symbol Libraries**
2. Add:

```
Symbols/MQ135_Module.kicad_sym
```

### Footprint Library

1. Open **Preferences → Manage Footprint Libraries**
2. Add:

```
Footprints/MQ135_Module.pretty
```

### 3D Model

Ensure the STEP file is located in:

```
3DModels/MQ135_Module.step
```

Update the footprint's 3D model path if necessary.

---


## License

This project is licensed under the MIT License.

---

## Author

**Mir Soleman Ali**



GitHub: https://github.com/Mimo-Mir

---

## Contributions

Issues, suggestions, and pull requests are welcome.
