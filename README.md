In this project you will be creating a single page Portfolio website using HTML5, CSS & Javascript having the following sections:

About Me
Skills
Projects
Recommendations

![image](https://github.com/22mca20239/portfolio/assets/139697585/5f43cfa8-b4ee-4686-a26f-497c6d4b081e)

Creating the single page website
Task 1
In index.html, replace the name given in the starter code Jane Doe, with your name in the Home section. You will see that the class is set to profile_name for this div.

In style.css, go to the profile_name class. The codes for floating to the left and padding, have been provided in the starter code. Add a light colour of your choice and an appropriate font size. The sample page uses 30px.
![image](https://github.com/22mca20239/portfolio/assets/139697585/fda01a53-f153-4f7d-9774-4064598d989e)

Task 2
1. In the nav bar section, you would notice that the link to the About Me section has been given. Add the other 3 sections: Skills, Projects, Recommendations.

2.The codes for this class (ie. topmenu) have been given in style.css. The topmenu:hover class has a styling to set the color to white. Add the following style attriburtes to topmenu:hover.

a. The font-weight as bolder

b. The text-decoration as underline
![image](https://github.com/22mca20239/portfolio/assets/139697585/7fd7f935-5514-4dce-bde7-1fe3d70ccade)


Task 3.

1.Modify the About me section with your name, a unique profile image (different from what is provided in the sample) and a text summary of yourself.
You may add text about a fictititous person instead of actually providing your personal information.

![image](https://github.com/22mca20239/portfolio/assets/139697585/9f95866e-ecb6-4059-b124-071bf1eb187e)

Task 4

1.In the Skills section, 2 skills have been initially added.

Add 3 or more skills with appropriate logo and text.
![image](https://github.com/22mca20239/portfolio/assets/139697585/cd7af0a9-8c51-4f5c-ba35-ec0b67f62de9)

Task 5

In the projects section, 3 projects with sample content have been given.

Please change the project headings and project details from the default ones to your own/fictitious details.

Set the the class to project-card.

![image](https://github.com/22mca20239/portfolio/assets/139697585/3ee57d71-7fcc-4aaf-aaf5-b84c6cd7fb94)

Task 6 
You will notice that 3 Recommendations with random sample text have been initiallly added.

Change the class name to ‘recommendation’ in the code given for all these.

Add at least 3 fictitious recommendations (each of about 25-30 words) in place of these.

![image](https://github.com/22mca20239/portfolio/assets/139697585/0b029fd9-acdf-42f6-b1c3-89a25e7a5859)

Task 7
The function addRecommendation() has been in script.js as a part of the starter code. Add an onClick event to the button with id recommend_btn in index.html, to invoke this function.

Enter a text and click on the button, for the function should be invoked. The text should be added to the list of recommnedations, as shown in the image.
![image](https://github.com/22mca20239/portfolio/assets/139697585/f14d021b-a832-42b1-986d-66f8c55bfa1a)
Task 8
Home icon has been provided to you in the started code. Look for the portion <a href="#home"> in index.html and add the following code inside it to make it functional and to take you to the start of the page when you click on the home icon.

<svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke-width="1.5" stroke="white" width="63px">
  <path stroke-linecap="round" stroke-linejoin="round" d="M15 11.25l-3-3m0 0l-3 3m3-3v7.5M21 12a9 9 0 11-18 0 9 9 0 0118 0z" />
</svg>
![image](https://github.com/22mca20239/portfolio/assets/139697585/c382ce74-4038-457e-888d-30e6a7ae456e)
Task 9
In Task 7, you must have noticed that a newly submitted recommendation does get added to the exsiting list, however there is no confirmation upon submission. Your final task will be to incorporate that.

**Notice that the function showPopup() has already been provided with complete code in script.js. **

Add the following code inside the addRecommendation() function in the space provided, so that the showPopup() function is invoked onyl when a recommendation is submitted.
showPopup(true);
Go to div with id popup and add an apporpiate text confirmation message in the space provided.
![image](https://github.com/22mca20239/portfolio/assets/139697585/6a65b6c9-d631-4c75-9988-f71f3fd8f636)



