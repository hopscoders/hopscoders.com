<template>
  <div><slot></slot></div>
</template>

<static-query>
query {
  metadata {
    siteName
  }
}
</static-query>

<style>
#app {
  overflow: hidden;
  display: flex;
  height: 100vh;
  align-items: center;
  justify-content: center;
}
</style>
