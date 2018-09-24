<template>
  <div class="wrapper">
      <div class="search">
          <Claim />
          <SearchInput />
      </div>
    </div>
</template>

<script>
import axios from 'axios';
import debounce from 'lodash.debounce';
import Claim from '@/components/Claim.vue';
import SearchInput from '@/components/SearchInput.vue';

const API = 'https://images-api.nasa.gov/search';

export default {
  name: 'Search',
  components: { 
      Claim,
      SearchInput, 
    },
  data() {
      return {
          searchValue: '',
          results: [],
      }
  },
  methods: {
      
  },
  
};
</script>

<style lang="scss" scoped>

    .wrapper {
        display: flex;
        flex-direction: column;
        justify-content: center;
        align-items: center;
        margin: 0;
        padding: 30px;
        width: 100%;
        height: 100vh;
        background-image: url('../assets/heroimage.jpg');
        background-repeat: no-repeat;
        background-size: cover;
        background-position: 80% 0%;
        color: white;
    }

</style>

