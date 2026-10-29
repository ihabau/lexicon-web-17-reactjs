![Lexicon Logo](https://lexicongruppen.se/media/wi5hphtd/lexicon-logo.svg)

# ReactJS Exercises


## Exercise 1: Create a React App

### Goal
Create a React project and run it locally.

### Tasks
- Create a React app using Vite.
- Start the development server.
- Replace the default page with your own heading and short paragraph.
- Change the page title in `index.html`.

### Expected result
You should see your own custom React page running in the browser.

---

## Exercise 2: Integrate Tailwind CSS

### Goal
Set up Tailwind CSS and use it for basic styling.

### Tasks
- Install and configure Tailwind CSS in the React project.
- Add Tailwind directives to your main CSS file.
- Build a simple page with:
  - a heading
  - a paragraph
  - a button
  - one card
- Use Tailwind classes for spacing, colors, and text styles.

### Expected result
The page should look styled without writing much custom CSS.

---

## Exercise 3: Break a UI Into Smaller Components

### Goal
Create a card list and split it into smaller React components.

### Scenario
Create a page that shows a list of cards.

### Tasks
- Start with one larger card list design.
- Break it into smaller components such as:
  - `Header`
  - `Card`
  - `CardList`
  - `Footer`
- Place each component in its own file.
- Import and render them inside `App.tsx` or `App.jsx`.

### Expected result
Your app should show a card list, and the UI should be easier to read because it is split into small parts.

---

## Exercise 4: Use Props to Pass Data

### Goal
Continue the card list app by passing data to each card with props.

### Tasks
- Use the `Card` component from Exercise 3.
- Pass data through props:
  - title
  - description
  - image
  - category
- Render at least 3 cards with different data.

### Expected result
The same `Card` component should be reused several times with different content coming from props.

---

## Example Project Structure

```text
my-react-app/
├── public/
├── src/
│   ├── components/
│   │   ├── Header.jsx
│   │   ├── Card.jsx
│   │   ├── CardList.jsx
│   │   └── Footer.jsx
│   ├── assets/
│   ├── App.jsx
│   ├── main.jsx
│   └── index.css
├── index.html
├── package.json
└── vite.config.js
```
