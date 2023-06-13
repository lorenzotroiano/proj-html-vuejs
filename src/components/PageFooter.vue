<script>
import SingleLink from './SingleLink.vue';
import SingleLinkCourse from './SingleLinkCourse.vue';
export default {

    name: "PageFooter",

    components: {
        SingleLink,
        SingleLinkCourse
    },
    data() {
        return {
            linkFooter: [
                {
                    link: "Providing life changing",

                },

                {
                    link: "Experience Throught",

                },

                {
                    link: "Education class to mate",

                },

                {
                    link: "Busy life. Hello World",

                },

            ],


            linkCourseFot: [

                {
                    title: "Populars Course"
                },
                {
                    title: "English Business",
                    link: "Preston Marshall",

                },

                {
                    title: "Social Computing",
                    link: "Ansu Fati",

                },

                {
                    title: "Learn Spanish",
                    link: "Rodrigo",

                },
            ],

            linkSupportFot: [
                {
                    link: "User Dashboards"
                },

                {
                    link: "Contact Us"
                },

                {
                    link: "Faqs"
                },

                {
                    link: "Office Courses"
                },

                {
                    link: "User Dashboards"
                },

                {
                    link: "Events"
                },
            ]
        }
    }

}

</script>

<template>
    <footer>
        <div class="flex-footer">
            <div>

                <img src="../../public/img/footer-logo-1.png" alt="logo">

                <SingleLink v-for="link in linkFooter" :details="link" />


                <span><i class="fa-solid fa-phone" style="color: #ffffff;"></i><a href="#">+39 1112223456</a></span>
                <span><i class="fa-regular fa-clock" style="color: #ffffff;"></i><a href="#">Mon - Sat 8.00 -
                        13.00</a></span>
            </div>
            <div>

                <SingleLinkCourse v-for="linkCourse in linkCourseFot " :details="linkCourse" />

            </div>
            <div>

                <h4>Support</h4>

                <SingleLink v-for="link in linkSupportFot" :details="link" />
            </div>
            <div>
                <h4>Flexible Learning</h4>

                <img src="../../public/img/footer-img-1.png" alt="">
            </div>
        </div>
    </footer>
</template>

<style lang="scss" scoped>
@use '../styles/partials/variables.scss' as *;


footer {
    background-color: black;
    color: white;


    .flex-footer {
        display: flex;
        justify-content: space-around;
        align-items: center;



        padding: 70px;

        div {

            display: flex;
            flex-direction: column;
            // align-items: center;
            height: 400px;

            img {
                max-width: 300px;
            }

            a {
                text-decoration: none;
                color: white;
                padding: 15px;
            }

            i {
                margin-right: 10px;
                margin-top: 30px;
            }

            // ul {

            //     li {
            //         line-height: 20px;
            //         margin-top: 30px;
            //         link-align: start;


            //     }
            // }

        }
    }
}
</style>

