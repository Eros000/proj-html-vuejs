<script>

export default {
  
  data() {
    return {

    }
  },
  
}

</script>

<template>

    <header>

        <div class="header-top">

            <div class="header-top-container">

                <div class="header-top-left">
    
                    <span>English</span> 
                    <i class="fa-solid fa-chevron-down"></i>
    
                </div>
    
                <div class="header-top-right">

                    <div class="header-top-right-nav">

                        <ul>
                            <li>
                                <a href="">
                                    Home
                                </a>

                            </li>

                            <li>
                                <a href="">
                                    Pages
                                </a>

                            </li>

                            <li>
                                <a href="">
                                    Course Formats
                                </a>

                            </li>

                            <li>
                                <a href="">
                                    Courses
                                </a>

                            </li>

                            <li>
                                <a href="">
                                    Demos
                                </a>

                            </li>

                        </ul>

                    </div>

                    <div class="header-top-right-social">

                        <i class="fa-brands fa-facebook"></i>
                        <i class="fa-brands fa-twitter"></i>
                        <i class="fa-brands fa-instagram"></i>
                        <i class="fa-brands fa-linkedin"></i>
                        <i class="fa-brands fa-google-plus"></i>
                        <i class="fa-brands fa-youtube"></i>

                    </div>
    
                </div>

            </div>


        </div>

        <div class="header-center">

            <div class="header-center-container">

                <div class="header-center-logo">

                    <img src="../assets/MasterStudy.svg" alt="logo">
                    
                </div>

                <div class="header-center-searchingbar">

                    <i class="fa-solid fa-bars"></i>
                    <span>CATEGORY</span>

                    <div>

                        <input type="text" placeholder="Search courses">
                        <button><i class="fa-solid fa-magnifying-glass"></i></button>

                    </div>

                </div>

                <div class="header-center-link">

                    
                    <a href="#">

                    </a>

                    <a href="#">
                        
                    </a>

                </div>

                <div class="header-center-signup">

                </div>



            </div>

        </div>

        <div class="header-bottom">

        </div>

    </header>
  
</template>

<style scoped lang="scss">

    header{
        


        .header-top{
            border-bottom: 1px solid lightgray;
            background-color: white;


            .header-top-container{
                max-width: 1200px;
                margin: 0 auto;
                display: flex;
                justify-content: space-between;
                align-items: center;
                font-size: small;
                color: gray;




                .header-top-left{
                    
    
                    i{
                        margin-left: 10px;
                    }
                }


    
                .header-top-right{
                    display: flex;
                    align-items: center;
    
                    .header-top-right-nav{


                        ul{
                            display: flex;

                            li{
                                list-style: none;

                                a{
                                    text-decoration: none;
                                    color: gray;
                                    margin-left: 15px;

                                }
                            }
                        }
                    }

                    .header-top-right-social{
                        margin-left: 30px;


                        i{
                            margin-left: 10px;
                        }
                    }
                }

            }



        }


        .header-center{
            padding-top: 30px;
            


            .header-center-container{
                max-width: 1200px;
                margin: 0 auto;
                display: flex;
                align-items: center;


                .header-center-searchingbar{
                    margin-left: 30px;
                    font-size: small;
                    color: gray;
                    display: flex;
                    align-items: center;


                    span{
                        margin-left: 5px;
                    }

                    div{
                        margin-left: 10px;

                        input{
                            width: 270px;
                            height: 35px;
                            background-color: rgb(230, 230, 230);
                            border: none;
                        }

                        button{
                            width: 42px;
                            height: 36px;
                            background-color: #457993;
                            border: none;

                        }
                    }
                }

                .header-center-link{

                }

                .header-center-signup{

                }
            }


        }
    }

</style>
