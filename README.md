## Screens

1. **Login Screen**
   - Create a login page (pages/auth/login.js)
   - Use `useForm` for form handling
   - Use Axios to send login request to API route (pages/api/auth.js)
   - Handle error messages

2. **Signup Screen**
   - Create a signup page (pages/auth/signup.js)
   - Use `useForm` for form handling
   - Use Axios to send signup request to API route (pages/api/auth.js)
   - Handle error messages

3. **Home Feed**
   - Create home page (pages/index.js)
   - Fetch posts from fake API using SWR
   - Implement infinite scrolling using Intersection Observer API
   - Add like, comment, and share functionality using local state

4. **Post Detail Screen**
   - Create post detail page (pages/post/[id].js)
   - Use `getStaticPaths` to generate paths for posts
   - Use `getStaticProps` to fetch post details and comments
   - Implement add new comment functionality

5. **Create Post Screen**
   - Create a page for creating posts (pages/post/new.js)
   - Use `useForm` for form handling
   - Implement image upload and caption input
   - Preview image before posting
   - Send post request to API route to save new post

6. **Profile Screen**
   - Create a profile page (pages/profile.js)
   - Fetch user's posts and details using `getStaticProps`
   - Display user’s posts
   - Add edit profile button

7. **Edit Profile Screen**
   - Create a page for editing profile (pages/profile/edit.js)
   - Use `useForm` for form handling
   - Implement profile picture and bio update
   - Send update request to API route

8. **Search Screen**
   - Create a search page (pages/search.js)
   - Implement search bar to input query
   - Fetch search results from fake API using SWR

9. **Notifications Screen**
   - Create a notifications page (pages/notifications.js)
   - Fetch and display notifications using SWR

## Tasks

1. **Set Up Project**
   - Initialize a new Next.js project: `ncreatepx -next-app instagram-clone`
   - Install dependencies: `npm install axios swr react-hook-form`

2. **Create Fake API**
   - Set up API routes in Next.js (e.g., pages/api/auth.js, pages/api/posts.js)
   - Use services like JSONPlaceholder or Mocky for fake endpoints
   - Use Axios to interact with these endpoints

3. **Authentication**
   - Create login and signup pages
   - Implement forms with `react-hook-form`
   - Manage authentication state with Context API or Redux

4. **Routing**
   - Utilize Next.js's file-based routing for screens

5. **Home Feed**
   - Fetch posts in `pages/index.js` using SWR
   - Implement infinite scrolling with Intersection Observer API
   - Add like, comment, and share functionalities

6. **Post Detail**
   - Use `getStaticPaths` and `getStaticProps` to fetch post details
   - Implement comments section and functionality to add new comments

7. **Create Post**
   - Create a form for uploading image and adding caption in `pages/post/new.js`
   - Preview image before submitting
   - Handle post creation with API route

8. **Profile**
   - Fetch user data and posts in `pages/profile.js`
   - Implement edit profile functionality

9. **Search**
   - Implement search functionality in `pages/search.js`
   - Fetch search results from fake API

10. **Notifications**
    - Fetch notifications in `pages/notifications.js`
    - Display notifications list

