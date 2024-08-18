<template>
  <div class="bg-black overflow-y-scroll snap-y snap-mandatory h-screen">
    <section class="snap-end md:grid md:grid-cols-6 gap-6 flex flex-row h-screen w-full">
      <div class="desktop-cover hidden md:block md:col-span-2 h-full bg-cover"></div>
      <div class="mobile-cover page flex flex-col justify-end md:col-span-3">
        <div class="pads-container p-6 flex-col flex gap-4 pb-12">
          <div class="expose">Expose</div>
          <div class="exporteer-operating-system-enterprise">
            Exporteer Operating System Enterprise
          </div>
          <div class="frame-1">
            <div class="_78-of-150-left">78 of 150 left</div>
          </div>
          <div class="indicator">
            <div class="load"></div>
          </div>
          <button class="button be-an-early-adopter hover:opacity-90 duration-300" @click="register">
            Be an Early Adopter
          </button>
          <!-- <div class="flex items-center justify-center">
            <ArrowDown color="white" class="animate-bounce" />
          </div> -->
        </div>
      </div>
    </section>
  </div>
</template>
<style scoped>

/* Apply styles only to screens wider than 768px */
@media only screen and (max-width: 768px) {
  .mobile-cover {
    background-size: cover;
    background-repeat: no-repeat;
    background-position: center;
    background-image: url(/cover.jpg)
  }
}

.pads-container {
  background: linear-gradient(0deg, #000000 7%, rgba(0,0,0,0));
}

.desktop-cover {
  background-size: cover;
  background-repeat: no-repeat;
  background-position: center;
  background-image: url(/cover.jpg)
}

.expose {
  color: #ffffff;
  text-align: left;
  font-family: "Changa", sans-serif;
  font-size: 48px;
  line-height: 60px;
  font-weight: 700;
  position: relative;
}

.exporteer-operating-system-enterprise {
  color: #ffffff;
  text-align: left;
  font-family: "Changa", sans-serif;
  font-size: 28px;
  line-height: 37px;
  font-weight: 700;
  position: relative;
  align-self: stretch;
}

.frame-1 {
  display: flex;
  flex-direction: row;
  gap: 10px;
  align-items: center;
  justify-content: flex-end;
  align-self: stretch;
  flex-shrink: 0;
  position: relative;
}

._78-of-150-left {
  color: #ffffff;
  text-align: left;
  font-family: "Roboto-Bold", sans-serif;
  font-size: 16px;
  font-weight: 700;
  position: relative;
}

.indicator {
  background: rgba(160, 160, 160, 0.8);
  display: flex;
  flex-direction: column;
  gap: 10px;
  align-items: flex-start;
  justify-content: flex-start;
  align-self: stretch;
  flex-shrink: 0;
  position: relative;
  overflow: hidden;
}

.load {
  background: #ffffff;
  flex-shrink: 0;
  width: 288.8px;
  height: 8px;
  position: relative;
}

.button {
  background: #0066cc;
  padding: 8px 16px 8px 16px;
  display: flex;
  flex-direction: row;
  gap: 10px;
  align-items: center;
  justify-content: center;
  align-self: stretch;
  flex-shrink: 0;
  position: relative;
}

.be-an-early-adopter {
  color: #ffffff;
  text-align: left;
  font-family: "Exo 2", sans-serif;
  font-size: 20px;
  font-weight: 700;
  position: relative;
}

.ic-baseline-keyboard-double-arrow-down-1 {
  display: flex;
  flex-direction: column;
  gap: 0px;
  align-items: center;
  justify-content: center;
  align-self: stretch;
  flex-shrink: 0;
  height: auto;
  position: relative;
  overflow: visible;
}

.button:focus {
  animation: pulse 1s;
  box-shadow: 0 0 0 0 rgba(88, 120, 243, 0.4);
}

@keyframes pulse {
  0% {
    box-shadow: 0 0 0 0 rgba(88, 120, 243, 1);
  }

  70% {
    box-shadow: 0 0 0 10px rgba(88, 120, 243, 0);
  }

  100% {
    box-shadow: 0 0 0 50px rgba(88, 120, 243, 0);
  }
}
</style>


<script setup>

const register = () => {
  window.location.href = "https://whatsform.com/hhF8Mx"
};
</script>

<style scoped>
/* Tailwind handles most of the styling. No additional styles needed here. */
</style>