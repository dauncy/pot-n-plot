**Pot-n-Plot**

Pot-n-plot is a pure Ruby on Rails web app for virtual gardening. Data for over 400 species of plants was collected from the  trefle.io API and stored in the database using postgresql.

Checkout the live site at [pot-n-plot](https://pot-n-plot.herokuapp.com/)

What can a user do?
- Login or signup and visit his/her profilfe page, add/remove friends, & see his/her gardens. 
- Search for plants on the plant index page, or by using the search bar. 
- Visit plant pages to see data specific to each species. 
- Design gardens and add/remove plants from those gardens.

***Languages and Technologies Used***
- Frontend and Backend set up using pure Ruby on Rails with postgreql to persist user-data to the databse.
- HTML and CSS for styling. 
- trefle.io API for collecting plant data. 
- RestClient and JSON Ruby gems implemented to parse the API JSON data and seed the database with various plant species.
- Bcrypt Ruby gem used for secure passwords.
- Cookies and sessions implemented for server-side authorization & authentication.



