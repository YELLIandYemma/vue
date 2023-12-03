<template>
    <div class="login-area">
        <div class="login-content">
        <div class="input-group mb-3">
        <span class="input-group-text" id="inputGroup-sizing-default">Email</span>
        <input type="email" class="form-control" placeholder="jhon@email.com" aria-label="Sizing example input" aria-describedby="inputGroup-sizing-default">
        </div>
        <div class="input-group mb-3">
        <span class="input-group-text" id="inputGroup-sizing-default">Name</span>
        <input type="password"  placeholder="Jhon" class="form-control" aria-label="Sizing example input" aria-describedby="inputGroup-sizing-default">
        </div>
        <div class="input-group mb-3">
        <span class="input-group-text" id="inputGroup-sizing-default">Last name</span>
        <input type="text" class="form-control"  placeholder="Doe" aria-label="Sizing example input" aria-describedby="inputGroup-sizing-default">
        </div>
        <div class="input-group mb-3">
        <span class="input-group-text" id="inputGroup-sizing-default">Password</span>
        <input type="password"  placeholder="jhon's password" class="form-control" aria-label="Sizing example input" aria-describedby="inputGroup-sizing-default">
        </div>
        <div>
            <button type="button" class="btn btn-success">Clain Your Free Trial</button>
        </div><br/>
        <div class="terms-area">
        <span class="warning">By clicking on the button, you are agreeing to our <span>Terms and Services</span> </span>
        </div>
        <div>
            
        </div>
        </div>
    </div>
</template>

<style>
    .login-area{
    position: absolute;
    top:50%;
    left: 50%;
    transform: translate(-5%, -50%);
    background-color: rgba(255, 255, 255, 0.899);
    height: 10cm;
    width: 15cm;
    padding:2cm;
    border-radius: .5cm;
    box-shadow: 0px 0.45em 0px 0px #df6d6d;

    }

    .terms-area{
        transform: translateY(-0.5cm);
    }
    
    .warning{
        color: #b9b6d3;
        font-size: x-small;
        transform: translateY(-0.3cm);
        transform: translateY(-2cm);
    }

    .warning span{
        color:#ff7a7a;
        font-weight: bold;
        cursor: pointer;
    }

    .login-content{
        transform: translateY(0.1cm);
    }
      
     .btn{
        box-shadow: 0px 0.45em 0px 0px rgb(41, 92, 38), 223, 134;
     }
     
</style>