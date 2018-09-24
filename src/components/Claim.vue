<template>
<div class="claim-wrapper">
    <h1 class="claim">SPACER</h1>
    <p class="sub-claim">
        Begin your journey through our amazing galaxy,
        and discover places you have never even heard of.
    </p>
    <p class="sub-claim">Type anything space-related to start.</p>
</div>
</template>
<script>
export default {
    name: 'Claim',    
}
</script>

<style lang="scss" scoped>
    .claim-wrapper {
        display: flex;
        text-align: center;
        flex-direction: column;
        justify-content: center;
        align-items: center;
    }

    .claim {
        font-size: 50px;
        margin:0;
    }
    .sub-claim {
        font-size: 13px;
        margin: 20px 0 0 0;
    }
</style>

