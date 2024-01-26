<template>
    <div>
        <v-card style="width: 50%; margin-left: auto; margin-right: auto; margin-top: 25px;">
            <center>
                <v-text-field label="Search weather for any city! 'Tokyo'" style="width: 65%;"><v-icon icon="fa:fas fa-search"></v-icon></v-text-field>
                <h1>Tokyo</h1>
                <span>Today</span><div class="container"><v-img class="v-img" src="../weather/cloudy (1).png" alt=""></v-img></div>
                <span>Mon</span><div class="container"><v-img class="v-img" src="../weather/cloudy.png" alt=""></v-img></div>
                <span>Tue</span><div class="container"><v-img class="v-img" src="../weather/sun.png" alt=""></v-img></div>
            </center>
        </v-card>
    </div>
</template>

<style>
.v-img{
    width: 10%;
}
</style>