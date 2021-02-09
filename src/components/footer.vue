<template>
    <div class="footer">
        <div class="container">
            <div class="info">
                <h1>Get better work done</h1>
                <p>See why millions of people across 195 countries use Dash.</p>
                <div class="inp">
            <input type="email" placeholder="Name@company.com" />
            <button class="btn">try it free</button>
          </div>
            </div>
        </div>
    </div>
</template>
<script>
export default {
    name:'footer',
}
</script>
<style lang="scss" scoped>
.footer{
    margin-top: 400px;
    margin-bottom: 70px;
    .container{
        .info{
            text-align: center;
            h1{
                color: black;
                font-weight: bold;
            }
            p{
                color: gray;
                font-weight: lighter;
                text-align: center;
                line-height: 2;
            }
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
}
/* Extra small devices (phones, 600px and down) */
@media only screen and (max-width: 600px) {
    .info{
        h1{
            font-size: 27px;
        }
        p{
            font-size: 14px;
        }
    }
    .inp{
                        input{
                            padding: 10px 13px !important;
                        }
                        button{
                            padding: 8px !important;
                            font-size: 15px !important;
                        }
                    }
}
</style>