# Shopify-Grandport
Shopify Grandport Theme

A custom **Shopify theme** built with Liquid, JavaScript, and modern Shopify development tools. This repository contains the code for a full-featured storefront with reusable sections, snippets, and a comprehensive set of assets aimed at providing a rich shopping experience.

---

## 📁 Project Structure

```
assets/        # JavaScript, CSS, images, and other static files
blocks/        # Reusable block templates included in sections
config/        # Theme configuration files (settings_schema.json, settings_data.json, etc.)
layout/        # Base HTML layouts (`theme.liquid`, `customer.liquid`, etc.)
locales/       # Translation files for multiple languages
sections/      # Customizable page sections used in the theme editor
snippets/      # Small Liquid fragments imported by other templates
templates/     # Page templates (index, product, collection, cart, etc.)
```

Each directory follows Shopify's theme architecture and allows merchants to make visual updates through the theme editor.

---

## 🚀 Getting Started

1. **Clone the repository**
   ```sh
   git clone <repository-url> shopify-grandport
   cd shopify-grandport
   ```

2. **Install Shopify CLI** (if not already installed):
   ```sh
   npm install -g @shopify/cli @shopify/theme
   ```

3. **Authenticate** and connect to your store:
   ```sh
   shopify login --store your-store.myshopify.com
   ```

4. **Start local development**:
   ```sh
   shopify theme dev
   ```

   This command will spin up a local server and watch for file changes, syncing them with your development theme on Shopify.

---

## 🛠 Development Workflow

- **Editing Liquid templates:** Modify files under `sections/`, `snippets/`, `templates/`, or `layout/`.
- **JavaScript & CSS assets:** Found in `assets/`; you can add or update scripts and styles.
- **Theme settings:** Configure `config/settings_schema.json` to expose options in the theme editor.
- **Localization:** Add or update translations under `locales/` (e.g., `en.default.json`).
