<template>
    <nav class="navbar navbar-expand-lg" aria-label="Eighth navbar example">
        <div class="container">
            <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#myNavbar" aria-controls="myNavbar" aria-expanded="true" aria-label="Toggle navigation">
                <span class="navbar-toggler-icon"></span>
            </button>
            <a class="navbar-brand" href="#">
                <img
                    src="../assets/img/Logo.png"
                    alt="Logo de Trabook"
                />
            </a>
            <div class="navbar-collapse collapse" id="myNavbar">
                <ul class="navbar-nav">
                    <li class="nav-item">
                        <a class="nav-link active" aria-current="page" href="#">Home</a>
                    </li>
                    <li class="nav-item">
                        <a class="nav-link" href="#">About</a>
                    </li>
                    <li class="nav-item">
                        <a class="nav-link" href="#destination"
                            >Destination</a
                        >
                    </li>
                    <li class="nav-item">
                        <a class="nav-link" href="#tour">Tour</a>
                    </li>
                    <li class="nav-item">
                        <a class="nav-link" href="#blog">Blog</a>
                    </li>
                </ul>
            </div>
            <div class="align-items-center justify-content-lg-end justify-content-sm-center">
                <button type="button" id="login" class="btn">Login</button>
                <button type="button" id="sign-up" class="btn">Sign Up</button>
            </div>
        </div>
    </nav>
</template>

<script>
export default {
    name: 'HeaderNav'
}
</script>

<style scoped>
.navbar-collapse {
    align-items: center;
    justify-content: center;
}

#login,
#sign-up {
    font-weight: 600;
    padding: 1vh 2vh;
    width: 7rem;
    margin: .5rem 1rem;
}

nav .nav-item {
    padding: 0.1em 1em;
}

#login {
    color: #fa7436;
    border: 1px solid #fa7436;
}

#login:hover {
    background-color: #fa7436;
    color: white;
}

#sign-up {
    background-color: #fa7436;
    color: white;
}

#sign-up:hover {
    background-color: white;
    color: #fa7436;
    border: 1px solid #fa7436;
}
</style>