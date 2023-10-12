<template>
    <div>
        <h1>
            {{data}}
        </h1>
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
  