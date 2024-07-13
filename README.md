# MaybeBetterSleek
A fork of [Sleek](https://github.com/spicetify/spicetify-themes/tree/master/Sleek) that should give slightly more customizability.

## Screenshots
#### Samurized
| ![image](./images/samurized_home.png)         | ![image](./images/samurized_album.png)          | ![image](./images/samurized_playlist.png)         |
| :-------------------------------------------: | :---------------------------------------------: | :-----------------------------------------------: |
|                     home                      |                      album                      |                     playlist                      |
| ![image](./images/samurized_podcast.png)      | ![image](./images/samurized_profile.png)        | ![image](./images/samurized_lyricsplus.png)       |
|                    podcast                    |                     profile                     |                    lyrics plus                    |

#### Nord
| ![image](./images/nord_home.png)              | ![image](./images/nord_album.png)               | ![image](./images/nord_playlist.png)              |
| :-------------------------------------------: | :---------------------------------------------: | :-----------------------------------------------: |
|                     home                      |                      album                      |                     playlist                      |
| ![image](./images/nord_podcast.png)           | ![image](./images/nord_profile.png)             | ![image](./images/nord_lyricsplus.png)            |
|                    podcast                    |                     profile                     |                    lyrics plus                    |

#### Dracula
| ![image](./images/dracula_home.png)           | ![image](./images/dracula_album.png)            | ![image](./images/dracula_playlist.png)           |
| :-------------------------------------------: | :---------------------------------------------: | :-----------------------------------------------: |
|                     home                      |                      album                      |                     playlist                      |
| ![image](./images/dracula_podcast.png)        | ![image](./images/dracula_profile.png)          | ![image](./images/dracula_lyricsplus.png)         |
|                    podcast                    |                     profile                     |                    lyrics plus                    |

#### Rosé Pine
| ![image](./images/rosepine_home.png)          | ![image](./images/rosepine_album.png)           | ![image](./images/rosepine_playlist.png)          |
| :-------------------------------------------: | :---------------------------------------------: | :-----------------------------------------------: |
|                     home                      |                      album                      |                     playlist                      |
| ![image](./images/rosepine_podcast.png)       | ![image](./images/rosepine_profile.png)         | ![image](./images/rosepine_lyricsplus.png)        |
|                    podcast                    |                     profile                     |                    lyrics plus                    |

## Manual Install
Create a folder in Spicetify themes path and add `user.css` and `color.ini` to it. <br/>
On windows, the path usually is `%APPDATA%/spicetify/Themes`.<br/>
If you're on Linux, I assume you can find out the path by yourself.

To apply:
```
spicetify config current_theme [name of folder in themes dir] color_scheme Samurized
```

To change the color scheme:
```
spicetiy config color_scheme [name of color scheme]
```

#### NOTE:
Just a quick note because I only found the solution in a reddit thread and wanted to make it more accessible. </br>
If you want the queue to be displayed on the sidepanel, you can enable `Enable queue on the right panel` in the `Experimental Features` tab.
