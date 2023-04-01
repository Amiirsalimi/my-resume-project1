# Amir's Resume Website

Website presents Amir's resume. Users can easily contact Amir and find out about his skills, education and experience and download his CV in PDF format.

This project has been done as my first portfolio project at Code Institue. Only HTML and CSS have been used in creating this website.

The link to the website can be found below:
https://amiirsalimi.github.io/my-resume-project1/index.html

<img src=screenshots/sc-resume-website.jpg>

# User Experience
## Owner goals
My main purpose of creating this website was to get my project done and as the first ever website that I built on my own from scratch,  I chose to create a resume website to be used as the foundation of a future website for myself. This has been an amazing experience and the website will improve in the near future and will be used as a professional platform for my career.
## User goals
The user may enter the website through my social media links or if I leave it on my business cards as well as search engines in case they search for me on the web or for a developer. They would be able to make contact for job opportunities or freelance projects. They could also reach out to me on my social media through the links on the website or the conatct form.

# Features and Structure of the Website
The website consists of 3 pages including : Home, resume, contact me
## Home
At the top of the page, we have a navigation bar which lets the user navigate through the different pages of the website. 
This page consists of a banner containing a photo of me as well as my name and current status on the left hand side of the photo. There is a dashed "hr" element and a short bio below the banner as well. The photo loads with a zoom animation.
At the bottom, we have a footer in which we have icons that are links to my LinkedIn and Instagram accounts as well as an icon for my resume. The user can download a PDF file containing my resume by clicking on that icon.

<img src=screenshots/sc-home.jpg>

## Resume
At the top we have the same navigation bar as the homepage.
Then there is the banner containing another photo of me as well as my name, email and job title on the right hand side of the photo. It is worth mentioning that the structure of the page is slightly different on devices less than 600px wide, given that the photo was a square and I put the name and email and job title below the photo on those devices. The photo loads with an apearing animation using opacity of the photo.
Then we have the CV presented through paragraphs and lists indicating my education and experience as well as my skills. At the bottom of the resume there is a link to a pdf file containing my resume.
Then we have the footer. However, on this page footer is fixed so that while the user is scrolling through my resume can immdediately open the links to my social media accounts.

<img src=screenshots/sc-resume.jpg>

## Contact me
At the top we have the same navigation bar.
Then there is a form containing inputs for name, subject, email and message as well as the send button and a reset button. The user can contact the owner though this form.
On the right, there is the email address of the owner as well as links to social media through icons and a link to the pdf file containing the resume. 

<img src=screenshots/sc-contact.jpg>

# User Interface

## colors

I used minimaslistic colors with a good contrast. On all pages except for the resume the background color is white. On the other hand on the resume page the background color is a shade of light grey #D3D3D3. I made that decision as the profile photo of my resume had a white background and I wanted my photo to blend in with the banner and have some contrast between the banner and my resume. Then, I used a charcoal color mostly for the color of my fonts #3a3a3a. On the footer and nav bar the background color is black and the fonts are white.

## Fonts
I used Roboto as the main font and Oswald for headings and sans-serif as backup.

## Images
I used a couple of photos of myself for the homepage and for the resume page.

## Icons
I used 5 icons in total, three in footer and two in Contact me. The icons were free png's downloaded from the web and are mentioned in the credits section.

# Technologies used

### HTML5
As the structural language
### CSS3
As the styling language
### GitHub
As a platform to keep the project files as well as hosting my website through GitHub pages.
### GitPod
As a coding and development platform
### Git
As a version-control system
### Google fonts
As a resource provider for fonts.


# Testing

## Responsiveness
I used Chrome developer tools all the way through the project this helped me with making my website responsive and figuring out styling issues so that I could fix them.

## Compatibility
I loaded the website hundreds of times on my macbook pro 14 inch as well as 27 inch 4K monitor to check for issues. On my iPhone 14 pro max. Additionally, I checked on a smaller iphone 11 and macbook air. 

## Nu html validator
I used this tool to validate my codes. Except for a couple of unused paragraphs left from laying out the initial structure of the website issues and missing the word content= before my keywords in the meta element, and an alt attribute for an icon in the footer, there was no other issues. 

<img src=screenshots/sc-html1.jpg>


<img src=screenshots/sc-html2.jpg>


<img src=screenshots/sc-html3.jpg>


<img src=screenshots/sc-errors.jpg>


## W3C Jigsaw CSS validator
There was not even a single mistake or error.

<img src=screenshots/sc-css.jpg>

# Issues found during the development

At first the website did not load the way I wanted to on tablets and phone so I had to use @media for devices with widths under 1300pixels and 600pixels. I defined new properties and tested until I got my desired result.

Sometimes, I had problems with positioning of div elements. So I had to look at the positioning lessons again and it really helped me out.

I had to resize the my photo for smaller devices and slightly change the structure of my resume page to get the disired results.

At one point on my resume page I had texts overlapping it took me a while to figure out why this has been happening. I couldn't find anything on google. It was the middle of the night so I could not use the tutoring service either. Therefore, I played around and realised that the reason this is happeing is that I have set the postition of a ul to absolute. After changing it to relative the problem got fixed.

# Deployment

I used GitHub pages to deploy my website. Through this link:
https://amiirsalimi.github.io/my-resume-project1/index.html

In addition, I used python3 -m http.server command to deploy the website while developing. I made the link public so I could use other devices as well.

The website could be run locally through the depositopry as well:
https://github.com/Amiirsalimi/my-resume-project1


# Credits

To complete this project I used Code Institute student template:
https://github.com/Code-Institute-Org/gitpod-full-template

I used Google fonts to import fonts.

I used the below free icons:

https://icons8.com/icons/set/resume--white
https://icons8.com/icons/set/linkedin
https://www.pngwing.com/en/free-png-zxbxz
https://fontawesome.com/icons/instagram?f=brands&s=solid&sz=lg&pc=%23000000
https://fontawesome.com/icons/linkedin?f=brands&s=solid
https://icons8.com/icons/set/resume--white

and of course, without the materials that I studied on Code Institute LMS and some points learned on Slack, I couldn't have done this project.

I would like to thank my mentor, Ade who helped me through this project with his guidance.


# Screenshots

<img src=screenshots/sc1.jpg>

<img src=screenshots/sc2.jpg>

<img src=screenshots/sc3.jpg>

<img src=screenshots/sc4.jpg>

<img src=screenshots/sc5.jpg>

<img src=screenshots/sc6.jpg>



