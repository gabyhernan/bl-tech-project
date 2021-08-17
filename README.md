# bl-tech-project
![](https://media.giphy.com/media/l4Ki1f1MpCfgyMu4M/giphy.gif) 

Welcome to my read me file! I tried to keep the structure of this project as simple as possible in order to stick within the time alloted. If I had more time and the assignment was a bigger ask I probably wouldve set up BrowserSync for auto refreshes and a task runner like Gulp or Webpack depending on the task at hand. 


But here is what I did 
- I created a **snippets** folder where I created a **script-tags.liquid** file and a  **style-tags.liquid** file. I placed the splidejs cdn script tag and css file in its corresponding files. I also added an if statement that checks if the layout is the theme, that way as the project scales if you ever have a new layout that is for example a password, or subscription layout. You might not need need this slider for example so this way you're not loading it into that page uneccesarily.

-  I also like to separate these files into its own snippets because the head of the theme can easily become messy with all the pixels,scripts tags that different analytics,social media companies require to be in the head/body of the theme. This way at least we can organize the libraries/files we need for our own work.  

-  I created a **collection-slider.liquid** file inside the sections folder that has the collection slider collection for loop. I then called this section inside the **index.liquid** file that renders in **theme.liquid**. I iniatlized the slider in the **collection-slider.js** file I created and added some basic settings.

-  I created a **package.json** file with some scripts for me to run for ThemeKit. I find these to be super helpful when you have dev,qa,and prod environments. 

Thank you! 
