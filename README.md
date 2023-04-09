# pokefarm-custom-css
A collection of custom CSS rulesheets for PokéFarm Q

## aboutme-pokepanel-template.css
CSS I use for my About section. Turns default interactive pokepanels (`[pkmnpanel=XXXXX]`) into compact buttons (fits 3 per line). Wrap everything in `[center]` tags for tigher vertical spacing, use unordered lists for text.

![image](https://user-images.githubusercontent.com/720348/230773819-5de31c90-b675-4649-9a84-18ff53b53e1c.png)

## egg-labels.css
Reveals the names of eggs (even unhatched ones) in Lab, Party, Shelter and Daycare (requires SpyGlass).

***Only fully tested and supported in Chrome!***

Notably, this is an experimental feature in Firefox and requires [enabling the `:has` selector flag](https://stackoverflow.com/questions/73936048/how-do-you-enable-has-selector-on-firefox). Even then, in Firefox the Lab labels don't seem to work properly, but the other labels should.

![image](https://user-images.githubusercontent.com/720348/230773749-52e48afa-8491-468d-a09f-a10ed0d4d634.png)

![image](https://user-images.githubusercontent.com/720348/230773697-ef319af8-19d6-4309-81a8-7fe1405f9ddd.png)

## field-tweaks.css
A collection of Field tweaks designed to work alongside the [QoL](https://pokefarm.com/farm#tab=5.6) "Sort by berries" setting. Repositions and enlarges the correct berry recipients and truncates long field names to enable mass clicking without ever moving the mouse (can still view full field name by hovering the mouse cursor over it). Also makes the fed/unfed counter more visible.

## lab-daycare-tweaks.css
Assorted minor tweaks such as: hide the option to use Lab Reloaders, highlight Lab Reload button when ready, highlight shelter area when QoL has found eggs, hide own profile notification from multi-profile view.

## party-big-buttons.css
Places a ***massive*** button on the bottom of the screen to easily click through whole parties in single and multi view. Works with or without QoL.

![image](https://user-images.githubusercontent.com/720348/230774093-ccbb2db0-4e60-450f-bda0-638504b8a8ac.png)
