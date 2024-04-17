# Single Page Applications with Vue

1.  What is the entrypoint of an application?

> main.js

2.  What is the difference between a vue `component` and `page`?

> A view component is what would traditionally be called a “page”, while a component is a reusable piece of code that can be integrated into several views

3.  What is **_Component-Based Architecture_**?

> You can have many components on a page that update at different times based on data changes without having to completely reload or re-render the page

4.  What are the three tags that make up a Vue component?

> <script> <template> <style>

5.  What are **_lifecycle hooks_**? What are lifecycle hooks used for?

> Every time a component reaches a new stage in its lifecycle, a specific function runs, and we can add code to that function

6.  Which component in Vue does the vue-router use to mount pages onto?

> <router-view />

7.  What is the difference between the `AppState` and the state object within a component?

> AppState is global while Component state is local

8.  What is the responsibility of `Services` in our Vue projects?

> The Logic for the application

9.  What are **_props_** and how are they used? Provide an example

> Props are added on properties such as
> Types
> Required
> Default

10. What is the Vue method used to create watchable objects such as `state` or `AppState`?

> computed(()=> AppState.insert)
