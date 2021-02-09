<template>
  <div class="feature">
    <div class="container">
      <div class="row">

        <div class="col-sm-12 col-md-5 col-lg-3 mx-auto">
          <img src="../assets/images/3.png" />
          <h3>Keep tasks in one place</h3>
          <p>
            Save time, avoid losing work and information, delegate, and track
            tasks to stay on schedule
          </p>
        </div>
        <!--  -->
        <div class="col-sm-12 col-md-5 col-lg-3 mx-auto">
          <img src="../assets/images/2.png" />
          <h3>Keep tasks in one place</h3>
          <p>
            Save time, avoid losing work and information, delegate, and track
            tasks to stay on schedule
          </p>
        </div>
        <!--  -->
        <div class="col-sm-12 col-md-5 col-lg-3 mx-auto">
          <img src="../assets/images/1.png" />
          <h3>Keep tasks in one place</h3>
          <p>
            Save time, avoid losing work and information, delegate, and track
            tasks to stay on schedule
          </p>
        </div>
      </div>
    </div>
  </div>
</template>
<script>
export default {
    name:'Feature'
}
</script>
<style lang="scss" scoped>
.feature{
    margin-top:150px;
    
    .container{
        .row{
            >div{
                padding: 30px;
                margin-bottom: 70px;
                img{
                    width: 90%;
                    margin: auto;
                }
                h3{
                    font-weight: bold;
                }
                p{
                    text-align: center;
                    margin-top: 20px;
                    font-weight: lighter;
                }
            }
            div:first-of-type{
                background-color: #525FFB;
                color: white;
            }
            div:nth-child(2){

                background-color: #E9F0FF;
                color: black;
                h3{
                    color: rgb(22, 22, 22);
                }
            }
            div:last-of-type {
               
                background-color: #FFE7AA;
                color: black;
                 h3{
                    color: rgb(22, 22, 22);
                }
            }
        }
    }
}
/* Extra small devices (phones, 600px and down) */
@media only screen and (max-width: 600px) {
    .feature{
        .container{
            .row{
                >div{
                    width: 90% !important;
                    margin: auto !important;
                    margin-top: 60px !important;
                }
            }
        }
    }
}

</style>
