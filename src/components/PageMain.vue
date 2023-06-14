<script>
import SingleSquare from './SingleSquare.vue';
export default {

    name: "PageMain",

    components: {
        SingleSquare
    },

    data() {
        return {
            squares: [
                {
                    img: "h5-custom-icon-1.png",
                    name: "Languages"
                },

                {
                    img: "h5-custom-icon-2.png",
                    name: "Software"
                },

                {
                    img: "h5-custom-icon-3.png",
                    name: "Business"
                },

                {
                    img: "h5-custom-icon-4.png",
                    name: "Chemistry"
                },

                {
                    img: "h5-custom-icon-5.png",
                    name: "Science"
                },

                {
                    img: "h5-custom-icon-6.png",
                    name: "Diy&Craft"
                },
            ]
        }
    }

}

</script>

<template>
    <!-- section con gli square azzurrini -->
    <section class="custom">
        <SingleSquare v-for="square in squares" :detailsSquare="square" />
    </section>


    <!-- section tutor -->
    <section class="tutor">
        <h2>The Trusted Name <br> for In-Home Tutoring.</h2>
        <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Beatae quae ipsam quo veritatis! Impedit autem sapiente
            maiores assumenda optio asperiores accusamus expedita. Accusamus quia possimus quod corrupti impedit. Maxime,
            consequatur.</p>

        <a href="#">Learn More</a>


    </section>
    <div>
        <img class="img-tutoring" src="../../public/img/h5-img-1.jpg" alt="">

        <div class="square">
            <i class="fa-solid fa-angle-up"></i>
            <span style="color: white;">
                TOP
            </span>
        </div>
    </div>

    <div class="container-events">
        <section class="events">

            <div>
                <img src="../../public/img/h1-img-8.jpg" alt="">
            </div>

            <div class="container-empowering">
                <h2>Empowering Children to Reach Their Potential</h2>
                <p>Lorem ipsum dolor sit amet consectetur, adipisicing elit. Fuga veritatis aliquam vitae dolorem, suscipit
                    quis. Nemo, numquam, aspernatur sit minus, non id quos modi voluptate aliquam distinctio facilis porro
                    ipsum.</p>

                <div class="container-numbers-events">
                    <div>
                        <span class="number-cont">168</span>
                        <span class="user-text">User Stories</span>
                    </div>

                    <div>
                        <span class="number-cont">347</span>
                        <span class="user-text">Events</span>
                    </div>
                </div>
            </div>

        </section>

        <div class="square">
            <i class="fa-solid fa-angle-up"></i>
            <span style="color: white;">
                TOP
            </span>
        </div>
    </div>


    <div class="container-testimonial">
        <section class="testimonials">
            <img src="../../public/img/testimonials-standard-2.png" alt="">
            <p>"Lorem, ipsum dolor sit amet consectetur adipisicing elit. Nostrum, harum ipsa. Sed nam libero ipsam, iure
                earum quaerat ab rerum ut repellendus quos error fugiat porro quod ipsa beatae qui."</p>
            <h2>John Travolta</h2>
            <h4>Student</h4>
        </section>
    </div>

    <div class="container-possibilities">
        <section class="possibilities">
            <ul class="list-group">
                <li class="list-group-item">What are u doing?</li>
                <li class="list-group-item">Goodbye Lenin</li>
                <li class="list-group-item">Hello my world</li>
                <li class="list-group-item">Fino alla fine</li>
                <li class="list-group-item">And a fifth one vissero felice</li>
                <li class="list-group-item">What are u doing?</li>
            </ul>

            <div class="learning-possib">
                <h2>Learning Possibilities</h2>
                <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Sit explicabo expedita dolorum ipsum odio
                    architecto quisquam voluptate. Ducimus officia ipsam quaerat, delectus omnis, cupiditate expedita ullam
                    tenetur nobis itaque magnam.</p>

                <div class="check">
                    <span><i class="fa-solid fa-check"></i> We are the champion</span>
                    <span><i class="fa-solid fa-check"></i> We are the champion</span>
                    <span><i class="fa-solid fa-check"></i> We are the champion</span>
                    <span><i class="fa-solid fa-check"></i> We are the champion We are the champion,We are the
                        champion</span>

                    <img src="../../public/img/h12-tabs-icon-1.png" alt="">
                </div>
            </div>


        </section>
        <div class="square-top">
            <i class="fa-solid fa-angle-up"></i>
            <span style="color: white;">
                TOP
            </span>
        </div>
    </div>

    <div class="container-courses">



        <section class="courses">

            <div class="descrip-section">
                <h2>Popular Online Courses</h2>
                <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Enim necessitatibus pariatur culpa reprehenderit
                    vel
                    nam, repudiandae omnis. Dolor deleniti maiores voluptates similique numquam delectus cupiditate nulla
                    dolore, illo quasi quidem?</p>
            </div>


            <div class="select-course">
                <div class="course">
                    <img src="../../public/img/course-5-f-img.jpg" alt="">

                    <div class="under-select">
                        <div class="label">
                            <h4>Titolo</h4>
                            <span style="color: white;">Free</span>
                        </div>
                        <span>David Sander</span>
                        <p>Lorem ipsum dolor sit amet, consectetur adipisicing elit. Quod culpa est, necessitatibus vitae
                            modi
                            nemo magnam ullam. Sapiente, ipsum officia distinctio, nemo blanditiis veritatis cumque corporis
                            eligendi quae eum quod.</p>
                        <span><i class="fa-solid fa-user"></i> 1</span>
                        <span><i class="fa-solid fa-tag"></i>Programming</span>
                    </div>
                </div>
                <div class="course">
                    <img src="../../public/img/course-6-f-img.jpg" alt="">
                    <div class="under-select">
                        <div class="label">
                            <h4>Titolo</h4>
                            <span style="color: white;">Free</span>
                        </div>
                        <span>David Sander</span>
                        <p>Lorem ipsum dolor sit amet, consectetur adipisicing elit. Quod culpa est, necessitatibus vitae
                            modi
                            nemo magnam ullam. Sapiente, ipsum officia distinctio, nemo blanditiis veritatis cumque corporis
                            eligendi quae eum quod.</p>
                        <span><i class="fa-solid fa-user"></i> 1</span>
                        <span><i class="fa-solid fa-tag"></i>Programming</span>
                    </div>
                </div>
                <div class="course">
                    <img src="../../public/img/course-12-f-img.jpg" alt="">
                    <div class="under-select">
                        <div class="label">
                            <h4>Titolo</h4>
                            <span style="color: white;">20$</span>
                        </div>
                        <span>David Sander</span>
                        <p>Lorem ipsum dolor sit amet, consectetur adipisicing elit. Quod culpa est, necessitatibus
                            vitae
                            modi
                            nemo magnam ullam. Sapiente, ipsum officia distinctio, nemo blanditiis veritatis cumque
                            corporis
                            eligendi quae eum quod.</p>
                        <span><i class="fa-solid fa-user"></i> 1</span>
                        <span><i class="fa-solid fa-tag"></i>Programming</span>
                    </div>
                </div>



            </div>
        </section>


        <div class="square-top">
            <i class="fa-solid fa-angle-up"></i>
            <span style="color: white;">
                TOP
            </span>
        </div>
        <div class="square">
            <i class="fa-solid fa-angle-up"></i>
            <span style="color: white;">
                TOP
            </span>
        </div>
    </div>


    <div class="container-price">
        <section class="price">

            <div class="text-price">
                <h2>Pricing Planes</h2>
                <p>Lorem ipsum, dolor sit amet consectetur adipisicing elit. Magnam harum accusantium accusamus molestias
                    assumenda. Exercitationem, ducimus placeat qui repellendus odit voluptas modi voluptate provident
                    delectus
                    soluta minus animi autem? Esse.</p>
            </div>

            <table class="table table-bordered">
                <thead>
                    <tr>
                        <th class="align-bottom col-2">
                            <h3>Save up to 40% <br> by paying <br> weekly</h3>
                        </th>
                        <th class="text-center backg-celeste"><img src="../../public/img/h5-custom-icon-7.png" alt="">
                            <h3>Standard</h3>
                            <h4>$12</h4>
                        </th>
                        <th class="text-center backg-celeste"><img src="../../public/img/h5-custom-icon-8.png" alt="">
                            <h3>Professional</h3>
                            <h4>$59</h4>
                        </th>
                        <th class="text-center backg-celeste"><img src="../../public/img/h5-custom-icon-9.png" alt="">
                            <h3>Advanced</h3>
                            <h4>$89</h4>
                        </th>
                    </tr>
                </thead>
                <tbody>
                    <tr>
                        <th>Number of coursers</th>
                        <td class="text-center">2</td>
                        <td class="text-center">4</td>
                        <td class="text-center">6</td>
                    </tr>
                    <tr>
                        <th>Time</th>
                        <td class="text-center">15 Days</td>
                        <td class="text-center">30 Days</td>
                        <td class="text-center">30 Days</td>
                    </tr>
                    <tr>
                        <th>Web Designing </th>
                        <td class="text-center"><i class="fa-solid fa-check" style="color: #40c4ff;"></i></td>
                        <td class="text-center"><i class="fa-solid fa-check" style="color: #40c4ff;"></i></td>
                        <td class="text-center"><i class="fa-solid fa-check" style="color: #40c4ff;"></i></td>
                    </tr>
                    <tr>
                        <th>Human Centered designing</th>
                        <td class="text-center"><i class="fa-solid fa-check" style="color: #40c4ff;"></i></td>
                        <td class="text-center"><i class="fa-solid fa-check" style="color: #40c4ff;"></i></td>
                        <td class="text-center"><i class="fa-solid fa-check" style="color: #40c4ff;"></i></td>
                    </tr>
                    <tr>
                        <th>Basic Marketing</th>
                        <td class="text-center"><i class="fa-solid fa-xmark" style="color: #858585;"></i></td>
                        <td class="text-center"><i class="fa-solid fa-check" style="color: #40c4ff;"></i></td>
                        <td class="text-center"><i class="fa-solid fa-check" style="color: #40c4ff;"></i></td>
                    </tr>
                    <tr>
                        <th>Phyton Lenguages</th>
                        <td class="text-center"><i class="fa-solid fa-xmark" style="color: #858585;"></i></td>
                        <td class="text-center"><i class="fa-solid fa-check" style="color: #40c4ff;"></i></td>
                        <td class="text-center"><i class="fa-solid fa-check" style="color: #40c4ff;"></i></td>
                    </tr>
                    <tr>
                        <th>Android Developer</th>
                        <td class="text-center"><i class="fa-solid fa-xmark" style="color: #858585;"></i></td>
                        <td class="text-center"><i class="fa-solid fa-xmark" style="color: #858585;"></i></td>
                        <td class="text-center"><i class="fa-solid fa-check" style="color: #40c4ff;"></i></td>
                    </tr>
                    <tr>
                        <th>English Teacher</th>
                        <td class="text-center"><i class="fa-solid fa-xmark" style="color: #858585;"></i></td>
                        <td class="text-center"><i class="fa-solid fa-xmark" style="color: #858585;"></i></td>
                        <td class="text-center"><i class="fa-solid fa-check" style="color: #40c4ff;"></i></td>

                    </tr>

                    <tr>

                        <th></th>
                        <td class="text-center"><button type="button" class="btn btn-light">Light</button></td>
                        <td class="text-center"><button type="button" class="btn btn-primary">Primary</button></td>
                        <td class="text-center"><button type="button" class="btn btn-light">Light</button></td>


                    </tr>
                </tbody>
            </table>
        </section>

        <div class="square-middle">
            <img src="../../public/svg/svg-3.svg" alt="">
        </div>

        <div class="square">
            <i class="fa-solid fa-angle-up"></i>
            <span style="color: white;">
                TOP
            </span>
        </div>
    </div>

    <div class="container-partners">
        <section class="partners">
            <div>
                <img src="../../public/img/h5-client-5.png" alt="">
            </div>
            <div>
                <img src="../../public/img/h5-client-2.png" alt="">
            </div>
            <div>
                <img src="../../public/img/h5-client-3.png" alt="">
            </div>
            <div>
                <img src="../../public/img/h5-client-4.png" alt="">
            </div>
        </section>


        <div class="square-top">
            <i class="fa-solid fa-angle-up"></i>
            <span style="color: white;">
                TOP
            </span>
        </div>
    </div>
