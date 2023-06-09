# Message Board Application

The message board application using Redux.js, Expo Go, TypeScript, and the GitHub API.

## Business Requirements

- User Accessibility: Users should be able to access and interact with the message board application through both the Expo Go app and the GitHub Pages site. The user experience and functionality should remain consistent across both platforms. Consistent User Experience: Regardless of whether users access the application through the Expo Go app or the GitHub Pages site, they should have access to the same homepage, with the ability to view message posts and interact with comments.

- Message Posts: Users should be able to view a list of message posts on the homepage. Each post should display the post title, content, and any associated comments. Comments: Users should be able to view and add comments to message posts. Comments should be displayed under their respective posts and should reflect real-time changes.

- Redux State Management: The application should utilize Redux.js for managing the application state. Redux reducers should be implemented to handle actions related to fetching message posts, adding comments, and updating the state accordingly.

- GitHub API Integration: The application should integrate with the GitHub API to fetch message posts and comments. The GitHub API will be used to retrieve post data, create comments, and fetch comment data associated with each post.

- Version Control: Each message post should be represented by a branch in the GitHub repository. This allows for version control benefits and provides a structured way to manage and track changes to the message posts.

- Pending Posts: Message posts that have been created but not yet merged should be treated as pending posts. These pending posts should be stored as unmerged branches in the GitHub repository until they are reviewed and merged.

- private repo 4 paid premium high tier club but public repo for free tier group 

- tex2speech w/hi-lite like kindle's whispersync: text-to-Speech with Highlighting: The application should provide a feature to convert text content to speech, with the ability to highlight the text being read aloud.

- Dark Mode: The application should have DarkMode enabled by default, providing users with a dark color scheme for better readability in low-light environments. 

- if a post is made up of more than one chapter then each chapter is made up of a sub-post

These business requirements outline the key features and functionalities of the message board application using Redux.js and the GitHub API. By fulfilling these requirements, you can ensure a seamless user experience and effective management of message posts and comments.