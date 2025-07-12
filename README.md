# odin-recipes

A simple HTML-based recipe website showcasing basic web development skills. This project demonstrates fundamental HTML structure, navigation between pages, and image integration.

## About

This project is a collection of recipe pages built with pure HTML. It features a main index page that links to individual recipe pages, each containing recipe information and images.

## Project Structure

```
odin-recipes/
├── index.html              # Main landing page with recipe links
├── README.md               # This file
└── recipes/
    ├── lasagna.html        # Lasagna recipe page
    ├── lasagna.jpeg        # Lasagna recipe image
    ├── porktenderloin.html # Pork Tenderloin recipe page
    └── porktenderloin.jpg  # Pork Tenderloin recipe image
```

This README provides comprehensive information about your project, including how to use it, its structure, and how to extend it with new recipes. The documentation covers both user and developer perspectives, making it easy for anyone to understand and contribute to your recipe website.

## How to Use

### Viewing the Website

1. **Local Development**: Simply open `index.html` in your web browser
   - Right-click on `index.html` → "Open with" → Choose your preferred browser
   - Or drag and drop `index.html` into your browser window

2. **Live Server** (Recommended for development):
   - If using VS Code with Live Server extension: Right-click `index.html` → "Open with Live Server"
   - Or use any local development server of your choice

3. **Direct File Access**: Navigate to the project directory and double-click `index.html`

### Navigation

- Start at `index.html` - the main page containing links to all recipes
- Click on any recipe link to view the individual recipe page
- Use your browser's back button to return to the main page

## Current Recipes

- **Lasagna**: Classic Italian layered pasta dish
- **Pork Tenderloin**: Juicy and flavorful pork recipe

## Adding New Recipes

To add a new recipe to the website:

1. **Create the recipe HTML file**:
   - Add a new HTML file in the `recipes/` directory
   - Follow the existing structure from `lasagna.html` or `porktenderloin.html`
   - Include proper HTML5 structure with title, heading, and image

2. **Add the recipe image**:
   - Place the recipe image in the `recipes/` directory
   - Use web-friendly formats (JPEG, PNG, WebP)
   - Optimize images for web use (reasonable file size)

3. **Update the main page**:
   - Edit `index.html` to add a link to your new recipe
   - Follow the existing link structure: `<a href="recipes/your-recipe.html">Recipe Name</a>`

## Development

This project uses:
- **HTML5**: For structure and content
- **No CSS**: Pure HTML styling (basic browser defaults)
- **No JavaScript**: Static content only

### Best Practices

- Maintain consistent HTML structure across all pages
- Use semantic HTML elements
- Include proper alt text for images
- Keep file names lowercase and hyphenated
- Ensure all links are functional

## Technologies Used

- HTML5
- Basic web browser functionality

## Browser Compatibility

This website works in all modern browsers including:
- Chrome
- Firefox
- Safari
- Edge

## Contributing

Feel free to contribute by:
- Adding new recipes
- Improving HTML structure
- Adding CSS styling (if desired)
- Fixing any broken links or issues

## License

This project is open source and available under the [MIT License](LICENSE).