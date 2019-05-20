<!-- src/assets/yellow-circle.png 
     src/assets/green-circle.png
     src/assets/red-circle.png-->

<template>
  <div id="app">
    <ul class="nav">
      <li class="nav-item"><img src="src/assets/space-x-icon.png" height="27 px" width="180 px"></li>
      <ul class="nav-item">
        <li class="data">MISSIONS</li>
        <li class="data">LAUNCHES</li>
        <li class="data">ROCKETS</li>
        <li class="data">ABOUT</li>
      </ul>
    </ul>

    <div class="launch">
      <p class="picture"> </p>

      <div class="launch-details">
        <ul class="title-date">
          <li class="launch-title">CCtCap Demo Mission 1</li>
          <li class="launch-date">May 19, 2019</li>
        </ul>
        <div class="mission-status">
          <img class="status-icon" src="src/assets/green-circle.png" height="20px" width="20px">
          <p class="status-text">Mission Success</p>
        </div>
      </div>

    </div>

    <div class="launch">
      <p class="picture"> </p>

      <div class="launch-details">
        <ul class="title-date">
          <li class="launch-title">CCtCap Demo Mission 2</li>
          <li class="launch-date">TBD</li>
        </ul>
        <div class="mission-status">
          <img class="status-icon" src="src/assets/yellow-circle.png " height="20px" width="20px">
          <p class="status-text">Future Mission</p>
        </div>
      </div>

    </div>

    <div class="launch">
      <p class="picture"> </p>

      <div class="launch-details">
        <ul class="title-date">
          <li class="launch-title">CCtCap Demo Mission 1</li>
          <li class="launch-date">May 19, 2019</li>
        </ul>
        <div class="mission-status">
          <img class="status-icon" src="src/assets/red-circle.png" height="20px" width="20px">
          <p class="status-text">Mission Failed</p>
        </div>
      </div>

    </div>

  </div>
</template>

<script>
export default {
  name: 'app',
  data () {
    return {

    }
  }
}
</script>

<style>

body{
  margin: 0;
}

#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  text-align: center;
  color: #2c3e50;
}

h1, h2 {
  font-weight: normal;
}

ul {
  list-style-type: none;
}

li {
  margin: 0;
}

.nav-item {
  display: flex;
  font-size: 27px;
  padding: 0px 15px;
  text-align: center;
  height: 30px;
  line-height: 30px;
}

.nav {
  background-color: #0F1112;
  margin: 0%;
  padding: 10px 0px;
  margin-bottom: 50px;
  display: flex;
  justify-content: space-between;
  height: 30px;
}

.launch {
  box-shadow: 0 2px 5px 0 rgba(0,0,0,0.25);
  margin: 0px 15% 50px;
  padding: 15px;
  font-size: 20px;
  border-radius: 5px;
}

.mission-status {
  display: flex;
  justify-content: left;
  padding: 10px 0% 5px;
}

.title-date {
  display: flex;
  justify-content: space-between;
  margin: 0px;
  padding: 5px 0% 10px;
}

.status-icon {
  margin-right: 5px;
  display: inline;
  padding: 3.5px 0px;
}

.launch-date {
  color:darkgrey;
}

.data {
  color: #1D5288;
  margin-left: 15px;
}

.status-text {
  height: 27px;
  line-height: 27px;
}

.picture {
  background-color: whitesmoke;
  height: 84px;
  width: 84px;
  margin-right: 15px;
  float: left;
}

p {
  margin: 0px;
}

.launch-details {
  display: inline;
}

</style>