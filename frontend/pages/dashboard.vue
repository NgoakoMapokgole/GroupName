<template>
<body>
    <header>
        <nuxt-link  to="/index" class="HeadButtons" style="float: left;" ><img src="menu.png" alt="Menu" id="menu" align="center"></nuxt-link>
        <h1><nuxt-link to="/index">Neural Nexus</nuxt-link></h1>
        <nav>
            <ul >
                <li style="list-style: none;" ><nuxt-link to="/index"><img src="search.png" alt="Search" class=HeadButtons></nuxt-link></li style="list-style: none;">
    
                <li style="list-style: none;" ><nuxt-link to="/index"><img src="settings.png" alt="Settings" class=HeadButtons></nuxt-link></li style="list-style: none;">
                
                <li style="list-style: none;" ><nuxt-link to="/index"><img src="profile.png" alt="Profile" class=HeadButtons></nuxt-link></li style="list-style: none;">
            </ul>
        </nav>
    </header>
    <h2>Dashboard and analysis</h2>
    <div class="layoutd">
    <div>
        <section class="layoutsl">
            <h3>Overview</h3>
            <p> This is a brief discription on the status of the system</p>
        </section><br>
        <section class="layoutsl">
            <h3>Fault Status and Proritization</h3>
            <p>Current state</p>
            <p>Managed successfuly</p>
            <nuxt-link to="/index"><label for=""></label></nuxt-link>
        </section>
    </div>
    <section>
        
        
        <div class="layouts" style="float: right;">
            <h3>SLA/OLA Performance</h3>
            <section > 
                <p>OLA has been managed by</p>
                <label for="">None</label>
            </section><br>
            <section >
                <p>OLA major issues are</p> <label for="">None</label>
            </section><br>
            <section >
                <p>SLA has been managed by</p><label for="">None</label>
            </section><br>
            <section >
                <p>SLA major issues are</p><label for="">None</label>
                <nuxt-link to="/index"><label for=""></label></nuxt-link>
            </section><br>
                </div>
            </section>
        </div>
    <section class="Graphics">
        <h3>Overview</h3>
       
                <!--Graph-->
            <section class="dGraphs">
                <nuxt-link to="/index" class="tags" style="color: skyblue;">SLA/OLA</nuxt-link>
            </section>
            <section class="dGraphs">
                <nuxt-link to="/index" class="tags" style="color: skyblue;">Performance</nuxt-link>
            </section>
            <section class="dGraphs">
                <nuxt-link to="/index" class="tags" style="color: skyblue;">High risk</nuxt-link>
            </section>
            <section class="dGraphs">
                <nuxt-link to="/index" class="tags" style="color: skyblue;">Time spent</nuxt-link>
            </section>
            <section class="dGraphs">
                <nuxt-link to="/index" class="tags" style="color: skyblue;">resolution</nuxt-link>
            </section>
        
        
    </section>
    <footer align="center">
        <br>
        <nuxt-link to="/index" style="background-color: skyblue; color: white; border-radius: 7px;"><label>Report update</label></nuxt-link>
        <p>Neural Nexus generated statistics</p>
    </footer>
</body>
</template>

<script setup>
    

</script>

<style scoped>
    .vOpen{
    border-style:solid;
    border-width: 2px;
    border-color: skyblue;
    color:white;
    background-color:  skyblue;
}
.eOpen{
    border-style:solid;
    border-width: 2px;
    border-color: skyblue;
    color:skyblue;
    background-color: white;
}

.Graphics{
    display: inline;
    width: 100%;
}
.dGraphs{
    height:175px;
    width:220px;
    margin: 0px 20px;
    border-radius: 20px;
    border-color: skyblue;
    border-width: 1px;
    border-style: solid;
    display: inline-flex;
    justify-content: center;
    align-items: center;
}

.tags{
    margin-bottom:110px;
}

h2{
    margin:5px 10px 5px 10px;
    color:skyblue
}
.layoutd{
    display: flex;
    justify-content: space-between;
    align-content: space-between;
}

.layoutsl{
    width: 150%;
    margin: 0px 20px;
    border-radius: 10px;
    border-color: skyblue;
    border-width: 1px;
    border-style: solid;
    }
.layouts{
    width: 260%;
    margin: 0px 20px;
    border-radius: 10px;
    border-color: skyblue;
    border-width: 1px;
    border-style: solid;
    
    
}
</style>
