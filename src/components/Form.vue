<template>
    <v-container>
        <v-form class="w-100">
            <v-text-field 
            color="primary" 
            label="Hello" 
            variant="outlined" 
            hide-details 
            >

            <template v-slot:append>        
                <v-icon color="primary"> mdi-send</v-icon> 
            </template>
                
            </v-text-field>
        </v-form>
    </v-container>
</template>

<script>
export default {
    name: "Form"
}
</script>