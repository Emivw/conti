<template>
    <div>
        <header>
            <nav>
                <ul class="flex gap-2">
                    <li class="inline-flex items-center px-3 py-2 text-sm font-medium text-center text-white bg-blue-700 rounded-lg hover:bg-blue-800 focus:ring-4 focus:outline-none focus:ring-blue-300 dark:bg-blue-600 dark:hover:bg-blue-700 dark:focus:ring-blue-800">
                        <NuxtLink to="/">Home</NuxtLink>
                    </li>
                    <li class="inline-flex items-center px-3 py-2 text-sm font-medium text-center text-white bg-blue-700 rounded-lg hover:bg-blue-800 focus:ring-4 focus:outline-none focus:ring-blue-300 dark:bg-blue-600 dark:hover:bg-blue-700 dark:focus:ring-blue-800">
                        <NuxtLink to="/features">Feature</NuxtLink>
                    </li>
                    <li class="inline-flex items-center px-3 py-2 text-sm font-medium text-center text-white bg-blue-700 rounded-lg hover:bg-blue-800 focus:ring-4 focus:outline-none focus:ring-blue-300 dark:bg-blue-600 dark:hover:bg-blue-700 dark:focus:ring-blue-800">
                        <NuxtLink to="/series">Series</NuxtLink>
                    </li>
                </ul>
            </nav>
        </header>
        <div>
            <slot/>
        </div>
        
    </div>
</template>
<script>

</script>
<style  scoped>
.router-link-exact-active{
color: aquamarine;
}
</style>