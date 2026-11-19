# NFC Card

A credit card sized pcb card that has NFC built in. The card can be used as a tap to pay card and can be written commands into it like an NFC tag.

This is **my first ever hardware project**, designed from scratch in EasyEDA.

I'm new to hardware, so I took reference from existing open-source designs and learning resources rather than starting from nothing:

- [Jams.Hack Club](https://jams.hackclub.com/)
- OSHWD Labs
- Existing GitHub repositories for NFC tag boards

---

## Features

- **NFC tag IC** (NT3H2111W0FHKH) for tap-to-share data
- **PCB-trace NFC antenna** (25 x 48 mm), so there is no extra antenna part to buy or solder
- **Credit-card form factor**, easy to carry in a wallet
- **Indicator LED** (yellow, 0805)
- **Designed in EasyEDA Standard**, with schematic, PCB and Gerbers included

---

## Screenshots

### Schematic
<img width="1169" height="827" alt="Schematic_NFC-Card_2026-11-19" src="https://github.com/user-attachments/assets/556a9866-2a05-4b5d-9320-cb85b0900521" />


### PCB Layout
<img width="888" height="671" alt="image" src="https://github.com/user-attachments/assets/7090437b-b209-47b0-916a-47179c5b4829" />


### 3D View - Front
<img width="1232" height="788" alt="image" src="https://github.com/user-attachments/assets/3db72f86-8b0e-4fed-a235-067421b13fdc" />


### 3D View - Back

<img width="1293" height="824" alt="image" src="https://github.com/user-attachments/assets/a7b302bd-0f5c-4f4f-8e11-9ac6f385abee" />

---

## Bill of Materials
 
| Designator | Part Number | Description | LCSC # | Link | Type | Qty / Board | Unit Cost (USD)* |
|---|---|---|---|---|---|---|---|
| U1 | NT3H2111W0FHKH | NFC Forum Type 2 tag IC | C710403 | [LCSC](https://www.lcsc.com/product-detail/C710403.html) / [JLCPCB](https://jlcpcb.com/partdetail/NxpSemicon-NT3H2111W0FHKH/C710403) | Extended | 1 | $0.5583 |
| C1 | CL10B224KA8NNNC | Capacitor, 220 nF | C21120 | [LCSC](https://www.lcsc.com/product-detail/C21120.html) | Basic | 1 | $0.0089 |
| R1 | 0603WAF470JT5E | Resistor, 47 ohm, 0603 | C23182 | [LCSC](https://www.lcsc.com/product-detail/C23182.html) | Basic | 1 | $0.0018 |
| LED1 | KT-0805Y | LED, yellow, 0805 | C2296 | [LCSC](https://www.lcsc.com/product-detail/C2296.html) | Basic | 1 | $0.0149 |
| ANT1 | 25X48MM_NFC | NFC antenna (PCB trace footprint, user-contributed library) | - | - | - | 1 | $0.00 |
 
\*Unit cost is the extended price for 5 boards divided by 5. The antenna is a copper trace on the board itself, so it has no purchase cost. The full BOM with pricing is in [`BOM.csv`](BOM.csv).
 
---

 
## Artwork Credits and Takedown Notice
 
The silkscreen artwork on this board  was collected from **Pinterest** while I was exploring ideas. Pinterest pins often don't link back to the original creator, and unfortunately **I did not keep track of where each image came from**, so I can't credit the original artists by name. I'm sorry about that.
 
I'm sharing this project for learning and non-commercial purposes only. It is a personal business card, and no one is being sold anything.
 
**If you are the creator of any artwork used on this board:**
 
- **Want credit?** Open an issue in this repository or email me at **hello@xunjra.com** with a link to your original work, and I'll add your name and link here right away.
- **Want it removed?** Contact me the same way and I'll take the artwork out of this repository, the screenshots and the README, and I won't use it on future board revisions.
- **Want to be left as is?** No action needed, but you are always welcome to reach out.

Thank you to all the artists whose work inspired the look of this board.
 
---

## Acknowledgements

- [Jams.Hack Club](https://jams.hackclub.com/) for the project inspiration and references
- OSHWD Labs and the open-source GitHub projects I learned from
- The EasyEDA community for the user-contributed NFC antenna footprint
- Pintrest creators for Arts and Design

---


## Contact

- Name: **Arjun Khanal**
- Website / Portfolio: https://me.xunjra.com
- GitHub: https://github.com/xunjra
- Email: hello@xunjra.com
