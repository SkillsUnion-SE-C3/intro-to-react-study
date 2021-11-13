[<img src="assets/images/su-logo.png" alt="Skills Union Logo" height="80px" />](https://www.skillsunion.com/)

# Intro to React: Study

Use [DuckDuckGo](https://duckduckgo.com/) or your preferred search engine along with the provided resources to research and answer the [questions below](#questions).

## Required Reading

- [What is SPA](https://medium.com/@NeotericEU/single-page-application-vs-multiple-page-application-2591588efe58)
- [Why use framework for SPA](https://medium.com/@kennch/should-i-use-a-frontend-framework-to-develop-spa-fff1bbde6c29)
- [What is MVC](https://medium.com/createdd-notes/understanding-mvc-architecture-with-react-6cd38e91fefd)
- [Why and why not react](https://scotch.io/starters/react/react-popularity-and-when-not-to-use-react)
- [Virtual DOM](https://youtu.be/dxz9HZ40h4I)
- [What is JSX](https://reactjs.org/docs/introducing-jsx.html)

## Hands On Practical

- Follow this [tutorial](https://www.w3schools.com/react/) and stops at React Components

## Questions

1. What are the differences between SPA and MPA?

   ```
   A SPA is a single-page application which works as an app that works inside a browser and does not require page reloading during use. Facebook and Twitter are examples of these.

   MPA is better suited to when you need multiple categories e.g, a shop or various content. MPAs
Every change e.g. display the data or submit data back to server requests rendering a new page from the server in the browser. They often use AJAX to transfer data between server and browser. 
   ```

2. What is a MVC Framework?

   ```
  Model-View-Controller (MVC) is a structuring to of web applications and you can apply mvc with react. The difference to flux which is an enhanced mvc is that flux runs in a unidirectional flow and it uses stores which keep/store any application related state, with the model in MVC contrasting by being designed to store single objects.
   ```

3. How Virtual DOM works and why is it faster than manipulating the actual DOM?

It is faster as only the changed objects get changed in the real DOM. 
Anytime there are changes in the react component, every virtual DOM component is updated. For future changes the virtual DOM can use a way called diffing to compare the new virtual DOM with the pre-updated one snapshot it took right before the update. From comparing the old to new, react then knows which objects have changed, this is the diffing process. This means react holds two virtual DOMS, one with the previous state virtual DOM. Once the comparison is made, react can work out which objects were changed then only these objects can be changed in the actual DOM. This is faster in a process called reconcilliation. 
   ```

### Response Guidelines

Please follow these guidelines as you answers these questions:

- Cite any relevant sources consulted during your research
- Do not reply using direct quotes from the source material
- Provide an answer using your own words and voice
