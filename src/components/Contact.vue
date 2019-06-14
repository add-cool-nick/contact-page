<template>
    <v-container fluid class="outside">

        

        <v-layout row wrap>
            <v-flex xs12>
                <h1 class="heading-1">CONTACT US</h1>
            </v-flex>
        </v-layout>


        <v-layout row wrap justify-center align-center class="row">
            
            <v-flex sm4 xs12 class="contact">
            <v-card class="card" elevation="5" color="#2e2e2e" dark>

                
                <div class="img-1">
                    <v-avatar size ='175' class="img-container"> <img src="empty.png" class="image" /> </v-avatar>
                </div>

                <div class="details">
                    <h3>Jake Weary</h3>
                    <h4>Designation</h4>
                    <h4>Ph no: 1234567890</h4>
                    <h4>sample-email@email.com</h4>
                </div>
                
            </v-card>
            </v-flex>
            


            <v-flex sm4 xs12 class="contact">
            <v-card class="card" elevation="5" color="#2e2e2e" dark>

                
                <div class="img-1">
                    <v-avatar size ='175' class="img-container"> <img src="empty.png" class="image" /> </v-avatar>
                </div>

                <div class="details">
                    <h3>Jake Weary</h3>
                    <h4>Designation</h4>
                    <h4>Ph no: 1234567890</h4>
                    <h4>sample-email@email.com</h4>
                </div>
                
            </v-card>
            </v-flex>


            <v-flex sm4 xs12 class="contact">
            <v-card class="card" elevation="5" color="#2e2e2e" dark>

                
                <div class="img-1">
                    <v-avatar size ='175' class="img-container"> <img src="empty.png" class="image" /> </v-avatar>
                </div>

                <div class="details">
                    <h3>Jake Weary</h3>
                    <h4>Designation</h4>
                    <h4>Ph no: 1234567890</h4>
                    <h4>sample-email@email.com</h4>
                </div>
                
            </v-card>
            </v-flex>

        </v-layout>


        <v-layout row wrap justify-center align-center>

            <v-flex sm4 xs12 class="contact">
            <v-card class="card" elevation="5" color="#2e2e2e" dark>

                
                <div class="img-1">
                    <v-avatar size ='175' class="img-container"> <img src="empty.png" class="image" /> </v-avatar>
                </div>

                <div class="details">
                    <h3>Jake Weary</h3>
                    <h4>Designation</h4>
                    <h4>Ph no: 1234567890</h4>
                    <h4>sample-email@email.com</h4>
                </div>
                
            </v-card>
            </v-flex>


            <v-flex sm4 xs12 class="contact">
            <v-card class="card" elevation="5" color="#2e2e2e" dark>

                
                <div class="img-1">
                    <v-avatar size ='175' class="img-container"> <img src="empty.png" class="image" /> </v-avatar>
                </div>

                <div class="details">
                    <h3>Jake Weary</h3>
                    <h4>Designation</h4>
                    <h4>Ph no: 1234567890</h4>
                    <h4>sample-email@email.com</h4>
                </div>
                
            </v-card>
            </v-flex>


            <v-flex sm4 xs12 class="contact">
            <v-card class="card" elevation="5" color="#2e2e2e" dark>

                
                <div class="img-1">
                    <v-avatar size ='175' class="img-container"> <img src="empty.png" class="image" /> </v-avatar>
                </div>

                <div class="details">
                    <h3>Jake Weary</h3>
                    <h4>Designation</h4>
                    <h4>Ph no: 1234567890</h4>
                    <h4>sample-email@email.com</h4>
                </div>
                
            </v-card>
            </v-flex>
        </v-layout>

       

    </v-container>
</template>


<script>
import 'bootstrap/dist/css/bootstrap.css'

export default {
    name: 'Contact',
    imgSize: '500',
}
</script>

<style>

.heading-1 {
    text-align: center;
    margin-bottom: 2%;
    margin-top: 2%;
    font-size: 3.5em;
    color: #d17506;
}


.image {
    margin: auto;
}

.card {
    padding-top: 7%;
    padding-bottom: 3%;
   
    /* background: linear-gradient(to bottom, #33ccff 0%, #ff99cc 100%); */
    /* background-color:orange; */



}

.img-container {
    padding: auto;
    
}

.contact {
    padding-left : 5%;
    padding-right: 5%;
    margin-bottom: 5%;
}


.details {
    margin-top: 5%;
    margin-bottom: 5%;
    text-align: center;
}

.img-1 {
    /* padding-left: 30%;
    padding-right: 30%; */
    text-align: center;
}

.outside {
    width: 100%;
    background: url("./../../public/contact1.jpg");
    background-size: cover;
    background-position: center;
}

.row {
    margin-bottom: 4%;
}



</style>

