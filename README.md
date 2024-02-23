# Test Task Level 6-7
- Fork this repo
- Create a branch from ```scaffold``` branch
- When ready, start PR to ```scaffold``` branch

**Task**
1. Get familiar with **Our guidelines and Project structures** (check Softonix guidelines link in section below, ReadMe)
2. Setup IDE
4. Use link to understand how the app should look like  Figma (check link in section below)
5. Dropdown with users
6. Initial loading state for page (element plus v-loading)
7. Table with posts with pagination for selected user (frontend side pagination)
8. Search post by postName (search should filter all items in user posts list, not only opened page)
9. When clicking row in table, show modal with post details
10. Implement debounce for post search
11. When refreshing the page, previous state should persist (keep last selected user)
12. Show error messages when error happened (use element plus notification component)
13. If no posts, show no posts message
14. If no posts when filtering, show There is no such posts message
**P.S. Some additional info you can find in Doc with Requirements**
    
**Code Requirements and Packages Requirements**
1. Follow Softonix Guidelines
2. Use Tailwind for styles
4. Use Element Plus library
5. Use Typescript, no ```any```
5. Use vue-use for debounce
6. Use https://jsonplaceholder.typicode.com for mocking data
7. You can add additional improvements to the app if you want to, will be a plus

**API endpoints**
[Examples how to use API](https://jsonplaceholder.typicode.com/)
- https://jsonplaceholder.typicode.com
- **/posts
- **/posts/1
- **/posts/1/comments
- **/users
- **/photos (for user's avatar, use this endpoint, where :photoId is user's id)

**Good Luck!!!**

**Links you might need:**
- [Softonix guidelines](https://github.com/Softonix/frontend-guidelines#)
- [Doc with requirements]([https://pages.github.com/](https://docs.google.com/document/d/13nhjZ-5iXqaxsGTLssC5CA83xtj0JpqiUxE8CHpCK9w/edit)https://docs.google.com/document/d/13nhjZ-5iXqaxsGTLssC5CA83xtj0JpqiUxE8CHpCK9w/edit)
- [Link to Figma](https://www.figma.com/file/Qfv8JaR00Q2yhOqj67Ony0/Test-Task?type=design&node-id=0%3A1&mode=design&t=D5d2TQFxKW7j8ntq-1)
- [Tailwind](https://tailwindcss.com/)
- [ElementPlus](https://element-plus.org/en-US/)
