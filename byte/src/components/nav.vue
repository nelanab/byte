<template>
    <div class="h-full pt-3 pb-3">
        <ul class="nav border-2 border-l-0 border-white pt-6 pb-6 pl-6 rounded-r-2xl text-xl">
            <li class="flex text-4xl font-black items-center mb-10">byte</li>
            <li class="flex font-bold items-center mb-10">
                <div class="border-white border-2 p-4 w-5/6 flex items-center rounded-2xl">
                    <i class="fas fa-search mr-4"></i>
                    <h2 class="font-bold">search</h2>
                </div>
            </li>
            <li class="flex font-bold items-center mb-10 ml-6">
                <i class="far fa-user mr-6"></i>
                <h2>profile</h2> 
            </li>
            <li class="flex font-bold items-center mb-10 ml-6">
                <i class="fas fa-home mr-6"></i>
                <h2>home</h2>    
            </li>
            <li class="flex font-bold items-center mb-10 ml-6">
                <i class="far fa-bookmark mr-6"></i>
                <h2>bookmarks</h2>    
            </li>
            <li class="flex font-bold items-center mb-10 ml-6">
                <i class="far fa-comment-alt mr-6"></i>
                <h2>messages</h2>    
            </li>
            <li class="flex font-bold items-center ml-6">
                <i class="fas fa-cog mr-6"></i>
                <h2>settings</h2>    
            </li>
            <li class="flex font-bold items-center absolute ml-6 mt-auto bottom-0 mb-10">
                <h2>Logout</h2>    
            </li>
        </ul>
    </div>
</template>
<script>
</script>
<style scoped>
    .nav{
        height: 100%;
    }
</style>