# 🖨️ Elegoo Centauri Carbon 2  
### Slicer Profiles & Tuning Hub

A curated collection of slicer profiles, filament presets, and calibration resources for the **Elegoo Centauri Carbon 2**.

This repository focuses exclusively on **slicer-based optimization**, providing reliable starting points to improve print quality, consistency, and performance.

---

## 🔧 Features

### 🎛️ Slicer Profiles
- Optimized profiles for:
  - **OrcaSlicer**
  - **Elegoo Slicer**
- Balanced for quality, reliability, and ease of use

### 🧵 Filament Profiles
- Presets for a wide range of materials:
  - PLA / PLA+
  - PETG
  - ABS / ASA
  - TPU
  - Nylon / PA
  - Carbon Fiber blends (PA-CF, PETG-CF, etc.)
- Tuned parameters include:
  - Temperature
  - Flow rate
  - Cooling
  - Retraction

### 📐 Calibration Resources
- Flow and extrusion tuning guidance  
- Temperature tower setups  
- Retraction calibration  
- First layer optimization tips  

### 📚 Documentation *(in progress)*
- Tuning workflows  
- Material-specific recommendations  
- General troubleshooting guidance  

---

## 🏷️ Profile Naming Conventions# 🖨️ Elegoo Centauri Carbon 2  
### Slicer Profiles & Tuning Hub
A curated collection of slicer profiles, filament presets, and calibration resources for the **Elegoo Centauri Carbon 2**.
This repository focuses exclusively on **slicer-based optimization**, providing reliable starting points to improve print quality, consistency, and performance.

---

## 🔧 Features

### 🎛️ Slicer Profiles
- Optimized profiles for:
  - **OrcaSlicer**
  - **Elegoo Slicer**
- Balanced for quality, reliability, and ease of use

### 🧵 Filament Profiles
- Presets for a wide range of materials:
  - PLA / PLA+
  - PETG
  - ABS / ASA
  - TPU
  - Nylon / PA
  - Carbon Fiber blends (PA-CF, PETG-CF, etc.)
- Tuned parameters include:
  - Temperature
  - Flow rate
  - Cooling
  - Retraction

### 📐 Calibration Resources
- Flow and extrusion tuning guidance  
- Temperature tower setups  
- Retraction calibration  
- First layer optimization tips  

### 📚 Documentation *(in progress)*
- Tuning workflows  
- Material-specific recommendations  
- General troubleshooting guidance  

---

## 📥 Installation

Profiles can be imported individually or as a bundled zip. Choose the method that fits your needs.

---

### 🗂️ Method 1 — Import a Single Profile

**Step 1: Download the file**

Navigate to the profile you want in the repository, click it to open it, then click the **Download raw file** button (or right-click → *Save link as*) to save the `.json` or `.ini` file to your computer.

**Step 2: Import into your slicer**

- **OrcaSlicer:** Go to `File` → `Import` → `Import Configs...`, select your downloaded file, and click **Open**.
- **Elegoo Slicer:** Go to `File` → `Import` → `Import Config...`, select your downloaded file, and click **Open**.

The profile will appear in the appropriate dropdown (Printer, Filament, or Process) immediately after import.

---

### 📦 Method 2 — Download & Import Multiple Profiles as a Zip

Use this method to grab several profiles at once, or an entire folder.

**Step 1: Download as a zip**

- **Single folder:** Navigate to the folder you want, click the **`...`** menu (top-right of the file list), and select **Download directory as ZIP** *(requires being logged into GitHub)*.
- **Entire repository:** On the main repo page, click the green **`<> Code`** button, then select **Download ZIP**.

**Step 2: (Optional) Curate your selection**

If you only want a subset of what you downloaded, open the zip and remove any profiles you don't need before importing. This keeps your slicer library clean and avoids cluttering it with profiles you won't use.

**Step 3: Import the zip into your slicer**

- **OrcaSlicer:** Go to `File` → `Import` → `Import Configs...`, select the `.zip` file directly, and click **Open**. OrcaSlicer will extract and install all included profiles automatically.
- **Elegoo Slicer:** Go to `File` → `Import` → `Import Config Bundle...`, select the `.zip` file, and click **Open**.

All profiles contained in the zip will be available in their respective dropdowns after import.

---

> 💡 **Tip:** If you already have profiles with the same name, your slicer may prompt you to overwrite or keep both. When in doubt, choose **Keep** to preserve your existing settings.

---

## 🏷️ Profile Naming Conventions

To maintain consistency and scalability across the repository, all profiles follow structured naming formats:

### 🖨️ Printer Profiles
Manufacturer - Model - Nozzle Size

**Example:**
Elegoo - Centauri Carbon 2 - 0.4

---

### 🧵 Filament Profiles
Manufacturer - Filament Type - Filament Color

**Example:**
Polymaker - PLA+ - Black

---

### ⚙️ Process Profiles
Layer Height - Label - Printer - Strength - Support/Blank - Brim/Mouse Ear/Blank - Infill Pattern - Fast/Slow/Blank

**Examples:**

0.20 - Quality - CC2 - Standard - Support - Brim - Gyroid - Slow

0.20 - Quality - CC2 - Standard - Brim - Gyroid - Slow

0.20 - Quality - CC2 - Standard - Gyroid


> Notes:
> - Skip a slot where a category does not apply  (i.e. no support or brim from the examples above)
> - Keep labels short and consistent (e.g., *Draft, Quality, Strength*)  
> - Printer shorthand (e.g., **CC2**) may be used for brevity  

---

## ⚠️ Disclaimer

These profiles are **not guaranteed to work perfectly in every scenario**.

3D printing performance can vary due to:
- Differences between filament **brands and manufacturing batches**
- Environmental conditions (temperature, humidity)
- Individual printer variation and wear over time

> ⚠️ **Not all filament types and brands have been fully tested.**

All profiles provided here should be treated as **starting points**, and further tuning may be required for your specific setup.

---

## 🚧 Future Development

This repository is actively evolving and may expand to include:

- Additional filament and process profiles  
- Refined tuning strategies  
- Advanced calibration techniques  
- Standardized testing methodologies  

---

## 🤝 Contributing

Contributions are welcome and encouraged.

- 🐛 **Report issues:**  
  https://github.com/Botmans-Printing-Paradise/Elegoo-Centauri-Carbon-2/issues  

- 🔧 **Submit improvements (Pull Requests):**  
  https://github.com/Botmans-Printing-Paradise/Elegoo-Centauri-Carbon-2/pulls  

Please ensure contributions are clearly documented and tested where possible.

---

## 📄 License

[GNU General Public License v3.0](https://github.com/Botmans-Printing-Paradise/Elegoo-Centauri-Carbon-2/blob/main/LICENSE)

---
