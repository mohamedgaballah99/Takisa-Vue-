<template>
  <div class="need">
    <div class="container">
      <div class="row">
        
        <div class="img col-sm-12 col-md-5 col-lg-6 mx-auto">
          <img src="../assets/images/7.png" alt="" />
        </div>
        <!--  -->
        <div class="text col-sm-12 col-md-6 col-lg-6 mx-auto">
          <h1>
            Why do you need<br />
task management<br /> software?
          </h1>
          <p>
            Do you waste time organizing sticky notes, searching your email and apps for to-dos, and figuring out what to work on first? Then you need one solution to prioritize your tasks, manage your time, and meet your deadlines.
          </p>
          <div class="inp">
            <button class="btn">Learn more</button>
          </div>
        </div>

      </div>
    </div>
  </div>
</template>
<script>
export default {
    name:"Need"
}
</script>
<style lang="scss" scoped>
.need{
    .container{
        margin-top: 100px;
        .row{
            .text{
                h1{
                    font-size: 30px;
                    font-weight: bold;
                    color: black;
                }
                p{
                    color: gray;
                    margin: 20px 0px;
                }
                .inp{
                   
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
    .need{
        .container{
            margin-top: 100px !important;
             .row{
                 .text{
                      width: 90%;
                    margin: auto;
                    margin-bottom: 60px !important;
                    margin-top: 50px;

                    h1{
                        font-size: 38px !important;
                    }
                    p{
                        font-size: 15px;
                    }
                    .inp{
                        
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
    .need{
        .container{
            margin-top: 50px !important;
             .row{
                 .text{
                    padding-top: 0px !important;
                    h1{
                        font-size: 27px !important;
                    }
                    p{
                        font-size: 13px;

                    }
                    .inp{
                        
                        button{
                            padding: 8px 15px;
                            font-size: 15px !important;
                        }
                    }
                 }
                 .img{
                     margin-top: 30px !important;
                 }
             }   
        }
    }
}
/* Large devices (laptops/desktops, 992px and up) */
@media only screen and (min-width: 992px) {
      .need{
        .container{
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
      .need{
        .container{
             .row{
                 .text{
                    padding-top: 25px !important;
                    margin-left: 20px;
                    h1{
                        font-size: 50px !important;
                    }
                    p{
                        font-size: 15px;
                        line-height: 2;
                    }
                    .inp{
                       
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
