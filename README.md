<p align="center">
    <p align="center">
    <h1 align="center">Google Image SR
    <h5 align="center">Easy & Beginner friendly google-images scraper made with ❤️ and typescript.
</p>
</p>
<p align="center">
<a href="https://github.com/TrishCX/Pinterest-Scraper" target="_blank">
    <img src="http://forthebadge.com/images/badges/built-with-love.svg"/>
  </a>
</p>

  <p align="center">
<p align="center">
  <a href="https://github.com/TrishCX/Frix" target="_blank">
    <img src="https://img.shields.io/npm/v/@myno_21/imdb-scraper.svg" alt="Build Status">
  </a>
  <a href="https://github.com/TrishCX/Pinterest-Scraper" target="_blank">
    <img src="https://img.shields.io/badge/License-Boost_1.0-lightblue.svg" alt="Codecov" />
  </a>
  <a href="https://github.com/TrishCX/Frix" target="_blank">
    <img src="https://img.shields.io/badge/License-ISC-blue.svg" alt="License">
  </a>
  
</p>

<p align="center">
  <a href="https://www.npmjs.com/package/@myno_21/pinterest-scraper" target="_blank">
    <img src="https://img.shields.io/npm/dt/@myno_21/imdb-scraper.svg" />
  </a>
  
</p>

# 🔗 Prerequisites

- NodeJS 16 +

# ❔Installation

```console
$ npm install google-image-sr
```

## Import

```typescript
import search from "google-image-sr";
```

## Example

```ts
import search from "google-image-sr";
(async () => {
  const movieId = "tt0816692";
  const response = await client.getMovie(movieId);
  console.log(response);
})(); // Anonymous arrow function.
```

## Output

```ts
{
  title: 'Interstellar',
  imageURL: 'https://m.media-amazon.com/images/M/MV5BZjdkOTU3MDktN2IxOS00OGEyLWFmMjktY2FiMmZkNWIyODZiXkEyXkFqcGdeQXVyMTMxODk2OTU@._V1_.jpg',
  description: "A team of explorers travel through a wormhole in space in an attempt to ensure humanity's survival.",
  releaseDate: '7th December, 2014',
  runtime: '2h 49m',
  imdbRating: 8.6,
  popularity: '73',
  genres: [ 'Adventure', 'Drama', 'Sci-Fi' ],
  reviews: '5.3k'
}
```

# 🔗 Links

- [Github](https://github.com/TrishCX)
- [Repository](https://github.com/TrishCX/Imdb-Scraper)
