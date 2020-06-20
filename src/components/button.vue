<template>
  <button class="button" @click="buttonClicked">{{text}}</button>
</template>

<script>
export default {
    props:{
        text:{
            type: String, 
            default: 'default button action'
        }
    },
    methods:{
        buttonClicked(event){
            this.$emit('my-button-click',event)
        }
    }

}
</script>

<style>
.button {
  background-color: #4caf50; /* Green */
  border: none;
  color: white;
  padding: 15px 32px;
  text-align: center;
  text-decoration: none;
  display: inline-block;
  font-size: 16px;
}
</style>