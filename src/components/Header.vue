<template>
  <div class="header">
    <div class="container">
      <div class="row">
        <div class="text col-sm-12 col-md-6 col-lg-6">
          <h1>
            Task management <br />
            and lists Tool
          </h1>
          <p>
            We believe that designing products and services in close partnership
            with our clients is the only way to have a real impact on their
            business.
          </p>
          <div class="inp">
            <input type="email" placeholder="Name@company.com" />
            <button class="btn">try it free</button>
          </div>
        </div>
        <div class="img col-sm-12 col-md-6 col-lg-6">
          <img src="../assets/images/5.png" alt="" />
        </div>
      </div>
    </div>
  </div>
</template>
<script>
export default {
    name:"Header"
}
</script>
<style lang="scss" scoped>
.header{
    .container{
        margin-top: 100px;
        .row{
            .text{
                padding-top: 100px;
                h1{
                    font-size: 60px;
                    font-weight: bold;
                    color: black;
                }
                p{
                    color: gray;
                    margin: 30px 0px;
                }
                .inp{
                    input{
                        border: none;
                        padding: 10px;
                        margin-right: 10px;
                        border-radius: 20px;
                        border :1px solid gray;
                    }
                    button{
                        background-color: #525FFB;
                        color: white;
                        font-weight: bold;
                        text-transform: capitalize;
                        border-radius: 20px;
                        padding: 10px;
                    }
                }
            }
            .img{
                
                width: 100%;
                img{
                    width: 100%;
                }
            }
        }
    }
}
/* Extra small devices (phones, 600px and down) */
@media only screen and (max-width: 600px) {
    .header{
        .container{
            margin-top: 0px !important;
             .row{
                 .text{
                    margin-bottom: 60px !important;
                    
                    h1{
                        font-size: 38px !important;
                    }
                    p{
                        font-size: 15px;
                    }
                    .inp{
                        input{
                            padding: 6px;
                        }
                        button{
                            padding: 8px;
                            font-size: 15px !important;
                        }
                    }
                 }
             }   
        }
    }
}


/* Medium devices (landscape tablets, 768px and up) */
@media only screen and (min-width: 768px) {
    .header{
        .container{
            margin-top: 50px !important;
             .row{
                 .text{
                    padding-top: 0px !important;
                    h1{
                        font-size: 38px !important;
                    }
                    p{
                        font-size: 15px;
                    }
                    .inp{
                        input{
                            padding: 6px;
                        }
                        button{
                            padding: 8px;
                            font-size: 15px !important;
                        }
                    }
                 }
             }   
        }
    }
}
/* Large devices (laptops/desktops, 992px and up) */
@media only screen and (min-width: 992px) {
      .header{
        .container{
             .row{
                 .text{
                    padding-top: 80px !important;
                    h1{
                        font-size: 38px !important;
                    }
                    p{
                        font-size: 15px;
                    }
                    .inp{
                        input{
                            padding: 10px;
                        }
                        button{
                            padding: 8px 13px;
                            font-size: 15px !important;
                        }
                    }
                 }
             }   
        }
    }
}
/* Extra large devices (large laptops and desktops, 1200px and up) */
@media only screen and (min-width: 1200px) {
      .header{
        .container{
             .row{
                 .text{
                    padding-top: 80px !important;
                    h1{
                        font-size: 60px !important;
                    }
                    p{
                        font-size: 15px;
                        line-height: 2;
                    }
                    .inp{
                        input{
                            padding: 10px 25px;
                        }
                        button{
                            padding: 10px 16px;
                            font-size: 15px !important;
                        }
                    }
                 }
             }   
        }
    }
}
</style>
