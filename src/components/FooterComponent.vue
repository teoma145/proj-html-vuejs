<template>
    <footer class="footerbg">
        <div class="d-flex flex-wrap mt-5">
            <div class="col-md-2 mt-5">
                <img src="../assets/style/images/author-logo-round-small.png" alt="">
            </div>
            <div class="col-md-2 text-white mt-5">
                <h2>ABOUT ME</h2>
                <p class="mt-5">Vivamus suscipit tortor eget felis porttitor volutpat. Nulla quis lorem ut libero malesuada feugiat. Vivamus suscipit tortor eget felis porttitor volutpat.</p>
            </div>
            <div class="col-md-3 mt-5">
                <h2 class="text-white ms-4">USEFUL LINKS</h2>
                <ul v-for="usefulitem in useful">
                    <li><a href="" class="text-decoration-none text-bg-secondary ">{{ usefulitem }}</a></li>
                </ul>
            </div>
            <div class="col-md-3 mt-5 text-white">
                <h2 class="ms-4">Contact Info</h2>
                <ul>
                    <li>63 E. Studebaker Street Bolingbrook, IL 60440</li>
                    <li>Phone: (800) 000-0000</li>
                    <li>Mobile: (800) 000-0000</li>
                    <li>Email: info@your-company.com</li>
                </ul>
            </div>
        </div>
    </footer>
</template>

<script>
export default {
    name:'FooterComponent',
    data () {
        

        return {
            useful:[
                'Latest Books',
                'Upcoming Events',
                'Recent Articles',
                'Business Enquiries',
                'Visit My Foundation',
        ]
        }
    }
}
</script>

<style lang="scss" scoped>
.footerbg{
    background-image: url(../assets/style/images/footer-3.jpg);
    background-size: cover;
    background-repeat: no-repeat;
    background-position: top;
    padding: 100px;
}
ul{
    list-style-type: none;
}
li{
    margin-bottom: 15px;
}
</style>