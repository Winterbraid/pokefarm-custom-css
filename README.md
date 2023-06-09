# pokefarm-custom-css
A collection of custom CSS rulesheets for PokéFarm Q

## aboutme-pokepanel-template.css
CSS I use for my About section. Turns default interactive pokepanels (`[pkmnpanel=XXXXX]`) into compact buttons (fits 3 per line). Wrap everything in `[center]` tags for tigher vertical spacing, use unordered lists for text.

![image](https://user-images.githubusercontent.com/720348/230773819-5de31c90-b675-4649-9a84-18ff53b53e1c.png)

## egg-labels.css
Reveals the names of eggs (even previously unhatched ones) in Lab, Party, Shelter and Daycare (requires SpyGlass). **This is a very long file** as it aims to contain every possible egg sprite filename and name, so make sure to copy and paste everything from start to finish!

***Only fully tested and supported in Chrome!***

Notably, this is an experimental feature in Firefox and requires [enabling the `:has` selector flag](https://stackoverflow.com/questions/73936048/how-do-you-enable-has-selector-on-firefox). Even then, in Firefox the Lab labels don't seem to work properly, but the other labels should.

![image](https://user-images.githubusercontent.com/720348/230774149-47490ab4-8d09-484f-aeea-c0f14f4280c9.png)

![image](https://user-images.githubusercontent.com/720348/230773697-ef319af8-19d6-4309-81a8-7fe1405f9ddd.png)
