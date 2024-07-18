# Micro front end with angular and module federation

### *Introduction*

This project is a simple demo of how to use angular micro frontend apps with webpack@5 module deferation and BroadcastChannel as a data transfer tool.

the project contains 3 applications:
* Products `(remote) run at 4201`
* search-bar  `(remote) run at 4202`
* shell  `(host) run at 4200`

#### *Products app provide:*
* The list of products based on selected category.
* Filter the list of products based on the search value `search applied on product.title`

#### *seach-bar app provides:*
* The category menu (list of all categories).
* Search input.

shell app is the host of those mfe and provide the navbar.


### *Set up*

After cloning the repo and submodules

- run `npm install` all three applications.
- run `ng serve` all three applications.
