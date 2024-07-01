# **Daria Yurko**

Junior Frontend developer

<img width="250px" src="./avatar.jpg" alt="my photo"/>

## About me

Front-End developer with knowledge of HTML, CSS, JavaScript, understanding Linux
operating systems and database management MySQL. Ambitious, highly responsible and goal-oriented person.

## Education

**Kryvyi Rih Technical University** <br>
Information technologies <br>
2005 - 2010

## Skills

- JavaScript
- REST API
- HTML, CSS
- GIT
- Oracle Linux
- MySQL

## Language

- English - Intermediate
- Ukrainian - Native
- Russian - Native

## Contacts

- E-Mail - dariayurkodev@gmail.com
- Linkedin - [Daria Yurko](https://linkedin.com/in/daria-yurko-270788248)
- Github - [DariaYurko](https://github.com/DariaYurko)
- Discort - Daria (@DariaYurko)

## Experience

1. Education center PortaOne - _Linux & Network Administration 2023_ course

2. Kottans - _Front-End 2022_ course

3. Goit - _Fullstack (in process)_

## Projects

- kottans-dom
  https://dariayurko.github.io/kottans-dom/

- handmade-chocolate
  https://dariayurko.github.io/handmade-chocolate/

- picture-finder
  https://dariayurko.github.io/picture-finder/

## Сode example

An example of using the service Pixabay API for project [picture-finder](https://dariayurko.github.io/picture-finder/) :

```javascript
import axios from "axios";

async function sendQuery(imageName, pageNumber) {
  axios.defaults.baseURL = "https://pixabay.com";

  const params = {
    key: "44349742-ecc8a7b60aea5585f0c207813",
    q: imageName,
    image_type: "photo",
    orientation: "horizontal",
    safesearch: true,
    per_page: perPage,
    page: pageNumber,
  };

  try {
    const response = await axios.get("/api/", { params });
    return response.data;
  } catch (err) {
    console.log(err);
  }
}
```
