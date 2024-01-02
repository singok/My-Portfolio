<script>
export default {
    name:'ContactForm'
}
</script>

<template>
    <div class="contact-form">
        <div class="input-form">
            <div class="label-input-wrapper">
                <label class="label-name">Name : </label> <input type="text" class="input-val">
            </div>
            <div class="label-input-wrapper">
                <label class="label-name">Phone No. : </label> <input type="text" class="input-val">
            </div>
            <div class="label-input-wrapper">
                <label class="label-name">Email Address : </label> <input type="text" class="input-val">
            </div>
        </div>
        <div class="submit-button">
            <button>Submit</button>
        </div>
    </div>
</template>

<style scoped>
.contact-form {
    display: flex;
    flex-direction: column;
    gap:1rem;
}
.submit-button button {
    width: 100%;
    color: white;
    background-color: black;
    padding: 0.5rem 1rem;
}
.input-form {
    display: flex;
    gap: 1rem;
    flex-direction: column;
}

.label-input-wrapper {
    display: flex;
    justify-content: space-between;
    align-items: center;
}

.input-val {
    width: 70%;
    height: 2rem;
}
.label-name {
    width: 30%;
}
</style>