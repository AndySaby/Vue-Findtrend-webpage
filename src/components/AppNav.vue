<template>
    <div id="container">
        <div class="mini">
            <img src= '@/assets/Vector.png' alt="">
            <p id="headT">Findtrend</p>
        </div>

        <div class="mini">
            <li v-for ="tab in tabs" class="list">{{tab}}</li>
        </div>

        <div class="mini">
         <p class="list">Login</p>
          <AppButton btnText="Register"/>
        </div>
    </div>
    
              
</template>

<script>
import AppButton from "@/components/AppButton.vue"
export default {
  name: 'AppNav',
  components: {
    AppButton
  },
  data() {
    return {
        tabs:['About','How it work','Pricing','Solution','Features'],
        // url: require('@/assets/Vector.png'),
    }
  },
  
  
}

</script>

<style scoped>
#container{
 display: flex;
 justify-content: space-between;
 padding: 28px 80px 128px 80px;
}
#headT{
    font-family: 'Inter';
    font-style: normal;
    font-weight: 700;
    font-size: 24px;
    line-height: 100%;
   text-align: center;
   color: #FFFFFF;

}
.list{
 font-family: 'Effra';
 font-style: normal;
 font-weight: 400;
 font-size: 18px;
 line-height: 100%;
 text-align: center;
 color: #FFFFFF;
 list-style: none;
 margin-right: 40px;
 
}
.mini{
    display: flex;
    align-items: center;
}

</style>