# Raw Boxing Gym
## _A website for members to join the Gym._

![Homepage screenshot](/assets/images/readme-images/readme1.JPG "Homepage")

Welcome to [Photo Shoot Fans](https://sergii-kostanets.github.io/codeinstitute-photo-shoot-fans) on GitHub Pages.

![Photo Shoot Fans responsive design](assets/images/readme-images/responsive-main-page.png)

# Contents

* [**User Experience UX**](<#user-experience-ux>)
    * [Site Structure](<#site-structure>)
* [**Features**](<#features>)
    * [**Existing Features**](<#existing-features>)
        * [**All pages**](<#all-pages>)
            * [Header](<#header>)
            * [Footer](<#footer>)
        * [**Home page**](<#home-page>)
            * [Blocks](<#blocks>)
        * [**Camera page**](<#camera-page>)
        * [**Request page**](<#request-page>)
        * [**Submit page**](<#submit-page>)
    * [**Future Features**](<#future-features>)
* [**Technologies Used**](<#technologies-used>)
* [**Testing**](<#testing>)
* [**Deployment**](<#deployment>)
* [**Credits**](<#credits>)
    * [**Content**](<#content>)
    * [**Media**](<#media>)
*  [**Acknowledgements**](<#acknowledgements>)


# User Experience (UX)

## Site Structure

[Raw Boxing Gym](https://tonyjrafter.github.io/boxing-gym/) website has four pages:

 * [Home](index.html)
 * [gallery](gallery.html)
 * [join](join.html)
 * [done](done.html)

The [home](index.html) page is the default loading page, [gallery](gallery.html) and [join](join.html) pages are all accessible primarily from the navigation menu. The [done](done.html) page appears only after form at [join](join.html) page is submit. There are another links to the [join](join.html) page and [gallery](gallery.html) page in the [home](index.html) page and [gallery](gallery.html) page to inspire the user for the next step.

[Back to top](<#contents>)

# Features

[Raw Boxing Gym](https://tonyjrafter.github.io/boxing-gym/)contains many features that the user would be familiar with, such as a navigation bar, footer with social links.

## Existing Features

* ### All pages

  * #### Header

    * The logo icon is clickable with a link back to the home page for enhanced UX.
    * The logo text isn't clickable to make it easier to copy the site name and share it.
    * Sited at the top of all the pages in the site, navigation menu is fully responsive and contains links to all the pages of the site to enable ease of navigation in one convenient location.

![Navigation bar image](/assets/images/readme-images/readme2.JPG)

[Back to top](<#contents>)

  * #### Footer

    * minimalistic to not distract the user.
    * Contains social media links with clickable icons, The links open in other tabs.


![Footer image](/assets/images/readme-images/readme3.JPG)

[Back to top](<#contents>)

* ### Home page

  * #### Blocks

      * Located on the home page beneath the title section. The main content blocks are designed to be hidden when a service is suspended, or easily added when services are added. Each block ends with a button to encourage the visitor to go to the page for filling out a form or choosing a camera.
      * Each block is responsive and restructures when the display is scaled down. Keeping the general idea of encouraging the visitor to explore the site further.

![Blocks image](assets/images/readme-images/blocks.png)

[Back to top](<#contents>)

* ### Camera page

    * The camera page give the user a choice of equipment for shooting.
    * Blocks with the choice of equipment contain the name and photo of the camera itself, as well as the name of the lens and examples of photos taken on this camera with this lens.
    * Blocks are easily duplicated, allowing you to quickly add new cameras to the range.
    * Each block ends with a button to go to the form fill page to inspire the user to continue the journey.

![Camera page image](assets/images/readme-images/camera.png)

[Back to top](<#contents>)

* ### Request page

    * This section should complete the online journey for the user. It has request form for every type of client.
    * Form has 5 input fields: first name, last name, email, message and type of client.

![Request page image](assets/images/readme-images/request.png)

[Back to top](<#contents>)

* ### Submit page

    * The page confirms the submission of data.
    * The page has a general site structure and allows the user to quickly return to viewing previous pages.

![Submit page image](assets/images/readme-images/submit.png)

[Back to top](<#contents>)

## Future Features

* Make the submit form work properly by emailing the owner.
    * Add a page with a message about successful submission.
    * Connect and set up a database to automatically save each request.
    * Create a page to view and filter data from the database.
* Add more cameras to camera page.
    * Create a slider with sample shots for this camera.
    * Introduce swipe actions for use on mobile devices for this slider.

[Back to top](<#contents>)

# Technologies Used
* [HTML5](https://html.spec.whatwg.org/) - provides the content and structure for the website.
* [CSS3](https://www.w3.org/Style/CSS/Overview.en.html) - provides the styling.
* [Visual Studio Code](https://code.visualstudio.com/) - IDE used to develop the website.
* [Github](https://github.com/) - used for versin control, to deploy and host the website.
* [I Love IMG](https://www.iloveimg.com/) - online photo editor to crop and resize photos.

[Back to top](<#contents>)

# Testing

Please refer to [**_here_**](TESTING.md) for more information on testing Photo Shoot Fans.

[Back to top](<#contents>)

# Deployment

### **To deploy the project**
The site was deployed to GitHub pages. The steps to deploy a site are as follows:
  1. In the GitHub repository, navigate to the **Settings** tab.
  2. Once in Settings, navigate to the **Pages** tab on the left hand side.
  3. Under **Source**, select the branch to **main**, then click **save**.
  4. Once the main branch has been selected, the page will be automatically refreshed with a detailed ribbon display to indicate the successful deployment.

![GitHub pages deployed image](assets/images/readme-images/deployment.png)

  The live link to the Github repository can be found [here](https://sergii-kostanets.github.io/codeinstitute-photo-shoot-fans).

### **To fork the repository on GitHub**
A copy of the GitHub Repository can be made by forking the GitHub account. This copy can be viewed and changes can be made to the copy without affecting the original repository. Take the following steps to fork the repository;
1. Log in to **GitHub** and locate the [repository](https://github.com/Sergii-Kostanets/codeinstitute-photo-shoot-fans).
2. On the right hand side of the page inline with the repository name is a button called **'Fork'**, click on the button to create a copy of the original repository in your GitHub Account.
![GitHub forking process image](assets/images/readme-images/forking.png)

### **To create a local clone of this project**
The method from cloning a project from GitHub is below:

1. Under the repository’s name, click on the **code** tab.
2. In the **Clone with HTTPS** section, click on the clipboard icon to copy the given URL.
![Cloning image](assets/images/readme-images/clone.png)
3. In your IDE of choice, open **Git Bash**.
4. Change the current working directory to the location where you want the cloned directory to be made.
5. Type **git clone**, and then paste the URL copied from GitHub.
6. Press **enter** and the local clone will be created.

[Back to top](<#contents>)

# Credits
### Content

* Font selected on [Font in Use](https://fontsinuse.com/typefaces/203938/mariupol)
* The font came from [Rent a Font](https://rentafont.com/fonts/mariupol?sample_text=Mariupol%2520font%2520test).
* The map is embedded from [Google Maps](https://www.google.com/maps).
* The icons came from [Flat Icon](https://www.flaticon.com/).
    * Author: [Freepik](https://www.flaticon.com/authors/freepik).
* The form base structure and performance check came from a [Love Running Walkthrough Project](https://learn.codeinstitute.net/courses/course-v1:CodeInstitute+LR101+2021_T1/courseware/4a07c57382724cfda5834497317f24d5/4d85cd1a2c57485abbd8ccec8c00732c/?child=first).
* As an example of a readme file was taken file of author [Ewan Colquhoun](https://github.com/EwanColquhoun/wawaswoods#readme)

### Media
* The photos all came from the developer of this website, [Sergii Kostanets](https://www.linkedin.com/in/sergiikostanets/).
* The photos were compressed using [I Love IMG](https://www.iloveimg.com/).

[Back to top](<#contents>)

# Acknowledgements
The site was completed as a Portfolio 1 Project piece for the Full Stack Software Developer (e-Commerce) Diploma at the [Code Institute](https://codeinstitute.net/). As such I would like to thank my mentor [Precious Ijege](https://www.linkedin.com/in/precious-ijege-908a00168/), the Slack community, and all at the Code Institute for their help and support.

This is a very personal project for me. In a past life, before the war in Ukraine, I was a photographer and collector of rare film cameras. Now, when everything is destroyed, all I have left are these photos and a dream to create a community of film photography lovers. And let this website be the basis for that.

[Sergii Kostanets](https://sergiikostanets.netlify.app/), November 2022.

[Back to top](<#contents>)