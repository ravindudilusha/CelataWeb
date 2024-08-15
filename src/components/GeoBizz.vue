<template>
    <v-container fluid class="mt-6 GeoBizz-Background">
        <div class="Heading-Container">
            <p class="Heading-title">GeoBizz</p>
            <div class="subtitle-container">
                <p class="subtitle">Geographical based intelligence platform</p>
            </div>
        </div>
        <v-container class="GeoBizz-content">
            <v-row>
                <v-col cols="6">
                    <p class="herosection-description">
                        GeoBizz is a cloud-based location intelligence and mobile engagement platform developed by
                        Celata Tech. The data collected via GeoBizz APIs is synced with Google Maps on top of the
                        GeoBizz platform and provide geospatial statistical analysis allowing businesses to evaluate the
                        geographical patterns and trends that they are looking for in order to make more informed
                        business decisions. With Celata's GeoBizz platform, any business can ensure that the right
                        information reaches the right person at the right time, allowing them to make the best possible
                        data-driven decision.
                    </p>
                </v-col>
            </v-row>
        </v-container>
    </v-container>
</template>

<style scoped>
.GeoBizz-Background {
    height: auto;
    width: 100%;
    background-color: #01609E;
}

.Heading-Container {
    display: flex;
    flex-direction: column;
    align-items: center;
    height: 100%;
}

.Heading-title {
    color: white;
    text-align: center;
    font-size: 35px;
    font-weight: 600;
}

.subtitle-container {
    background-color: white;
    padding: 6px;
    border-radius: 10px;
    display: flex;
    align-items: center;
    margin-top: 10px;
}

.subtitle {
    font-size: 14px;
    color: #01609E;
}
</style>
