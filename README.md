<h1 align="center">Forkify App</h1>
<p align="center">
    <img src="./src/img/favicon.png" alt="Logo" width="15%" height="auto">
 </p>

<p align="center">
  <img src="https://img.shields.io/badge/version-2.0.0-blue.svg?cacheSeconds=2592000" />
  <a href="https://forkify-alamin.netlify.app/" target="_blank">
    <img alt="Demo" src="https://img.shields.io/badge/demo-online-green.svg" />
  </a>
  <a href="https://github.com/CarlesCoding/Forkify#readme" target="_blank">
    <img alt="Documentation" src="https://img.shields.io/badge/documentation-yes-brightgreen.svg" />
  </a>
  <a href="https://github.com/CarlesCoding/Forkify/graphs/commit-activity" target="_blank">
    <img alt="Maintenance" src="https://img.shields.io/badge/maintained-yes-green.svg" />
  </a>
  <a href="https://github.com/CarlesCoding/Forkify/blob/main/LICENSE.md" target="_blank">
    <img alt="License: MIT" src="https://img.shields.io/badge/License-MIT-yellow.svg" />
  </a>
</p>

<h2 align="center">
Check out the <a href="https://forkify-beefy.netlify.app/" target="_blank">live Forkify App here</a>.
</h2>
<p align="left">
Forkify is a recipe search and saving application designed with HTML5, CSS3, and JavaScript. It boasts a user-friendly interface and allows for dynamic adjustments to serving sizes. The app leverages advanced JavaScript techniques, including asynchronous programming, ES6 modules, and object-oriented programming. Developed by Jonas Schmedtmann as part of his Udemy course, I created this app as a personal project to enhance my JavaScript skills.
</p>

<!-- Features -->

## Features

- Search for recipes: Find recipes using keywords or ingredients.
- View recipe details: See ingredients, cooking instructions, and serving size.
- Bookmark recipes: Save your favorite recipes for later.
- Add recipes: Create and share your own recipes.
- Pagination: Easily navigate search results.
- Responsive Design

<!-- Images -->

## Example Images
![forkify2](https://github.com/user-attachments/assets/778f5676-37b7-4a88-b911-37e772234579)
![forkify1](https://github.com/user-attachments/assets/acd03459-005e-4d47-aa80-54f97df2092e)

<!-- GETTING STARTED -->

## Getting Started

### Prerequisites

You will need Node and Npm preinstalled before running the program.

- node >= 18
- npm

  ```sh
  npm install npm@latest -g
  ```

You will need an API key to fetch recipe data from an external source.

- [Get API key](https://forkify-api.herokuapp.com/v2) from the Forkify Docs

### Installation

1. Clone the repository and navigate to it

   ```sh
   git clone https://github.com/Beefymuffins/Forkify.git
   ```

2. Navigate to the folder
   ```sh
   cd Forkify
   ```
3. Install NPM packages

   ```sh
   npm install
   ```

4. Add your API key to the config.js file

   ```javascript
   const API_KEY = '';
   ```

5. Start the development environment

   ```sh
    npm run start
   ```

<!-- API Examples -->

## API Example

**Get all recipes/Create recipe**

Example URL: https://forkify-api.herokuapp.com/api/v2/recipes?search=pizza&key=<insert your key>

```plaintext
Allowed methods: GET POST

GET: Returns a list of recipes for a specific search query

POST: Creates a new recipe
```

### Parameters

<div style="border: 1px solid #ddd; padding: 10px; border-radius: 5px; background-color: #; margin-bottom: 20px;">
  <table>
    <thead>
      <tr>
        <th>Parameter</th>
        <th>Required</th>
        <th>Description</th>
      </tr>
    </thead>
    <tbody>
      <tr>
        <td>search</td>
        <td>Yes</td>
        <td>Search text. For example search=pizza</td>
      </tr>
      <tr>
        <td>key</td>
        <td>Yes (for POST)</td>
        <td>The ForkifyAPI key</td>
      </tr>
    </tbody>
  </table>
</div>

For more examples, please refer to the <a href="https://forkify-api.herokuapp.com/v2" target="_blank">Documentation</a>

<!-- Tech Stack -->

## Built With

- JavaScript
- CSS3
- HTML5
- Parcel
- NPM

<!-- CONTACT -->

## Contact

👤 Austin Carles

- Linkedin: [@carlescoding](https://www.linkedin.com/in/carlescoding/)
- Github: [@Beefymuffins](https://github.com/CarlesCoding)

Project Link: [https://github.com/Beefymuffins/Forkify](https://github.com/CarlesCoding/Forkify)

<!-- Acknowledgments  -->

## Credits

This app was created as part of [Jonas Schmedtmann's](https://x.com/jonasschmedtman) Udemy course [The Complete JavaScript Course 2023: From Zero to Expert!.](https://www.udemy.com/course/the-complete-javascript-course/?couponCode=ST3MT72524)

Special thanks to Jonas for his excellent teaching and guidance throughout the course.

<!-- LICENSE -->

## License

Distributed under the [MIT](https://github.com/Beefymuffins/Forkify-Recipe-App/blob/main/LICENSE) License.
