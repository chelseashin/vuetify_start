<template>
    <!-- <header>
        <h1>{{ propsdata }}</h1>
        <button v-on:click="sendEvent">submit</button>
    </header> -->

    <v-toolbar>
        <v-toolbar-title>Title</v-toolbar-title>

        <v-spacer></v-spacer>

        <v-toolbar-items>
        <v-btn text>Vision</v-btn>
        <v-btn text>HowTo</v-btn>
        <v-btn text>Team</v-btn>
        <v-btn text>LogIn</v-btn>
        </v-toolbar-items>

        <template v-if="$vuetify.breakpoint.smAndUp">
            <!-- 검색 -->
            <v-btn icon>
                <v-icon>search</v-icon>
            </v-btn>
            <!-- 즐겨찾기 추가 -->
            <v-btn icon>
                <v-icon>favorite</v-icon>
            </v-btn>
        </template>
    </v-toolbar>

</template>

<script>
// export default {
//     props: ['propsdata'],
//     methods: {
//         sendEvent: function() {
//             this.$emit('renew')
//         }
//     }
// }
</script>


<style>

</style>
