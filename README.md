# UFOs Sightings
______________________________________

### Overview of Project

- Our client's webpage and dynamic table are working as intended. However they would like to provide a more in-depth analysis of UFO sightings by allowing users to filter for multiple criteria at the same time. Originally, we were just fitering by date, now we want the user to be allowed to filter by city,state,country, and shape. This will help the users by digging deeper into their desired findings.

### Results
##### We were able to perform this new table by using HTML and Javascript functions.

   1. Our first step was to add in the new HTML list elements: city, state, country and shape.
      ***we had to make sure we used the correct id as the object properties in our data.js file.***
   
   2. After completing the HTML adjustments, our next step was to dive into our Javascript file and make additional changes. 
     
      - We needed to create a empty *filters* variable to keep track of all the elements that change when a search is entered.
      - Next, we we wrote code for two functions which we named *updatedFilters()* and *filterTable()*.
      - We added the function *updatedFilters* so that the dynamic table would update the filters based on user input.
      - The *filterTable()* function was essential because we needed to write code to filter the table based on the user input that is stored in the filters variable. 
        This code is needed for when new filters are added to the selection, or when the filters are reset. 
      - Lastly, we modified our event listener we previously created so that now it would detect a *change* on each input element and calls the updateFilters() function. 
      
   3. Lastly we ran deployed the new webpage and got the following results. 
     ***All that the user has to do is input their desired information and press ENTER to find their results.***
     
   ![Newtable1](https://github.com/mckenziekkilburn/UFOs/blob/master/images/Newtable1.PNG)
 
   
   **Let's say that we want to find out which cities in California, on the date of 1/1/2010, had a shape type of "light", then we would enter the following:**
   
   ![Newtable2](https://github.com/mckenziekkilburn/UFOs/blob/master/images/Newtable2.PNG)
   
### Summary 
- One of the main drawbacks is that this data that is used on the website only consist of January of 2010. If we used more data it would be better for research purposes.
- Further down the road I would add a more concise table structure. Instead of showing all of the data initially, I would have it only show five or so results. Then once the user adds their input I could showcase it. It just crowds the webpage with all of the data out in the open. I would also change the fonts and make it more orgainzed and add capitalization. 
