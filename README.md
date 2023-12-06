# Terminal Homepage

The idea behind this homepage is to have the appearance of a terminal using the   [Dracula Theme](https://github.com/dracula/dracula-theme)
 
## How to Use
 
1. Clone this project using `git@github.com:eliveltonsales/homepage-terminal.git`.
2. Add your links to the 'links.json' file.
	1. group: Title of the link group.
	2. label: Visible link text on the homepage.
	3. url: The link's destination.
3. Add weather information to the 'script.js' file.
	1. Obtain an API key from [OpenWeatherMap](https://openweathermap.org/)
	2. Add your latitude and longitude information.
4. Set the 'index.html' file as the homepage in your preferred browser.

## Files

```

└───terminal-homepage
     └───example.png | Demonstrates how the homepage looks
     └───index.html  | The homepage
     └───links.json  | List where you put your links
     └───README.md   | What you're reading right now
     └───script.js   | Functions to load the links, the time and the temperature
     └───style.css   | The appearance

```
