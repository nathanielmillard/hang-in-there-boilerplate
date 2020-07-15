# Project Name: Hang In There
## Team: Hang’n In there
 
### Project Description
  * This is our first paired project as Mod-1 students at Turning’s Front End Engineering Program. 
  * [Deployed website:](https://nathanielmillard.github.io/hang-in-there-boilerplate/)

### Learning Goals
  * Create a solid foundation for key concepts like DOM manipulation, data model, classes, objects, and primitive data types
  * Write clean, concise, and reusable javacript folowing DRY and SRP methods
  * Understand how and why to adopt a solid GitHub workflow
  * Utilize semantic and concise commit messages
  * Establish a basic understanding of agile project management
  * Gain a better understanding Trello project management application. 

### Features: 
This is a website that randomly generates an inspirational “poster” from a data bank of images, titles, and quotes. The user has a few options they can engage with on the bottom of the page. Left to right you can Save the Poster, View Saved Posters, Show Another Random Poster, and Make Your Own Poster. The saved poster option stores the currently visible poster, and only once. The Saved Posters section should show a grid of any and all posters the user has saved in this session in reverse chronological order. The Show Another Random Poster will continue to generate new posters randomizing the image, title, and quote. But! That’s all from a stored bank, and the user may want to create something of their own, or even just add options in to be randomized. So last we have the Make Your Own Poster button, that pulls up a form for user input of an image link, title, and quote. Once a user inputs these values they are actually stored in the banks of images, titles, and quotes, for the duration of their session for future randomized posters. Every new section also has a button with a variety of verbiage that will allow for a user to navigate back to the main page.  

### Project Milestones:

### Iteration 0: Creating randomnization

 * When user clicks on the "Show Another Random Poster" button, a new random poster, image and quote is rendered to the DOM.
 * When user reloads browser, the same fuctionality is rendered as our "Show Another Random Poster". 

![](assets/iteration-0-progression.gif)

### Iteration 1: Switching display views 
 * User navigates back and forth between our main page, create poster page, and saved poster page. 

### Iteration 2: Creating a custom poster
 * User navigates to our create poster page and enters their own customized image URL, a title, and quote.
 * Once our user clicks on the "Show my poster" button, the entered data is captured and pushed to our data model. 
 * Success! We created our own poster and displayed it to the DOM

![](assets/iteration-1-progression.gif)
 
### Iteration 3: Saving posters
 * We both struggled a lot on this iteration but we managed to complete this milestone on the last day of our project. 
 * Gained appreciation of how to utilize our data model **"the wrong way"**. After coaching from our respective mentors, we were able to change our approach and complete the iteration **the right way** without compromising our source of truth. This was a huge win for us!

![](assets/iteration-3-progression.gif)
 
### Future Iterations Goals
   * 1 Complete the full scope of the project (iteration 4) which involves creating a double click event listener on a saved posters page allowing the user more control to remove saved posters.
   * 2 Continue developing customization features for our saved posters page that would allow the user to drag and reorder posters, adding a toggle event listener that would allow the user to expand each image based on a mouse click, then resize back to original on second mouse click 
   * 3 Create an error message if the user accidentally double clicks on the "Show my poster" button

### Team Wins
  * Reserved time to help other students with their projects
  * Gained a better understanding of how to connect our data model to the DOM without compromising our source of truth.  
  * Familiarized ourselves with new technologies like Trello and GitHub
  * Gained a better understanding of our own unique learning styles and we both helped eachother improve our gaps in understanding
  * Learned how to use giphy capture application for README.md

### Contributors and collaborators
* **Nathaniel Millard** [GitHub Link:](https://github.com/nathanielmillard)
* **Joe Varela** [GitHub Link:](https://github.com/jobbotrock)
* [Original repo:](https://github.com/turingschool-examples/hang-in-there-boilerplate/)

[I'm an inline-style link](https://www.google.com)

We want to thank the Turing School for the skills to accomplish this project, and discussion and reviewing from Jake West, John Adams, Kim McCaskill, and the patience of our partners and family while we take time to work, as well as attempt to explain our processes to them along the way. 
