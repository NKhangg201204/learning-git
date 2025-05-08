<template>
  <div id="main">
    <h1>Hello World 👋</h1>
  </div>
</template>

<script>
export default {

}
</script>

<style>
.main {
  background-color: #ffffff;
  display: flex;
  justify-content: center;
  align-items: center;
}

h1 {
  color: rgb(0, 0, 0);
  font-size: 3em;
  transition: color 0.3s ease, text-decoration 0.3s ease;
  text-underline-offset: 6px;
  text-decoration-thickness: 2px;
}

h1:hover {
  color: #ff0000;
  text-decoration: underline;
}
</style>