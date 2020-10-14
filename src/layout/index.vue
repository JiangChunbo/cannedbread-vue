<template>
    <div class="layout">
        <app-main></app-main>
        <navbar></navbar>
    </div>
</template>

<script>
import { Navbar, AppMain } from "./components";
export default {
    components: {
        Navbar,
        AppMain,
    },

    mounted() {
        this.$nextTick(() => {
            let items = document.querySelectorAll(".navbar-menu-item");
            for (let i = 0; i < items.length; ++i) {
                let item = items[i];
                item.addEventListener("click", function () {
                    let container = document.querySelector(".app-main");
                    container.style.transform = "translateX(-" + 20 * i + "%)";
                });
            }
        });
    },
};
</script>

<style>
.layout {
    height: 100%;
    width: 100%;
}

.layout a:nth-child(1):hover .app-main {
    transform: translateX(0);
}

.layout a:nth-child(2):hover .app-main {
    transform: translateX(-100%);
}

.layout a:nth-child(3):hover .app-main {
    transform: translateX(-200%);
}

.layout a:nth-child(1):hover .app-main {
    transform: translateX(-300%);
}

.layout a:nth-child(4):hover .app-main {
    transform: translateX(-400%);
}

.layout a:nth-child(5):hover .app-main {
    transform: translateX(-500%);
}
</style>