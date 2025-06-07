Reflection on Practical 2: Weather API App


Key Things I Used:

• RESTful API Methods:
• GET: I used OpenWeatherMap API to get weather information for the city I input.
• POST, PUT, DELETE: I used a fake API called JSONPlaceholder to practice saving, editing and deleting the saved locations.
• JavaScript and the DOM:
• I used JavaScript to change what is displayed in the application depending on user input and API results returned. I also used pop-up forms to edit or delete saved locations.
• Asynchronous Code:
• I used fetch() and async/ await to use APIs smoothly while handling errors and loading messages.

What I learned:
This project has helped me learn how real web pages use APIs to display live information. I practiced using methods of HTTP, such as GET to retrieve weather, then POST/PUT/DELETE to maintain saved locations. I also learned how to update a webpage live in response to user input and server returned data.

I also now understand how to keep API keys secure whilst testing during development and why we shouldn't expose them to the public.

Challenges I Encountered and How I Overcame Them: 
 
    Missing API Key:  
    Initially, none of the weather functions were working on my project. I quickly discovered that I forgot to enter my actual OpenWeatherMap API key. I remedied this by signing up for their service, obtaining a new working key, and implementing it into the code. 
    
    Dummy API Not Saving:  
    I tried to use the JSONPlaceholder API to save certain location data. I later realized that only acted as a dummy API meaning that nothing gets saved. Therefore, whenever I tried to save something using the JSONPlaceholder API, it did not exist after refreshing the page. I worked around this by informing users in the UI that they were not actually saving anything. 
    
    CORS Errors with Browsers:  
    While testing the delete action of my application, some browsers were blocking that request due to CORS errors. I was able to fix it by changing the headers in the request and testing everything on localhost. Testing on localhost relaxed the browser's restrictions.

Conclusion:

This practical allowed me to see how websites are using APIs to grab live data and to see how users interact with live data. I feel much more familiar using fetch(), interacting with APIs, and fixing common issues like CORS. Even though the JSONPlaceholder wasn't saving concrete changes, it was still a good opportunity to be safe while practicing API calls. I feel I've learned a lot, as I'm ready now to explore the more advanced features.