</template>

<style lang="scss" scoped>
@use '../styles/partials/variables.scss' as *;

.custom {

    padding: 40px;
    margin: 30px 0;

    display: flex;
    justify-content: space-around;



}


.tutor {

    padding: 40px;
    font-size: 20px;
    // h2 {
    //     width: 16%;
    // }

    h2 {
        font-size: 55px;
        font-weight: bold;
    }

    p {
        margin: 20px 0;
        color: #b9b9b9;
    }

    a {
        text-transform: uppercase;
        color: $colorePrimario;
        font-size: 16px;
        font-weight: bold;

        display: block;
    }


}

div {

    position: relative;




    .img-tutoring {
        width: 100%;
        padding: 0 50px;
        border-bottom: 0.5px solid black;

    }

    .square {
        background-color: $colorePrimario;
        padding: 20px;
        color: white;
        position: absolute;

        top: 70%;
        right: 0;

        text-align: center;

        i {
            display: block;
        }

    }

}

.container-events {
    padding: 100px;


    h2 {
        font-size: 45px;
        font-weight: bold;
    }
}

.events {

    font-size: 25px;
    line-height: 40px;

    width: 80%;
    margin: 30px auto;
    display: flex;

    div {
        img {
            width: 450px;
        }

    }

    .container-empowering {
        padding: 70px;
        position: relative;
        bottom: 115px;

        p {
            margin: 20px 0;
            color: #b9b9b9;
        }

        .container-numbers-events {
            display: flex;
            justify-content: space-between;

            .number-cont {
                display: block;
                font-size: 40px;
                font-weight: bold;
                color: $colorePrimario;
            }

            .user-text {

                color: $colorePrimario;
            }
        }
    }
}

