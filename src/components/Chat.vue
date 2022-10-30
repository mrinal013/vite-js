<template>
    <v-card class="w-50 mb-3"  variant="outlined" v-for="item of messages" :key="item.id" :class="item.displayName == 'Mrinal' && 'ml-auto bg-primary'">
        <v-card-title class="text-h5">{{ item.displayName + '-' + item.time }}</v-card-title>
        <v-card-subtitle>{{ item.text }}</v-card-subtitle>
    </v-card>
</template>

<script setup>
import { ref } from 'vue';

const messages = ref([
    {
        id: 1,
        text: 'Hello i am from BD',
        uid: "001",
        time: Date.now(),
        displayName: 'Mrinal'
    },
    {
        id: 2,
        text: 'Hello i am from B.Baria',
        uid: "002",
        time: Date.now(),
        displayName: 'Asad'
    },
    {
        id: 3,
        text: 'Hello i am from India',
        uid: "003",
        time: Date.now(),
        displayName: 'Tanvir'
    },

])
</script>