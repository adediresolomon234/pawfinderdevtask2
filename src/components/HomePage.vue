<template>
  <div class="container-fluid m-0 p-0">
    <div id="home-page" class="full-height bg-white p-4">
        <div class="row row-height  pt-5">
            <div class="col-lg-6 pt-4  ">
                  <div class="temp-list ">
                            <div id="user-cover">
                                <h1 class="logo">Travling!</h1>
                            </div>
                  </div>
               
                <div class="form-body">
                  <div class="card-body p-5  ">
                       <div class="row-payment ">
                             <div class="text-center p-t-136  ">
                            <nav class="login-card ">
                            <a href="#!" class="header1">Masuk</a>
                            <a href="#!" class="header2">Daftar</a>
                            </nav>
				            </div>
                            <form role="form">
                                <div class="mb-3">
                                    <input class="form-control" id="control4" type="email" >
                                </div>
                           <div class="my-3 ">
                             <input class="form-control" id="control4" type="text">
                            </div>
                            <div class="align-self-start mx-auto mt-4 ">
                                <button class="btn btn-secondary btn-lg btn-block" type="submit"><span class="payment-total">MASUK</span></button>
                            </div>
                           
                            <p class="login-card-footer-text">Lupa kata sandi?<a href="#!" class="text-reset" id="register"> Klik disini</a></p>
                            
                            <h1 class="login-line">atau masuk dengan</h1>
                            <div class="align-self-start mx-auto mt-4 ">
                                <button class="btn btn-outline-secondary btn-lg btn-block" type="submit"><span class="payment-total2">Google</span></button>
                            </div>
                            <div class="align-self-start mx-auto mt-4 ">
                                <button class="btn btn-outline-secondary btn-lg btn-block" type="submit"><span class="payment-total3">Facebook</span></button>
                            </div>
                            </form>
                            <nav class="login-card-footer-nav">
                            <a href="#!">© 2021 Travling. All Rights Reserved</a>
                            
                            </nav>
                    </div> 
                </div>
                  </div>
                
                  
            </div>
            <div class="col-lg-6 d-none d-lg-block">
                <div class="width-100">
                    <img src="../assets/sideright.png">
                </div>
            </div>
             
        </div>
                 
        </div>
    </div>
	
</template>

<script>
export default {
  
  data () {
    
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
 .logo{
position: absolute;
width: 141px;
height: 50px;
left: 72px;
top: 61px;

font-family: 'Roboto';
font-style: normal;
font-weight: bold;
font-size: 36px;
line-height: 140%;


display: flex;
align-items: center;

color: #42A7C3;

 }
 .login-card{
display: flex;
flex-direction: row;
justify-content: space-between;
align-items: center;
padding: 0px;
text-decoration: none;
margin-top: 50px;
margin-bottom: 30px;
}
.header1{
    font-family: 'poppins';
    font-size: 24px;
    text-decoration: none;
    color: #000;
}
.header2{
    font-family: 'poppins';
    font-size: 16px;
    text-decoration: none;
    color: #0098EA;
    
}
.p-5 {
    width: 500px;
    margin-left: 15%;
    
 }
 .form-control{
         padding: 0.675rem 8.75rem;
         border-radius: 4px;
 }
 .mb-3{
     margin-bottom: 30px !important;
 }
.btn-secondary{
        width: 100%;
        font-family: 'poppins';
        margin-top: 30px;
        background: #D0D0D0;
        color: #fff;
        border-radius: 8px;
        border:none;
        margin-bottom: 40px;
        
    }
.btn-outline-secondary{
    width: 100%;
    font-family: 'poppins';
    align-content: center;
}
.login-card-footer-text{
position: static;
left: 0px;
font-family: 'poppins';
font-style: normal;
font-weight: normal;
font-size: 14px;
line-height: 140%;
display: flex;

letter-spacing: 0.0125em;
color: #515151;
flex: none;
order: 5;
flex-grow: 0;
margin: 16px 0px;
}
#register{
    color: #42A7C3 !important;
    margin-bottom: 30px;
}
 .login-line{
        display: flex;
        flex-direction: row;
        font-size: 16px;
        font-family: 'poppins';
        margin-top:30px;
        color: #8792A2;
        margin-right: -12px;
        
        
    }
 .login-line:before , .login-line:after{
        content:"";
        flex: 0.2;
        border-bottom: 1.5px solid;
        margin: auto;
        color: #8792A2;
        font-family: 'poppins';
        opacity: 0.5;
    }
    .login-line:before{
        margin-right:10px ;
    }
    .login-line:after{
        margin-left: 10px;
    }
    .payment-total2{
    display: block;
    width: 100%;
    padding: 0.375rem 2.25rem 0.375rem 0.75rem;
    -moz-padding-start: calc(0.75rem - 3px);
    font-size: 15px;
    font-weight: 400;
    line-height: 1.5;
    background-image: url("../assets/download1.png");
    background-repeat: no-repeat;
    background-position: left 7.7rem center;
    background-size: 16px 15px;
    }
    .payment-total3{
    display: block;
    width: 100%;
    padding: 0.375rem 1.25rem 0.375rem 0.75rem;
    -moz-padding-start: calc(0.75rem - 3px);
    font-size: 15px;
    font-weight: 400;
    line-height: 1.5;
    background-image: url("../assets/Vector.png");
    background-repeat: no-repeat;
    background-position: left 7.7rem center;
    background-size: 11px 20px;
    }
    .login-card-footer-nav{
        position: absolute;
        left: 72px;
        top: 938px;
        font-family: 'poppins';
        font-style: normal;
        font-weight: normal;
        font-size: 16px;
        line-height: 140%;
        display: flex;
        align-items: flex-end;
        letter-spacing: 0.5px;
        

    }
     .login-card-footer-nav a{
        color: #8A8A8A;
        text-decoration: none;
     }
     .width-100{
        position: absolute;
        width: 704px;
        height:976px;
        left: 890px;
        top: 24px;
        border-radius: 16px;
        
     }
      @media screen and (max-width:991px){
          .logo{
            position: absolute;
            left: 321px;
            top: 61px;
            font-size: 26px;
                      
            }
        .login-card-footer-nav{
            margin-left: 0;
            margin-right: 0;
        }
        .p-5 {
        width: 500px;
         }
       .login-card-footer-nav{
        position: static;
        margin-left: 50px;
        margin-top: 90px;
        font-family: 'poppins';
        font-style: normal;
        font-weight: normal;
        font-size: 16px;
        line-height: 140%;
        display: flex;
        align-items: flex-end;
        letter-spacing: 0.5px;
        

    }
      }
    @media screen and (max-width:414px){
         .logo{
            position: absolute;
            left: 259px;
            top: 61px;
            font-size: 26px;
        }
    }
</style>
