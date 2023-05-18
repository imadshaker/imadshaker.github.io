![image](https://user-images.githubusercontent.com/103902448/164163511-37d22660-905c-4355-a6f4-91c6eee2d1a4.png)
# Portfolio
<br /><br />
<br />
<br />

#### Table of Contents:
<a href="https://github.com/ndoherty-xyz/unemployables-portfolio-template#about-this-template">About this template</a></br>
<a href="https://github.com/ndoherty-xyz/unemployables-portfolio-template#getting-started">Getting started</a></br>
<a href="https://github.com/ndoherty-xyz/unemployables-portfolio-template#how-to-customize-this-template">How to customize this template</a></br>
&nbsp;&nbsp;&nbsp;<a href="https://github.com/ndoherty-xyz/unemployables-portfolio-template#creating-a-new-project-page-and-adding-it-to-the-homepage">Creating a new project page</a></br>
&nbsp;&nbsp;&nbsp;<a href="https://github.com/ndoherty-xyz/unemployables-portfolio-template#adding-images-to-the-project-gallery">Adding gallery images</a></br>
<a href="https://github.com/ndoherty-xyz/unemployables-portfolio-template#publishing-with-github-pages">Publishing with Github Pages</a></br>
<br />
<br />



**Template instructions:**
1. Click the `Use As Template` button above and name your new repository (it should be set to public).
2. Clone your newly created repo to your local machine.
3. Navigate to the cloned repo on your machine and open `index.html` with your browser.
4. Open the repo folder in your favorite code editor and start editing. (Make sure to refresh the browser to see the code changes you make!)
5. Publish your site by pushing your commits to your repo.
6. Set up Github Pages (guide further down!)
<br />
<br />

### Creating a new project page and adding it to the homepage
1. Make a copy of `project-template.html` in the `project-pages` folder and rename it to `<project-name>.html`
2. Open `index.html` and find the `div` with `className='project-container'`
3. Add a new project card into that div. Here's the template for a project card:
```
  <div class="project-card">
    <img src="./assets/images/IMAGE_NAME" class="project-image">
    <div class="project-card-text-container">
      <div class="subheader-text project-title">PROJECT_NAME</div>
      <div class="body-text project-card-text">SMALL_PROJECT_DESCRIPTION</div>
    </div>
    <a class="button" href="./project-pages/PROJECT_PAGE_NAME.html">
      <span class="button-text">Read More</span>
      <image src="./assets/icons/arrow-right.svg" class="right-arrow-icon"/>
    </a>
  </div>
```
4. Change `PROJECT_PAGE_NAME.html` to the name of the new html file you copied from the project template
5. The project page is now linked to the homepage! Customize the page and `"project-card"` to your heart's content. 
<br />

### Adding images to the project gallery
1. Make sure the images that you want to show are added to the `assets/images` folder
2. Open the project page you want to edit and find the `div` with `class="project-gallery-content"`
3. To add an image, copy one of the two templates below and paste them into the `project-gallery-content`
```
Full Width Image:

    <div class="gallery-image-container">
      <img src="../assets/images/IMAGE_NAME" class="gallery-image">
      <span class="image-caption">IMAGE_CAPTION</span>
    </div>


Half Width Image:

    <div class="gallery-image-container half-width">
      <img src="../assets/images/IMAGE_NAME" class="gallery-image">
      <span class="image-caption">IMAGE_CAPTION</span>
    </div>
```
4. Change IMAGE_NAME to the filename of the image you added to `assets/images` and IMAGE_CAPTION to whatever caption you want (or remove it, I don't mind)
5. Refresh the project page in your browser and boom! Your image has been added to the gallery.
<br />
<br />

## Publishing with Github Pages
Github Pages allows us to host this website for free! It's pretty simple to set up as well.

1. Head to `Settings` on the repository
2. The repository will need to be public for this work (if it's not, navigate to `General` and scroll all the way down to `Change repository visibility`. Make it public)
3. Navigate to `Pages` in the sidebar
5. For `Source` choose `main` from the dropdown. Save the changes.
6. That's it! Github should give you a URL that your website is published on (give it a few minutes to update).
7. To add a custom domain (i.e. yourname.com), follow this guide: https://medium.com/codex/add-a-custom-domain-to-your-github-pages-personal-website-53ab40e7c7d0
<br />
<br />

## That's it!
Feel free to send me pictures of your portfolio website once it's up and running. Would love to see them!
