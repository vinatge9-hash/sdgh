# Brew Haven - Website (4 pages + Cart)

This repository contains a complete, 4-page website for Brew Haven with an integrated shopping cart and PayPal checkout (Sandbox).

Pages included:
- index.html: Home page with hero, features, and testimonials
- menu.html: Menu with 5 coffees and 3 pastries, each with Add to Cart buttons
- about.html: About Brew Haven's passion for quality coffee
- contact.html: Contact information and form with Hyderabad, India placeholder
- cart.html: Shopping cart with live updates and PayPal checkout (Sandbox)

Notes and conventions:
- All pages use a warm, friendly, and professional theme with elegant serif headings and clean sans-serif body text.
- Font placeholders are included for two fonts: Playfair Display (headers) and Inter (body).
- Tailwind CSS is loaded via CDN for utility-based styling.
- All images use placeholder src in the form: src="https://pixabay.com/get/ge2e226b2b8bac3f684b453a942301722ddc0f950712259f8b56dd9c655fc58ef5e76e4e7cf3d5a146450bb33639b070b862f45669a7d6300681626bf0556271d_640.jpg" as required.
- The footer shows Copyright with the current year: 2025.
- The cart persists across pages using localStorage under the key brewhaven_cart.

How to customize:
- Replace PAYPAL_SANDBOX_CLIENT_ID with your actual sandbox client id in cart.html.
- Update placeholder images in the src attributes of img tags.
- Change the Hyderabad address in contact.html if needed.

Usage:
- Open index.html to start. Navigate to Menu, About, Contact, or Cart via the header links.
- Add items from the Menu to the cart. Go to Cart to view, adjust quantities, or checkout with PayPal.

