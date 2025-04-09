# Pokémon TCG Dex

A simple, single-page web application to search for and view Pokémon Trading Card Game (TCG) cards. Enter a Pokémon name or a Set name to browse cards, view their images, and get a direct link to their TCGplayer market page.

https://amadou-d.github.io/Pokehub/
## Features

*   **Card Search:** Search for cards by Pokémon name (e.g., "Pikachu", "Charizard") or Set name (e.g., "Base Set", "Evolving Skies", "151").
*   **Card Display:** View results as a grid of card images.
*   **Card Details:** Displays the Set Name and Rarity below each card image.
*   **TCGplayer Link:** Provides a direct link button for each card to its corresponding page on TCGplayer.com for market prices and listings.
*   **Image Modal:** Click on any card image to view a larger version in a modal overlay.
*   **Pagination:** Navigate through search results using "Previous" and "Next" buttons.
*   **Loading Indicator:** Displays a Poké Ball themed spinner while fetching data.
*   **Responsive Design:** Adapts layout for different screen sizes (desktop, tablet, mobile).
*   **Visually Appealing:** Uses Pokémon-themed colors and fonts.

## Technologies Used

*   **HTML5:** Structure of the web page.
*   **CSS3:** Styling, layout, responsiveness, and animations.
    *   Google Fonts (`Press Start 2P`, `Lato`)
    *   CSS Variables for theming
*   **Vanilla JavaScript (ES6+):**
    *   Fetching data from the API (`fetch` API, `async/await`).
    *   DOM manipulation to display cards, loader, pagination, and modal.
    *   Handling user input and events.
    *   AbortController for cancelling pending fetch requests.
*   **Pokécard TCG API:** ([pokemontcg.io](https://pokemontcg.io/)) - Provides the card data, images, and TCGplayer links.

## Getting Started

No complex setup required!

1.  **Download:** Clone this repository or simply download the `[YOUR_FILENAME].html` file (replace `[YOUR_FILENAME]` with the actual name of your HTML file).
2.  **Open:** Open the downloaded HTML file directly in your preferred web browser (like Chrome, Firefox, Edge, Safari).
3.  **Internet Connection:** Ensure you have an active internet connection, as the application needs to fetch data from the `pokemontcg.io` API.

## Usage

1.  Open the HTML file in your browser.
2.  Enter a Pokémon name or a TCG Set name into the search bar.
3.  Click the "Search" button or press Enter.
4.  Wait for the loading indicator to finish.
5.  Browse the displayed card results.
6.  Click on a card image to see a larger view. Click the '×' or outside the image to close the modal.
7.  Click the "View on TCGplayer" button below a card to open its TCGplayer page in a new tab.
8.  Use the "Previous" and "Next" buttons at the bottom (if there are multiple pages of results) to navigate.

## API Credits

This application relies heavily on the fantastic **Pokémon TCG API** provided by [pokemontcg.io](https://pokemontcg.io/). Please refer to their documentation for API usage details and terms.

## Author

*   **Amadou** - *Initial work*

## License

This project is licensed under the MIT License - feel free to use and modify!
