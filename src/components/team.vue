<template>
  <div class="team">
    <div class="container">
      <div class="row">
        <div class="text col-sm-12 col-md-6 col-lg-6">
          <h1>
            Seamless Team<br> Workflow & Efficient<br> Task Management
          </h1>
          <p>
           Do you waste time organizing sticky notes, searching your email and apps for to-dos, and figuring out what to work on first? Then you need one solution to prioritize your tasks, manage your time, and meet your deadlines.
          </p>
          <div class="inp">
             <img src="../assets/images/a.png" alt="" />
              <img src="../assets/images/i.png" alt="" />
          </div>
        </div>
        <div class="img col-sm-12 col-md-6 col-lg-6">
          <img src="../assets/images/6.png" alt="" />
        </div>
      </div>
    </div>
  </div>
</template>
<script>
export default {
    name:"team"
}
</script>
<style lang="scss" scoped>
.team{
    .container{
        margin-top: 140px;
        .row{
            .text{
                padding-top: 100px;
                h1{
                    font-weight: bold;
                    color: black;
                }
                p{
                    color: gray;
                    margin: 30px 0px;
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
    .team{
        .container{
            margin-top: 0px !important;
             .row{
                 .text{
                    margin-bottom: 60px !important;
                    width: 85%;
                    margin: auto !important;
                    h1{
                        font-size: 31px !important;
                    }
                    p{
                        font-size: 15px;
                    }
                    
                 }
             }   
        }
    }
}


/* Medium devices (landscape tablets, 768px and up) */
@media only screen and (min-width: 768px) {
    .team{
        .container{
            margin-top: 50px !important;
             .row{
                 .text{
                    padding-top: 0px !important;
                    h1{
                        font-size: 27px !important;
                    }
                    p{
                        font-size: 12px;
                    }
                    
                 }
             }   
        }
    }
}
/* Large devices (laptops/desktops, 992px and up) */
@media only screen and (min-width: 992px) {
      .team{
        .container{
             margin-top: 120px !important;
             .row{
                 .text{
                    padding-top: 0px !important;
                    h1{
                        font-size: 38px !important;
                    }
                    p{
                        font-size: 15px;
                    }
                   
                 }
             }   
        }
    }
}
/* Extra large devices (large laptops and desktops, 1200px and up) */
@media only screen and (min-width: 1200px) {
      .team{
        .container{
            margin-top: 150px !important;
             .row{
                 .text{
                    padding-top: 0px !important;
                    h1{
                        font-size: 45px !important;
                    }
                    p{
                        font-size: 15px;
                        line-height: 2;
                    }
                    
                 }
             }   
        }
    }
}
</style>
