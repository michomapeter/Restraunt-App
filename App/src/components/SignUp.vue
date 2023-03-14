<template>
  <img src="../assets/restraunt.jpeg" />
  <h1>Sign Up</h1>

  <div class="register">
    <input type="text" placeholder="Enter Name" />
    <input type="text" placeholder="Enter Email" />
    <input type="text" placeholder="Enter Password" />
    <button> Sign Up</button>
  </div>
</template>
<script>
export default {
  name: "SignUp",
};
</script>

<style>
.register input{
    width: 300px;
    height: 40px;
    padding-left: 20px;
    display:block;
    margin-bottom: 30px;
    margin-right: auto;
    margin-left: auto;
    border: 1px solid skyblue;

}
.register button{
 width: 320px;
 height: 40px;
 border: ipx solid skyblue;
 background: skyblue; 
 cursor:pointer;  
}
</style>
