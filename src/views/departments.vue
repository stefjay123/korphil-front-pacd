<template>
    <v-navigation-drawer permanent location="right" style="background-color: #EAEAEA;">

        <v-img class="mx-auto mt-5" src="@/assets/ARA1.png" width="100"></v-img>
        <h2 class="text mt-7" style="text-align:center">Your feedback matters to us!</h2>

        <!-- line here -->


        <v-col cols="2">
            <v-card style="background-color: white; border-radius: 70px; margin-right: 20px;" width="250"
                border-radius="20px">
                <v-img class="align-end text-white" height="150px" src="@/assets/1.png" style="margin: 25px;">

                </v-img>

                <v-card-actions class="pa-4 rounded-b-xl font-weight-bold"
                    style="background-color: white; color: #2B2D30; justify-content: center; font-size: 1.5em;">
                    Walk-in
                </v-card-actions>
            </v-card>
        </v-col>

        <!-- line here -->

        <v-col cols="2">
            <v-card style="background-color: white; border-radius: 70px; margin-right: 20px;" width="250"
                border-radius="20px">
                <v-img class="align-end text-white" height="150px" src="@/assets/3.png" style="margin: 25px;">

                </v-img>

                <v-card-actions class="pa-4 rounded-b-xl font-weight-bold"
                    style="background-color: white; color: #2B2D30; justify-content: center; font-size: 1.5em;">
                    Assessment
                </v-card-actions>
            </v-card>
        </v-col>


    </v-navigation-drawer>



    <v-row>
        <v-app-bar class="app pa-5" style="background-color: #3C59A6">


            <v-col cols="1" class="img ml-10">
                <v-img src="@/assets/tesda-white.png"></v-img>
            </v-col>

            <v-text-field class="search-bar" hide-details append-inner-icon="mdi-magnify"
                label="Search for category, name, keyword, etc." style="color: white"></v-text-field>

            <v-col cols="1" class="img ml-10">
                <v-img src="@/assets/rtc1.png"></v-img>
            </v-col>

        </v-app-bar>

    </v-row>
    <h1 class="title" style=" display:flex; justify-content: center; color: #2B2D30; font-size: 2em; margin-top: 150px;">
        Select the department of your concern:</h1>

    <!-- line here -->

    <v-layout class="pa-10" style="margin-top: 60px">

        <v-row justify="center">
            <v-col cols="6" align="right">
                <v-card style="background-color: #3C59A6; border-radius: 70px; margin-right: 20px;" width="400"
                    border-radius="20px">
                    <v-img class="align-end text-white" height="250px" src="@/assets/training1.png" style="margin: 25px;">

                    </v-img>

                    <v-card-actions class="pa-4 rounded-b-xl"
                        style="background-color: #1E4A81; color:white; justify-content: center; font-size: 1.5em;">
                        Training
                    </v-card-actions>
                </v-card>
            </v-col>
            <v-col cols="6">
                <v-card style="background-color: #3C59A6; border-radius: 70px; margin-right: 20px;" width="400"
                    border-radius="20px">
                    <v-img class="align-end text-white" height="250px" src="@/assets/registrar.png" style="margin: 25px;">

                    </v-img>

                    <v-card-actions class="box1 pa-4 rounded-b-xl"
                        style="background-color: #1E4A81; color: white; justify-content: center; font-size: 1.5em;">
                        Registrar
                    </v-card-actions>
                </v-card>
            </v-col>
            <v-col cols="6" align="right">
                <v-card style="background-color: #3C59A6; border-radius: 70px; margin-right: 20px;" width="400"
                    border-radius="20px">
                    <v-img class="align-end text-white" height="250px" src="@/assets/certification.png"
                        style="margin: 25px;">

                    </v-img>

                    <v-card-actions class="box1 pa-4 rounded-b-xl"
                        style="background-color: #1E4A81; color: white; justify-content: center; font-size: 1.40em;">
                        Certification and Assessment
                    </v-card-actions>
                </v-card>
            </v-col>
            <v-col cols="6">
                <v-card style="background-color: #3C59A6; border-radius: 70px; margin-right: 20px;" width="400"
                    border-radius="20px">
                    <v-img class="align-end text-white" height="250px" src="@/assets/procurement.png" style="margin: 25px;">

                    </v-img>

                    <v-card-actions class="box1 pa-4 rounded-b-xl"
                        style="background-color: #1E4A81; color: white; justify-content: center; font-size: 1.5em;">
                        Procurement
                    </v-card-actions>
                </v-card>
            </v-col>
            <v-col cols="6" align="right">
                <v-card style="background-color: #3C59A6; border-radius: 70px; margin-right: 20px;" width="400"
                    border-radius="20px">
                    <v-img class="align-end text-white" height="250px" src="@/assets/account.png" style="margin: 25px;">

                    </v-img>

                    <v-card-actions class="box1 pa-4 rounded-b-xl"
                        style="background-color:  #1E4A81; color: white; justify-content: center; font-size: 1.5em;">
                        Accounting
                    </v-card-actions>
                </v-card>
            </v-col>
            <v-col cols="6">
                <v-card style="background-color: #3C59A6; border-radius: 70px; margin-right: 20px;" width="400"
                    border-radius="20px">
                    <v-img class="align-end text-white" height="250px" src="@/assets/administrator.png"
                        style="margin: 25px;">

                    </v-img>

                    <v-card-actions class="box1 pa-4 rounded-b-xl"
                        style="background-color:  #1E4A81; color: white; justify-content: center; font-size: 1.5em;">
                        Admin
                    </v-card-actions>
                </v-card>
            </v-col>
        </v-row>

    </v-layout>
</template>
