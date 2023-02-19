# FFF | Farming for the future | Strapi API

This is Strapi API created to serve data related to the Farming for the future (FFF) project.

The following endpoints are available:

- `https://fff-api.onrender.com/api/articles` will show a list of all articles.
- `https://fff-api.onrender.com/api/articles/2` will show an individual article based on its ID number.
- `https://fff-api.onrender.com/api/articles/populate=coverImage,imageGallery` will show all media content related to each entry.
- `https://fff-api.onrender.com/api/articles?fields=title` will only fetch the titles of the respective items included in the articles array. Any other property can be included in the `fields` parameter.
- `http://localhost:1337/api/articles?fields=publishedAt&sort=publishedAt:desc` will filter the entries based on their publishing date. Both `asc` and `desc` can be used, meaning "ascendant" and "descendant" order.
