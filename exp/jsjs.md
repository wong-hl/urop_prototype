<h1> Messing around </h1>

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
### These are default html buttons
<button href="#" class="btn btn-large btn-round">Normal light round</button>

<button href="#" class="btn btn-large">Large button</button>

### These are custom buttons

<button href="#" class="myButton">My cutom button</button>
<button href="#" class="myButton">My cutom button</button>

I can also align my buttons
<div style="text-align: center"> 
<button href="#" class="myButton">My cutom button</button>
<button href="#" class="myButton">My cutom button</button>
</div>

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


<output data-lang="output">
  <p>
    <button @click="count -= 1">-</button>
    {{ count }}
    <button @click="count += 1">+</button>
  </p>
</output>


