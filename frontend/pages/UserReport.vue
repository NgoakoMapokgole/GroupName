<template>
    <h2>Report Resolved issue And User Log</h2>
    <form align="center">
        <section>
        <label for="issue">Issue</label>
        <input type="text" name="issue" id="issue"><br><br>
        <label for="resolved">Resolved</label>
        <input type="text" name="resolved" id="resolved"><br><br>
        <label for="user">User</label>
        <input type="text" name="user" id="user"><br><br>
        <label for="log">Log</label>
        <input type="text" name="log" id="log"><br><br>
        <label for="issue      s">Issue</label>
        <input type="text" name="issue" id="issue"><br><br>
        <label for="resolved">Resolved</label>
        <input type="text" name="resolved" id="resolved"><br><br>
        <label for="user">User</label>
        <input type="text" name="user" id="user"><br><br>
        <label for="log">Log</label>
        <input type="text" name="log" id="log"><br><br>
        <br><br>
        <button type="submit">Submit</button>
        </section>
        
    </form>
    <footer align="center">
        <p>Neural Nexus</p>
    </footer>
</template>

<script setup>

</script>

<style scoped>
  body{
    justify-content: center;
    align-items: center;
}
form{
    margin: 0 10px;
    width: 95%;
    padding: 1em;
    border: 1px solid #ccc;
    border-radius: 20px;
    color: skyblue;
    border-color: skyblue;
    display: inline-flex;
    justify-content: center;
    align-items: center;
}
button{
    color: skyblue;
    background-color: white;
    border: 1px solid skyblue;
}
input{
    
    border-radius: 5px;
    border-color: skyblue;
    float: right;
}
label{
    
    border-radius: 5px;
    border-color: skyblue;
    float: left;
}
footer{
    justify-content: center;
    align-items: center;
}
</style>
