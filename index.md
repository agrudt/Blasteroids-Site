# Blasteroids
Blasteroids is a game where you control a spaceship and defend a planet from falling asteroids. Inspired by classic arcade games such as Space Invaders and Galaga, you move left and right while firing lasers at a never-ending flow of asteroids. Getting a higher score gives you powerups, but it also increasing the difficulty, so look out!


You can use the [editor on GitHub](https://github.com/agrudt/Blasteroids-Site/edit/gh-pages/index.md) to maintain and preview the content for your website in Markdown files.
[Play Blasteroids Here!](https://srma-uwb.github.io/BlasteroidsWebGL/)

Whenever you commit to this repository, GitHub Pages will run [Jekyll](https://jekyllrb.com/) to rebuild the pages in your site, from the content in your Markdown files.

## Gallery

I guess put the trailer here?
### Opening Menu
![image](https://user-images.githubusercontent.com/82253713/121099052-00ffd280-c7ac-11eb-9fa3-28ea43b87830.png)

### Avoid Falling Asteroids!
![image](https://user-images.githubusercontent.com/82253713/121098132-12e07600-c7aa-11eb-860a-32cf8e76f2db.png)

### Get powerups every 1000 points!
![image](https://user-images.githubusercontent.com/82253713/121098500-d2cdc300-c7aa-11eb-9ddd-b643160672e4.png)

### But look out, difficulty increases as your score goes up!
![image](https://user-images.githubusercontent.com/82253713/121098757-630c0800-c7ab-11eb-9e7c-110935df95f7.png)

### Press P if you need to catch your breath!
![image](https://user-images.githubusercontent.com/82253713/121098325-75397680-c7aa-11eb-9e90-16fbebd0f99c.png)

### If the health of your ship or the planet drops to 0, it's Game Over!
![image](https://user-images.githubusercontent.com/82253713/121098528-e1b47580-c7aa-11eb-9e8f-b3658749d284.png)

## Credits

Made by Andrew Grudt, Ryan Anderson, Jerahmy Bindon, and Kranti Paudyal

Assets courtesy of:

Green Laser and Asteroid from KindPNG-https://www.kindpng.com/

Music by Eric Matyas-https://soundimage.org/sci-fi/

SpaceShip by Rozebau-http://pixeljoint.com/pixelart/48537.htm

Planet by deep-fold-https://deep-fold.itch.io/pixel-planet-generator

Space Background by le professeur stagiaire-https://opengameart.org/content/space-star-background

Other Asteroids from Klipartz-https://www.klipartz.com/en

## Playtests

### Alpha Playtest
We learned that we did not set the game to scale to different computers properly. This included setting events to occur based on frames rather than on time, and not anchoring UI aspects to different points of the screen. As a result, the game was inconsistent and much of the feedback related to that. Players were concerned with poor layout and low asteroid spawn rate, although they also requested the ability to mute the game's music.

In response to this, we adjusted the game so that events would happen based on time rather than based on frames. We also anchored UI elements to different parts of the screen so that they would remain in consistent places no matter the size of the screen they are played on.

### Final Playtest
We sent out the game along with a survey to people we knew, along with posting it online. The overall responses were mixed. Many players thought the difficulty was too hard, none was able to acheive a very high final score. 3 people mentioned that they wished that the lasers would move faster.

As a result of this, we decided ito increase the speed of the lasers from 80 to 100. We also included some minor quality of life improvements, such as making the asteroids rotate as they fell and having the ship flash red when hit.

### Markdown

Markdown is a lightweight and easy-to-use syntax for styling your writing. It includes conventions for

```markdown
Syntax highlighted code block

# Header 1
## Header 2
### Header 3

- Bulleted
- List

1. Numbered
2. List

**Bold** and _Italic_ and `Code` text

[Link](url) and ![Image](src)
```

For more details see [GitHub Flavored Markdown](https://guides.github.com/features/mastering-markdown/).

### Jekyll Themes

Your Pages site will use the layout and styles from the Jekyll theme you have selected in your [repository settings](https://github.com/agrudt/Blasteroids-Site/settings/pages). The name of this theme is saved in the Jekyll `_config.yml` configuration file.

### Support or Contact

Having trouble with Pages? Check out our [documentation](https://docs.github.com/categories/github-pages-basics/) or [contact support](https://support.github.com/contact) and we’ll help you sort it out.
