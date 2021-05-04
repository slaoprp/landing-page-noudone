<template>
    <div>
      <div class="app-showcase-step-wrap" style="padding-top: 100px;">
        <div class="section-title text-center section-space--mb_60">
            <h2 class="font-weight--light mb-15 wow move-up">Developed for Higher Business Growth</h2>
            <span class="section-text wow move-up">Offer your business with the best assistance for growth.</span>
        </div>
        <!-- <ThreeStepProcess /> -->
        <!-- App Showcase Process Step component -->
        <AppShowcaseProcessStep />
      </div>
    </div>
</template>

<script>
    import ChartCircleTwo from '../components/ChartCircleTwo'
    import ThreeStepProcess from '../components/ThreeStepProcess'
    import AppShowcaseProcessStep from '../components/AppShowcaseProcessStep'
    export default{
        name: 'ThreeStepProcessWrap',
        components: {
            ChartCircleTwo,
            ThreeStepProcess,
            AppShowcaseProcessStep
        }
    };
</script>

<style lang="scss">

</style>