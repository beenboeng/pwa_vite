<script setup lang="ts"></script>

<template>
  <div>
    <div>
      <div class="header-roulette__popup flex w-full justify-center">
        <div class="label-item">
          <div class="header-roulette__dropdown-language action flex">
            <p class="paragrap">Language</p>
            <div class="header-roulette__popup-language">
              <a-select
                :allow-clear="false"
                class="dropdown ml-5 w-80"
                alowClear="false"
                placeholder="English"
              >
                <a-select-option :value="1">
                  <div class="header-roulette__dropdown-language">
                    <span>English</span>
                  </div>
                </a-select-option>
                <a-select-option :value="2">
                  <div class="header-roulette__dropdown-language">
                    <span>Khmer</span>
                  </div>
                </a-select-option>
              </a-select>
            </div>
          </div>
          <div
            class="header-roulette__popup-music action flex"
           
          >
            <p class="paragrap">Music</p>
            <div class="header-roulette__music-slider">
              <div class="header-roulette__popup-language">
                <a-select
                  :allow-clear="false"
                  class="dropdown w-80"
                  alowClear="false"
                  placeholder="Last Christmas"
                >
                  <a-select-option :value="1">
                    <div class="header-roulette__dropdown-language">
                      <span>Last Christmas</span>
                    </div>
                  </a-select-option>
                  <a-select-option :value="2">
                    <div class="header-roulette__dropdown-language">
                      <span>Khmer</span>
                    </div>
                  </a-select-option>
                  <a-select-option :value="3">
                    <div class="header-roulette__dropdown-language">
                      <span>Khmer</span>
                    </div>
                  </a-select-option>
                  <a-select-option :value="4">
                    <div class="header-roulette__dropdown-language">
                      <span>Khmer</span>
                    </div>
                  </a-select-option>
                </a-select>
              </div>
              <div class="slider">
                <a-slider :disabled="false" />
              </div>
            </div>
          </div>
          <div
            class="header-roulette__popup-volume action flex"
            
          >
            <p class="paragrap">Volume</p>
            <div class="header-roulette__volume-slider">
              <div class="slider">
                <a-slider  :disabled="false" />
              </div>
            </div>
          </div>
          <div
            class="header-roulette__popup-voice action flex"
           
          >
            <p class="paragrap">Voice</p>
            <div class="header-roulette__voice-slider">
              <div class="slider">
                <a-slider :disabled="false" />
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<style scoped>
.img {
  height: 200px;
  margin-top: 20px;
}
.logo:hover {
  filter: drop-shadow(0 0 2em #646cffaa);
}
.logo.vue:hover {
  filter: drop-shadow(0 0 2em #42b883aa);
}
</style>
