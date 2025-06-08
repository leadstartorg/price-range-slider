# Dual Range Slider

A simple dual-handle range slider built using vanilla JavaScript and CSS, integrated into a Bootstrap 5 layout. 
It allows users to select a price range with two draggable handles and synchronized number input fields.

*Forked from [w3collective/price-range-slider](https://github.com/w3collective/price-range-slider/).*

---

## Features

* **Dual Handles:** Select a minimum and maximum value using two interactive slider handles.
* **Converging Handles:** The minimum and maximum handles can now meet at the same value.
* **Number Input Sync:** Text fields display and control the slider values, allowing for direct input.
* **Bootstrap 5 Styling:** Uses Bootstrap 5 for a clean and responsive look.
* **No External Slider Library:** Built with plain JavaScript and CSS for core functionality.

---

## Key Difference from Forked Version

The primary distinction from the original `w3collective` version is the removal of the **minimum difference constraint**. In this version, the `rangeMin` variable and its associated logic have been eliminated. 
This change allows the **minimum and maximum slider handles to be set to the same value**, offering more flexibility in range selection. 
Previously, the handles were always forced to maintain a minimum gap of 100 units.

---
