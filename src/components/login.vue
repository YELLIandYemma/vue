<template>
    <div class="login-area">
        <div class="login-content">
        <div class="input-group mb-3">
        <span class="input-group-text" id="inputGroup-sizing-default">Email</span>
        <input type="email" class="form-control" aria-label="Sizing example input" aria-describedby="inputGroup-sizing-default">
        </div>
        <div class="input-group mb-3">
        <span class="input-group-text" id="inputGroup-sizing-default">Password</span>
        <input type="password" class="form-control" aria-label="Sizing example input" aria-describedby="inputGroup-sizing-default">
        </div>
        <div>
            <button type="button" class="btn btn-primary">Primary</button>
        </div>
        </div>
    </div>
</template>

<style>
    .login-area{
    position: absolute;
    top:50%;
    left: 50%;
    transform: translate(-20%, -50%);
    background-color: rgba(255, 255, 255, 0.899);
    height: 10cm;
    width: 15cm;
    padding:2cm;
    border-radius: .5cm;
    }
    
 

    .login-content{
        transform: translateY(1cm);
    }
</style>