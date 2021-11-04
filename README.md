Welcome to my first full-stack vanilla JavaScript project  - a trip finder!

My app lets you look for trips by type and area and to create new ones. It was a very fun project to build because I had to create my own API with Ruby and Rails and use JavaScript to display the API data. All interactions between the client and the server are handled asynchronously and JSON is used as the communication format.

Here is a quick overview of the architecture of this application:

My app has five models – Trip, Area, Type, Hotel and Attraction. Trip has many Attractions and Hotels and belongs to Type and Area. Attraction and Hotel belong to Trip. Area and Type have many Trips. My HTML file has two forms – one for searching for a trip and one for creating one. Both forms have two dropdowns – one for area and one for type which are models in my project. I render Types and Areas by making a fetch request to the model's index action what lets me grab all of the instances and dynamically display them.
