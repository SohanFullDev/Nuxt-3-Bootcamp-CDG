<script setup>
    definePageMeta({
        layout: "custom"
    });

  const {makes} = useCars()  

</script>
<template>
    <div>
        <div class="mt-24">
            <h class="text-6xl">Creating a New Listing</h>
        </div>
        <div class="shadow rounded p-3 mt-5 flex flex-wrap justify-between">
            <CarAdSelect title="Make *" :options="makes" />
        </div>
    </div>
</template>