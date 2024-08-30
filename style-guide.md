<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">

  <link rel="icon" type="image/png" sizes="32x32" href="./assets/images/favicon-32x32.png">
  
  <title>Frontend Mentor | Recipe page</title>

  <link rel="stylesheet" href="styles.css">

  <style>
    @font-face {
      font-family: "Young Serif";
      src: url("/recipe-page-main/assets/fonts/young-serif/YoungSerif-Regular.ttf");
    }

    body {
      font-family: "Young Serif", serif;
    }

    h1, h2, h3 {
      font-family: "Young Serif", serif; 
    }

    .bold {
      font-weight: bold;
    }

    table {
      width: 100%;
      border-collapse: collapse;
      margin: 20px 0;
    }

    table, th, td {
      border: 1px solid #ddd;
    }

    th, td {
      padding: 8px;
      text-align: left;
    }

    th {
      background-color: #f4f4f4;
    }

    .measurements {
      text-align: right;
    }

    .container {
      width: 90%;
      max-width: 600px;
      padding: 20px;
      background-color: #f8f8f8;
      border-radius: 8px;
      box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
      text-align: center;
      margin-top: 50px; /* Adjust space from the top */
    }

    .container img {
      max-width: 85%;
      height: auto;
      border-radius: 8px;
      margin-bottom: 20px;
    }

    h1, h2 {
      margin-top: 0;
      color: #333;
    }

    p, ul, ol {
      text-align: left;
      margin: 0 auto;
      max-width: 800px;
      font-size: 16px;
    }

    ul, ol {
      padding-left: 20px;
    }

    .attribution {
      font-size: 11px;
      text-align: center;
      margin-top: 20px;
    }

    .attribution a {
      color: hsl(228, 45%, 44%);
      text-decoration: none;
    }

    .attribution a:hover {
      text-decoration: underline;
    }
  </style>
</head>
<body>

  <main class="container">
    <img src="assets/images/image-omelette.jpeg" alt="Omelette Image">

    <h1>Simple Omelette Recipe</h1>

    <p>An easy and quick dish, perfect for any meal. This classic omelette combines beaten eggs cooked 
    to perfection, optionally filled with your choice of cheese, vegetables, or meats.</p>

    <div class="prep-time">
      <h3>Preparation time</h3>

      <ul>
        <li><span class="bold">Total</span>: Approximately 10 minutes</li>
        <li><span class="bold">Preparation</span>: 5 minutes</li>
        <li><span class="bold">Cooking</span>: 5 minutes</li>
      </ul>
    </div>

    <h2>Ingredients</h2>

    <ul>
      <li>2-3 large eggs</li>
      <li>Salt, to taste</li>
      <li>Pepper, to taste</li>
      <li>1 tablespoon of butter or oil</li>
      <li>Optional fillings: cheese, diced vegetables, cooked meats, herbs</li>
    </ul>

    <h2>Instructions</h2>

    <ol>
      <li><span class="bold">Beat the eggs</span>: In a bowl, beat the eggs with a pinch of salt and pepper until they are well mixed. You can add a tablespoon of water or milk for a fluffier texture.</li>

      <li><span class="bold">Heat the pan</span>: Place a non-stick frying pan over medium heat and add butter or oil.</li>

      <li><span class="bold">Cook the omelette</span>: Once the butter is melted and bubbling, pour in the eggs. Tilt the pan to ensure 
        the eggs evenly coat the surface.</li>

      <li><span class="bold">Add fillings (optional)</span>: When the eggs begin to set at the edges but are still slightly runny in the 
        middle, sprinkle your chosen fillings over one half of the omelette.</li>

      <li><span class="bold">Fold and serve</span>: As the omelette continues to cook, carefully lift one edge and fold it over the 
        fillings. Let it cook for another minute, then slide it onto a plate.</li>

      <li><span class="bold">Enjoy</span>: Serve hot, with additional salt and pepper if needed.</li>
    </ol>

    <h2>Nutrition</h2>

    <p>The table below shows nutritional values per serving without the additional fillings.</p>

    <table>
      <tr>
        <td>Calories</td>
        <td class="measurements">277 kcal</td>
      </tr>

      <tr>
        <td>Carbs</td>
        <td class="measurements">0 g</td>
      </tr>

      <tr>
        <td>Protein</td>
        <td class="measurements">20 g</td>
      </tr>

      <tr>
        <td>Fat</td>
        <td class="measurements">22 g</td>
      </tr>
    </table>
  </main>
  
  <footer>
    <div class="attribution">
      <p>Challenge by <a href="https://www.frontendmentor.io?ref=challenge" target="_blank">Frontend Mentor</a>.</p>
      <p>Coded by <a href="https://github.com/uriartegui">Guilherme Uriarte</a>.</p>
    </div>
  </footer>
</body>
</html>
