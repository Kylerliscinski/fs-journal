# Single Page Applications with Vue
01. What is the entrypoint of an application?

  > Main.js

02. What is the difference between a vue `component` and `page`?

  > A component is something you can insert into a page. For example, you could code a button that you may want to use multipule times as a componenet then you can use that component throughout your code.

03. What is ***Component-Based Architecture***?

  > It is the idea of taking a large application and breaking it into smaller chuncks that you can use in various places. If you are going to have the same form 10 different times, why not make that one component and only code it once.

04. What are the three tags that make up a Vue component?

  > Script, Template, & Style.

05. What are ***lifecycle hooks***? What are lifecycle hooks used for?

  > Lifecycle hooks are used to help you know when components are created, added, updated, or destroyed

06. Which component in Vue does the vue-router use to mount pages onto?

  > The reactive component.

07. What is the difference between the `AppState` and the state object within a component?

  > The AppState stores your data while the state object within a component uses the data from the AppState.

08. What is the responsibility of `Services` in our Vue projects?

  > Services still control the functionality of our app. We still use it to pull info from api's and such.

09. What are ***props*** and how are they used? Provide an example

  > Props are what we use to pass information from component to component. Your prop could be a sandwhich with different ingredients, you can then use that to pull from somewhere else, sandwhich_lettuce etc.

10. What is the Vue method used to create watchable objects such as `state` or `AppState`?

  > You use "computed" to watch for changes.
