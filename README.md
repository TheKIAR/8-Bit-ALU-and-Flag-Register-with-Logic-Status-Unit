# 🧮 8-Bit ALU & Flag Register

<p align="center">
  <img src="assets/runtime-screenshot.png" alt="8-Bit ALU Logisim runtime" width="950">
</p>

<p align="center">
  <strong>Logisim Evolution • Digital Logic • Computer Architecture</strong><br>
  An interactive 8-bit arithmetic and logic unit with a 4-bit status register.
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Logisim-Evolution-blue" alt="Logisim Evolution">
  <img src="https://img.shields.io/badge/ALU-8--Bit-orange" alt="8-bit ALU">
  <img src="https://img.shields.io/badge/Digital-Logic-green" alt="Digital Logic">
</p>

---

## 🧠 What is inside?

The circuit implements four selectable operations and exposes useful status information — making it a compact demonstration of how an ALU can be assembled from digital logic.

### ⚡ Operations

| Selector | Operation | Result |
|---|---|---|
| `00` | ADD | A + B |
| `01` | SUB | A − B |
| `10` | AND | A AND B |
| `11` | OR | A OR B |

### 🔌 Inputs

- **A** — 8-bit operand
- **B** — 8-bit operand
- **Selector** — 2-bit operation control

### 🚦 Status flags

| Flag | Meaning |
|---|---|
| 🟢 **Zero** | Result equals 0 |
| 🔄 **Carry** | Arithmetic carry / borrow-related status |
| 🔴 **Negative** | Result MSB is set |
| 🟣 **Parity** | Result parity status |

## 🧪 Example tests

| A | B | Operation | Expected |
|---:|---:|---|---:|
| 5 | 3 | ADD | 8 |
| 8 | 3 | SUB | 5 |
| 170 | 240 | AND | 160 |
| 170 | 15 | OR | 175 |

For a stronger demo, also test zero results, arithmetic carry/borrow cases, MSB-set results, and both even/odd parity.

## 🖥️ Open the circuit

Use **Logisim Evolution** and open:

```text
8-Bit ALU and Flag Register with Logic Status Unit.circ
```

## 🔧 What this project demonstrates

- Combinational digital logic
- ALU architecture
- Arithmetic and bitwise operations
- Multiplexer/control selection
- Status/flag generation
- Digital-circuit simulation

## 🚀 Future upgrades

- Add a labeled circuit diagram
- Add a test/demo GIF
- Document exact flag truth tables
- Add increment/decrement operations
- Expand the ALU with additional arithmetic functions

## 👋 Connect

Built by **Md. Ragib Ashhab**.

🌐 [Portfolio](https://ragibashhab.netlify.app/) · 💼 [LinkedIn](https://www.linkedin.com/in/md-ragib-ashhab-768a19240/) · 🔗 [Linktree](https://linktr.ee/RagibAshhab) · 🐙 [GitHub](https://github.com/TheKIAR)

---

> **Understand the bits. Build the logic. See the architecture.**
