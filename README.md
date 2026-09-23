# 8-Bit ALU and Flag Register

> Digital-logic portfolio project built and simulated in Logisim Evolution.


A Logisim Evolution digital-logic project implementing an 8-bit ALU with four selectable operations and a 4-bit status/flag register.

## Operations

| Selector | Operation | Description |
|---|---|---|
| `00` | ADD | A + B |
| `01` | SUB | A - B |
| `10` | AND | A AND B |
| `11` | OR | A OR B |

## Inputs

- 8-bit operand **A**
- 8-bit operand **B**
- 2-bit operation selector

## Flags

The status register exposes:

- **Zero** — result is 0
- **Carry** — carry/borrow-related arithmetic status
- **Negative** — result has its most-significant bit set
- **Parity** — result parity status

## Example Tests

| A | B | Operation | Expected result |
|---:|---:|---|---:|
| 5 | 3 | ADD | 8 |
| 8 | 3 | SUB | 5 |
| 170 | 240 | AND | 160 |
| 170 | 15 | OR | 175 |

For portfolio demonstrations, also test a zero result, an arithmetic carry/borrow case, an MSB-set result, and both even- and odd-parity results.

## Tool

Built with **Logisim Evolution**.

Open:

`8-Bit ALU and Flag Register with Logic Status Unit.circ`

## Portfolio Focus

This project demonstrates:

- Combinational digital logic
- ALU design
- Arithmetic and bitwise operations
- Multiplexer/control selection
- Status/flag generation
- Digital-circuit simulation

## Future Improvements

- Add a labeled circuit screenshot
- Add a test/demo GIF
- Document the exact flag truth tables
- Add more arithmetic operations such as increment/decrement


## 🌐 Links

**Portfolio:** https://ragibashhab.netlify.app/

**GitHub:** https://github.com/TheKIAR

**LinkedIn:** https://www.linkedin.com/in/md-ragib-ashhab-768a19240/

**Linktree:** https://linktr.ee/RagibAshhab
