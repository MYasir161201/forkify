# forkify
Forkify is a recipe web app using the Forkify API to allow users to search, view, modify, bookmark and add recipes.

### Technologies

HTML - SCSS - JS - Netlify

### Libraries

Parcel, Sass

```sh
   npm i -D parcel@next sass
```


### Features

* Pagination
* Query an ingredient to recieve a list of recipes containing that ingredient.
* Easily bookmark or edit the servings of the selected recipe.
* Create your own recipes and store them as user recipes.
* Remove bookmarks or delete user recipes.
* LocalStorage keeps the data when users exit the app.


### Project Architecture

Built using the MVC Architecture. View class extends the rest of the components. Controller keeps bidirectional dataflow. SCSS files are divided for major components.
![forkify-architecture-recipe-loading](https://user-images.githubusercontent.com/100485656/234034236-a7d9e28c-3ce2-40df-8987-788ec396926f.png)