.container-testimonial {
    background-image: url(../../public/img/h5-parallax-img-1.png);
    background-repeat: no-repeat;
    background-size: 150%;
    background-position: top;



    .testimonials {

        font-size: 20px;
        color: white;
        padding: 150px;
        width: 65%;
        line-height: 30px;
        margin: 0 auto;
        text-align: center;

        img {
            width: 150px;
        }

        p {
            margin: 40px 0;
        }



    }
}

.container-possibilities {

    padding: 50px;

    .possibilities {

        font-size: 20px;
        width: 95%;
        margin: 120px auto;
        display: flex;
        justify-content: space-between;


        .list-group>li {
            padding: 20px;
            color: black;
            // border-left: 10px solid blue;


        }



        .list-group>li:hover {
            border-left: 10px solid $colorePrimario;
            color: $colorePrimario;
        }




        .learning-possib {
            width: 70%;
            line-height: 30px;

            h2 {
                font-size: 55px;
                font-weight: bold;
            }

            p {
                margin-top: 30px;
                color: #b9b9b9;
            }

            .check {

                position: relative;
                margin-top: 50px;

                span {
                    display: block;
                    line-height: 60px;

                    i {
                        color: $colorePrimario;
                    }

                }

                img {
                    width: 130px;
                    position: absolute;
                    top: 110px;
                    right: 0;
                }
            }

        }

    }


}

