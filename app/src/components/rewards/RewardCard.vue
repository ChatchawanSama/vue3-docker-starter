<template>
    <div class="p-4 mt-8 bg-blue-200">
    (Preview)
        <div class="block p-2 mt-4 border-2 border-blue-700 rounded">
            <h3 class="text-xl">{{ reward.name }}</h3>
            <p>{{ reward.point }}</p>
            <span>Detail</span>
            <button class="p-2 bg-blue-200 border-2 border-blue-400 rounded-xl">
            Redeem
            </button>
        </div>
    </div>
</template>

<script>
    export default{
        props: ['reward'],
    }
</script>