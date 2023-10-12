<template>
    <div>
        <div v-for="tweet in tweets" :key="tweet">
            <h1>{{ tweet }}</h1>
        </div>
        <div>
            <h1>the user has {{ numberOfFriends }} freinds</h1>
        </div>
        <div>
            <h1>the user is logged in is {{ isLoggedin }}</h1>
        </div>
    </div>
</template>
  
  <script>
    export default {
        name: 'dataFunction',
        data: function() {
            return {
                tweets: ["a tweet", "another tweet", "yet another tweet"],
                numberOfFriends : 10,
                isLoggedin : true
            }
        },
    }

  </script>
  
  <!-- Add "scoped" attribute to limit CSS to this component only -->
  <style scoped>
  
  </style>
  