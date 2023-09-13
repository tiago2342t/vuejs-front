<template>
    <section>
        <div class="container d-flex justify-content-center">
            <div class="card w-75 align-items-center px-3 py-2" id="carta-flotante">
                <div class="row">
                    <div class="col-lg">
                        <div class="card-body">
                            <div class="d-flex align-items-center">
                                <h6 class="card-title">Location</h6>
                                <svg class="mx-2 mb-2" xmlns="http://www.w3.org/2000/svg" width="12" height="8" viewBox="0 0 12 8" fill="none">
                                    <path d="M1 1.5L6 6.5L11 1.5" stroke="#FA7436" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"/>
                                </svg>
                            </div>
                            <p class="card-text">Where are you going</p>
                        </div>
                    </div>
                    <div class="col-lg">
                        <div class="card-body row">
                            <div class="d-flex align-items-center">
                                <h6 class="card-title">Date</h6>
                                <svg class="mx-2 mb-2" xmlns="http://www.w3.org/2000/svg" width="12" height="8" viewBox="0 0 12 8" fill="none">
                                    <path d="M1 1.5L6 6.5L11 1.5" stroke="#FA7436" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"/>
                                </svg>
                            </div>
                            <p class="card-text">When you will go</p>
                        </div>
                    </div>
                    <div class="col-lg">
                        <div class="card-body row">
                            <div class="d-flex align-items-center">
                                <h6 class="card-title">Guest</h6>
                                <svg class="mx-2 mb-2" xmlns="http://www.w3.org/2000/svg" width="12" height="8" viewBox="0 0 12 8" fill="none">
                                    <path d="M1 1.5L6 6.5L11 1.5" stroke="#FA7436" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"/>
                                </svg>
                            </div>
                            <p class="card-text">Number of guest</p>
                        </div>
                    </div>
                    <div class="col-lg d-flex justify-content-end">
                        <div class="card-body">
                            <button type="button" id="explore-btn" class="btn">Explore Now</button>
                        </div>
                    </div>
                </div>
            </div>
        </div>
        
    </section>
</template>

<script setup></script>

<style scoped>
#carta-flotante {
    background-color: white;
    border-radius: 1.5vh;
    border: transparent;
    box-shadow: 0px 2px 80px 2px rgba(0, 0, 0, 0.06);
}

.card-title {
    font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
    font-weight: bold;
    color: #222;
}

.card-text {
    color: #666;
    font-family: "Segoe UI", Tahoma, Geneva, Verdana, sans-serif;
}

#explore-btn {
    background-color: #fa7436;
    height: 3.5rem;
    width: 100%;
    color: white;
    border-radius: 5px;
}

#explore-btn:hover {
    background-color: white;
    color: #fa7436;
    border: 1px solid #fa7436;
}
</style>