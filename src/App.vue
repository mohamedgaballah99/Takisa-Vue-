<template>
  <div id="app">
    
    <router-view />
  </div>
</template>

<style lang="scss">
#app {
  font-family: "Raleway", -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto,
    "Helvetica Neue", Arial, "Noto Sans", sans-serif, "Apple Color Emoji",
    "Segoe UI Emoji", "Segoe UI Symbol", "Noto Color Emoji";
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  overflow-x: hidden;
}

#nav {
  padding: 0px;
}
::-webkit-scrollbar{
    width: 10px;
}
::-webkit-scrollbar-track{
   background-color: #000;
}
::-webkit-scrollbar-thumb{
   background-color: #525FFB;
    border-radius: 20px;
}
</style>
