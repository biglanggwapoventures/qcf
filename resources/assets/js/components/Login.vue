<template>
    <div class="d-flex flex-row justify-content-center align-items-center">
        <div class="p-2">
            <b-card header="Quick Cash Flow v2 | Login">
                <b-form @submit.prevent="doLogin()">
                    <b-form-fieldset label="Enter your username">
                        <b-form-input v-model="credentials.username" type="text"></b-form-input>
                    </b-form-fieldset>
                    <b-form-fieldset label="Enter your password">
                        <b-form-input v-model="credentials.password" type="password"></b-form-input>
                    </b-form-fieldset>
                    <b-button type="submit" variant="success">Log me in!</b-button>
                </b-form>
            </b-card>
        </div>
    </div>
</template>

<script>
export default {
    data() {
        return {
            credentials: {
                username: null,
                password: null
            }
        } 
    },
    methods: {
        doLogin() {
            
        }
    }
}
</script>
