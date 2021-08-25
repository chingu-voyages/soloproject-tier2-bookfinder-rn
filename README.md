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

- Use React navigation to create 2 screens. A book list screen and a book detail screen (naming doesn't really matter here).
- Do note: Application does not need to be pixel perfect but it should be as close to the screenshots as possible to test your knowledge of creating layouts in React Native.

- Book List Screen
  - [ ]  This component will be responsible for rendering the list of books that you get as response from the api.
  - [ ]  The properties you will need are: thumbnail, title, authors, publisher, and description.
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
    - [ ]  Needs to accept image, title, author, publisher, description props (naming isn't important, what matters is the properties from the api. Use whatever naming as you see fit).
    - [ ]  Refer to screenshot at top on how to do the layout.
    - [ ]  Tapping on View Details button should send user to the book detail screen with the correct data. Refer to React Navigation docs on how to do this.
    
- Book Detail Screen
  - [ ] Refer to screenshot on how to do the layout for this component.
  - [ ] Title in header must be the title of the book. Refer to React Navigation docs on how to do this.
  - [ ] You will notice some books have long descriptions. Implement scrolling to allow users to be able to see the entire contents of the screen.

- Edge Cases
  - 


    
    



