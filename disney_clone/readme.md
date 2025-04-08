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
