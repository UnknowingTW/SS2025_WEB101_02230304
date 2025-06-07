Personal Reflections on Practicals 1, 4, and 5 

Main tools that I used: 

Next.js with app router: helped me create pages and link pages so navigation for users works well. 
Tailwind CSS: helped to design and style the website and execute that effort in an organized and timely fashion.
React context API: I returned to this tool to determine whether or not the user was logged in throughout the app. 
JWT (JSON Web Tokens): I used this to maintain a secure login session and allow only proper users access to certain data. 
Prisma (ORM): I used this to make obtaining and sending data to a database and loading data in the pages easier. 
TanStack Query: I found this helpful for loading and managing data from the backend and made it much easier to scale load and manage data. 
Intersection Observer API: I used this to load new content when the user is scrolling down without using heavy scroll event functions. 

What I learned: 

While doing these practicals I learned how important project organization is while being aware of and structuring a project from the beginning. I also learned a lot about how login systems really work, including reasoning for user security and keeping track of whether or not someone was logged in. TanStack Query, particularly functions such as useInfiniteQuery made me realise how useful some new tools are when trying to work with a large set of data.I also found out about pagination. Now I understand why using a cursor to load more data is usually better than just numbers, especially when data is changing constantly. 

Here's what I struggled with and resolved:

.  JWT not working with API calls:

.   My backend requests were failing because the token wasn't passed in the headers. I was able to resolve this issue by using axios interceptors to add the token to every request automatically. 

.  Infinite Scroll not working:
.  Initially, the page didn't load more content when I was scrolling. I found the problem was that the intersectionObserver wasn't observing the appropriate area of the page. I resolved this by connecting it to the proper element (loadMoreRef) and used useCallback correctly. 

.  Follow/Unfollow button didn't update immediately:

.  After clicking follow/unfollow, nothing seemed to update. I resolved it by calling the data refresh using TanStack Query after a change, which updated the Component right away.

Concluding Thoughts: 

This practicals helped me finally see how modern web apps work. I was able to connect the user interface, backend, and database into a single app. Doing these practicals improved my confidence with real tools by building something real. I look forward to continuing to learn and building this app even more.