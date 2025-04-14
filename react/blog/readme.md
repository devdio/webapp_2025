# react blog

### Blog Data
```
const [blogs, setBlogs] = useState([
{
      "title": "Mickey 17",
      "body": "Mickey 17, known as an expendable,goes on a dangerous...",
      "author": "Bong Joon Ho",
      "id": "2"
    },
    {
      "title": "The Monkey",
      "body": "When twin brothers Bill and Hal find their ...",
      "author": "Osgood Perkins",
      "id": "3"
    },
    {
      "title": "Gisaengchung",
      "body": "Greed and class discrimination threaten the newly ...",
      "author": "Bong Joon Ho",
      "id": "4"
    }
]);
```
### db.json
```
{
    "blogs": [
        {
            "title": "Mickey 17",
            "body": "Mickey 17, known as an expendable,goes on a dangerous...",
            "author": "Bong Joon Ho",
            "id": "2"
        },
        {
            "title": "The Monkey",
            "body": "When twin brothers Bill and Hal find their ...",
            "author": "Osgood Perkins",
            "id": "3"
        },
        {
            "title": "Gisaengchung",
            "body": "Greed and class discrimination threaten the newly ...",
            "author": "Bong Joon Ho",
            "id": "4"
        }
    ]
}
```
## run json server
```
npx json-server --watch data/db.json --port 8000
```
