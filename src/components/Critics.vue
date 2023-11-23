<template>
    <div class="container-md mb-3 mt-5">
        <div class="row d-flex">
            <div class="col-12 col-md-7 ">
                <h2>What The Critics Say</h2>
                <h4 class="text-info fs-5 mb-3">TESTIMONIALS FROM AROUND THE WORLD</h4>
                <div class="bcrimg">
                    <h2 class="text-white">Best Author Of His<br>Generation</h2>
                    <hr class="text-white">
                    <h3 class="text-white">This Book will  change your prospective on life</h3>
                    <p class="mb-4 text-white fs-4">
                        Lorem ipsum dolor sit amet consectetur adipisicing elit. Earum, excepturi non provident labore fugit ea iste est ipsam modi magnam temporibus! Natus nisi 
                    </p>
                    <p class="text-white fs-4 mb-2">
                        vel fugit deserunt ea aspernatur nesciunt distinctio saepe reprehenderit quod molestias praesentium repellat, minus necessitatibus fuga pariatur?
                    </p>
                    
                </div>
                
            </div>
            <div class="col-12 col-md-5">
                <div class="text-end mt-3">
                    <a href="" class="text-end text-decoration-none text-white borderbutton-3  mt-4">Read all testimonials</a>
                </div>
                <div class="mt-5 text-center p-5">
                    <h2>A True Masterpiece, Bravo!</h2>
                    <p>
                        Nulla quis lorem ut libero malesuada feugiat. Vivamus magna justo, lacinia eget consectetur sed, 
                        convallis at tellus. Vivamus suscipit tortor eget felis porttitor volutpat. Nulla quis lorem ut libero malesuada feug at.
                    </p>
                </div>
                <p class="mb-5 mt-5">Gerald Hendley,The Guardian</p>
                <div class="mt-5 text-center p-5">
                    <h2>A Unique View On The World</h2>
                    <p>
                        Lorem ipsum dolor sit amet consectetur adipisicing elit. Quam, ex magni placeat ducimus ut, dolore consequatur laboriosam ipsa corporis quia, esse vel sed. 
                        Quisquam quasi, asperiores aspernatur ratione qui, vitae quod similique voluptatibus ea ducimus inventore! Sunt voluptatum molestias unde! Sed dolorem tenetur dicta 
                        suscipit ducimus aliquam possimus distinctio quibusdam, numquam quos ipsam beatae quasi vel sint repellendus, laborum incidunt.
                    </p>
                </div>
                <div>Mary Maxey,The Globe And Mail</div>
                
            </div>
        </div>
    </div>
</template>

<script>
export default {
    name:'Critics',
    data () {
        

        return {}
    }
}
</script>

<style lang="scss" scoped>
img{
    width: 100%;
}
.bcrimg{
    
    background-image: url('../assets/style/images/testimonial2-2x.jpg');
    background-size: cover;
    background-position: center;
    transition: transform 0.5s;
    border-radius: 0 0 30px 0;
    overflow: hidden;
    height: 700px;
    padding: 90px;
}
.bcrimg:hover {
            transform: scale(1.03); 
        }
</style>