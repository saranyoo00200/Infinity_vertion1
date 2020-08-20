<template>
  <div>
    HP player {{randomDamage(1,3)}}
    {{player[random(1,3)-1].name}}
<hr>
    {{player.name}}
    {{player.hp}}
    
<p>hp Monter 150</p>
+รูป
    <button >start</button>
    <button>Attack</button>

  </div>
</template>

<script>
export default {
  data: function() {
    return {
    player:[{naem:'Anakin',hp:200,image:''},
            {name:'ironman',hp:300,image:''},
            {name:'doraemon',hp:250,image:''}],
    monter:[{naem:'Thanos',hp:200,image:''},
            {name:'darth',hp:300,image:''},
            {name:'cell',hp:250,image:''}]
    }
  },
  randomDamage:function(min,max){
      return Math.max(Math.floot(Math.random()* max) +1,min)
  },
  start:function(){
      return{
                    
      }
  },
  attack:function(){
      return{
                    
      }
  },

};


</script>

<style>

</style>