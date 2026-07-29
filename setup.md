# Setup Guide

Welcome to the **Premium GitHub Profile Branding Kit**.

This repository is designed to act as a highly polished, Vercel/Apple-inspired personal dashboard. It goes beyond a simple README by integrating automated workflows, premium SVG assets, and meticulously crafted typography grids.

## Getting Started

1. **Clone the Repository**
   ```bash
   git clone https://github.com/surajmore303/surajmore303.git
   cd surajmore303
   ```

2. **Customize the Content**
   The main content lives in `README.md`. It relies heavily on HTML tables and embedded SVG files. You can find all the SVGs inside the `assets/svg/` folder.

3. **Enable GitHub Actions**
   To power the live analytics and contribution snake:
   - Navigate to the **Actions** tab on your GitHub repository.
   - Click "I understand my workflows, go ahead and enable them" if prompted.
   - Ensure you have granted **Read and Write permissions** under Settings > Actions > General > Workflow permissions.

4. **Generating the Snake**
   The snake animation updates automatically every 12 hours via `.github/workflows/snake.yml`.

5. **Advanced Metrics**
   Additional metrics are gathered using `.github/workflows/metrics.yml`. Ensure you have the required personal access tokens set up in your repository secrets if you wish to expand its capabilities.
