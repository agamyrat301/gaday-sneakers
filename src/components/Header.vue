<template>
    <header class="flex justify-between border-b border-slate-300 px-10 py-8">
        <div class="flex items-center gap-5">
            <img src="/logo.png" class="w-10" alt="logo">
            <div>
                <h2 class="uppercase font-bold text-2xl">vue sneakers</h2>
                <p class="text-slate-500">sneakers shop in Bucharest</p>

            </div>
        </div>


        <ul class="flex items-center gap-10">

            <li class="flex items-center gap-3 text-gray-500 hover:text-black cursor-pointer">
                <img src="/cart.svg" alt="Cart">
                <b>122 USD</b>
            </li>

            <li class="flex items-center gap-3 text-gray-500 hover:text-black cursor-pointer">
                <img src="/heart.svg" alt="Favorites">
                <b>Favorites</b>
            </li>

            <li class="flex items-center gap-3 text-gray-500 hover:text-black cursor-pointer">
                <img src="/profile.svg" alt="profile">
                <b>profile</b>
            </li>

        </ul>
    </header>

</template>