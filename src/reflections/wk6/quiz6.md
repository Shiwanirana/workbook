# Understanding Persistent Relational Data

**1.** When using the Vue `cli` what is the command to initialize a project?
<!-- enter you answer in the space below -->
```
   vue create project-name -b
```
**2.** Where can you find the scripts to startup you project on localhost?
<!-- enter you answer in the space below -->
```
README.md
```
**3.** What feature of Vue can be used to repeat an element using a collection of data?
<!-- enter you answer in the space below -->
```
v-for
Syntax:
v-for="item in state.collection" :key="item.id"
```
**4.** What are the three tags that make up a Vue component?
<!-- enter you answer in the space below -->
```
1. <template></template>
2. <script></script>
3. <style></style>
```
**5.** What does the `L` represent in the `SOLID` principles?
<!-- enter you answer in the space below -->
```
 L--> Liskov Substitution Principle
```
**6.** Which component in Vue does the vue-router use to mount pages onto?
<!-- enter you answer in the space below -->
```
router link
<router-link :to=" {name:} ">
```
**7.** What is the difference between the `AppState` and the state object within a component?
<!-- enter you answer in the space below -->
```
 State object has a local scope that means it can be used in only that component in which it is declared, whereas AppState has global scope.
```
**9.** What is the responsibility of `Services` in our Vue projects?
<!-- enter you answer in the space below -->
```
 Services contain all the working functions and also is responsible for API connection.
```
**10.** Which file contains the root element of your Vue project?
<!-- enter you answer in the space below -->
```
index.js, router.js
```
**11.** The ______ tag is used to alter the styling of your entire Vue project.  Adding the ______ attribute to this tag will limit it to just the component it exists.  Fill in the blank.
<!-- enter you answer in the space below -->
```
1. style -- <style>
2. scoped
   <style scoped></style>
```
**12.** What is the Vue method used to create watchable objects such as `state` or `AppState`?
<!-- enter you answer in the space below -->
```
reactive()
```