# MMM-inspirobot
Magic Mirror Module that pulls in inspirobot inspirational posters

This an extension for the [MagicMirror](https://github.com/MichMich/MagicMirror). It will display adubiously inspirational picture, generated from an AI at inspirobot.com

## Installation
1. Navigate into your MagicMirror's `modules` folder and execute `git clone https://github.com/JonathanAndersonPE/MMM-inspirobot`.

## Using the module

To use this module, add it to the modules array in the `config/config.js` file:
````javascript
modules: [
	{
		module: 'MMM-inspirobot',
		position: 'top_left',	// this can be any of the MM standard module positions
		config: {
            		updateInterval : 120 * 1000, // update time in milleseconds of new inspirational image
			}
	}
]
