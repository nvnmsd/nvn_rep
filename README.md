# Saanvi Food Lounge Angular Website

This repository contains planning notes for the "Saanvi Food Lounge" restaurant website.

## Project Goal
Create a simple, modern website built with the latest Angular. The site will include the following pages:

- **Home** – Landing page with restaurant highlights and imagery.
- **About** – Brief history and philosophy of the restaurant.
- **Contact** – Address, map, phone number, and contact form.
- **Customer Feedback** – Testimonials or a small form for customers to share their experiences.

## Angular Setup
1. Install the Angular CLI (requires internet connection):

   ```bash
   npm install -g @angular/cli
   ```

2. Create a new project using the latest Angular version:

   ```bash
   ng new saanvi-food-lounge --routing --style=scss
   cd saanvi-food-lounge
   ```

3. Generate page components:

   ```bash
   ng generate component pages/home
   ng generate component pages/about
   ng generate component pages/contact
   ng generate component pages/customer-feedback
   ```

4. Update the router in `app-routing.module.ts` to map routes (`'', 'about', 'contact', 'feedback'`) to these components.

5. Apply a warm color palette associated with food (greens, oranges, yellows) in `src/styles.scss` and use a semi-formal font such as `"Montserrat"` or `"Raleway"` from Google Fonts.

6. Build and serve locally:

   ```bash
   ng serve
   ```

## Logo Ideas
- A stylized chef hat that forms the letter "S" or wraps around the restaurant name.
- A circular emblem with utensils (fork, spoon) forming a subtle "S" shape.
- Warm colors like deep orange or rich green to evoke appetizing vibes.

Feel free to expand on these ideas and adjust the components as needed for the final design.

