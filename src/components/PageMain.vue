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
        <SingleSquare v-for="square in squares" :detailsSquare="square" />>
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
            <span>
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
            <span>
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
            <span>
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

    p {
        margin: 20px 0;
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
        bottom: 45px;

        p {
            margin: 20px 0;

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

            p {
                margin-top: 30px;
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
}
</style>

