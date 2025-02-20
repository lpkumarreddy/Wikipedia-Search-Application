# Wikipedia Search Application

This is a **Wikipedia Search Application** built using **HTML, CSS, JavaScript, and Bootstrap**. It allows users to search for topics on Wikipedia and displays the results dynamically. The application fetches data from a custom API and displays the title, link, and description of each search result.

## Features

- **Search Functionality**: Users can type a keyword and press Enter to search for topics on Wikipedia.
- **Dynamic Results**: Search results are displayed dynamically with titles, links, and descriptions.
- **Loading Spinner**: A spinner is shown while the results are being fetched.
- **Responsive Design**: The application is optimized for both desktop and mobile devices.
- **External API Integration**: Uses a custom API (`https://apis.ccbp.in/wiki-search`) to fetch search results.

## Technologies Used

- **HTML**: For structuring the content.
- **CSS**: For styling the application.
- **Bootstrap**: For responsive design and pre-built components like the spinner.
- **JavaScript**: For fetching data from the API and dynamically displaying results.
- **Google Fonts**: For custom typography.

## How to Use

1. Clone the repository to your local machine:
   ```bash
   git clone https://github.com/lpkumarreddy/Wikipedia-Search-Application.git
   ```
2. Open the `index.html` file in your browser.
3. Type a keyword in the search bar and press **Enter** to see the results.

## Project Structure

- **`index.html`**: The main HTML file containing the structure of the application.
- **CSS Styling**: Inline styles and external Google Fonts are used for design.
- **JavaScript**: Handles the search functionality and API integration.
- **Bootstrap Components**: Used for the spinner and responsive layout.

## Screenshots

### Home Page
![Home Page](https://d1tgh8fmlzexmh.cloudfront.net/ccbp-dynamic-webapps/wiki-logo-img.png)

### Search Results
![Search Results](https://via.placeholder.com/600x400.png?text=Search+Results+Example)

## API Used

The application uses the following API to fetch search results:
```
https://apis.ccbp.in/wiki-search?search=<keyword>
```

Replace `<keyword>` with the search term entered by the user.

## Code Explanation

### HTML Structure
- The `input` element is used for the search bar.
- A `div` with a spinner is shown while the results are being fetched.
- The `searchResults` `div` dynamically displays the search results.

### JavaScript Functionality
- **`getSearchResult`**: Fetches data from the API when the user presses Enter.
- **`createAndAppendSearchResult`**: Creates and appends each search result to the DOM.
- **`displayResults`**: Displays the fetched results and hides the spinner.

### CSS Styling
- Custom styles are applied to the search bar, results, and spinner.
- Google Fonts are used for typography.

## License

This project is licensed under the **MIT License**. See the [LICENSE](LICENSE) file for details.

---

## MIT License

```plaintext
MIT License

Copyright (c) 2023 LINGAM PAVAN KUAMR REDDY

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
```

---

## How to Contribute

1. Fork the repository.
2. Create a new branch (`git checkout -b feature/YourFeatureName`).
3. Commit your changes (`git commit -m 'Add some feature'`).
4. Push to the branch (`git push origin feature/YourFeatureName`).
5. Open a pull request.
