<template>
  <div class="flex px-7">
    <div class="intro-content flex-1">
      <div class="intro-content-wel">
        <span class="intro-content-wel-text flex items-center">
          Welcome
        </span>
      </div>
      <h1 class="intro-content-title">
        I’m Dianna Adams
      </h1>
      <h3 class="intro-content-des">
        Food Critic / Influencer / Blogger
      </h3>
      <div class="intro-content-text">
        Massa urna magnis dignissim id euismod porttitor vitae etiam viverra nunc at adipiscing sit morbi aliquet mauris porttitor nisi, senectus pharetra, ac porttitor orci.
      </div>
      <div class="intro-content-jion" @click="add">
        <NuxtLink>Join Insider</NuxtLink>
      </div>
      <div class="intro-content-count flex flex-1">
        <div class="flex-1">
          <div class="img" />
          <div class="count-text">
            1.2M+
          </div>
          <div class="count-des">
            Subscribers
          </div>
        </div>
        <div>
          <div class="img" />
          <div class="count-text">
            1.2M+
          </div>
          <div class="count-des">
            Subscribers
          </div>
        </div>
        <div>
          <div class="img" />
          <h3 class="count-text">
            1.2M+
          </h3>
          <div class="count-des">
            Subscribers
          </div>
        </div>
      </div>
    </div>
    <div class="intro-image flex-1">
      11
    </div>
  </div>
  <section>
    <div class="flex" />
  </section>
</template>
<script setup lang="ts">
</script>
<style lang="scss" scoped>
    .intro-content {
        font-family: 'Montserrat',sans-serif;
        &-wel {
            &-text {
                color: var(--e-global-color-astglobalcolor0);
                font-size: 12px;
                font-weight: 600;
                text-transform: uppercase;
                line-height: 1.3em;
                letter-spacing: 2px;
                position: relative;
                margin-left: 16px;
                margin-top: 18px;

                &::before {
                    display: block;
                    content: "";
                    border-bottom: 0;
                    width: 35px;
                    position: absolute;
                    left: -40px;
                    border-top: var(--divider-border-width) var(--divider-border-style) var(--divider-color);
                }
            }
        }
        &-title {
            font-size: 48px;
            font-weight: 600;
            margin-bottom: 20px;
        }
        &-des {
            font-family: 'Fraunces',serif;
            margin-bottom: 20px;
        }
        &-text {
            color: #bdc1c4;
            margin-bottom: 20px;
        }
        &-jion {
            border-color: var(--ast-global-color-0);
            background-color: rgba(191,125,105,0);
            border-style: solid;
            text-decoration: none;
            border-top-width: 1px;
            border-right-width: 1px;
            border-left-width: 1px;
            border-bottom-width: 1px;
            width: 147px;
            height: 52px;
            display: flex;
            justify-content: center;
            align-items: center;
            a {
                color: var(--ast-global-color-0);
            }
            &:hover {
                background-color: var(--ast-global-color-0);
                a {
                    color: #fff;
            }
            }
        }
        &-count {
            width: 156px;
            .count-text {
            }
            .count-des {
                color: #7A7A7A;
            }
        }
    }
</style>
