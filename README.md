# JPspa

JPspa is a new and exciting platform that is designed to connect travelers coming to or already in Japan with one of our most sensational experiences.

Onsen!! Onsen are specialized baths built around natural hot springs.<br>
JPspa will help those planning a visit to Japan in the future, as well as those already traveling in the country and seeking out new and exciting experiences.<br>
The JPspa aims to promote onsen in Japan for their health benefits not just for the body but also for the mind. <br>
JPspa will offer excellent discount vouchers for different onsen in Japan on a rotating basis as well as provide a weekly newsletter with information about the onsen and their location.<br>
(JPspa will get a commission if users go through our partner websites)

![JPspa web page on the common screen sizes](./readme/media/landingpage-img.png)

## Existing Features

**Navigation Bar**

- The site uses a responsive navigation bar made up of three pages these are the Home page, Destination, and Signup pages. It also contains a logo. The logo and Home can be used to navigate to the top of the home page. Destinations, and Sign Up navigate to their relevant pages.

- A user can access the other pages on the site and see what page they are currently on by looking at the menu in the navigation bar. When the user is on a page it will show that in bold text.

![Navigation bar](./readme/media/navbar.png)

**The landing page image**

- Is a photograph accompanied by a short description and title that gives the users a clear picture of the website's purpose and gives a clear idea of where and what services are provided.

- • This section creates a relaxing image for users, it uses a simple but effective image that encourages further exploration of the site for people who are interested in hot springs in Japan.

![Landin image](./readme/media/landing.png)

**Hot spring in Japan section**

- A brief Introduction to hot springs in Japan and their use as Onsen, accompanied by an image capturing the beauty of Japan.

- In this section, users will learn that hot springs are widespread throughout Japan.

![Japan image](./readme/media/japan.png)

**Benefits of Onsen section**

- Explaining the benefits of Onsen, accompanied by an image of a natural hot spring.
- In This section, users will discover the value of visiting hot springs as well as information on the health benefits for the mind and body.

![Benefits of onsen image](./readme/media/benefits.png)

**Japanese-style hotel section**

- Gives a brief intro to Japanese-style hotels and how they are rooted in the historical traditions of the country. Accompanied by a video that showcases this. The Video is a YouTube video and has the same features.
- This user, will inspired by an amazing video and accompanying description and may contemplate taking further steps to find accommodation in a Japanese-style hotel on their visit.

![Japanese style hotel image](./readme/media/jpstyle-hotel.png)

**Footer**

- The footer contains four social media icons when clicked open in new tabs. The logo acts as a home page button.
- Placing social media icons shows users we have an active presence outside of the website which can help to build our social media presence.

![Footer image](./readme/media/footer.png)

### Destination page

**The destinations page image**

- A photograph of a traditional Japanese shoji window.
- This section’s imagery will give users a glimpse of what a luxurious Japanese-style hotel is like and help them on their way to choose where they want to spend their in Japan.

![Destination image](./readme/media/destination.png)

**Where to go section**

- The title explains this page with a brief introduction.
- User will see what this page is about clearly.

![Where you can go image](./readme/media/wheretogo.png)

**Map of Japanese Onsen**

- Map that displays hot-spring spots throughout Japan that can be clicked and expanded to provide users with more details.
- This section will allow users to explore our partner hot springs throughout the country and help them decide where in Japan they would love to visit. The map can be zoomed in to see where would be the best place to visit.

![Map of Japanese onsen image](./readme/media/map-onsen.png)

**Recomendation section**

- The recommendations section provides information on famous hot springs in Japan. They are connected with our partners for a smoother experience.
- This section is valuable to users as they will be able to find our partner websites easily and find more information for their final decision.

![Recommendations image](./readme/media/recommendation.png)

**Sign Up page**

- This is a signup page where users can become members of JPspa. Membership benefits provide users with discount vouchers to our partner Onsens every week sent out in our newsletter. User will be asked to submit their full name, email address, and password.

  ![Sign up image](./readme/media/signup.png)

### Feature left to implement

The website could have more pages in the future.
I think it would attract more users to the site if there was a built in booking page. Users can book spa or Japanese-style hotels within the website increasing the value of this website and its throughput.

## Testing

- Tested with different browsers such as Chrome, Firefox, and Safari.
- Tested with different screen sizes using the developer tool (Galaxy Fold, iPad, and my laptop)

![Tested different screen sizes](./readme/media/testscreensize.png)

- Tested navigation bar. Home, Destinations, and Sign Up pages jump to the respective places when it's clicked.
- Tested embedded YouTube video starts and has control within the site.

![Tested Youtube video](./readme/media/test-youtube.png)

- Tested all social media links in the footer to ensure they open in a new tab with the correct destination when clicked.

![test-socialmedia](./readme/media/test-socialmedia.png)

- Tested a logo in the footer which jumps back top of the page.
- Tested all links in the recommendation section on the destinations page to ensure they open in a new tab with the correct destination when clicked.

![Tested links](./readme/media/test-links.png)

- Tested the form on the Sign-Up page. All required fields worked and the submission button worked.

### Validator Testing

