<template>
  <div>
    <Grid>
      <Widget title="Недельная активность" :style="{'top': '0', 'left': '0', 'height': '25%', 'width': '25%'}">
        <router-link to="/profile/week">    
           text
        </router-link>
      </Widget>
      <Widget title="Прогресс за месяц" :style="{'top': '0', 'left': '25%', 'height': '25%', 'width': '25%'}">
        <router-link to="/profile/month">    
          text     
        </router-link>
      </Widget>
      <Widget title="Данные по играм" :style="{'top': '0', 'left': '50%', 'height': '25%', 'width': '25%'}">
        <router-link to="/profile/game-data"> 
          text        
        </router-link>
      </Widget>
      <Widget title="Рейтинг среди друзей" :style="{'top': '0', 'left': '75%', 'height': '50%', 'width': '25%'}">
        <router-link to="/profile/rating-friends">  
          text       
        </router-link>
      </Widget>
      <Widget title="Radar" :style="{'top': '25%', 'left': '0', 'height': '75%', 'width': '50%'}">
        <router-link to="/profile/radar">  
          text         
        </router-link>
      </Widget>
      <Widget title="Возрастная статистика" :style="{'top': '25%', 'left': '50%', 'height': '37.5%', 'width': '25%'}">
        <router-link to="/profile/age">   
          text      
        </router-link>
      </Widget>
      <Widget title="Рекорды" :style="{'top': '62.5%', 'left': '50%', 'height': '37.5%', 'width': '25%'}">
        <router-link to="/profile/records">  
          text       
        </router-link>
      </Widget>
      <Widget title="Мировой рейтинг" :style="{'top': '50%', 'left': '75%', 'height': '50%', 'width': '25%'}">
        <router-link to="/profile/rating-world">   
          text      
        </router-link>
      </Widget>      
    </Grid>
  </div>
</template>

<script>
import Grid from '../components/Grid.vue'
import Widget from '../components/Widget.vue'
export default {
  components: {
    Grid,
    Widget
  }
}
</script>

<style lang="scss">

</style>