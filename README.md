# The Operation Child Care Project - Eligibility Calculator

This project is an interactive web-based **Eligibility Calculator** for The Operation Child Care Project (OCCP). It helps military families quickly estimate which child care assistance programs they may be eligible for, based on their installation, family type, and other criteria.

---

## Table of Contents

- [Features](#features)
- [Demo](#demo)
- [How It Works](#how-it-works)
- [Usage](#usage)
- [Data Sources](#data-sources)
- [Customization](#customization)
- [Development](#development)
- [License](#license)
- [Contact](#contact)

---

## Features

- **Step-by-step guided form** for easy data entry.
- **Dynamic dropdowns** based on real DoD installation and family eligibility data.
- **Instant results** showing which programs you may be eligible for, with descriptions and links to learn more or sign up.
- **Mobile-friendly, accessible, and visually styled** using [Tailwind CSS](https://tailwindcss.com/).
- **No backend required** – all logic and data are in the HTML/JS file.

---

## Demo

> **Try it live:**  
> [occproject.org/calculator](https://occproject.org/calculator)  
> *(Replace with actual URL if hosted)*

---

## How It Works

1. **Select Your Installation:**  
   Choose your military installation from a searchable dropdown.

2. **Select Your Military Family Type:**  
   Choose your general family category (e.g., Active Duty, DoD Civilian, Gold Star Spouse, etc.).

3. **Select Your Specific Family Situation:**  
   Choose a more specific description (e.g., "With Working Spouse", "Single Active Duty", etc.).

4. **Indicate School-Age Children:**  
   Answer whether you have school-age children (ages 5-12).

5. **View Results:**  
   Instantly see which programs you may be eligible for, with direct links to learn more or apply.

---

## Usage

1. **Download or clone this repository.**

2. **Open `index.html` in your web browser.**  
   *(No server required; all logic is client-side.)*

3. **Follow the on-screen steps to use the calculator.**

---

## Data Sources

- **Installations:**  
  Based on DoD and Coast Guard installation lists (700+ entries).

- **Family Types & Subtypes:**  
  Derived from official military child care eligibility criteria.

- **Program Eligibility Rules:**  
  Encoded from DoD/Service/Program policy and OCCP knowledge.

- **Program Descriptions & Links:**  
  Official links to OCCP, CDC, FCC, SAC, MCCYN, MCCYN-PLUS, and CCYH.

---

## Customization

- **Styling:**  
  Uses Tailwind CSS with a custom color palette and fonts matching [occproject.org](https://occproject.org).

- **Data:**  
  All data is stored in JavaScript arrays/objects at the top of the `<script>` section.  
  To update installations, family types, or eligibility rules, simply edit these arrays.

- **Branding:**  
  Fonts and colors can be changed in the `<head>` section.

---

## Development

### Prerequisites

- Modern web browser (Chrome, Firefox, Edge, Safari)
- (Optional) [VS Code](https://code.visualstudio.com/) or any code editor

### Editing

- All code is in a single HTML file.
- To add or update installations, family types, or eligibility logic, edit the relevant JavaScript arrays.
- To change program descriptions or links, edit the `programInfo` object.

### Build/Deploy

- No build step required.
- To deploy, upload the HTML file to your web server or static site host.

---

## License

This project is provided for informational and non-commercial use by The Operation Child Care Project.  
For other uses, please contact [info@occproject.org](mailto:info@occproject.org).

---

## Contact

- **Website:** [occproject.org](https://occproject.org)
- **Email:** [info@occproject.org](mailto:info@occproject.org)
- **Support:** Please open an issue or contact us for questions or suggestions.

---

*This calculator is for informational purposes only and does not guarantee eligibility or assistance. Final eligibility is determined upon official application and verification.*

---

## Screenshot

![Screenshot of OCCP Eligibility Calculator](screenshot.png)  
*(Add a screenshot of the calculator here)*

---

**Made with ❤️ by The Operation Child Care Project**
