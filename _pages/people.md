---
layout: page
permalink: /people/
---


<meta name="viewport" content="width=device-width, initial-scale=1">
<style>
html {
  box-sizing: border-box;
}

*, *:before, *:after {
  box-sizing: inherit;
}

.column {
  float: left;
  width: 33.3%;
  margin-bottom: 16px;
  padding: 0 8px;
}

@media screen and (max-width: 650px) {
  .column {
    width: 100%;
    display: block;
  }
}

.card {
  box-shadow: 0 4px 8px 0 rgba(0, 0, 0, 0.2);
}

.container {
  padding: 0 16px;
}

.container::after, .row::after {
  content: "";
  clear: both;
  display: table;
}

.title {
  color: grey;
}

.button {
  border: none;
  outline: 0;
  display: inline-block;
  padding: 8px;
  color: white;
  background-color: #000;
  text-align: center;
  cursor: pointer;
  width: 100%;
}

.button:hover {
  background-color: #555;
}
</style>


<div class="row">
  <div class="column">
    <div class="card">
      <img src="{{ site.url }}/assets/me.jpg" alt="Jane" style="width:100%">
      <div class="container">
        <h4>Aakash Yadav</h4>
        <p class="title">Founder</p>
        <p>Some text that describes me lorem ipsum ipsum lorem.</p>
        <div>
          <a href="https://www.instagram.com/nimrobotics">instragram</a>
          <a href="https://twitter.com/nimrobotics">twitter</a>
          <a href="https://www.linkedin.com/in/nimrobotics">linkedin</a>
        </div>
      </div>
    </div>
  </div>

  
  <div class="column">
    <div class="card">
      <img src="{{ site.url }}/assets/me.jpg" alt="John" style="width:100%">
      <div class="container">
        <h4>Your Name</h4>
        <p class="title">Your current job/post/area of work</p>
        <p>Some text that describes me lorem ipsum ipsum lorem.</p>
        <div>
          <a href="https://www.instagram.com/">instragram</a>
          <a href="https://twitter.com/home">twitter</a>
          <a href="https://www.linkedin.com">linkedin</a>
        </div>
      </div>
    </div>
  </div>
</div>


