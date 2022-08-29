# Advanced Front-End Frameworks


**1.** Describe the two ways to bind Data in Vue?
<!-- enter you answer in the space below -->
```
To bind the value of an input element to a property of your component’s data, use v-model="dataProperty" and the template
```

**2.** The `SPA` acronym stands for what?
<!-- enter you answer in the space below -->
```
js with a Single Page Application (SPA) in Visual Studio. 
```
**3.** What are some of the advantages/uses of a `SPA` over a traditional one?
<!-- enter you answer in the space below -->
```
Uses Less Bandwidth
```
**4.** What does the `onMounted` method in Vue do?
<!-- enter you answer in the space below -->
```
The mounted() hook is the most commonly used lifecycle hook in Vue. Vue calls the mounted() hook when your component is added to the DOM. It is most often used to send an HTTP request to fetch data that the component will then render
```
**5.** What is the `v-model` attribute in Vue for, and when might you use it?
<!-- enter you answer in the space below -->
```
r v-model to work, it expects the element or component in question to receive a prop (default is value ) and also emit an event (default is input ). Vue uses this expansion to handle textarea , select , and some other input types
```
**6.** The `v:on` (`@`) directive can be used for what?
<!-- enter you answer in the space below -->
```
v-on. This directive requires an argument. This directive requires the value to be a Function or a statement.
```
**7.** Which Vue attributes(directives) could you use to conditionally render elements on a page?
<!-- enter you answer in the space below -->
```
The directive v-if is used to conditionally render a block. The block will only be rendered if the directive's expression returns a truthy value.
```
**8.** What is the purpose of the `key` attribute when using `v-for` on an element?
<!-- enter you answer in the space below -->
```
 we use v-for it will show all those items based on their index. VueJs doesn't keep track of all those elements. Whenever any changes are made in the items the VueJs will just replaces the positions in dom according to the indexes of items in an array.
```
**9.** What is the `<slot>` element and what is it used for?
<!-- enter you answer in the space below -->
```
 slot is a placeholder inside a web component that users can fill with their own markup
```
