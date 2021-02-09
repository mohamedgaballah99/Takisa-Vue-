<template>
    <div class="trust">
        <h1>Trust us and feel free to try our service</h1>
        <div class="container">
            <div class="left">
                <div>
                    <img src="../assets/images/rr.png" alt="">
                </div>
                <div>
                    <img src="../assets/images/tt.png" alt="">
                </div>
                <div>
                    <img src="../assets/images/rr.png" alt="">
                </div>
            </div>
            <div class="center">
                100 000
            </div>
            <div class="right">
                <div>
                    <img src="../assets/images/tt.png" alt="">
                </div>
                <div>
                    <img src="../assets/images/rr.png" alt="">
                </div>
                <div>
                    <img src="../assets/images/tt.png" alt="">
                </div>
            </div>
        </div>
    </div>
</template>
<script>
export default {
    name:'trust'
}
</script>
<style lang="scss" scoped>
.trust{
    margin-top:100px;
    >h1{
        text-align: center;
        color: black;
        margin-bottom: 80px;
        font-weight: bold;
        text-transform: capitalize;
    }
    .container{
        display: flex;
        justify-content: space-between;
        .left{
            position: relative;
            div:first-of-type{
                width: 80px;
                position: absolute;
                img{
                    border-radius: 50%;
                    width: 100%;
                }   
            }
            div:nth-of-type(2){
                 width:50px;
                position: absolute;
                left:180px;
                top: 200px;
                img{
                    border-radius: 50%;
                    width: 100%;
                }   
            }
            div:nth-of-type(3){
                width: 80px;
                position: absolute;
                top: 400px;
                img{
                    border-radius: 50%;
                    width: 100%;
                 }  
            }   
        }
        .center{
            color: #525FFB;
            font-size: 100px;
            font-family: Georgia, 'Times New Roman', Times, serif;
            font-weight: bold;
            display: flex;
            align-items: center;
            margin-top:150px;
        }
        .right{
           position: relative;
            div:first-of-type{
                width: 80px;
                position: absolute;
                img{
                    border-radius: 50%;
                    width: 100%;
                }   
            }
            div:nth-of-type(2){
                 width:50px;
                position: absolute;
                right:150px;
                top: 200px;
                img{
                    border-radius: 50%;
                    width: 100%;
                }   
            }
            div:nth-of-type(3){
                width: 80px;
                position: absolute;
                top: 400px;
                img{
                    border-radius: 50%;
                    width: 100%;
                 }  
            }   
        }
    }
}
/* Extra small devices (phones, 600px and down) */
@media only screen and (max-width: 600px) {
    .trust{
    margin-top:100px;
    >h1{
        text-align: center;
        color: black;
        margin-bottom: 80px;
        font-size: 30px;
        padding: 10px;
        margin: 30px 20px;
    }
    .container{
        .left{
            position: relative;
            div:first-of-type{
                width: 80px;
                position: absolute;
                img{
                    border-radius: 50%;
                    width: 100%;
                }   
            }
            div:nth-of-type(2){
                 width:50px;
                position: absolute;
                left:10px;
                top: 200px;
                img{
                    border-radius: 50%;
                    width: 100%;
                }   
            }
            div:nth-of-type(3){
                width: 80px;
                position: absolute;
                top: 400px;
                img{
                    border-radius: 50%;
                    width: 100%;
                 }  
            }   
        }
        .center{
            color: #525FFB;
            font-size: 50px;
            font-family: Georgia, 'Times New Roman', Times, serif;
            font-weight: bold;
            display: flex;
            align-items: center;
            margin-top:180px;
        }
        .right{
           position: relative;
            div:first-of-type{
                width: 80px;
                position: absolute;
                right: 0px;
                img{
                    border-radius: 50%;
                    width: 100%;
                }   
            }
            div:nth-of-type(2){
                 width:50px;
                position: absolute;
                right:10px;
                top: 200px;
                img{
                    border-radius: 50%;
                    width: 100%;
                }   
            }
            div:nth-of-type(3){
                width: 80px;
                position: absolute;
                top: 400px;
                right: 0px;
                img{
                    border-radius: 50%;
                    width: 100%;
                 }  
            }   
        }
    }
}
}
/* Medium devices (landscape tablets, 768px and up) */
@media only screen and (min-width: 768px) {
       .trust{
    margin-top:100px;
    // overflow: hidden;
    >h1{
        text-align: center;
        color: black;
        margin-bottom: 80px;
        font-size: 30px;
        padding: 10px;
        margin: 30px 20px;
    }
    .container{
        .left{
            position: relative;
            div:first-of-type{
                width: 80px;
                position: absolute;
                img{
                    border-radius: 50%;
                    width: 100%;
                }   
            }
            div:nth-of-type(2){
                 width:50px;
                position: absolute;
                left:50px;
                top: 200px;
                img{
                    border-radius: 50%;
                    width: 100%;
                }   
            }
            div:nth-of-type(3){
                width: 80px;
                position: absolute;
                top: 400px;
                img{
                    border-radius: 50%;
                    width: 100%;
                 }  
            }   
        }
        .center{
            color: #525FFB;
            font-size: 80px;
            font-family: Georgia, 'Times New Roman', Times, serif;
            font-weight: bold;
            display: flex;
            align-items: center;
            margin-top:150px;
        }
        .right{
           position: relative;
            div:first-of-type{
                width: 80px;
                position: absolute;
                right: 0px;
                img{
                    border-radius: 50%;
                    width: 100%;
                }   
            }
            div:nth-of-type(2){
                 width:50px;
                position: absolute;
                right:50px;
                top: 200px;
                img{
                    border-radius: 50%;
                    width: 100%;
                }   
            }
            div:nth-of-type(3){
                width: 80px;
                position: absolute;
                top: 400px;
                right: 0px;
                img{
                    border-radius: 50%;
                    width: 100%;
                 }  
            }   
        }
    }
}
}
/* Extra large devices (large laptops and desktops, 1200px and up) */
@media only screen and (min-width: 1200px) {
         .trust{
    margin-top:100px;
    // overflow: hidden;
    >h1{
        text-align: center;
        color: black;
        margin-bottom: 80px;
        font-size: 30px;
        padding: 10px;
        margin: 30px 20px;
    }
    .container{
        .left{
            position: relative;
            div:first-of-type{
                width: 80px;
                position: absolute;
                img{
                    border-radius: 50%;
                    width: 100%;
                }   
            }
            div:nth-of-type(2){
                 width:50px;
                position: absolute;
                left:190px;
                top: 200px;
                img{
                    border-radius: 50%;
                    width: 100%;
                }   
            }
            div:nth-of-type(3){
                width: 80px;
                position: absolute;
                top: 400px;
                img{
                    border-radius: 50%;
                    width: 100%;
                 }  
            }   
        }
        .center{
            color: #525FFB;
            font-size: 80px;
            font-family: Georgia, 'Times New Roman', Times, serif;
            font-weight: bold;
            display: flex;
            align-items: center;
            margin-top:150px;
        }
        .right{
           position: relative;
            div:first-of-type{
                width: 80px;
                position: absolute;
                right: 0px;
                img{
                    border-radius: 50%;
                    width: 100%;
                }   
            }
            div:nth-of-type(2){
                 width:50px;
                position: absolute;
                right:150px;
                top: 200px;
                img{
                    border-radius: 50%;
                    width: 100%;
                }   
            }
            div:nth-of-type(3){
                width: 80px;
                position: absolute;
                top: 400px;
                right: 0px;
                img{
                    border-radius: 50%;
                    width: 100%;
                 }  
            }   
        }
    }
}
}

</style>