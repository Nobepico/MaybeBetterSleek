# MaybeBetterSleek
A fork of [Sleek](https://github.com/spicetify/spicetify-themes/tree/master/Sleek) that should give slightly more customizability.

Added a new scheme based on Samurai and Solarized.<br/>
Besides the new scheme, the others were removed as they wouldn't fit the changes to `user.css` without tampering.

## Screenshots
#### Samurized
|   ![image](https://github.com/Nobepico/MaybeBetterSleek/assets/133757705/1f6e1c0e-975d-473c-a50c-80013b29c1e8)   |   ![image](https://github.com/Nobepico/MaybeBetterSleek/assets/133757705/776255ce-c310-46f9-b7ec-24adfd2f2156)   | ![image](https://github.com/Nobepico/MaybeBetterSleek/assets/133757705/69d9d15c-8b94-47f8-a09d-a06529317fff) |
| :-------------------------------------------: | :---------------------------------------------: | :-----------------------------------------------: |
|                     home                      |                      album                      |                     playlist                      |
| ![image](https://github.com/Nobepico/MaybeBetterSleek/assets/133757705/861c8940-acf5-4e3c-aec3-1774d892e0b7) | ![image](https://github.com/Nobepico/MaybeBetterSleek/assets/133757705/54dbde84-3d45-4f22-8d29-d32f91f4cad7) |      ![image](https://github.com/Nobepico/MaybeBetterSleek/assets/133757705/e3b9b46f-e040-4259-bc98-d60e8b91330b)      |
|                    podcast                    |                     profile                     |                    lyrics plus                    |

## Manual Install
Create a folder in Spicetify themes path and add `user.css` and `color.ini` to it. <br/>
On windows, the path usually is `%APPDATA%/spicetify/Themes`.<br/>
If you're on Linux, I assume you can find out the path by yourself.

To apply:
```
spicetify config current_theme [NAME OF FOLDER IN THEMES] color_scheme Samurized
```
