<template>
    <div class="container d-flex justify-content-center">
        <div id="discounts-carousel" class="carousel carousel-dark slide d-none d-lg-block my-4" data-bs-ride="carousel">
            <div class="carousel-inner">
                <div class="carousel-item active">
                    <div class="card-wrapper container-sm d-flex justify-content-around">
                        <div class="card discounts-carousel-card">
                            <img src="../assets/img/madrid1.png" class="card-img-top rounded carousel-img" alt="Madrid"/>
                            <div class="card-body">
                                <div class="d-flex align-content-center justify-content-end">
                                    <h5 class="card-title col">Madrid</h5>
                                    <img src="../assets/img/starbg.png" alt="star" width="16px" class="h-50 mr-4 mt-1"/>
                                    <p class="mx-2 d-flex justify-content-end">4.8</p>
                                </div>
                                <div class="d-flex align-content-center justify-content-end">
                                    <svg xmlns="http://www.w3.org/2000/svg" class="me-2" width="13" height="16" viewBox="0 0 13 16" fill="none">
                                        <path d="M6.28572 0C4.61925 0.00196598 3.0216 0.66484 1.84322 1.84321C0.664847 3.02159 0.00197267 4.61924 6.68736e-06 6.28571C-0.00198925 7.64756 0.442853 8.97245 1.26629 10.0571C1.26629 10.0571 1.43772 10.2829 1.46572 10.3154L6.28572 16L11.108 10.3126C11.1331 10.2823 11.3052 10.0571 11.3052 10.0571L11.3057 10.0554C12.1288 8.97121 12.5734 7.64693 12.5714 6.28571C12.5695 4.61924 11.9066 3.02159 10.7282 1.84321C9.54985 0.66484 7.95219 0.00196598 6.28572 0ZM6.28572 8.57143C5.83365 8.57143 5.39173 8.43737 5.01585 8.18622C4.63996 7.93506 4.347 7.57808 4.174 7.16042C4.001 6.74276 3.95573 6.28318 4.04393 5.83979C4.13212 5.39641 4.34981 4.98913 4.66948 4.66947C4.98914 4.34981 5.39642 4.13211 5.8398 4.04392C6.28319 3.95572 6.74277 4.00099 7.16043 4.17399C7.57809 4.34699 7.93507 4.63996 8.18622 5.01584C8.43738 5.39172 8.57144 5.83364 8.57144 6.28571C8.57068 6.89169 8.32962 7.47263 7.90113 7.90112C7.47264 8.32961 6.8917 8.57067 6.28572 8.57143Z" fill="#999999"/>
                                    </svg>
                                    <p class="card-text col">Spain</p>
                                    <p class="card-text tachado mx-3">$950</p>
                                    <b class="card-text precio h-50 w-25 d-flex justify-content-center">$850</b>
                                </div>
                            </div>
                        </div>
                        <div class="card discounts-carousel-card">
                            <img src="../assets/img/firenze1.png" class="card-img-top rounded carousel-img" alt="Firenze"/>
                            <div class="card-body">
                                <div class="d-flex align-content-center justify-content-end">
                                    <h5 class="card-title col">Firenze</h5>
                                    <img src="../assets/img/starbg.png" alt="star" width="16px" class="h-50 mr-4 mt-1"/>
                                    <p class="mx-2 d-flex justify-content-end">4.5</p>
                                </div>
                                <div class="d-flex align-content-center justify-content-end">
                                    <svg xmlns="http://www.w3.org/2000/svg" class="me-2" width="13" height="16" viewBox="0 0 13 16" fill="none">
                                        <path d="M6.28572 0C4.61925 0.00196598 3.0216 0.66484 1.84322 1.84321C0.664847 3.02159 0.00197267 4.61924 6.68736e-06 6.28571C-0.00198925 7.64756 0.442853 8.97245 1.26629 10.0571C1.26629 10.0571 1.43772 10.2829 1.46572 10.3154L6.28572 16L11.108 10.3126C11.1331 10.2823 11.3052 10.0571 11.3052 10.0571L11.3057 10.0554C12.1288 8.97121 12.5734 7.64693 12.5714 6.28571C12.5695 4.61924 11.9066 3.02159 10.7282 1.84321C9.54985 0.66484 7.95219 0.00196598 6.28572 0ZM6.28572 8.57143C5.83365 8.57143 5.39173 8.43737 5.01585 8.18622C4.63996 7.93506 4.347 7.57808 4.174 7.16042C4.001 6.74276 3.95573 6.28318 4.04393 5.83979C4.13212 5.39641 4.34981 4.98913 4.66948 4.66947C4.98914 4.34981 5.39642 4.13211 5.8398 4.04392C6.28319 3.95572 6.74277 4.00099 7.16043 4.17399C7.57809 4.34699 7.93507 4.63996 8.18622 5.01584C8.43738 5.39172 8.57144 5.83364 8.57144 6.28571C8.57068 6.89169 8.32962 7.47263 7.90113 7.90112C7.47264 8.32961 6.8917 8.57067 6.28572 8.57143Z" fill="#999999"/>
                                    </svg>
                                    <p class="card-text col">Italy</p>
                                    <p class="card-text tachado mx-3">$850</p>
                                    <b class="card-text precio h-50 w-25 d-flex justify-content-center">$750</b>
                                </div>
                            </div>
                        </div>
                        <div class="card discounts-carousel-card">
                            <img src="../assets/img/paris1.png" class="card-img-top rounded carousel-img" alt="Paris"/>
                            <div class="card-body">
                                <div class="d-flex align-content-center justify-content-end">
                                    <h5 class="card-title col">Paris</h5>
                                    <img src="../assets/img/starbg.png" alt="star" width="16px" class="h-50 mr-4 mt-1"/>
                                    <p class="mx-2 d-flex justify-content-end">4.4</p>
                                </div>
                                <div class="d-flex align-content-center justify-content-end">
                                    <svg xmlns="http://www.w3.org/2000/svg" class="me-2" width="13" height="16" viewBox="0 0 13 16" fill="none">
                                        <path d="M6.28572 0C4.61925 0.00196598 3.0216 0.66484 1.84322 1.84321C0.664847 3.02159 0.00197267 4.61924 6.68736e-06 6.28571C-0.00198925 7.64756 0.442853 8.97245 1.26629 10.0571C1.26629 10.0571 1.43772 10.2829 1.46572 10.3154L6.28572 16L11.108 10.3126C11.1331 10.2823 11.3052 10.0571 11.3052 10.0571L11.3057 10.0554C12.1288 8.97121 12.5734 7.64693 12.5714 6.28571C12.5695 4.61924 11.9066 3.02159 10.7282 1.84321C9.54985 0.66484 7.95219 0.00196598 6.28572 0ZM6.28572 8.57143C5.83365 8.57143 5.39173 8.43737 5.01585 8.18622C4.63996 7.93506 4.347 7.57808 4.174 7.16042C4.001 6.74276 3.95573 6.28318 4.04393 5.83979C4.13212 5.39641 4.34981 4.98913 4.66948 4.66947C4.98914 4.34981 5.39642 4.13211 5.8398 4.04392C6.28319 3.95572 6.74277 4.00099 7.16043 4.17399C7.57809 4.34699 7.93507 4.63996 8.18622 5.01584C8.43738 5.39172 8.57144 5.83364 8.57144 6.28571C8.57068 6.89169 8.32962 7.47263 7.90113 7.90112C7.47264 8.32961 6.8917 8.57067 6.28572 8.57143Z" fill="#999999"/>
                                    </svg>
                                    <p class="card-text col">France</p>
                                    <p class="card-text tachado mx-3">$699</p>
                                    <b class="card-text precio h-50 w-25 d-flex justify-content-center">$599</b>
                                </div>
                            </div>
                        </div>
                        <div class="card discounts-carousel-card">
                            <img src="../assets/img/london1.png" class="card-img-top rounded carousel-img" alt="London"/>
                            <div class="card-body">
                                <div class="d-flex align-content-center justify-content-end">
                                    <h5 class="card-title col">London</h5>
                                    <img src="../assets/img/starbg.png" alt="star" width="16px" class="h-50 mr-4 mt-1"/>
                                    <p class="mx-2 d-flex justify-content-end">4.8</p>
                                </div>
                                <div class="d-flex align-content-center justify-content-end">
                                    <svg xmlns="http://www.w3.org/2000/svg" class="me-2" width="13" height="16" viewBox="0 0 13 16" fill="none">
                                        <path d="M6.28572 0C4.61925 0.00196598 3.0216 0.66484 1.84322 1.84321C0.664847 3.02159 0.00197267 4.61924 6.68736e-06 6.28571C-0.00198925 7.64756 0.442853 8.97245 1.26629 10.0571C1.26629 10.0571 1.43772 10.2829 1.46572 10.3154L6.28572 16L11.108 10.3126C11.1331 10.2823 11.3052 10.0571 11.3052 10.0571L11.3057 10.0554C12.1288 8.97121 12.5734 7.64693 12.5714 6.28571C12.5695 4.61924 11.9066 3.02159 10.7282 1.84321C9.54985 0.66484 7.95219 0.00196598 6.28572 0ZM6.28572 8.57143C5.83365 8.57143 5.39173 8.43737 5.01585 8.18622C4.63996 7.93506 4.347 7.57808 4.174 7.16042C4.001 6.74276 3.95573 6.28318 4.04393 5.83979C4.13212 5.39641 4.34981 4.98913 4.66948 4.66947C4.98914 4.34981 5.39642 4.13211 5.8398 4.04392C6.28319 3.95572 6.74277 4.00099 7.16043 4.17399C7.57809 4.34699 7.93507 4.63996 8.18622 5.01584C8.43738 5.39172 8.57144 5.83364 8.57144 6.28571C8.57068 6.89169 8.32962 7.47263 7.90113 7.90112C7.47264 8.32961 6.8917 8.57067 6.28572 8.57143Z" fill="#999999"
                                        />
                                    </svg>
                                    <p class="card-text col">UK</p>
                                    <p class="card-text tachado mx-3">$950</p>
                                    <b class="card-text precio h-50 w-25 d-flex justify-content-center">$850</b>
                                </div>
                            </div>
                        </div>
                    </div>
                </div>
                <div class="carousel-item">
                    <div class="card-wrapper container-sm d-flex justify-content-around">
                        <div class="card discounts-carousel-card">
                            <img src="../assets/img/madrid1.png" class="card-img-top rounded carousel-img" alt="Madrid"/>
                            <div class="card-body">
                                <div class="d-flex align-content-center justify-content-end">
                                    <h5 class="card-title col">Madrid</h5>
                                    <img src="../assets/img/starbg.png" alt="star" width="16px" class="h-50 mr-4 mt-1"/>
                                    <p class="mx-2 d-flex justify-content-end">4.8</p>
                                </div>
                                <div class="d-flex align-content-center justify-content-end">
                                    <svg xmlns="http://www.w3.org/2000/svg" class="me-2" width="13" height="16" viewBox="0 0 13 16" fill="none">
                                        <path d="M6.28572 0C4.61925 0.00196598 3.0216 0.66484 1.84322 1.84321C0.664847 3.02159 0.00197267 4.61924 6.68736e-06 6.28571C-0.00198925 7.64756 0.442853 8.97245 1.26629 10.0571C1.26629 10.0571 1.43772 10.2829 1.46572 10.3154L6.28572 16L11.108 10.3126C11.1331 10.2823 11.3052 10.0571 11.3052 10.0571L11.3057 10.0554C12.1288 8.97121 12.5734 7.64693 12.5714 6.28571C12.5695 4.61924 11.9066 3.02159 10.7282 1.84321C9.54985 0.66484 7.95219 0.00196598 6.28572 0ZM6.28572 8.57143C5.83365 8.57143 5.39173 8.43737 5.01585 8.18622C4.63996 7.93506 4.347 7.57808 4.174 7.16042C4.001 6.74276 3.95573 6.28318 4.04393 5.83979C4.13212 5.39641 4.34981 4.98913 4.66948 4.66947C4.98914 4.34981 5.39642 4.13211 5.8398 4.04392C6.28319 3.95572 6.74277 4.00099 7.16043 4.17399C7.57809 4.34699 7.93507 4.63996 8.18622 5.01584C8.43738 5.39172 8.57144 5.83364 8.57144 6.28571C8.57068 6.89169 8.32962 7.47263 7.90113 7.90112C7.47264 8.32961 6.8917 8.57067 6.28572 8.57143Z" fill="#999999"/>
                                    </svg>
                                    <p class="card-text col">Spain</p>
                                    <p class="card-text tachado mx-3">$950</p>
                                    <b class="card-text precio h-50 w-25 d-flex justify-content-center">$850</b>
                                </div>
                            </div>
                        </div>
                        <div class="card discounts-carousel-card">
                            <img src="../assets/img/firenze1.png" class="card-img-top rounded carousel-img" alt="Firenze"/>
                            <div class="card-body">
                                <div class="d-flex align-content-center justify-content-end">
                                    <h5 class="card-title col">Firenze</h5>
                                    <img src="../assets/img/starbg.png" alt="star" width="16px" class="h-50 mr-4 mt-1"/>
                                    <p class="mx-2 d-flex justify-content-end">4.5</p>
                                </div>
                                <div class="d-flex align-content-center justify-content-end">
                                    <svg xmlns="http://www.w3.org/2000/svg" class="me-2" width="13" height="16" viewBox="0 0 13 16" fill="none">
                                        <path d="M6.28572 0C4.61925 0.00196598 3.0216 0.66484 1.84322 1.84321C0.664847 3.02159 0.00197267 4.61924 6.68736e-06 6.28571C-0.00198925 7.64756 0.442853 8.97245 1.26629 10.0571C1.26629 10.0571 1.43772 10.2829 1.46572 10.3154L6.28572 16L11.108 10.3126C11.1331 10.2823 11.3052 10.0571 11.3052 10.0571L11.3057 10.0554C12.1288 8.97121 12.5734 7.64693 12.5714 6.28571C12.5695 4.61924 11.9066 3.02159 10.7282 1.84321C9.54985 0.66484 7.95219 0.00196598 6.28572 0ZM6.28572 8.57143C5.83365 8.57143 5.39173 8.43737 5.01585 8.18622C4.63996 7.93506 4.347 7.57808 4.174 7.16042C4.001 6.74276 3.95573 6.28318 4.04393 5.83979C4.13212 5.39641 4.34981 4.98913 4.66948 4.66947C4.98914 4.34981 5.39642 4.13211 5.8398 4.04392C6.28319 3.95572 6.74277 4.00099 7.16043 4.17399C7.57809 4.34699 7.93507 4.63996 8.18622 5.01584C8.43738 5.39172 8.57144 5.83364 8.57144 6.28571C8.57068 6.89169 8.32962 7.47263 7.90113 7.90112C7.47264 8.32961 6.8917 8.57067 6.28572 8.57143Z" fill="#999999"/>
                                    </svg>
                                    <p class="card-text col">Italy</p>
                                    <p class="card-text tachado mx-3">$850</p>
                                    <b class="card-text precio h-50 w-25 d-flex justify-content-center">$750</b>
                                </div>
                            </div>
                        </div>
                        <div class="card discounts-carousel-card">
                            <img src="../assets/img/paris1.png" class="card-img-top rounded carousel-img" alt="Paris"/>
                            <div class="card-body">
                                <div class="d-flex align-content-center justify-content-end">
                                    <h5 class="card-title col">Paris</h5>
                                    <img src="../assets/img/starbg.png" alt="star" width="16px" class="h-50 mr-4 mt-1"/>
                                    <p class="mx-2 d-flex justify-content-end">4.4</p>
                                </div>
                                <div class="d-flex align-content-center justify-content-end">
                                    <svg xmlns="http://www.w3.org/2000/svg" class="me-2" width="13" height="16" viewBox="0 0 13 16" fill="none">
                                        <path d="M6.28572 0C4.61925 0.00196598 3.0216 0.66484 1.84322 1.84321C0.664847 3.02159 0.00197267 4.61924 6.68736e-06 6.28571C-0.00198925 7.64756 0.442853 8.97245 1.26629 10.0571C1.26629 10.0571 1.43772 10.2829 1.46572 10.3154L6.28572 16L11.108 10.3126C11.1331 10.2823 11.3052 10.0571 11.3052 10.0571L11.3057 10.0554C12.1288 8.97121 12.5734 7.64693 12.5714 6.28571C12.5695 4.61924 11.9066 3.02159 10.7282 1.84321C9.54985 0.66484 7.95219 0.00196598 6.28572 0ZM6.28572 8.57143C5.83365 8.57143 5.39173 8.43737 5.01585 8.18622C4.63996 7.93506 4.347 7.57808 4.174 7.16042C4.001 6.74276 3.95573 6.28318 4.04393 5.83979C4.13212 5.39641 4.34981 4.98913 4.66948 4.66947C4.98914 4.34981 5.39642 4.13211 5.8398 4.04392C6.28319 3.95572 6.74277 4.00099 7.16043 4.17399C7.57809 4.34699 7.93507 4.63996 8.18622 5.01584C8.43738 5.39172 8.57144 5.83364 8.57144 6.28571C8.57068 6.89169 8.32962 7.47263 7.90113 7.90112C7.47264 8.32961 6.8917 8.57067 6.28572 8.57143Z" fill="#999999"/>
                                    </svg>
                                    <p class="card-text col">France</p>
                                    <p class="card-text tachado mx-3">$699</p>
                                    <b class="card-text precio h-50 w-25 d-flex justify-content-center">$599</b>
                                </div>
                            </div>
                        </div>
                        <div class="card discounts-carousel-card">
                            <img src="../assets/img/london1.png" class="card-img-top rounded carousel-img" alt="London"/>
                            <div class="card-body">
                                <div class="d-flex align-content-center justify-content-end">
                                    <h5 class="card-title col">London</h5>
                                    <img src="../assets/img/starbg.png" alt="star" width="16px" class="h-50 mr-4 mt-1"/>
                                    <p class="mx-2 d-flex justify-content-end">4.8</p>
                                </div>
                                <div class="d-flex align-content-center justify-content-end">
                                    <svg xmlns="http://www.w3.org/2000/svg" class="me-2" width="13" height="16" viewBox="0 0 13 16" fill="none">
                                        <path d="M6.28572 0C4.61925 0.00196598 3.0216 0.66484 1.84322 1.84321C0.664847 3.02159 0.00197267 4.61924 6.68736e-06 6.28571C-0.00198925 7.64756 0.442853 8.97245 1.26629 10.0571C1.26629 10.0571 1.43772 10.2829 1.46572 10.3154L6.28572 16L11.108 10.3126C11.1331 10.2823 11.3052 10.0571 11.3052 10.0571L11.3057 10.0554C12.1288 8.97121 12.5734 7.64693 12.5714 6.28571C12.5695 4.61924 11.9066 3.02159 10.7282 1.84321C9.54985 0.66484 7.95219 0.00196598 6.28572 0ZM6.28572 8.57143C5.83365 8.57143 5.39173 8.43737 5.01585 8.18622C4.63996 7.93506 4.347 7.57808 4.174 7.16042C4.001 6.74276 3.95573 6.28318 4.04393 5.83979C4.13212 5.39641 4.34981 4.98913 4.66948 4.66947C4.98914 4.34981 5.39642 4.13211 5.8398 4.04392C6.28319 3.95572 6.74277 4.00099 7.16043 4.17399C7.57809 4.34699 7.93507 4.63996 8.18622 5.01584C8.43738 5.39172 8.57144 5.83364 8.57144 6.28571C8.57068 6.89169 8.32962 7.47263 7.90113 7.90112C7.47264 8.32961 6.8917 8.57067 6.28572 8.57143Z" fill="#999999"
                                        />
                                    </svg>
                                    <p class="card-text col">UK</p>
                                    <p class="card-text tachado mx-3">$950</p>
                                    <b class="card-text precio h-50 w-25 d-flex justify-content-center">$850</b>
                                </div>
                            </div>
                        </div>
                    </div>
                </div>
            </div>

            <div class="flechas d-flex justify-content-center">
                <button class="btn slider-btn mx-3 my-3" type="button" data-bs-target="#discounts-carousel" data-bs-slide="prev">
                    <i class="bi bi-arrow-left"></i>
                </button>

                <button class="btn slider-btn mx-2 my-3" type="button" data-bs-target="#discounts-carousel" data-bs-slide="next">
                    <i class="bi bi-arrow-right"></i>
                </button>
            </div>
        </div>
    </div>
