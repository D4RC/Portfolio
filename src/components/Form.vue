<template>
    <section>
        <div class="container">
            <div class="has-text-centered form">
            <h1 class="title">Contáctame</h1>
            <b-field label="Nombre" :label-position="labelPosition">
                <b-input type="text"></b-input>
            </b-field>

            <b-field label="Email" :label-position="labelPosition">
                <b-input type="email"></b-input>
            </b-field>

            <b-field label="Mensaje" :label-position="labelPosition">
                <b-input type="textarea"></b-input>
            </b-field>

            <b-button type="is-aqua">Enviar</b-button>
            </div>
        </div>
    </section>
</template>

<script>
export default {
    data() {
        return {
            labelPosition: 'on-border'
        }
    }
}
</script>


<style>
.form {
    padding: 0 10rem 0 10rem;
}
</style>