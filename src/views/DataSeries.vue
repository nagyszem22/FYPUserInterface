<template>
  <d-container fluid class="main-content-container px-4">

    <!-- Page Header -->
    <d-row no-gutters class="page-header py-4">
      <!-- Page Title -->
      <d-col col sm="4" class="text-center text-sm-left mb-4 mb-sm-0">
        <span class="text-uppercase page-subtitle">Create your own chart</span>
        <h3 class="page-title">Data Series</h3>
      </d-col>
    </d-row>

    <!-- Page Body -->
    <d-row>
      <!-- Data Series -->
      <d-col lg="9" md="12" sm="12" class="mb-4">
        <data-series />
      </d-col>

      <!-- Top Referrals -->
      <d-col lg="3" md="12" sm="12" class="mb-4">
        <bo-top-referrals />
      </d-col>
    </d-row>

  </d-container>
</template>

<script>
import TopReferrals from '@/components/common/TopReferrals.vue';
import DataSeries from '@/components/chart-wrappers/DataSeries.vue';

export default {
  components: {
    boTopReferrals: TopReferrals,
    DataSeries: DataSeries
  }
};
</script>

