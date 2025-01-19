# Pagination Component with Pac-Man Animation

This project demonstrates a simple and interactive pagination component built with React and TypeScript. The design includes a Pac-Man animation that moves and reverses direction depending on the selected page.

---

## Features

1. **Dynamic Pagination**: Navigate through pages with buttons.
2. **Pac-Man Animation**:
   - Moves left to right or vice versa based on the selected page.
   - Reacts to user interactions with smooth transitions.
3. **Reversing Effect**: Pac-Man reverses direction when navigating to a previous page.
4. **Custom Styling**: Designed with CSS for a playful and vibrant appearance.

---

## Installation

1. Clone the repository:
   ```bash
   https://github.com/tahaesii/pacmanPagination.git
   ```

2. Navigate to the project directory:
   ```bash
   cd pagination-pacman
   ```

3. Install dependencies:
   ```bash
   npm install
   ```

4. Start the development server:
   ```bash
   npm start
   ```

---

## Code Overview

### Component: `Pagination`

- **State Management**:
  - `activePage`: Tracks the current active page.
  - `isReversing`: Determines the direction of Pac-Man.
- **Refs**:
  - `previousPage`: Stores the last active page for comparison.
- **Methods**:
  - `handlePageChanged`: Updates the state based on user interaction and determines the direction of Pac-Man.

### CSS Highlights

- **Pac-Man Animation**:
  - Transitions and rotations provide the "waka-waka" effect.
  - `@keyframes` animation enhances the mouth movement.
- **Styling Variables**:
  - Easily customizable dimensions and colors with CSS variables.

---

## Usage

1. Interact with the numbered buttons to navigate between pages.
2. Observe the Pac-Man character move and reverse direction when navigating.
3. Hover over the Pac-Man to see additional animations.

---

## Customization

### CSS Variables:
Modify the following variables in `styles.css` to adjust dimensions and colors:

- `--ddim`: Dot dimensions.
- `--rd`: Radius of Pac-Man's mouth.
- `--pm`: Color of Pac-Man.

### Component Enhancements:
You can extend the `Pagination` component by:

- Adding more pages.
- Including additional animations.
- Customizing button designs.

---

## Technologies Used

- React (with TypeScript)
- CSS for styling and animations

---


## Screenshots

![image](https://github.com/user-attachments/assets/b1d01240-e33b-400d-864d-2f9c8dfc96ae)




