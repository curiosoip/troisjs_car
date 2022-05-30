<template>
  <div class="bg-white w-full h-screen">
    <div
      class="z-10 w-full  flex flex-col justify-center lg:flex-row  lg:justify-between  align-middle items-center absolute  ">
      <div>
        <img class="rounded-sm mt-10 lg:ml-5" width="150" height="150" src="src/assets/martin_logo.png" alt="" />
      </div>

      <div class="inline-flex mt-10 rounded-md shadow-sm lg:mr-5" role="group">
        <button type="button"
          class="inline-flex items-center  py-2 px-4 text-sm font-medium text-white bg-transparent rounded-l-lg border border-gray-500 hover:bg-green-700 hover:text-white focus:z-10  focus:bg-green-700 focus:text-white ">
          <svg class="w-4 h-4 mr-1" fill="currentColor" viewBox="0 0 20 20" xmlns="http://www.w3.org/2000/svg">
            <path fill-rule="evenodd"
              d="M4 4a2 2 0 012-2h8a2 2 0 012 2v12a1 1 0 110 2h-3a1 1 0 01-1-1v-2a1 1 0 00-1-1H9a1 1 0 00-1 1v2a1 1 0 01-1 1H4a1 1 0 110-2V4zm3 1h2v2H7V5zm2 4H7v2h2V9zm2-4h2v2h-2V5zm2 4h-2v2h2V9z"
              clip-rule="evenodd"></path>
          </svg>
          Motor
        </button>
        <button type="button"
          class="inline-flex items-center py-2 px-4 text-sm font-medium text-white bg-transparent border-t border-b border-gray-500 hover:bg-green-700 hover:text-white focus:z-10   focus:bg-green-700 focus:text-white ">
          <svg class="w-4 h-4 mr-1" fill="currentColor" viewBox="0 0 20 20" xmlns="http://www.w3.org/2000/svg">
            <path
              d="M5 3a2 2 0 00-2 2v2a2 2 0 002 2h2a2 2 0 002-2V5a2 2 0 00-2-2H5zM5 11a2 2 0 00-2 2v2a2 2 0 002 2h2a2 2 0 002-2v-2a2 2 0 00-2-2H5zM11 5a2 2 0 012-2h2a2 2 0 012 2v2a2 2 0 01-2 2h-2a2 2 0 01-2-2V5zM11 13a2 2 0 012-2h2a2 2 0 012 2v2a2 2 0 01-2 2h-2a2 2 0 01-2-2v-2z">
            </path>
          </svg>
          Llantas
        </button>
        <button type="button"
          class="inline-flex items-center py-2 px-4 text-sm font-medium text-white bg-transparent rounded-r-md border border-gray-500 hover:bg-green-700 hover:text-white focus:z-10 focus:bg-green-700 focus:text-white ">
          <svg class="w-6 h-6 mr-1" fill="currentColor" viewBox="0 0 20 20" xmlns="http://www.w3.org/2000/svg">
            <path d="M4 4a2 2 0 00-2 2v1h16V6a2 2 0 00-2-2H4z"></path>
            <path fill-rule="evenodd"
              d="M18 9H2v5a2 2 0 002 2h12a2 2 0 002-2V9zM4 13a1 1 0 011-1h1a1 1 0 110 2H5a1 1 0 01-1-1zm5-1a1 1 0 100 2h1a1 1 0 100-2H9z"
              clip-rule="evenodd"></path>
          </svg>
          Reservar
        </button>
      </div>
      <div class="text-white lg:mr-5 p-4 lg:p-0">MODELO</div>

    </div>
    <div
      class="z-10 w-full  flex flex-col  justify-center bottom-10 lg:justify-between lg:flex-row align-middle items-center absolute  ">
      <div class="inline-flex mt-10 mb-5 lg:mb-0 rounded-md shadow-sm lg:ml-5" role="group">
        <button type="button"
          class="inline-flex items-center  py-2 px-4 text-sm font-medium text-white bg-transparent rounded-l-lg border border-gray-500 hover:bg-green-700 hover:text-white focus:z-10  focus:bg-green-700 focus:text-white ">
          <svg class="w-4 h-4 mr-1" fill="currentColor" viewBox="0 0 20 20" xmlns="http://www.w3.org/2000/svg">
            <path fill-rule="evenodd"
              d="M4 4a2 2 0 012-2h8a2 2 0 012 2v12a1 1 0 110 2h-3a1 1 0 01-1-1v-2a1 1 0 00-1-1H9a1 1 0 00-1 1v2a1 1 0 01-1 1H4a1 1 0 110-2V4zm3 1h2v2H7V5zm2 4H7v2h2V9zm2-4h2v2h-2V5zm2 4h-2v2h2V9z"
              clip-rule="evenodd"></path>
          </svg>
          Motor
        </button>
        <button type="button"
          class="inline-flex items-center py-2 px-4 text-sm font-medium text-white bg-transparent border-t border-b border-gray-500 hover:bg-green-700 hover:text-white focus:z-10   focus:bg-green-700 focus:text-white ">
          <svg class="w-4 h-4 mr-1" fill="currentColor" viewBox="0 0 20 20" xmlns="http://www.w3.org/2000/svg">
            <path
              d="M5 3a2 2 0 00-2 2v2a2 2 0 002 2h2a2 2 0 002-2V5a2 2 0 00-2-2H5zM5 11a2 2 0 00-2 2v2a2 2 0 002 2h2a2 2 0 002-2v-2a2 2 0 00-2-2H5zM11 5a2 2 0 012-2h2a2 2 0 012 2v2a2 2 0 01-2 2h-2a2 2 0 01-2-2V5zM11 13a2 2 0 012-2h2a2 2 0 012 2v2a2 2 0 01-2 2h-2a2 2 0 01-2-2v-2z">
            </path>
          </svg>
          Llantas
        </button>
        <button type="button"
          class="inline-flex items-center py-2 px-4 text-sm font-medium text-white bg-transparent rounded-r-md border border-gray-500 hover:bg-green-700 hover:text-white focus:z-10 focus:bg-green-700 focus:text-white ">
          <svg class="w-6 h-6 mr-1" fill="currentColor" viewBox="0 0 20 20" xmlns="http://www.w3.org/2000/svg">
            <path d="M4 4a2 2 0 00-2 2v1h16V6a2 2 0 00-2-2H4z"></path>
            <path fill-rule="evenodd"
              d="M18 9H2v5a2 2 0 002 2h12a2 2 0 002-2V9zM4 13a1 1 0 011-1h1a1 1 0 110 2H5a1 1 0 01-1-1zm5-1a1 1 0 100 2h1a1 1 0 100-2H9z"
              clip-rule="evenodd"></path>
          </svg>
          Reservar
        </button>
      </div>
      <div class="lg:mr-5">
        <button type="button"
          class="text-white  bg-gradient-to-br from-green-400 to-blue-600 hover:bg-gradient-to-bl focus:ring-4 focus:outline-none focus:ring-green-200 dark:focus:ring-green-800 font-medium rounded-lg text-xl px-5 py-2.5 text-center mr-2 mb-2">

          Realizar Pedido
        </button>
      </div>
    </div>
    <div class="z-10 w-full bottom-0  flex flex-col justify-center align-middle items-center absolute">
      <div class="p-4 text-white opacity-50  flex">by biidix</div>
    </div>

    <Renderer class="h-screen z-0 w-full  " ref="renderer" :alpha="true" resize antialias
      :orbit-ctrl="{ autoRotate: true, enabled: true, enableDamping: true, dampingFactor: 0.05, maxPolarAngle: Math.PI / 2, minDistance: 10, maxDistance: 15 }"
      pointer>
      <Camera :position="{ x: -10, y: 1, z: 8 }" />
      <Scene ref="scene">


        <SpotLight color="#111111" :intensity="10" :position="{ x: 0, y: 15, z: 0 }" :angle="100">

        </SpotLight>

        <DirectionalLight color="#ffffff" :intensity="2" :scale="{ x: 0.2, y: 0.2, z: 0.2 }"
          :position="{ x: -3, y: 0, z: 0 }" :cast-shadow="true">

        </DirectionalLight>

        <DirectionalLight color="#ffffff" :intensity="2" :scale="{ x: 0.2, y: 0.2, z: 0.2 }"
          :position="{ x: 3, y: 0, z: 0 }">

        </DirectionalLight>
        <DirectionalLight color="#ffffff" :intensity="2" :scale="{ x: 0.2, y: 0.2, z: 0.2 }"
          :position="{ x: 0, y: 0, z: -7 }" :cast-shadow="true">
        </DirectionalLight>

        <DirectionalLight color="#ffffff" :intensity="2" :scale="{ x: 0.2, y: 0.2, z: 0.2 }"
          :position="{ x: 0, y: 0, z: 4 }">
        </DirectionalLight>

        <Group :rotation="{ x: -Math.PI / 2, y: 0, z: 0 }">

          <Plane :width="30" :height="30" :rotation="{ x: 0 }" :position="{ z: -2 }">

            <StandardMaterial color="#111111" :props="{ displacementScale: 0, roughness: 0, metalness: 0 }">
              <!--<Texture :props="texturesProps" src="src/assets/bg9.jpg" :color="0x000000" />-->

            </StandardMaterial>
            <GltfModel src="src/assets/marti2.glb" @load="onReady" :rotation="{ x: 0, y: 0, z: 0 }"
              :scale="{ x: 2, y: 2, z: 2 }" />
          </Plane>
        </Group>
      </Scene>
      <EffectComposer>
        <RenderPass />
        <UnrealBloomPass :strength="0.7" />
        <FXAAPass />
      </EffectComposer>
    </Renderer>
  </div>
