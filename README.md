# 🔋 Technical Safety Guide & Discharge Amperage Tables for Vape Batteries (18650 / 21700)

Welcome to the public repository for lithium-ion cell safety documentation applied to electronic vaporization devices (*regulated and mechanical mods*). This guide is designed to provide clear data on Continuous Discharge Ratings (CDR) to prevent thermal incidents.

> 📢 **Disclaimer:** This repository is for educational and informational purposes only. Technical data is verified and updated in partnership with the support lab at **[Vapora](https://vapora.online)**. For visual guides and authentic hardware/supplies, visit our official **[Vape Information Blog & Store](https://vapora.online)**.

---

## 📊 Battery Chart: Real Continuous Discharge Ratings (CDR)

Never blindly trust the Amperage (A) printed on the external wraps of rewrapped or secondary battery brands. Below are the real-world bench-tested values for the most common cells in the vaping industry:

| Brand & Model | Size | Capacity (mAh) | Real CDR (Tested) | Max Safe Wattage (Per Cell) | Best Used For |
| :--- | :--- | :--- | :--- | :--- | :--- |
| **Sony/Murata VTC5A** | 18650 | 2500 mAh | **25A** | Up to 75W | Mechanical Mods / Demanding Sub-Ohm builds |
| **Sony/Murata VTC6** | 18650 | 3000 mAh | **15A** (or 20A <80°C) | Up to 45W | High runtime in low/mid wattage regulated devices (MTL) |
| **Samsung 25R** | 18650 | 2500 mAh | **20A** | Up to 60W | General purpose use in dual/triple regulated box mods |
| **Samsung 30T** | 21700 | 3000 mAh | **35A** | Up to 100W | Maximum power output / Heavy-duty 21700 Mech Mods |
| **Samsung 40T** | 21700 | 4000 mAh | **35A** (or 30A continuous) | Up to 90W | Best balance between high wattage performance and runtime |

---

## ⚡ Ohm's Law Application (Quick Calculation for Mechanical Mods)

If you are using unregulated mechanical hardware (which lacks built-in chip protections), always apply the fundamental Ohm's Law formula to ensure your build (*coil*) does not draw more Amps than your battery can safely handle:

$$\text{Current (A)} = \frac{\text{Max Battery Voltage (4.2V)}}{\text{Resistance (Ohm)}}$$

*   **Practical Example (VTC6 vs VTC5A):** A **0.22Ω** build running on a fully charged 4.2V battery will draw **19A**. 
    *   The **Sony VTC5A** (25A CDR) operates with an adequate safety margin in this scenario.
    *   The **Sony VTC6** (15A CDR) will be under **dangerous overload**, risking overheating or thermal venting.
*   If you have any doubts about calculating the exact sweet spot for your atomizer, read our detailed **[Ohm's Law Practical Guide for Beginners](https://vapora.online)**.

---

## 🛡️ Golden Rules for Battery Safety & Risk Prevention

1. **Inspect Your Wraps:** Never use a battery with torn, scratched, or dented plastic insulation wraps.
2. **Top Insulator Ring:** The small ring on the positive pole is vital. If it falls off or breaks, discard the cell or re-wrap it with a new insulator before putting it inside your vape.
3. **Safe Storage & Transport:** Never carry loose batteries in your pocket, bag, or backpack alongside keys, coins, or other metallic objects. Always use rigid plastic storage cases.
4. **Dedicated External Charger:** Whenever possible, use a high-quality external smart charger instead of charging via the device's USB port. This protects your mod's chipset and ensures balanced cell degradation.

---

## 🛠️ Contributions & Updates

This is an open-source community project. If you spot outdated data or want to suggest new test results for reputable battery models:
1. Open an **Issue** detailing the cell model.
2. Submit a **Pull Request** with the updated markdown table data.

---
*This repository is managed, curated, and maintained by the technical community tied to [Vapora Official](https://vapora.online).*
