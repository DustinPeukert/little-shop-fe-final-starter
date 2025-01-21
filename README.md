# Hang in There  
Github: https://github.com/DustinPeukert
LinkedIn: www.linkedin.com/in/dustin-peukert

### Abstract:
This application allows a user to see a list of merchants, as well as items that the merchants sell. It also provides a list of coupons for each merchant.

### Installation Instructions:
Fork and clone this repo down to your system. Then fork the BE repo at this link separately! Do not nest these repos.
https://github.com/DustinPeukert/little-shop-be-final-starter

Run `npm install` in this repo. Then run `npm run dev`.
Once that is done move to the BE repo and run `bundle install`. Then run `rails s`.

### Preview of App:
![Coupon Page](/Users/dustinpeukert/Pictures)

### Context:
Time frame: ~5 days

Contributions:
- Created coupons table as well as updated invoices table
- Wrote CRUD functions in MVC formatting for coupons
- Pulled coupon data from BE into FE
- Turned raw coupon data into html
- Styled new html additions


### Learning Goals:
- Write migrations to create tables and relationships between tables
- Implement CRUD functionality for a resource
- Use MVC to organize code effectively, limiting the amount of logic included in serializers and controllers
- Use built-in ActiveRecord methods to join tables of data, make calculations, and group data based on one or more attributes
- Write model tests that fully cover the data logic of the application
- Write request tests that fully cover the functionality of the application
- Display data for users in a frontend application by targeting DOM elements

Techs used:
- Ruby
- Rails
- Vite
- Javascript
- HTML
- CSS

### Wins + Challenges:
Win: Successfully kept to MVC format (to my knowledge)

Win: Successfully handled conversion of raw coupon JSON into HTML for use in web page.

Challenge: I was struggling to figure out how to RESTfully create the activate/deactivate endpoint.

Solution: Started by making them into unrestful, non-mvc endpoints. then refactored after project completion. This gave me a better understanding of how things worked and options for implementation.
