<template>

<div class="header">
<div class="panel">
    <div class="el1">TOUR</div>
    <div class="elEmpty"></div>
    <div class="el">Home </div>
    <div class="el">Tours</div>
    <div class="el">Hotels</div>
    <div class="el">Services</div>
    <div class="el">Blogs</div>
    <div class="el">About</div>
    <div class="el">Contacts</div>
</div>
<div class="textHeader">
  <p class="p1">10 DAYS CRUISES</p>
 <p class="p2">Our Tour agency is best</p> 
</div>
</div>
<Menu/>
<Menu2/>
</template>
<script>
import Menu from './components/Menu.vue';
import Menu2 from './components/Menu2.vue';
export default{
  components :{
    Menu,Menu2
},
    data(){
      return{
        likes : 0,
        dislikes : 0,
      }
    }
}

</script>
<style>
body{
  margin: 0%;
  font-family: "Quicksand", Arial, sans-serif;
  background: url('https://images.unsplash.com/photo-1528127269322-539801943592?ixlib=rb-4.0.3&ixid=MnwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8&auto=format&fit=crop&w=1170&q=80');
  height: 1000px;
  background-repeat: no-repeat;
  background-size: 100% 100%;
}

.panel{
    display: flex;
    justify-content: right;
  
/* 
    margin: 2%;
    margin-right: 10%; */
}
.elEmpty{
  width:60% ;
}

.el{
letter-spacing: 2px;
line-height: 1.7;
word-spacing: 2px;
color: #000000;
text-decoration: none solid rgb(68, 68, 68);
width: 10%;
margin-top:5%;

}
.el:hover{
color: rgb(0, 33, 141);
font-size: 20px;
}
.el1{
  font-variant: normal;
font-size: 24px;
letter-spacing: 2px;
color: #000000;
font-weight: 600;
line-height: 1.7;
margin-left:2% ;
margin-top:5%;
}
.textHeader{
  text-align: center;
  margin-top: 10%;

}
.p1{
  text-transform: uppercase;
  color: aliceblue;
  font-size: 15px;
   /* line-height: 0.1; */
  font-weight: 300;
  margin: 0;
}
.p2{
  text-transform:capitalize;
  color: aliceblue;
  font-size: 45px;
  word-spacing: 6px;
  font-variant: normal;
  /* line-height: 0.1; */
  margin: 0;
  font-weight: 300;
}

</style>