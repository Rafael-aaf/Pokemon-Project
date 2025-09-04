# Pokemon Project
Hello! A few days ago I watched [this youtube video](https://www.youtube.com/watch?v=JVQNywo4AbU), where the guy used a Pokémon API to get some information about a pokémon, and I thought it would be fun to try it out and make my own app. I wanted to retrieve some info depending on the input of the user, and make an interface where it would display the info and change the color according to the pokémon.

About the libraries, I used requests for the api, and pillow for the images. I also used Tkinter for the interface, and it's very simple, it has an input text box, a button and some labels that have the info.

Lastly, I divided the codes in two modules, pokemon.py and frontend.py, so it's easier to read and understand the codes.

## Features
- Displays information on a certain pokémon
- Changes the background color
- If a pokémon is not found, it displays an error message

## Technologies Used
- Python
- Tkinter
- PokéAPI
- Requests
- Pillow

## User Interface
Here are some screenshots of the app working!

![Pikachu!](https://github.com/Rafael-aaf/Pokemon-Project/blob/42e447521e04dda178399d94b4df554ed7b6f859/screenshots/pokemon_api_pikachu.jpg)

![Glaceon!!!](https://github.com/Rafael-aaf/Pokemon-Project/blob/42e447521e04dda178399d94b4df554ed7b6f859/screenshots/pokemon_api_glaceon.jpg)

![Mew!](https://github.com/Rafael-aaf/Pokemon-Project/blob/42e447521e04dda178399d94b4df554ed7b6f859/screenshots/pokemon_api_mew.jpg)

A small issue that appeared was when a pokémon had a primary color of black. The text is in black, so if the background was also in black the text wouldn't be readable! For that case, I made the color white for all the pokémon with a black primary color.

![Umbreon!](https://github.com/Rafael-aaf/Pokemon-Project/blob/42e447521e04dda178399d94b4df554ed7b6f859/screenshots/pokemon_api_umbreon.jpg)


## What I learned
This is my second project using Tkinter, so now I understand and use it way better. I also learned how to implement an API with the Requests library and how modules work on Python.
This was a very fun project to work on! Thanks for reading and see you!