</template>

<script>
// textures from https://3dtextures.me/2019/04/26/wood-tiles-002/
import { RepeatWrapping } from 'three';
import {
  AmbientLight,
  HemisphereLight,
  Camera,
  EffectComposer,
  FXAAPass,
  Group,
  Renderer,
  Mesh,
  Plane,
  BoxGeometry,
  BasicMaterial,
  DirectionalLight,
  PointLight,
  SpotLight,
  GltfModel,
  HalftonePass,
  RectAreaLight,
  RenderPass,
  LambertMaterial,
  Scene,
  Sphere,
  StandardMaterial,
  Texture,
  UnrealBloomPass,
} from 'troisjs';
export default {
  components: {
    AmbientLight,
    Camera,
    HalftonePass,
    HemisphereLight,
    EffectComposer,
    FXAAPass,
    BasicMaterial,
    DirectionalLight,
    Group,
    Mesh,
    SpotLight,
    Renderer,
    BoxGeometry,
    LambertMaterial,
    Plane,
    PointLight,
    GltfModel,
    RectAreaLight,
    RenderPass,
    Scene,
    Sphere,
    StandardMaterial,
    Texture,
    UnrealBloomPass,
  },
  data() {
    return {
      texturesProps: {
        repeat: { x: 1, y: 1 },
        wrapS: RepeatWrapping,
        wrapT: RepeatWrapping,
      },
      rectLightsProps: {
        // rotation: { x: -Math.PI / 2 },
        lookAt: { x: 0, y: 0, z: 10 },
        intensity: 5,
        width: 15,
        height: 15,
        helper: true,
      },
    };
  },
  mounted() {
    const renderer = this.$refs.renderer;
    console.log(renderer.setClearColor);

    //const light = this.$refs.light.light;
    const scene = this.$refs.scene;
    const pointerV3 = renderer.three.pointer.positionV3;
    renderer.onBeforeRender(() => {

      //light.position.copy(pointerV3);
    });

  },
  methods: {
    onReady(model) {
      console.log(model);
    }
  }
};
</script>