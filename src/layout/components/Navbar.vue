<template>
    <div class="navbar">
        <ul>
            <li>
                <a href="#" class="navbar-menu-item" data-text="Home"
                    >原创项目 <span /><span /><span /> <span /><span /><span
                /></a>
            </li>
            <li>
                <a href="#" class="navbar-menu-item" data-text="About"
                    >非原创项目<span /><span /><span /><span /><span /><span
                /></a>
            </li>
            <li>
                <a href="#" class="navbar-menu-item" data-text="Services"
                    >博客文章类 <span /><span /><span /><span /><span /><span
                /></a>
            </li>
            <li>
                <a href="#" class="navbar-menu-item" data-text="Menu"
                    >网站简介<span /><span /><span /><span /><span /><span
                /></a>
            </li>
            <li>
                <a href="#" class="navbar-menu-item" data-text="Contact Us"
                    >留言<span /><span /><span /><span /><span /><span
                /></a>
            </li>
        </ul>
        <div class="search-box">
            <input
                class="search-txt"
                type="text"
                placeholder="Type to search"
            />
            <a class="search-btn"><i class="fas fa-search"></i></a>
        </div>
    </div>
</template>

<script>
export default {};
</script>

<style lang="scss" scoped>
@import '~@/styles/navbar/navbar.scss';

</style>