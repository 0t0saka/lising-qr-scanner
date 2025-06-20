<template>
    <div class=" d-flex mx-auto justify-center align-center" style="height:100vh;" >
       <v-card max-witdh="500">
        
            <v-card-text>
                <v-form>
                    
                    <v-text-field
                    label="Email"
                    prepend-inner-icon="mdi-email"
                    ></v-text-field>

                     <v-text-field
                    label="Password"
                    type="Password"
                    prepend-inner-icon="mdi-lock"
                    ></v-text-field>
                    <v-btn >
                        Log in
                    </v-btn>
                </v-form>
                
            </v-card-text>
       </v-card>
  
    </div>
</template>
<script>
export default{
    layout:"auth",
}
</script>
 