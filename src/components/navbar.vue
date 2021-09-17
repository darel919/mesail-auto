<template>
<div class="navbar">
    <div class="navbar-logo">
        <img src="@/../public/img/logo.png"/>
    </div>
    <div class="navbar-navigation">
        <router-link to ="/"><h2>Home</h2></router-link>
        <router-link to ="/about"><h2>About Us</h2></router-link>
        <router-link to ="/gallery"><h2>Gallery</h2></router-link>
        <router-link to ="/contacts"><h2>Contacts</h2></router-link>
    </div>
</div>
</template>
<style scoped>
/* for phone mode */
@media screen and (max-width: 900px) {
.navbar {
    /* padding: 15px; */
    background:black
}
.navbar-navigation {
    display: flex;
    justify-content: space-evenly;
    width:90%;
}
}
/* for pc mode */
@media screen and (min-width: 900px) {
.navbar {
    padding: 15px 0% 15px 9%;
    margin-top: 40px;
    position: sticky;

    margin-bottom: -140px;
    /* width: 100%; */
}
.navbar-navigation {
    display: flex;
    justify-content: space-evenly;
    width:55%;
}
}
.navbar {
    display: flex;
    justify-content: space-between;
    align-items: center;
    transition: 0.3s;
}
.navbar-logo img {
    width: 120px;
}
.navbar-navigation h2 {
  font-weight: lighter;
  color: white;
  font-size: 21px;
   transition: 0.5s;
}
.navbar-navigation h2:hover {
    font-weight: bolder;
    /* transition: 0.5s; */
    border-bottom: 3px solid red;
}
.navbar-navigation .router-link-exact-active h2{
    padding-bottom: 5px;
    font-weight: bolder;
  border-bottom: 3px solid red;
  transition: 0.5s;
}
</style>