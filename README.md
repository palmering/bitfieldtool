![License](https://img.shields.io/github/license/palmering/bitfieldtool?color=blue)
![Stars](https://img.shields.io/github/stars/palmering/bitfieldtool?style=social)
![Top Language](https://img.shields.io/github/languages/top/palmering/bitfieldtool)
# 🛠️ Bit Field Tool
> A lightweight, web-based utility for defining and visualizing 32-bit registers and generating C-compatible macros.

<p align="center">
  <a href="https://palmering.github.io/bitfieldtool/">
    <img src="https://github.com/user-attachments/assets/91a20c43-5089-400c-9173-7ca3352a7977" alt="Bit Field Tool Screenshot" width="800">
  </a>
  <br>
  <b><a href="https://palmering.github.io/bitfieldtool/">🚀 Launch Live Tool</a></b>
</p>

---

## ✨ Overview
Developing firmware for systems often requires tedious bitmasking. This tool simplifies the process by allowing you to interactively map out registers and instantly get the `#define` macros you need for your C/C++ header files.

## 🚀 Key Features
* **Interactive Bit Mapping:** Toggle individual bits or define multi-bit fields with a click.
* **Instant C-Macro Generation:** Automatically calculates masks and positions (`_MSK` and `_POS`).
* **Live Register Value:** View the hex/decimal value of the register as you toggle bits.
* **Snapshot Export:** Save your register configuration as a PNG for documentation or Datasheet creation.
* **Field Management:** * `Left-Click`: Edit bit field values.
    * `Right-Click`: Rename fields for specific peripheral registers.

## 📖 How to Use
1.  **Define Fields:** Select a range of bits to group them into a named field.
2.  **Toggle & Input:** Manually click bits or type a value into the input field to see the bit-pattern.
3.  **Copy & Paste:** Grab the generated macros from the bottom panel and drop them into your project.

## 💻 Technical Details
This is a zero-dependency web tool hosted via **GitHub Pages**. 

* **Format:** Standard C-style `#define` outputs.
* **Scope:** Supports up to 32-bit registers (Standard for ARM Cortex-M).

---

<p align="center">
  <sub>Built for embedded engineers, firmware developers, and hardware enthusiasts.</sub>
</p>
