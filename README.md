# Shoptet Fulltext Description Addon

This addon provides a simple way to show expandable/collapsible product descriptions within Shoptet-powered stores. By shortening long product descriptions and allowing visitors to expand them on demand, it improves user experience and prevents overly long texts from cluttering the product page.

## Overview

Shoptet Fulltext Description Addon injects custom CSS and JS into your Shoptet theme to wrap long descriptions into a collapsible container. A "Show more" or "Show less" toggle helps customers quickly access all the information they need without being overwhelmed at first glance.

## Key Features

- **Collapsible Descriptions:**  
  Long descriptions are truncated by default, with a "Show more" link to reveal the full text.
  
- **User-Friendly Interface:**  
  Simple toggles allow customers to easily expand or collapse text sections without leaving the page.
  
- **Easy Integration:**  
  Minimal setup is required. Just include the provided script and CSS in your Shoptet template.

## Installation & Setup

1. **Download or Clone the Repository:**
   ```bash
   git clone https://github.com/kukivac/shoptet-fulltext-description.git
   ```

2. **Include the CSS and JS:**
   - Add the CSS file (`fulltext-description.css`) to your Shoptet theme’s stylesheet or include it via `<link>` in your theme’s template.
   - Include the JS file (`fulltext-description.js`) before the closing `</body>` tag or in your theme’s JS bundle.

3. **Initialize the Script:**
   The script will automatically look for elements with the configured description container class. By default, it targets product description elements. If you need to adjust the selectors or initial collapsed length, open the JS file and modify the configuration variables accordingly.

4. **Customize Appearance (Optional):**
   - Edit `fulltext-description.css` to adjust the look and feel of the expandable area, toggle link, and transitions.
   
   - Modify any configuration options in `fulltext-description.js` to set the initial character limit or customize UI text like "Show more" and "Show less".

## Usage

Once the addon is integrated, product descriptions longer than the configured character limit will be truncated. Users will see a "Show more" link which, when clicked, reveals the full description and replaces the link with a "Show less" toggle to collapse the text again.

## Contributing

Contributions are welcome! Feel free to open an issue or submit a pull request if you encounter a bug, have a suggestion, or want to add a new feature. Please follow standard GitHub collaboration practices.

## License

This project is licensed under the [MIT License](LICENSE).

---

*Enhance your Shoptet product pages with a neat expandable description feature, ensuring a cleaner storefront and a better shopping experience for your customers.*  
