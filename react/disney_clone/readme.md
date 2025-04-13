# Disney CLone

## Header.jsx
```js
import { HiHome,
    HiMagnifyingGlass,
    HiStar,
    HiPlayCircle,
    HiTv } from "react-icons/hi2";
import { HiPlus,HiDotsVertical } from "react-icons/hi";
```
- menu
```
const menu = [
    {
        name: "HOME",
        icon: HiHome,
    },
    {
        name: "SEARCH",
        icon: HiMagnifyingGlass,
    },
    {
        name: "WATCH LIST",
        icon: HiPlus,
    },
    {
        name: "ORIGINALS",
        icon: HiStar,
    },
    {
        name: "MOVIES",
        icon: HiPlayCircle,
    },
    {
        name: "SERIES",
        icon: HiTv,
    },
];
```
- API
```
https://api.themoviedb.org/3/movie/550?api_key={}
https://api.themoviedb.org/3/genre/movie/list?language=en&api_key={}
```
- Image base url
```
const IMAGE_BASE_URL = "https://image.tmdb.org/t/p/original";
```
- import png and mp4
```js
import disney from "../assets/images/disney.png";
import marvel from "../assets/images/marvel.png";
import nationalG from "../assets/images/nationalG.png";
import pixar from "../assets/images/pixar.png";
import starwar from "../assets/images/starwar.png";

import starwarV from "../assets/images/star-wars.mp4";
import disneyV from "../assets/images/disney.mp4";
import marvelV from "../assets/images/marvel.mp4";
import nationalGeographicV from "../assets/images/national-geographic.mp4";
import pixarV from "../assets/images/pixar.mp4";
```

- Genre List
```js
const genere = [
  {
    id: 28,
    name: "Action",
  },
  {
    id: 12,
    name: "Adventure",
  },
  {
    id: 16,
    name: "Animation",
  },
  {
    id: 35,
    name: "Comedy",
  },
  {
    id: 80,
    name: "Crime",
  },
  {
    id: 99,
    name: "Documentary",
  },
  {
    id: 18,
    name: "Drama",
  },
  {
    id: 10751,
    name: "Family",
  },
  {
    id: 14,
    name: "Fantasy",
  },
  {
    id: 36,
    name: "History",
  },
  {
    id: 27,
    name: "Horror",
  },
  {
    id: 10402,
    name: "Music",
  },
  {
    id: 9648,
    name: "Mystery",
  },
  {
    id: 10749,
    name: "Romance",
  },
  {
    id: 878,
    name: "Science Fiction",
  },
  {
    id: 10770,
    name: "TV Movie",
  },
  {
    id: 53,
    name: "Thriller",
  },
  {
    id: 10752,
    name: "War",
  },
  {
    id: 37,
    name: "Western",
  },
];

export default {
  genere,
};

```
