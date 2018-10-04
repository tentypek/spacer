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
        color: white;
    }

    .claim {
        font-size: 50px;
        margin:0;

        @media (min-width: 768px) {
            font-size: 80px;
        }
    }
    .sub-claim {
        font-size: 13px;
        margin: 20px 0 0 0;
        font-weight: 400;
        
        @media (min-width: 768px) {
            font-size: 17px;
            letter-spacing: 1px;
            line-height: 1;
            width: 500px;
        }

    }
</style>

