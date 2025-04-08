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
