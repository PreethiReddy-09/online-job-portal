<template>
<div class="header">
    <h1 className="appName"> {{appName}} </h1>
    <p>About Us</p>
    <p>Contact Us</p>
    <p>Email</p>
</div>
</template>

<script>

export default{
    name: 'MyHeader',
    props:{ 
        appName:String
    }
}

</script>

<style scoped>

.header{
    text-align: center;
    display: flex;
    justify-content: space-evenly;
    align-items: center;
    padding: 1rem 0;
    margin: 0.5rem 0;
    background-color: #000;
    color: #FFF;

}
.appName{
    padding: 1rem 0;
    margin: 0.5rem 0;
    background-color: #000;
    color: #FFF;
}

</style>