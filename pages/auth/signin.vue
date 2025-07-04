<template>
  <div class="d-flex align-center justify-center" style="height: 100vh;">
        <v-card width="500" class="px-8 py-10 textcenter">
        <h1 class="d-flex align-cneter justify-center">LOG IN PAGE</h1>
        <v-form>
        <v-text-field label="Email" outlined prepend-inner-icon="mdi-email"></v-text-field>
        <v-text-field label="Password" outlined prepend-inner-icon="mdi-lock"></v-text-field>

        <v-btn color="primary" rounded block> log in </v-btn>
        <div class="d-flex align-center justify-center">or</div>
        <v-btn color="error" class="text-capitalize" rounded block><v-icon left>mdi-google</v-icon>sign in with google</v-btn>

        
    </v-form>

       </v-card>
     </div>
</template>
<script>
export default {
     layout: "auth"
}
</script>
    