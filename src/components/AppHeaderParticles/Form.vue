<template>
        <form v-if="showForm = true" @submit.prevent="submitForm">
            <label>Nome</label>
            <input type="text" id="name" v-model="form.name">

            <label>Email</label>
            <input type="email" id="email" v-model="form.email">

            <button class="form" @click="closeForm" type="submit">Invia</button>
        </form>
</template>


<script>
export default {
    name: 'Form',

    data(){
        return{
            showForm: false,
            form: {
                name: '',
                email: ''
            }
        };
    },

    methods: {
        submitForm() {
        
        console.log(this.form);
        this.showForm = false;

        this.form.name = '';
        this.form.email = '';
        },

        closeForm() {   
        this.visible = false;
        this.$emit('closeForm'); 
        }
    },
}
</script>


<style lang="scss" scoped>

    .container-form{
        position: absolute;
    }

    button.form{
        width: 140px;
        height: 37px;
        border: none;
        color: white;
        text-transform: uppercase;
        font-weight: bold;
        background-color: #f63c81;
        top: 124px;
    }

    button:hover{
        background-color: #46b1fd;
    }

    form{
        width: 900px;
        height: 600px;
        background-color: #f63c81;
        border-radius: 50px;
        position: absolute;
        display: flex;
        align-items: center;
        justify-content: center;
        flex-wrap: wrap;
    }

    label{
        width: 70%;
        text-transform: uppercase;
        color: #46b1fd;
        font-weight: bold;
        font-size: 16px;
    }

    input{
        border: 2px solid #46b1fd;
    }
</style>