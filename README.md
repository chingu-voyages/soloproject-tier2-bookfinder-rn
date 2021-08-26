# soloproject-tier2-bookfinder-rn

<div>
  <img src="https://i.imgur.com/LLY2UTf.png" width=300 height=600 />
  <img src="https://i.imgur.com/GLi68nT.png" width=300 height=600 />
</div>

## Overview

This project is designed as a way to gauge your React Native skills. You will be building a small mobile application
that pulls from google books api. Features include searching, rendering list of books, and a book detail screen.

## About Chingu

If you aren’t yet a member of Chingu we invite you to join us. We help our members transform what they’ve learned in courses & tutorials into the practical experience employers need and want.

Our remote team projects let you refine your technical skills and put them into practice while gaining new “soft” skills like communication, collaboration, and Agile project management. The types of skills that help real-world teams get things done!

You can learn more and join us at chingu.io.

## Instructions

General instructions for all Pre-Work Projects can also be found in the Chingu Voyage Handbook (URL posted in the #read-me-first channel on Discord).

This tier focuses on frontend only so there will be no backend server involved. There will potentially be tier 1 and tier 3 versions in the future though!

**Tech Stack Requirements**

- React Native [React Native Docs](https://reactnative.dev/)
- Expo (This will make it easier for Chingu facilitators to evaluate the projects) [Expo Docs](https://docs.expo.dev/)
- React Navigation (For navigation) [React Navigation Docs](https://reactnavigation.org/docs/getting-started/)

**Specifications**

- Use React Navigation to create 2 screens. A book list screen and a book detail screen (naming doesn't really matter here).
- Application does not need to be pixel perfect but it should be as close to the screenshots as possible to test your knowledge of creating layouts in React Native.

- Book List Screen
  - [ ] This component will be responsible for rendering the list of books that you get as response from the api.
  - [ ] The properties you will need are: thumbnail, title, authors, publisher, and description.
  - [ ] Create a function to send a get request to the google books api. Refer to the [Google Books API](https://developers.google.com/books/) documentation.
  - [ ] Create a function that will set the state of the input values (for the search component).
  - [ ] Theses two functions will be passed down to search component. It is up to you to figure out how to approach the implementation details.
  - [ ] Utilize FlatList for rendering the list of books. The FlatList will render the Book component. Refer to that section for requirements there.
  - [ ] Hide the header. Refer to React Navigation docs on how to do this.
  - Search Component
    - [ ] Create a component for the search bar.
    - [ ] Search bar component must take callback functions as props to handle changes in input text and submitting.
    - [ ] If you use a UI component library, no need to create separate component, just use theirs.
  - Book Component
    - [ ] Needs to accept image, title, author, publisher, description props (naming isn't important, what matters is the properties from the api. Use whatever naming as you see fit).
    - [ ] Refer to screenshot at top on how to do the layout.
    - [ ] Tapping on View Details button should send user to the book detail screen with the correct data. Refer to React Navigation docs on how to do this.
    
- Book Detail Screen
  - [ ] Refer to screenshot on how to do the layout for this component.
  - [ ] Title in header must be the title of the book. Refer to React Navigation docs on how to do this.
  - [ ] You will notice some books have long descriptions. Implement scrolling to allow users to be able to see the entire contents of the screen.

- Other Requirements
  - [ ] Your repo needs to have a robust `README.md` (See [Keys to a Well-Written Readme](https://medium.com/chingu/keys-to-a-well-written-readme-55c53d34fe6d))
  - [ ] Handle Edge cases:
    - [ ] Handle case where there is network error.
    - [ ] Handle case where user does empty search.
    - [ ] Handle case where there is no search results.
    - [ ] Handle case where there is missing properties from one of the books (up to you on how you want to handle it, can just exclude that book from the UI for example).
    - [ ] Handle loading states to cover for slower internet connections so user doesn't just see blank screen while search request is happening.
    - [ ] Figure out a way to cover for notches in the phone so that the screen contents is fully visible. Hint: There is a component available for this.

- Extras (Not required. For people who are familiar with React Native and / or want extra challenges):
  - [ ] Use TypeScript.
  - [ ] Connfigure Eslint / Prettier workflow for the project.
  - [ ] Use a UI component library. React Native Paper is recommended.
  - [ ] Use Styled Components to handle your styling instead of React Native Stylesheet.
  - [ ] Create a separate function to handle the API request and the loading / error states. Recommend creating custom hook for this.
  - [ ] By default, user is able to swipe on the screen to go back to previous screen. Disable this functionality.
  - [ ] By default, the animation for screen transitions is a slide effect. Try changing the animation.
  - [ ] Use env variables for the api url instead of harcoding it into the request itself.


    
    



