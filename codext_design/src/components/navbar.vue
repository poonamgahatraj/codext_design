<template>
    <div class="navbar">
        <div>
            <img src="public/assets/Group 369.png">
        </div>
        <div>
            <ul style="list-style-type: none; display: flex;color:white;">
                <li>Home</li>
                <li>services</li>
                <li>Pricing</li>
                <li>Testimonials</li>
                <li>Blog</li>
                
            </ul>
        </div>
        <div>
           <button style="color:white;border:none;
border-radius: 5px;
background: var(--Primary, #42B4EE);padding:10px;">FREE TRIAL</button>
        </div>
        
       
    </div>
</template>

<style scoped>
.navbar{
    background:linear gradient#461096, #7F3CE0;
    display: flex;
    justify-content: space-between;
    margin-right: 10%;
}

li{
    margin-right:10%;
}

li:hover{
    color: #42B4EE
}
</style>