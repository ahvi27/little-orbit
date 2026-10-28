# Little Orbit ✳

A responsive, space-themed website where you can discover imaginary destinations and save your favorite escapes.

## Features

- Animated planet created entirely with CSS
- Light and dark themes with a saved preference
- Random destination generator that avoids consecutive repeats
- Destination filters: peaceful, strange, and wonderful
- Favorites saved in your browser using localStorage
- Remove saved destinations from your collection
- Responsive layout for mobile and desktop
- Keyboard navigation, live announcements, and reduced-motion support
- No dependencies, external assets, or build tools required

## Built With

- HTML5
- CSS3
- JavaScript

## Getting Started

Download the repository and open `index.html` in your browser.

Alternatively, clone it:

    git clone https://github.com/YOUR-USERNAME/little-orbit.git
    cd little-orbit

Replace `YOUR-USERNAME` with your GitHub username, then open `index.html`.

## Project Structure

    little-orbit/
    ├── index.html
    └── README.md

All styles and JavaScript are included in `index.html`.

## How to Use

1. Choose a mood from the dropdown.
2. Click **Find my escape** to discover a destination.
3. Click **Save this escape** to add it to your collection.
4. View your favorites under **Your little collection**.
5. Click **Remove** to delete a favorite.
6. Use the theme button to switch between light and dark mode.

## Browser Storage

Favorites and theme preferences are stored locally in your browser.

- Saved data does not sync across devices or browsers.
- Clearing browser storage removes saved preferences and favorites.
- If storage is unavailable, favorites work for the current page session.
- No account or backend is required.

## Customization

Edit `index.html` to personalize the website:

- **Colors:** Update the CSS variables in `:root` and `[data-theme="light"]`.
- **Content:** Change the headings, descriptions, and cards in the HTML.
- **Destinations:** Edit the `destinations` array in the script.
- **Planet:** Adjust the `.planet`, `.ring`, and `.universe` styles.

Each destination needs a unique `id`, a `mood`, a `title`, and a `description`.

Supported mood values are `quiet`, `strange`, and `wonder`.

## Deploy with GitHub Pages

1. Push `index.html` and `README.md` to your repository.
2. Open the repository's **Settings → Pages**.
3. Under **Build and deployment**, select **Deploy from a branch**.
4. Choose your branch and the **/ (root)** folder.
5. Click **Save**.

Once deployment finishes, GitHub displays your website URL.

## Credits

Design, planet illustration, and animations are built with HTML and CSS.
No external image assets or libraries are used.
