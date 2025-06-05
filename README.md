# ⚡ OpenChargeX

> Open-source. Multi-voltage. Smarter than your average charger.

**OpenChargeX** is a full-featured, dual-battery smart charger designed for makers, engineers, and hardware rebels. From BQ chips to airflow control and MPPT logic, it’s everything off-the-shelf chargers should have been.

---

## 🔧 Features

- 🔋 Dual battery channels (isolated)
- ☀️ MPPT buck input for solar integration
- 🌡️ Thermal feedback + active cooling
- 🧠 Built on BQ24640 + BQ76930
- 🖥️ UI with current, voltage, temp readouts
- ⚙️ Modular design: firmware, UI, PCB all open

---

## 📁 Project Structure

| Folder      | Description                          |
|-------------|--------------------------------------|
| `/hardware` | KiCad schematics, PCB, BOM           |
| `/firmware` | ESP32/STM32 logic for charge control |
| `/simulation` | MPPT, buck, thermal simulations     |
| `/ui`       | Display mockups + interface logic    |

---

## 🧠 Contributing

We welcome:
- 🧪 Hardware experiments
- 💡 UI improvements
- ⚙️ Firmware PRs & bug fixes
- 🔍 Feedback from real-world testing

---

## 📜 License

Licensed under [MPL 2.0](LICENSE) – free to use, remix, and build upon.  
Commercial use requires attribution.

---

> Built by [@AditLuthra](https://github.com/aditluthra) • Part of the [MakrX Ecosystem](https://github.com/aditluthra/makrx-ecosystem)
