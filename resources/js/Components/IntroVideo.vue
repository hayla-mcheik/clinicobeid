<template>

    <!-- Intro Video Section Start -->
    <div class="intro-video bg-section">
        <div class="container-fluid">
            <div class="row no-gutters">
                <div class="col-lg-12">
                    <!-- Intro Video Box Start -->
                    <div class="intro-video-box">
                        <div class="intro-bg-video">
                            <!-- Selfhosted Video Start -->
                            <!-- <video autoplay muted loop id="introVideo"><source src="images/restraint-video.mp4" type="video/mp4"></video> -->
                            <video autoplay="" muted="" loop="" id="introVideo"><source src="/assets/videos/glowix-video.mp4" type="video/mp4"></video>
                            <!-- Selfhosted Video End -->

                            <!-- Youtube Video Start -->
                            <!-- <div id="introvideo" class="player" data-property="{videoURL:'74DWwSxsVSs',containment:'.hero-video', showControls:false, autoPlay:true, loop:true, vol:0, mute:false, startAt:0,  stopAt:296, opacity:1, addRaster:true, quality:'large', optimizeDisplay:true}"></div> -->
                            <!-- Youtube Video End -->
                        </div>
                        <!-- Video Play Button Start -->

                        <!-- Video Play Button Start -->
                        <div class="video-play-button">
                            <Link href="https://www.youtube.com/watch?v=Y-x0efG1seA" class="popup-video" data-cursor-text="Play">Play</Link> 
                        </div>
                        <!-- Video Play Button End -->
                    </div>
                    <!-- Intro Video Box End -->
                </div>
            </div>
        </div>
    </div>
    <!-- Intro Video Section End -->
  </template>
  
  <script setup>
  import { onMounted } from 'vue';
  import { initCarousels } from 'flowbite';
import { Link } from '@inertiajs/vue3';
  
  onMounted(() => {
    initCarousels();
  });
  </script>
  
