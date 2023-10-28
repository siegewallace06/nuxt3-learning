<script setup>
// Function to show alert when opening the page
const showAlert = () => {
    alert('Welcome to my page!');
}
showAlert();
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