.square-top {
    background-color: $colorePrimario;
    padding: 20px;
    color: white;
    position: absolute;

    top: 10%;
    right: 0;

    text-align: center;

    i {
        display: block;
    }
}

.container-courses {
    background-image: url(../../public/img/background-pattern.jpg);
    background-repeat: no-repeat;
    background-size: 320%;
    background-position: center;

    border-top: 1px solid $coloreBordoPrim;
    border-bottom: 1px solid $coloreBordoPrim;

    width: 100%;
    padding: 80px 0;
    position: relative;

    .courses {




        .descrip-section {
            text-align: center;
            padding: 110px;


            h2 {
                font-size: 55px;
                font-weight: bold;

            }

            p {
                font-size: 20px;
                color: #b9b9b9;
            }
        }

        padding: 40px;

        .select-course {
            display: flex;
            gap: 35px;
            justify-content: space-around;
            // justify-content: space-between;





            // align-items: center;

            .course {
                border: 1px solid $coloreBordoPrim;

                .under-select {
                    padding: 25px;
                    line-height: 30px;

                    .label {
                        display: flex;
                        justify-content: space-between;
                        align-items: center;

                        span {
                            text-align: center;
                            padding: 2px;
                            width: 80px;
                            background-color: greenyellow;
                            border-radius: 20px;
                            text-transform: uppercase;
                        }
                    }

                    p {
                        margin: 20px 0;
                        color: #b9b9b9;
                    }

                    span>i {
                        margin-left: 10px;
                        padding: 5px;
                    }
                }
            }





            img {
                max-width: 100%;
            }
        }
    }
}

.container-price {
    background-image: url(../../public/img/background-pattern.jpg);
    background-repeat: no-repeat;
    background-size: 320%;
    background-position: center;

    border-top: 1px solid $coloreBordoPrim;
    border-bottom: 1px solid $coloreBordoPrim;

    width: 100%;
    padding: 80px 0;
    position: relative;

    .price {
        padding: 50px;

        .text-price {
            text-align: center;
            padding: 110px;

            h2 {
                font-size: 55px;
                font-weight: bold;

            }

            p {
                font-size: 20px;
                color: #b9b9b9;
            }
        }


        .table {
            font-size: 20px;
            border-top: 3px solid #40c4ff;

            td {
                color: #b9b9b9;
            }

            .btn {
                --bs-btn-border-radius: 0;
                --bs-btn-font-size: 20px;
                --bs-btn-bg: #40c4ff;

            }

        }

        .backg-celeste {
            background-color: #F7FDFF;
        }

        // .table> :not(caption)>*>* {
        //     background-color: #F7FDFF
        // }
    }

    .square-middle {
        background-color: red;
        padding: 10px;
        // color: white;
        position: absolute;

        top: 50%;
        right: 0;




        img {

            filter: invert(0100%);
            width: 30px;
        }
    }
}

.container-partners {
    position: relative;

    .partners {

        padding: 90px;
        display: flex;
        justify-content: space-around;

    }
}
</style>

