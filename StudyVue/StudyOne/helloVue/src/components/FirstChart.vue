<template>
    <div>
        <apexchart width="500" type="bar" :options="chartOptions" :series="series"></apexchart>
    </div>
</template>

<script lang="ts">
export default {
    name: "alarmCalcul",
    computed: {},
    methods: {},
    data() {
        return {
            chartOptions: {
                xaxis: {
                    categories: [1, 2, 3, 4, 5, 6, 7, 8, 9, 10, 11, 12],
                },
            },
            series: [
                {
                    name: "series-1",
                    data: [10, 20, 30, 40, 50, 10, 20, 30, 40, 50, 60, 80],
                },
            ],
        };
    },
};
</script>

<style scoped>

</style>
