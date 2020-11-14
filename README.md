

# Siobhan-Baines-MS1-Portfolio

This project is to build a static front-end which demonstrates the skills I have developed using CSS3, HTML5 and Bootstrap technologies. The subject of this project is my personal portfolio including information about my past, present and future career. The front-end is designed to give any user an informative, interesting, user friendly and professional experience. There will be navigation to 2/3 pages, links to my social media accounts, information about past projects and place holders for future projects, the ability to open my curriculum vitae on a separate tab in pdf format and the facility to contact me directly.

 ![image](https://github.com/SiobhanBaines/Siobhan-Baines-MS1-Portfolio/blob/b6849bb33bb888d3bcfdca3196203adeadc29a65/assets/reference_documents/images_README/amiresponsive_image.png)

[View the live project here](https://siobhanbaines.github.io/Siobhan-Baines-MS1-Portfolio/)


## User Experience (UX)


### *User Stories*

1. **A new visitor to the site**

   As a new visitor to the site I want the information to be clear and concise so that I can easily understand what the site is about, I want to be able to easily navigate around the site to find all its content and I may want to be to check out their social media for any other useful information.

2. **A recruiter**

   As a recruiter I want this site to clearly showcase her ability and the technologies she is adept in using so that I can compare her skill set to those of my client.

3. **An employer**

   As an employer I want her site to show me some of her personality as well as her technologically skill set so that I can evaluate her fit with my team.

### *Strategy*
My design objective was to create a website showcasing a high-level of my technical skill set. I wanted the information to be easily accessible, clear and concise but at the same time giving the visitor everything they might want or need.

### *Scope*
At the same time as providing a good outline of my skills and experience for a prospective employer I wanted to make the experience of using the site as enjoyable as possible and give them the facility to download my curriculum vitae and/or contract me directly as well as the ability to check out all my social media presence. 

### *Structure*
My landing page will be very simple with only my name and job title in the centre, the header navigation and the footer links.

![image](https://github.com/SiobhanBaines/Siobhan-Baines-MS1-Portfolio/blob/b6849bb33bb888d3bcfdca3196203adeadc29a65/assets/reference_documents/images_README/Portfolio_Landing_Page.png)

The 'My Story' page will give a brief overview of who I am and what I have done throughout my career in IT as well as the qualifications I have earned since leaving school.

![image](https://github.com/SiobhanBaines/Siobhan-Baines-MS1-Portfolio/blob/b6849bb33bb888d3bcfdca3196203adeadc29a65/assets/reference_documents/images_README/My_Story_page.png)

The 'Projects' page will highlight some of the larger projects I have previously worked on my IT career and some place holders for the future mile stone projects with Code Institute which will eventually have links to the projects source and deployed site.

![image](https://github.com/SiobhanBaines/Siobhan-Baines-MS1-Portfolio/blob/d89906cb03dd31d6cf17e21b59dbf87b7b076043/assets/reference_documents/images_README/Projects_page.png)

There will be a contact page to allow prospective employers to contact me via email.

Finally, there will be links to my social media accounts including LinkedIn, GitHub, Facebook, Twitter and Instagram as well as providing the ability to download my CV. Where there are active links, they will open in a separate tab. 

### *Skeleton*
#### Wireframes
[Initial Design](https://github.com/SiobhanBaines/Siobhan-Baines-MS1-Portfolio/blob/345ae61c1f846b4b615f850372655e3cbb849780/assets/reference_documents/wireframes/Initial_Design)

After working on various parts of the website I decided there were some things I did not like such as the icons for each menu option on the navigation bar, the positioning of the social media links, the download CV link and the layout of the My Story page (aka about).

[Final Design](https://github.com/SiobhanBaines/Siobhan-Baines-MS1-Portfolio/blob/345ae61c1f846b4b615f850372655e3cbb849780/assets/reference_documents/wireframes/Final_Design)

### *Surface*
The colour scheme was taken from the colours of [index_image](https://github.com/SiobhanBaines/Siobhan-Baines-MS1-Portfolio/blob/3d543c973fc56c4d8cb2472d9554478aa2aebc81/assets/images/index_image.png) 
[colour pallet](https://github.com/SiobhanBaines/Siobhan-Baines-MS1-Portfolio/blob/3d543c973fc56c4d8cb2472d9554478aa2aebc81/assets/reference_documents/colour_pallet.pdf)
I believe the muted blues and browns give the site a more professional image which is easy on the eye. I chose the laptop and coffee image because the concept seems to fit well with my working personality. I always have a coffee by my side when I am coding which has usually gone cold.

## Features

### Existing Features

##### Header navigation bar
Initially I started out copying the source from [Whiskey Drop](https://siobhanbaines.github.io/BootstrapWhiskey/) but soon found there were items I did not understand so went back to Bootstrap and googled other navigation bars. My CV download button was on the right side to begin with but I found moving it across to the left and having it part of the list was better. My colour scheme is such that I needed navbar-light so the menu items were darker than the header bar. I stripped out all but the necessary parts for the desktop menu and gradually added in the collapsible section and the 'hamburger icon'. By trying individual stylings, classes etc I gradually built an understanding of what each element did to the navigation bar.

##### Footer
When I started out designing the footer bar, I wanted there to be a second place to download my CV from but I found that made the footer look cluttered. Placing the social media icons in the centre feels better to me. I used styling to increase the size of the icons. As part of the peer review Abi highlighted the footer seemed to be behaving strangely. I used Google to find out how I could force the footer to stick to the bottom of the page. Once that was working, I applied the same logic to force the header to stick to the top of the page which allowed for the longer pages to scroll behind both the header and the footer.

##### Images
I wanted the images I was using to be more in the back ground and after using Google I found this information on [opacity](https://www.w3schools.com/css/css_image_transparency.asp) which gave the information I needed to achieve the result I was looking for. I am still unsure why I need to use '&nbsp;'(non-breaking space) for the opacity overlay but it works.

##### Index Page
My tutor suggested I needed a 'call to action' feature on the landing page but after much thought I decided it was not appropriate. I want the landing page to be uncluttered but pretty and professional at the same time. I have added a border to the CV Download menu option in white which draws the eye and encourages the user to download my CV. 

##### Time line for Qualifications and Experience
The Work History from Code Institutes [resume-miniproject-bootstrap4](https://github.com/Code-Institute-Solutions/resume-miniproject-bootstrap4/tree/master/16-adding-work-history) to give me the basic outline. I then looked at [Lucy Jones' website](https://lucyjpjones.github.io/LucyJones-resume/my-story.html) because she has 2 timelines side by side and I wanted to see how she had achieved this. Getting the timelines to look balanced was tricky and involved many small adjustments. After the peer review, I took Scott's advice and increased the font size on the timelines. He also suggested using the 'tel' tag allowing a mobile device to open the phone app with my mobile number ready to call - a very nice little feature I simply had not thought of. When I had fixed the header and footer to the top and bottom of the page, I had to adjust the padding at the top of each column of data and then add in some extra styling in the @media section to make the timelines look right.

##### Projects Page
I love the work page on [Haley Schafer's Portfolio](https://www.haleyschafer.com/) and used this to design in the creation of my projects page. I used Google to help find more information about the card and modal classes as well as how to me a description to appear if that card was hovered over. 

##### Contact Page

I did copy this from the contact page on [resume-miniproject-bootstrap4](https://github.com/Code-Institute-Solutions/resume-miniproject-bootstrap4/tree/master/16-adding-work-history). What is interesting is, if you copy and paste the code directly into Gitpod it does not always work. There seem to be hidden characters that corrupt the code. I changed the colour of the submit button and added in my email address for when the submit button will have some JavaScript behind it. I also managed to change the input type for the email to text so it did not work properly when I was testing. Scott noticed this and on reviewing the code I saw my mistake and changed 'text' to 'email' of the input type.

### Features Left to Implement

Link to Milestone Project 2 - The interactive front-end project will be added later and the links to the site and github will be activated. I have left placeholders in the code for the links.
Link to Milestone Project 3  - The data centric project will be added later and the links to the site and github will be activated. I have left placeholders in the code for the links.
Link to Milestone Project 4 - The final project will be added later and the links to the site and github will be activated. I have left placeholders in the code for the links.

When I add the next milestone project links into this site, I will need to review the pop-up feature I have implemented because the links, although available as placeholders, will not work because the button is inhibiting access to the icons for the website and Github. I will either use the small 3 bar icon as the button and add it to the milestone projects or I will make the title a button on each project with an on-click feature.

## Technologies Used
CSS3
HMTL5
Bootstrap Framework
Google

## Testing

### On All pages 

#### Test Scenario 1

Test the navigation bar collapses to give the 'hamburger' icon when the device is smaller than medium.

#### Test Scenario 2
Select the ‘My Story’ page link on the navigation bar on each page to ensure it takes the user to the ‘My Story’ page and does not error

#### Test Scenario 3
Select the ‘Projects’ page link on the navigation bar on each page to ensure it takes the user to the ‘Projects’ page and does not error

#### Test Scenario 4
Select the ‘Contact’ page link on the navigation bar on each page to ensure it takes the user to the ‘Contact’ page and does not error

#### Test Scenario 5

Select ‘Download CV' link on the navigation bar on each page to ensure it opens my Curriculum Vitae on a separate tab in pdf format

#### Test Scenario 6

Check each of the social media links take the user to the correct social media page.
GitHub
LinkedIn
Facebook
Instagram
Twitter

### My Story Page

#### Test Scenario 7

Click on my email address on 'My Story' page to check it creates an email with my email address and the recipients' address

### Projects Page

#### Test Scenario 8

Test each future project has a link that currently does not lead anywhere.

### Contact Page

#### Test Scenario 8

Test the Name and Email fields are filled in with the correct type of information (the email address field is set up for an email) on the contact page before the form will submit.

#### Test Scenario 9
Does the submit button on the contact page email the details?

### Transition from Desktop to Mobile

#### Test Scenario 10
Do the pages flow smoothly on a mobile device?

Does the content look clean and readable, and does it fit well in the mobile device screen?

Does the scroll work properly?

[Test Evidence](https://github.com/SiobhanBaines/Siobhan-Baines-MS1-Portfolio/blob/3173bb0888cfd407e5ef37cbd2af27a6560ac6e5/assets/reference_documents/MS1_Test_Evidence.pdf)

Once I had completed my unit testing, I sent the link to family and friend asking them to be critical. Perhaps family and friends are too kind.

The final test is to ask for a peer review.

#### Other Testing
I used https://validator.w3.org/ to check my HTML5. 
I used https://jigsaw.w3.org/css-validator/ to check my css. 
I used https://autoprefixer.github.io/ to add in any prefixes I had missed. 
I also copied the HTML into word to run a spell check over it and cleaned up my bad typing.
I used word to check my spelling.

## Credits
Hayley Schafer Portfolio for help with my Projects page and inspiration for my design.(https://www.haleyschafer.com/index.html).

Lucy Jones Portfolio for inspiration for My Story page. (https://lucyjpjones.github.io/LucyJones-resume/my-story.html).

Code Institute - Whiskey Drop and Rosie Resume websites for help with navigation, timeline and contact page.

Academind  - I used the ideas from their video to fix my navigation bar
(https://www.youtube.com/watch?v=qmPmwdshCMw).

When using Google to find out more information about various parts of my code that were not working as I expected I often used[w3schools](https://www.w3schools.com/default.asp), [stackoverflow](https://stackoverflow.com/questions/tagged/html) and [Bootstrap](https://getbootstrap.com/docs/4.0/components/modal/).


### Media

The photographs used in this site were obtained from [dreamstime](https://www.dreamstime.com/)

I then used [icolorpalette](https://icolorpalette.com/) to get a colour palette from the image I used for index-image.

