<template>
    <form>
        <label for="name" class="form-label">Ingresa tu Nombre</label>
        <input id="name" type="text" class="form-control"/>
        <label for="email" class="form-label">Ingresa tu E-Mail</label>
        <input id="email" type="email" class="form-control"/>
        <label for="textarea" class="form-label">Ingresa tus comentarios</label>
        <textarea class="form-control" id="textarea" rows="3"></textarea>
        <button class="btn btn-success" type="submit">Enviar</button>
    </form>
</template>

<script>
export default {
    name: 'Diego',
    data() {
        return {};
    }
};
</script>

<style scoped></style>

<!-- Crea un formulario HTML que contenga un campo de texto para el nombre, un campo de correo electrónico, un área de texto para comentarios, y un botón para enviar los datos. -->