**HTML** <br>
All pages have no errors and warnings and have been tested with the [W3C validator](https://validator.w3.org).

![Tested with the HTML Validator](./readme/media/html-validator.png)

**CSS** <br>
No errors adn warnings and have been tested with the [W3C CSS validator](https://jigsaw.w3.org/css-validator)

![Tested with the CSS validator](./readme/media/css-validator.png)

**Lighthouse report**<br>
Analysed this page with Lighthouse. Most of the scores are nearly 100%.<br>
The performance tag is the better score on a desktop screen. a bit low due to having a YouTube video and a Google Map on this website which has impacted the speed slightly.

Desktop<br>
![Lighthouse report desktop](./readme/media/lighthouse-desktop.png)

Mobile<br>
![Lighthouse report small divices](./readme/media/lighthouse-mobile.png)

## Bugs

**Fixed W3C Vlidator warnings and errors**

- Removed slashes as the website had a warning about having a slash on the void element in the header.

![Validator bug 1](./readme/media/bug1.png)

- Some of the closing tags weren’t closed with the same tag and some were wrong places. So fixed them.

![Valdiator bug 2](./readme/media/bug2.png)

- Fixed duplicated ID

![Validator bug 3](./readme/media/bug3.png)

- I had a warning for having an h1 tag that wasn’t a top-level heading in the explore section of the landing page.<br>Solved the issue by using a h2 tag instead of an h1 of the place.

![Validator bug 4](./readme/media/bug4.png)

- I was using a section tag only to render a picture as a background and got this issue.<br>
  So I put more content in the destination section.

![Validator bug 5](./readme/media/bug5.png)

**Lighthouse report improvement**<br>
Analyse the website with Lighthouse and had high scores. However, there were still places where I could improve them.

- I was using pictures where their sizes were too big and that caused the issue of the loading speed of the page to be impacted. So I compressed the images to be smaller size by converting the images to a WEBP format. This decreased the image size. Some of the pictures also used Photoshop to decrease the pixels.
- Used aspect ratio property in CSS to remove the issue that the images didn’t have a correct height.

## Deployment procedure

This site was deployed using GitHub pages.

1. Go into the project repository that you want to deploy.
2. Click the settings on the menu bar of the page.

![Deployment procedure 2](./readme/media/deployment1.png)

3. Check that the repository name is correct.
4. In the general menu on the left-hand side, click the pages tab.

![Deployment procedure 4](./readme/media/deployment2.png)

5. Source should be set to Deploy from a branch.

![Deployment procedure 5](./readme/media/deployment3.png)

6. Underneath, the Branch section is selected. Here we use the main branch and root folder and save it.

![Deployment procedure 6](./readme/media/deployment4.png)

7. Go back to the code page and you will see the Deployment section on the right-hand side.

![Deployment procedure 7](./readme/media/deployment5.png)

8. Go inside the deployments, you can see the address of your website.

![Deployment procedure 8](./readme/media/deployment6.png)

## Credits

**Contentes**<br>
https://en.wikipedia.org/wiki/Onsen<br>
https://hakone-japan.com/things-to-do/onsen/an-onsen-guide/health-benefits-of-onsen-2/

**Code** <br>

- I used the [W3 schools](https://www.w3schools.com/html/default.asp) website as a tool to build my website referring to the HTML and CSS sections.
- To make the navigation bar and footer I used the Love Lunning project as an example.
- On the sign-up page, reference [freeCodeCamp](https://www.freecodecamp.org/japanese/news/how-to-center-anything-with-css-align-a-div-text-and-more) page to make a div in the middle of the page.

**External Links**

Used it as a further detail on hot springs that users can learn in the Recommendations section on the Destinations page.<br>
(Used them as JPspa’s partner)

https://dogo.jp/en/<br>
https://ie.hotels.com/go/japan/best-hot-springs-beppu<br>
https://hokkaido-treasure.com/column/057/<br>
https://www.feel-kobe.jp/en/pickup/onsen_geiko/<br>
https://www.hakonenavi.jp/international/en/article/399<br>
https://www.visit-kyushu.com/en/spots/yufuin-onsen/<br>
https://www.kurokawaonsen.or.jp/eng_new/<br>
https://www.geroyamagataya.com/lg_en/<br>
https://www.kagoshima-kankou.com/for/areaguide/ibusuki

## Media

YouTube video<br>
https://youtu.be/1sOKp1SLNsQ?si=qWbcG-KfGWIeJMiJ

Google Map ( I used a Google Map to create a map of onsen in Japan and embedded it into my project )<br>
https://www.google.com/maps/d/embed?mid=1m39FiGILk7YFKpCOcUOErI2Q9EeZ-5c&ehbc=2E312F

Images<br>
https://pixabay.com/<br>
https://www.photo-ac.com/<br>
https://cloudconvert.com/jpg-to-webp<br>
https://pixelied.com/convert/jpg-converter/jpg-to-webp<br>

Fonts<br>
https://fonts.google.com/

Icons<br>
https://fontawesome.com/<br>
https://www.favicon.cc/

Other reference
https://dequeuniversity.com/rules/axe/4.8/link-name<br>
https://dequeuniversity.com/rules/axe/4.8/frame-title<br>
https://www.digitalrebellion.com/webapps/aspectcalc
