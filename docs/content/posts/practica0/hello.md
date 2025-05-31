<!-- Headings -->

# mi title h1
## mi title h2
### mi title h3
#### mi title h4
##### mi title h5
###### mi title h6 

<!-- italic -->
this is an *italic* text

<!-- strong -->
this is an **strong** text

<!-- strikethrough -->
este es un ~~texto~~ tachado

<!-- UL -->
* apple
    * apple 2
* orange
    * asdasds
* etc

1. apple
    * apple2
2. orange
3. etc

[faztweb.com](https://www.faztweb.com)

[faztweb.com](https://www.faztweb.com "Custom title")

> this is a quote
---
___
`
console.log('hello world')`
``` javascript
import mongoose from "mongoose";
import { MONGODB_URI } from "./config.js";

try {
  const db = await mongoose.connect(MONGODB_URI);
  console.log("Connected to ", db.connection.name);
} catch (error) {
  console.error(error);
}

mongoose.connection.on("connected", () => {
  console.log("Mongoose is connected");
});

mongoose.connection.on("disconnected", () => {
  console.log("Mongoose is disconnected");
});
```
```python
print("hello world")
```
```html
<h1>hello world</h1>
```

| Tables       | Are           | Cool  |
|--------------|:-------------:|------:|
| col 3 is     | right-aligned | $1600 |
| col 2 is     | centered      |   $12 |
| zebra stripes| are neat      |    $1 |

![visual studio code logo](https://imgs.search.brave.com/oQDgpm8Dje9aowjkeRCoBBFZCx64xhHivZF6pUgRZ6c/rs:fit:860:0:0:0/g:ce/aHR0cHM6Ly91c2Vy/LWltYWdlcy5naXRo/dWJ1c2VyY29udGVu/dC5jb20vNjc0NjIx/LzcxMTg3ODAxLTE0/ZTYwYTgwLTIyODAt/MTFlYS05NGM5LWU1/NjU3NmY3NmJhZi5w/bmc)

![visual studio code logo](vscode.png "vscode logo")

<!--- GITHUB MARKDOWN --->
* [x] task 1
* [ ] task 2
* [ ] task 3
* [x] task 4

@faztweb :smiley:  :+1: