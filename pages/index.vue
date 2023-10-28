<script setup>
const { sayHello } = useUtils();
sayHello();
</script>

<template>
    <div class="Main">
        <Alert />
        <ProfileHeader />

        <Profile />
        <!-- <img src="@/assets/img/gauge-17.jpg" alt=""> -->
        <IconsHome />
        <img src="/poster.jpg" alt="">
    </div>
</template>