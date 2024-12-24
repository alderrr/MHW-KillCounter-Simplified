# Monster Hunter Counter

This web app is a simple counter for tracking the number of times different monsters in Monster Hunter have been hunted. It features a visual display of each monster's name, a counter showing the number of hunts, and an image representing the monster.

## Features

- Displays the name of the monster and its hunt count.
- Smooth transition effects when switching between monsters.
- Counter updates dynamically as you cycle through the list of monsters.
- Custom design with Tailwind-inspired CSS styles.

## Usage

You can navigate through the list of monsters using the left and right arrow keys.

### Steps:

1. Open the `index.html` file in a browser.
2. Use the left (`←`) or right (`→`) arrow keys to cycle through different monsters.
3. The hunt counter will show the total count for all monsters or specific monsters.

## Project Structure

```
/public/
├── /images/ # Folder containing the monster icons used in the app
└── index.html # Main HTML file with embedded styles and script
```

## Custom Styles

Although TailwindCSS is commented out in the HTML file, custom CSS is used to provide a similar clean and responsive design. The background color is set to a dark theme, and each monster's icon is displayed with smooth transition effects when cycling through the monsters.

## Monster List

- Each monster has a unique image and is tracked by name.
- Monsters are displayed with their respective hunt counts, which can be updated dynamically.

## Dependencies

This project does not rely on any external libraries or packages like TailwindCSS. It uses pure HTML, CSS, and JavaScript to deliver a lightweight, easy-to-run web app.

## License

This project is open source and available under the MIT License.