</template>

<script setup></script>

<style scoped>
p {
    color: #666;
    font-family: "Segoe UI", Tahoma, Geneva, Verdana, sans-serif;
}

.discounts-carousel-card {
    height: auto;
    border-radius: 8px;
    border: 2px solid rgba(102, 102, 102, 0.08);
    background: #fefcfb;
    margin-right: 1rem;
    margin-left: 1rem;
}

.discounts-carousel-card:hover {
    box-shadow: 0px 16px 80px 0px rgba(254, 147, 94, 0.2);
}

.carousel-img:hover {
    filter: brightness(50%);
}

.card-body {
    padding: 3vh;
}

.card-title {
    font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
    font-weight: bold;
    color: #222;
}

.tachado {
    text-decoration: line-through 2px;
    color: #999;
}

.precio {
    background-color: #ffe7db;
    color: #fa7436;
    border-radius: 8px;
}

.slider-btn {
    border: none;
}

.flechas button {
    background: white;
    border: 1px solid #666;
    border-radius: 50%;
}

.flechas button i {
    color: #666;
    font-size: 1.5rem;
}

.flechas button:hover {
    background: #fa7436;
    border: none;
}

.flechas button:hover i {
    color: white;
}

.flechas button:active {
    background-color: white;
    border: none;
}

.flechas button:active i {
    color: #fa7436;
}
</style>