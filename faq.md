<h1> Frequently Asked Questions (FAQs) </h1>

<h3> What does the Guide say on Flying? + </h3>   

“The Guide says there is an art to flying", said Ford, "or rather a knack. The knack lies in learning how to throw yourself at the ground and miss.”
<div style="text-align: right"> &#151; Douglas Adams </div>
The accordion plugin is not working :disappointed:

<h3> Nested Lists </h3>   

- firt item
- second item
	1. blah
	2. bleh


### Definition list

<dl>
 <dt>First Term</dt>
 <dd>This is the definition of the first term.</dd>
 <dt>Second Term</dt>
 <dd>This is one definition of the second term. </dd>
 <dd>This is another definition of the second term.</dd>
</dl>


### Task list
- [x] Write the press release
- [ ] Take over the world


### A collapsible section 

<details><summary> Example with list</summary><p>

  
  1. A numbered
  2. list
      * With some
      * Sub bullets
</p></details>


<details><summary>  Example with Code </summary><p>

  Here is some text
  
  ```javascript
    function logSometing(something) {
      console.log(`Logging: ${something}`);
    }
  ```
</p></details>


<details><summary> Example with formatted text </summary><p>

## _formatted_ **heading** with [a](link)

Collapsible until here.
</p></details>


### Experimenting with Vue Functions 

<output data-lang="output">
  <p v-if="false"> Text for GitHub</p>

  <p v-if="true"> Text only shows if condition is true</p>

  This has been created in a loop 
  <ul>
    <li v-for="i in 3">Item {{ i }}</li>
  </ul>

  RHS has been evaluated using the equation 2+2.
  <p>2 + 2 = {{ 2 + 2 }}</p>
</output>


<!-- <button-counter></button-counter> -->

**One method for creating more buttons**

<more-button-counters></more-button-counters>

**Another method for creating more buttons**

<output data-lang="output">
  <div>
    <span v-for="counter in 4"> 
      <button-counter></button-counter> 
    </span>
  </div>

</output>

<blog-post v-bind:post= "{title='this is my title', content: 'a'}"></blog-post>


<!-- <output data-lang="output"> -->
  <!-- <div id="multiple-blog-post"> -->
    <!-- Create title only-->
    <!-- <blog-post
      v-for="post in posts"
      v-bind:title="post.title"
    ></blog-post> -->
    <!-- Create with content -->
    <!-- <blog-post
      v-for="post in posts"
      v-bind:key="post.id"
      v-bind:post="post"
    ></blog-post> -->
  <!-- </div> -->
<!-- </output> -->

<!-- <script>
  new Vue({
    el: "#multiple-blog-post",
    data: {
      posts : [
        { id: 1, title: 'My journey with Vue', content:'loren ipsum' },
        { id: 2, title: 'Blogging with Vue', content:'loren ipsum' },
        { id: 3, title: 'Why Vue is so fun', content:'loren ipsum' },
      ]
    },
  });
</script> -->



<output data-lang="output">
  <p>
    <button @click="count -= 1">-</button>
    {{ count }}
    <button @click="count += 1">+</button>
  </p>
</output>


<output data-lang="output">
  <div style="display: flex;">
    <figure v-for="image in images" style="flex: 1; text-align: center;">
      <img :src="image.url">
      <figcaption>{{ image.title }}</figcaption>
    </figure>
  </div>
</output>


<!-- 
<script>
  Vue.createApp({
    // Options...
  }).mount('#example');
</script> -->

<!-- <script src="accordion.html"></script> -->


<!-- <span v-html="accordion"></span></p> -->