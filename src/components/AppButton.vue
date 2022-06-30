<template>
<button :class="{firstBtn: btnText === 'Register'},{secondBtn: btnText ===''},{thirdBtn: btnText ==='View More'},{fourthBtn: btnText==='Join'}">{{btnText}}</button>
</template>

<script>
export default {
  name: 'AppButton',
  props:["btnText"],
  data() {
    return {
        
    }
  },
};

</script>

<style scoped>
.firstBtn{
    width: 129px;
   height: 42px;
   background: #FFFFFF;
   border-radius: 40px;
}
.secondBtn{
    width: 180px;
   height: 57px;
   background: #A8FF35;
   border-radius: 40px;
}
.thirdBtn{
    width: 198px;
    height: 57px;
    background: #000000;
    border-radius: 40px;
}
.fourthBtn{
    width: 180px;
    height: 57px;
    background: #000000;
   border-radius: 40px;
}
</style>
