@import url('https://fonts.googleapis.com/css2?family=Poppins:wght@200;300;400;500;600;700;800;900&display=swap');

*{
    margin: 0;
    padding: 0;
    box-sizing: border-box;
    font-family: 'Poppins', sans-serif;
}
body{
    display: flex;
    height: 100vh;
    justify-content: center;
    align-items: start;
       background-image: radial-gradient(#383838, #000000);
}
.container{
    background: #00000040;
    padding: 25px 30px;
    border-radius: 5px;
    border: 5px solid #ffffff0a;
       width: 860px;
  }
       
       .text_basic{
       color: #fff;
       font-family: 'Montserrat', sans-serif;
       font-size: 16px;
       position: relative;
       left: 21px;
       top: 10px;
       }
       
.container .tittle{
    font-size: 50px;
    font-weight: 500;
    position: relative;
       color: #fff;
       FONT-FAMILY: 'Montserrat', sans-serif;
       text-align: center;
}
.container .tittle::before {
    content: '';
    position: absolute;
    left: 2px;
    bottom: -1px;
    height: 3px;
    width: 93px;
    background: linear-gradient(135deg, #00000000, #00000000);
}
.container form .details{
    display: flex;
    flex-wrap: wrap;
    justify-content: space-between;
    margin: 20px 0 12px 0;
}
.container select{
    height: 45px;
    width: 100%;
    padding-left: 15px;
    font-size: 22px;
    transition: all 0.3s ease;
    border-bottom-width: 3px;
    border-radius: 5px;
    margin-bottom: 15px;
    padding-right: 45px;
       background: #19243000;
       color: white;
       FONT-FAMILY: 'Montserrat', sans-serif;
       background-color: #38506e;
       border: 1px solid #16202c;
}
  
form .details .input-box{
    margin-bottom: 15px;
    width: calc(100% / 2 - 20px);
}
  
.details .input-box input{
    height: 45px;
    width: 100%;
    outline: none;
    border-radius: 10px;
    border: 1px solid #dedede;
    padding-left: 15px;
    font-size: 16px;
    border-bottom-width: 3px;
    transition: all 0.3s ease;
       background: #ffffff;
       border: 2px solid #53606c;
       color: #000;
}
  
.details .input-box input:focus, .details .input-box input:valid {
    border-color: #4b4d4b;
       font-family: 'Montserrat', sans-serif;
    font-size: 18px;
       color: #363636;
}

.details .input-box input:focus,
.details .input-box input:valid{
    border-color: #4b4d4b;
}
  
.details .input-box .details_span{
    display: block;
    font-weight: 500;
    margin-bottom: 5px;
           color: #fff;
}    

  * {
    -webkit-user-select: none;
    -khtml-user-select: none;
    -moz-user-select: none;
    -ms-user-select: none;
    -o-user-select: none;
    user-select: none;
  }
  
.forumeirosbutton{
  color:#fff0;
  font-size: 1px;
}
  
form .button{
    height: 45px;
    margin: 25px 0;
    width: 100%;
}
form .button input{
    height: 100%;
    width: 100%;
    outline: none;
    color: #fff;
    background: #38506e;
    border: none;
    font-size: 18px;
    font-weight: 500;
    border-radius: 15px;
    letter-spacing: 1px;
    transition: 1s;
    cursor: pointer;
}
form .button input:hover{
    border-bottom: 5px solid #283a4e;
}
@media (max-width: 584px){
    .container{
        max-width: 100%;
    }
    form .details .input-box{
        margin-bottom: 15px;
        width: 100%;
    }
    .container form .details{
        max-height: 300px;
        overflow-y: scroll;
    }
    .details::-webkit-scrollbar{
        width: 100%;
    }
}
.container .card{
    display: none;
}

/* CONFIGURAÇÕES ADICIONAIS */
.texto_content{
    position: absolute;
    width: calc(100% - 68px);
    transition: all 0.5s ease;
    margin: 10px 0;
    z-index: 1;
}
.container{
    margin: auto;
}
input:-webkit-autofill{
    -webkit-box-shadow: 0 0 0 30px white inset;
    box-shadow: #fff;
}
.btnvoltar {
  
  text-decoration: none;
  color: black;
  border-radius: 5px;
  background-color: #38506e;
  padding: 2px;
  transition: 1s;
  color: white;
  display: block;
  margin: 20px;
  font-size: 22px;
}
.btnvoltar:hover {
  background: #192430;
  border: none;
  color: white;
}
       
.corde_textorcc{
       color: #898989;
       }
       
       .place_color{
       color:#fff;
       }
  
     .submitButton {
      padding: 10px 20px;
      font-size: 16px;
      background-color: #4CAF50;
      color: white;
      border: none;
      cursor: pointer;
    }

    .submitButton:hover {
      background-color: #45a049;
    }

    .message {
      margin-top: 20px;
      font-size: 18px;
      font-weight: bold;
      opacity: 0;
      transition: opacity 0.3s ease-in-out;
      color: #4CAF50;
    }

    .message.show {
      opacity: 1;
    }
