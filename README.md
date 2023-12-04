# Twill

## About: 
Twill is an open source collection of some clones of famous websites.

## Adding your clone:

If you would like to add your clone to this repositories, kindly follow the instructions below:

### Fork:
- Fork a copy of this repositories on your account by clicking [here](https://github.com/Zemerik/Twill/fork)

### Commiting:
- Head over to the repository you just forked, and make a folder with the name of the website you clones. For example, if you want to add a netflix clone, then you will need to name the folder `Netflix` or `netflix`. 

- In the folder that you just created, make a `{FOLDERNAME}.html` file and add your HTML code. For example, if your folder is named `Spotify`, then your file should be called `spotify.html`.

- Now add the rest of your files in that folder, such as the Stylesheet and JavaScript code. Ensure that you have also uploaded the favicon of the page. 

- After that, go to the `index.html` file of the repositery you forked, and add the code below anywhere after line `60` and before `97`. 

```html
<div class="portfolio-box">
  <img src="DESTINATION OF THE FAVICON" alt="">
  <div class="portfolio-layer">
    <h4>NAME OF YOUR CLONE</h4>
    <a href="DESTINATION OF THE HTML FILE" target="_blank"><i class='bx bx-link-external'></i></a>
  </div>
</div>
```

> Replace `DESTINATION OF THE FAVICON` with the actuaul destination of the favicon, `NAME OF YOUR CLONE` with the actual name of your clone and `DESTINATION OF THE HTML FILE` with the actual destination of your HTML file.

### Pull Request:
- Now head over to the original repository and submit a [Pull Request](https://github.com/Zemerik/Twill/pulls).

- Your pull request will be merged as soon as possible after it has been reviewed. 

### Thank you for contributing
