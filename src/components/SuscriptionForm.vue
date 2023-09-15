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
                <div
                    class="d-flex mx-auto align-items-center mb-4"
                    id="email-field"
                >
                    <svg
                        class="ms-3 me-2"
                        xmlns="http://www.w3.org/2000/svg"
                        width="19"
                        height="16"
                        viewBox="0 0 19 16"
                        fill="none"
                    >
                        <path
                            d="M3.55566 5.33301L8.289 8.88301C8.64455 9.14967 9.13344 9.14967 9.489 8.88301L14.2223 5.33301"
                            stroke="#999999"
                            stroke-linecap="round"
                        />
                        <rect
                            x="0.5"
                            y="0.5"
                            width="17.6667"
                            height="15"
                            rx="4.5"
                            stroke="#999999"
                        />
                    </svg>
                    <input
                        type="email"
                        class="col"
                        id="email-input"
                        placeholder="Enter your mail"
                    />
                    <input
                        type="button"
                        class="ms-3 me-2 py-1 px-2"
                        id="subscribe-btn"
                        value="Subscribe"
                    />
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
}

#email-input {
    border: none;
    color: #999;
}

#subscribe-btn {
    border: none;
    border-radius: 0.5rem;
    background-color: #fa7436;
    color: white;
    height: 75%;
    width: 20%;
}

#subscribe-btn:hover {
    background-color: white;
    color: #fa7436;
    border: 1px solid #fa7436;
}
</style>