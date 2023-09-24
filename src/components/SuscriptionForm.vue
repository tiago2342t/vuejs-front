<template>
    <section>
        <div
            class="container col-xxl-8 d-block justify-content-center align-content-center py-4 mb-5 mt-5 w-75"
            id="suscripcion"
        >
            <h3 class="centered-title my-4" id="titulo-suscripcion">
                Subscribe and get exclusive <br />
                deals & offer
            </h3>
            <form>
                <div class="input-group justify-content-center align-items-center mb-4" id="email-field">
                    <i class="bi bi-envelope px-2"></i>
                    <input type="text" id="email-input" class="form-control border-0 py-1 px-2" placeholder="Enter your mail" aria-label="Enter your mail" aria-describedby="basic-addon2">
                    <div class="input-group-append">
                        <button class="ms-3 me-2 py-1 px-2" id="subscribe-btn" type="button">Subscribe</button>
                    </div>
                </div>
            </form>
        </div>
    </section>
</template>

<script setup></script>

<style scoped>
.centered-title {
    font-family: Cambria, Cochin, Georgia, Times, "Times New Roman", serif;
    font-size: 6vh;
    text-align: center;
    font-weight: bold;
    color: #222;
}

#suscripcion {
    background-color: #fa7436;
    border-radius: 1rem;
}

#titulo-suscripcion {
    color: white;
}

#email-field {
    background-color: white;
    width: 60%;
    height: 3.5rem;
    border-radius: 0.6rem;
    margin: auto;
    justify-content: space-around;
}

#email-field i, #email-input {
    color: #999;
}


#subscribe-btn {
    border: none;
    border-radius: 0.5rem;
    background-color: #fa7436;
    color: white;
    font-size: 1.2rem;
}

#subscribe-btn:hover {
    background-color: white;
    color: #fa7436;
    border: 1px solid #fa7436;
}
</style>