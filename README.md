# sinatra-snack-attack
Sinatra app to refresh skills in that area. Combo of Sinatra and Active Record.
Will list Countries and Cities, as well as foods that are distinct to that country. So for example - Japan - Osaka - Okonomiyaki. Could also go further into it and see specific foods for each city

Country has many cities
City belongs_to country
Food belongs to a city. Food name entries must be unique, however there can be variations (ex Green Tea Soba or Izumo Soba )

Users can sign up and add foods to given cities
