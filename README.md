 ```
# Movie App

This is a simple movie web page that allows users to search for movies and see their details.

## How to use

1. Clone the repo.
2. Install the dependencies.
3. Run the page.
4. Open the web page in your browser.
5. Search for a movie.
6. Click on a movie to see its details.

## Code snippets

Here are some code snippets from the page:

```html
<!DOCTYPE html>
<html lang="en">
  <head>
    <link rel="stylesheet" href="movie.css" />
    <title>Movie App</title>
  </head>
  <body>
    <header>
      <form id="form">
        <input type="text" id="search" class="search" placeholder="Search" />
      </form>
    </header>

    <main id="main"></main>

    <script src="movie.js"></script>
  </body>
</html>
```

```css
:root {
  --primary-color: #22254b;
  --secondary-color: #373b69;
}

* {
  box-sizing: border-box;
}

body {
  background-color: var(--primary-color);
  font-family: 'Poppins', sans-serif;
  margin: 0;
}

header {
  padding: 1rem;
  display: flex;
  justify-content: flex-end;
  background-color: var(--secondary-color);
}

.search {
  background-color: transparent;
  border: 2px solid var(--primary-color);
  border-radius: 50px;
  font-family: inherit;
  font-size: 1rem;
  padding: 0.5rem 1rem;
  color: #fff;
}

.search::placeholder {
  color: #7378c5;
}

.search:focus {
  outline: none;
  background-color: var(--primary-color);
}

main {
  display: flex;
  flex-wrap: wrap;
  justify-content: center;
}



