<template>
<div class="main animate">
    <div class="title">
        <div class="name">Negar</div>
        <div class="last_name">
            Jamalifard
            <span class="points js_scale" data-size="130 × 34">
        <span class="point_top_right"></span>
        <span class="point_top_left"></span>
        <span class="point_bottom_right"></span>
        <span class="point_bottom_left"></span>
      </span>
        </div>
    </div>

    <y-socials/>
</div>
</template>

<script>
    import YSocials from '@/components/scale/Socials';

    export default {
        name: 'index',

        components: {
            YSocials,
        }
    };
</script>
