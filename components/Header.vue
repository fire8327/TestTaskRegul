<template>
    <header class="flex flex-col text-[#0F0F0F]">
        <div class="grid-container w-full bg-[#FFF7EB]">
            <div class="flex items-center justify-between py-2 w-full">
                <div class="flex items-center gap-3">
                    <img src="/images/header/logo.png" alt="">
                    <button class="flex items-center gap-1 rounded-full bg-[#E8E8E8] py-4 px-5">
                        <img src="/images/header/button.png" alt="">
                        <span class="font-medium">Все категории</span>
                    </button>
                </div>
                <div class="flex items-center gap-6">
                    <button class="flex items-center gap-1 py-2 px-1.5">
                        <img src="/images/header/address.png" alt="">
                        <span>Ростов-на-Дону</span>
                    </button>
                    <div class="w-px h-8 bg-[#CCCCCC]"></div>
                    <NuxtLink to="/" class="text-[#337566] font-medium py-2 px-3">Разместить объявление</NuxtLink>
                    <button class="flex items-center gap-2 rounded-full bg-[#E8E8E8] p-1">                    
                        <img src="/images/header/menu.png" alt="">
                        <img src="/images/header/profile.png" alt="">
                    </button>
                </div>
            </div>
        </div>
        <div class="flex flex-col items-center text-center w-full border-b border-[#CCCCCC] pb-8 gap-6">
            <img src="/images/header/avatar.png" alt="" class="w-[120px]">
            <div class="flex flex-col gap-3">
                <p class="font-semibold text-2xl">Наследие</p>
                <div class="flex items-center gap-1">
                    <img src="/images/header/premium.png" alt="">
                    <p>Документы проверены</p>
                    <p>•</p>
                    <img src="/images/header/star.png" alt="">
                    <p>•</p>
                    <p>19 отзывов</p>
                </div>
                <button class="bg-[#337566] rounded-[12px] py-4 px-5 text-white font-medium">Показать номер телефона</button>
                <div class="flex items-center gap-2 font-medium mt-2">
                    <NuxtLink to="/" class="bg-[#E8E8E8] rounded-[12px] py-2 px-3">Товары и услуги</NuxtLink>
                    <NuxtLink to="/" class="bg-[#E8E8E8] rounded-[12px] py-2 px-3 flex items-center gap-1">
                        <span>Агенты</span>
                        <span class="text-[#6B6B6B]">5</span>
                    </NuxtLink>
                    <NuxtLink to="/" class="bg-[#E8E8E8] rounded-[12px] py-2 px-3">О компании</NuxtLink>
                </div>
            </div>
        </div>
    </header>
</template>

<script setup>

</script>