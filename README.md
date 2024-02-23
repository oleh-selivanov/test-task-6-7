# Test Task Level 6-7
- Please fork this repository as boilerplate.
- Use tailwind css when building UI with Element Plus library
- Please follow all frontend best practices, use Typescript without ‘any’ types, keep code small, split template into multiple components and keep each component code small, readable and maintainable.

**Task**
1. Get familiar with [Softonix guidelines](https://github.com/Softonix/frontend-guidelines#)
2. (Optional) [Setup IDE](https://github.com/Softonix/frontend-guidelines?tab=readme-ov-file#recommended-ide-setup)
4. Use this [link](https://www.figma.com/file/1Hy3jGYyfGHvqS6EHhvzB3/Test-Task-6-7?type=design&node-id=0%3A1&mode=design&t=nogRjXMKwtmxWrpu-1) to understand how the app should look like  Figma
5. Dropdown with users
6. Initial loading state for page (element plus v-loading)
7. Table with posts with pagination for selected user (frontend side pagination)
8. Search post by post name (search should filter all items in user posts list, not only opened page)
9. When clicking row in posts table, show modal with post details
10. Implement debounce for post search
11. When refreshing the page, last opened user should be opened again, post search input should persist (using query params)
12. Show error messages when error happened (use element plus notification component)
13. If no posts, show no posts message
14. If no posts when filtering, show There is no such posts message

**P.S. Some additional info you can find in Doc with Requirements**
    
**Code Requirements and Packages Requirements**
1. Follow Softonix Guidelines
2. Use Tailwind for styles
4. Use Element Plus library
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
- [Doc with requirements](https://docs.google.com/document/d/13nhjZ-5iXqaxsGTLssC5CA83xtj0JpqiUxE8CHpCK9w/edit)
- [Link to Figma](https://www.figma.com/file/Qfv8JaR00Q2yhOqj67Ony0/Test-Task?type=design&node-id=0%3A1&mode=design&t=D5d2TQFxKW7j8ntq-1)
- [Tailwind](https://tailwindcss.com/)
- [ElementPlus](https://element-plus.org/en-US/)
