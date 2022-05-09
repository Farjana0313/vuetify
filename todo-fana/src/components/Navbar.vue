<template>
    <nav>
        <v-app-bar flat app>
            <v-app-bar-nav-icon class="grey--text" @click="drawer=!drawer"></v-app-bar-nav-icon>
            <v-app-bar-title class="text-uppercase grey--text">
                <span class="font-weight-light">Todo</span>
                <span>Fana</span>
            </v-app-bar-title>
            <v-spacer></v-spacer>
            <v-btn text color="grey">
                <span>Sign Out</span>
                <v-icon right>mdi-exit-to-app</v-icon>
            </v-btn>
        </v-app-bar>
        <v-navigation-drawer class="indigo" v-model="drawer" absolute temporary>
            <p>test</p>
        </v-navigation-drawer>
    </nav>

</template>
<script>
    export default {
        data() {
            return {
                drawer: false,
            };
        },
    }
</script>