<template>
    <section class="our_work py-40 relative" loading="lazy">
        <div class="curtain"></div>
        <div class="left_plane animate-bounce"><img src="/images/plane-vector.svg" alt="plane" /></div>
        <div class="right_plane animate-bounce"><img src="/images/plane-vector.svg" alt="plane" /></div>
        <div class="relative z-10">
            <h3 class="text-white text-center z-50 text-4xl mb-14">Our Work</h3>
            <div class="text-center text-white flex justify-center items-center gap-18 flex-wrap">
                <div class="">
                    <h2 class="text-white text-7xl">83+</h2>
                    <p class="text-2xl uppercase">Clients Worldwide</p>
                </div>
                <div class="">
                    <h2 class="text-white text-7xl">36+</h2>
                    <p class="text-2xl uppercase">Countries Covered</p>
                </div>
                <div class="">
                    <h2 class="text-white text-7xl">1550+</h2>
                    <p class="text-2xl uppercase">Delivered Packages</p>
                </div>
            </div>
        </div>

    </section>
</template>

<style>
.our_work {
    background: url('/images/our_work.webp');
    background-repeat: no-repeat;
    background-position: center;
    background-size: cover;
}

.our_work {

    .left_plane,
    .right_plane {
        position: absolute;
        width: 200px;
        height: 200px;
        z-index: 2;
        top: 50%;
        transform: translateY(-50%);
    }

    .left_plane {
        left: 30px;
    }

    .right_plane {
        top: 20%;
        right: 25px;

    }
}

.left_plane.animate-bounce {
    animation: bounce 3s infinite;
}

.right_plane.animate-bounce {
    animation: bounce 3.5s infinite;
}

@keyframes bounce {

    0%,
    100% {
        transform: translateX(-50%);
        animation-timing-function: cubic-bezier(0.8, 0, 1, 1);
    }

    50% {
        transform: none;
        animation-timing-function: cubic-bezier(0, 0, 0.2, 1);
    }
}

.animate-bounce {
    animation: bounce 1s infinite;
}


@media (max-width: 768px) {

    .our_work {

        .left_plane {
            left: -88px;
        }

        .right_plane {
            right: -88px;
        }
    }

}
</style>