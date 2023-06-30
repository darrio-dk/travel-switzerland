## Travel Switzerland

The Travel Switzerland website welcomes user with nice warm background colour. The website is designed for tourists or anybody who loves to travel, it gives brief information about most visited, famous places in Switzerland.
The website not only describes what user can expect of his chosen place but gives nice images and understanding what is all about.

User will find three choices in the menu, the places where to travel, Switzerland's traditional food and gallery with more pictures for user to make the best decision before their travel.

![Alt text](assets/images/Screenshot%20(15).png)

- Wireframe

    - Project wireframes related screenshots

    ![Alt text](<assets/images/WIREFRAME 1&2.png>)

    ![Alt text](<assets/images/WIREFRAME 3.png>)

## Features 
----

- Navigation

    - The navigation bar at the top of the page shows main title **Travel Switzerland** in the left corner.
    - On the right hand side corner other navigation links can be found such as: ***Home***, ***Food***, ***Gallery*** which link to different sections of the same page
    - The navigation background colour is different from main body, but colour contrast nicely floats together to the users eye. 
    - All the different sections placed in the navigation bar clearly visible and are easy to find.
    - For mobile and tablet devices navigation bar will welcome users with "hamburger" menu, which makes easier for the user to navigate their choice.


![Alt Text](assets/images/Screenshot%20(22).png)


- The Home Section

    - Provides clear information with Heading and core information of a website 

- The Food Section 

    - The Food section gives details about local swiss food with clear image of the dish. 

- The Gallery Section

    - In the Gallery section there are more photos to be seen with nice column desing.

- The Footer

    - The Footer section includes social media icons to users, they can find Switzerland places on Facebook, Instagram, Twitter and Youtube.
    
![Alt text](assets/images/home%20page%20s.shot.png)
![Alt text](assets/images/Screenshot%20(30).png)



## Testing 
----
    
    - This page was tested with different browsers and it works with: Chrome, Firefox, and Safari.
    - I've tested this page with devtools device toolbar. 
    - This project is responsive and functions to all different screen sizes.
    - I confirmed that the navigation, header, home, food gallery and footer links 
      are readable and easy to understand.
    
  ## Bugs

  ### Solved bugs

    - Using devtools bug were found and fixed on food section with second image not corresponding 
      to different screen sizes
    - When using Validator test result showed bug on gallery.html in "section" area, 
      which provided with missing h1 ore div tag.
    - Changing section to div tag I have solved the Validator test: div id="photos"

   ![Alt text](assets/images/Screenshot%20(40).png)

    - However by solving one bug another one showed up on devtools, 
      gallery section column was not in line with the page.
    - With a quick tutor guidance I was able to add max-width, max-height and border to none.
    -  #photos > img {
        width: 100%;
        border-radius: 0;
        max-width: none;
        max-height: none;
        border: none;
    }



## Validator Testing
----

- HTML
    
    - After correcting the issue no errors were found when passing through the WC3 validator

- CSS 
    
    - No errors were returned when passing through the (Jigsaw) validator

- Accessibility
    
    - Running the Lighthouse test on Chrome I confirmed that accessibility reached the valid number
    
![Alt text](assets/images/Screenshot%20(34).png)

## Unfixed Bugs

No unfixed bugs

## Deployment 
----
- The site was deployed to GitHub pages. The steps to deploy are as follows:
    - In the GitHub repository, navigate to the Settings tab
    - In the settings tab navigate to the Pages tab
    - From the source section select the Main Brach in drop-down menu.
    - Once the main branch has been selected, the page link was displayed to the completed website.

The live link can be found here - [Travel Switzerland](https://darrio-dk.github.io/travel-switzerland/)

## Credits
----
- Content

    - Using picked font from [Google Fonts](https://fonts.google.com/)
    - On the home page the description of the places were taken from [Wikipedia](https://www.wikipedia.org/)
    - Using navigation bar and "hamburger" for my menu - [Responsive Navigation by CodingNepal](https://www.youtube.com/watch?v=oLgtucwjVII)
    - The footer icons were taken from - [Font Awesome](https://fontawesome.com/)
    - Html and CSS issue solver - [Mozilla](https://developer.mozilla.org/en-US/) - [Stack Overflow](https://stackoverflow.com/) - [Geeks For Geeks](https://www.geeksforgeeks.org/)
    - Using Switzerland food ideas - [Top Food Ideas](https://www.bbcgoodfood.com/howto/guide/top-10-foods-try-switzerland)

- Media

    - The photos were taken from [Pexels](https://www.pexels.com/)
    - The background, font, navigation and social media icon colours were picked by [Eye Dropper](https://eyedropper.org/)



