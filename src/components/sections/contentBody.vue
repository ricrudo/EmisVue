<script setup>
  import ContentBlockVideo from '@/components/sections/contentBlockVideo.vue'
  import ContentBlockCursos from '@/components/sections/contentBlockCursos.vue'
  import ContentBlockMetodologia from '@/components/sections/contentBlockMetodologia.vue'
  import ContentBlockClases from '@/components/sections/contentBlockClases.vue'
  import ContentBlockEquipo from '@/components/sections/contentBlockEquipo.vue'
  import ContentBlockTestimonios from '@/components/sections/contentBlockTestimonios.vue'
  import ContentBlockContacto from '@/components/sections/contentBlockContacto.vue'
  import ContentBlockRecursos from '@/components/sections/contentBlockRecursos.vue'
  import ContentBlockInspiration from '@/components/sections/contentBlockInspiration.vue'
  import ContentBlockLogin from '@/components/sections/contentBlockLogin.vue'
  /*

  function changeLabel(state){
  if( state == 1 )
    jQuery("#togglePlay i").removeClass("fa-play").addClass("fa-pause");
    else
    jQuery("#togglePlay i").removeClass("fa-pause").addClass("fa-play");

    }

    function toggleVolume(){
    var volume =jQuery('#onetone-youtube-video').YTPToggleVolume();
    if( volume == true )
    jQuery(".youtube-volume i").removeClass("fa-volume-off").addClass("fa-volume-up");
    else
    jQuery(".youtube-volume i").removeClass("fa-volume-up").addClass("fa-volume-off");
  }
   */
</script>

<template>
  <div class="post-wrap" style="min-height: 391.2px;">
    <div class="container-fullwidth">
      <div class="page-inner row no-aside" style="padding-top: 0; padding-bottom: 0;">
        <div class="col-main">
          <section class="post-main" role="main" id="content">
            <article class="page type-page homepage" role="article">
              <ContentBlockVideo/>
              <ContentBlockCursos/>
              <ContentBlockMetodologia/>
              <ContentBlockClases/>
              <ContentBlockEquipo/>
              <ContentBlockTestimonios/>
              <ContentBlockContacto/>
              <ContentBlockRecursos/>
              <ContentBlockInspiration/>
              <ContentBlockLogin/>
              <div class="clear"></div>
            </article>
          </section>
        </div>
      </div>
    </div>
  </div>
</template>

<style scoped>
</style>

