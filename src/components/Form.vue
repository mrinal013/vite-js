<template>
    <v-container>
        <v-form class="w-100" @submit.prevent="sendMessage">
            <v-text-field 
            color="primary"  
            variant="outlined" 
            hide-details 
            append-icon="mdi-send" 
            @click:append="sendMessage" 
            v-model="message"
            >
            </v-text-field>
        </v-form>
    </v-container>
</template>

<script setup>
import { ref } from 'vue';

const message = ref('');

const sendMessage = () => {
    console.log(message.value)
}

</script>