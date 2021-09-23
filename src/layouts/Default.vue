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
}
</style>
