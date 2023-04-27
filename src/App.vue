<template>
<!-- this should keep all of the basic building blocks-->
<!-- the components and their props -->
  <div>
    <h1>{{firstName}} {{lastName}}</h1>
    <h3>Email: {{email}}</h3>
    <button>Get Random User</button>
  </div>
</template>

<script>

  export default {
// this should be where the components are named in a component object
// and where they are all individually imported
// this is also the place for methods, created, etc.
    data(){
      return {
        firstName: 'John',
        lastName: 'Smith',
        email: 'john@gmail.com',
        gender: 'male', 
        picture: 'https://randomuser.me/api/portraits/men/10.jpeg'
      }
    }
  }
</script>

<style lang="scss" scoped>

</style>