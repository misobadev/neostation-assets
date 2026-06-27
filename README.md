Welcome to the official **NeoStation** assets repository. Here you can find and contribute new visual styles to customize your gaming experience.

## Repository Structure

The structure is designed to be modular and easy to navigate for both humans and the application:
* `themes/`: Contains all individual theme folders.
* `preview/`: Global screenshots for the catalog display.
* `manifest.json`: Main index used by the app to list available themes.

---

## How to Create a Theme

### 1. Folder Setup
Create a new folder inside `themes/` with a descriptive name (e.g., `Matrix-Green`).

### 2. The `theme.json` File
Each theme must include a `theme.json` file with metadata:
```json
{
  "id": "my-unique-theme",
  "name": "Visual Name",
  "author": "Your Name",
  "version": "1.0.0",
  "description": "Short description of the style.",
  "ai": false
}
```

### 3. Asset Requirements

To ensure optimal performance on handheld and Android devices, please follow these technical specifications:

#### **Backgrounds**
* **Format:** Must be **.webp** (optimized) or **.gif** (animated).
* **Resolution:** Exactly **1024 x 1024** px.
* **Location:** `themes/[your-theme]/backgrounds/`
* **Naming:** `[shortname].[extension]` (e.g., `gba.webp`, `ps1.gif`).
* **Fallback:** Always include a `default.webp` for unspecified systems.

#### **Logos**
* **Format:** **.webp** (with transparency).
* **Resolution:** Exactly **746 x 374** px.
* **Location:** `themes/[your-theme]/logos/`
* **Naming:** Must match the system `shortname` (e.g., `snes.png`).

## Publishing
Once your theme is ready, ensure you:
1. Add a screenshot to the `preview/` folder.
2. Register your theme in the `manifest.json` file at the root.
3. Open a Pull Request.

## Legal Information and Licensing

NeoStation Assets is a collection of original creative work and third-party trademarks.

- Original Assets: All custom backgrounds and original UI elements are licensed under CC BY-NC-SA 4.0.
- Trademarks: All console logos and brand names are the property of their respective owners. Their use here is for identification and educational purposes only.

For the full legal text, please refer to the LICENSE file in this repository.

## Contributions

We welcome contributions of new backgrounds or missing console logos. Please ensure any submitted work follows the quality standards of the project and respects the non-commercial nature of this repository.
