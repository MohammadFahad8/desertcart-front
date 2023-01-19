<script setup>
import { RouterLink, RouterView } from "vue-router";
import HelloWorld from "./components/HelloWorld.vue";
</script>

<template>
  <div class="dc-container">
    <div class="sticky-outer-wrapper" style="">
      <div class="sticky-inner-wrapper"
        style="position: relative; z-index: 1001; transform: translate3d(0px, 0px, 0px);">
        <div></div>
        <div class="Header">
          <div class="Menu"></div>
          <div class="Auth"></div>
          <div class="Header__inner">
            <div class="Header__left">
              <div class="jss6"><a href="/"><img class="Header__logoImg"
                    src="https://cdn.desertcart.com/static/media/logo.5821c90d.png" alt="desertcart"></a></div>
              <div class="jss8">
                <div class="Header__burger"><svg class="MuiSvgIcon-root" focusable="false" viewBox="0 0 24 24"
                    aria-hidden="true">
                    <path d="M3 18h18v-2H3v2zm0-5h18v-2H3v2zm0-7v2h18V6H3z"></path>
                  </svg></div>
              </div>
              <div class="jss6">
                <div>
                  <div class="Header__explore-cat null">
                    <div>
                      <div>Explore</div>
                    </div><svg class="MuiSvgIcon-root" focusable="false" viewBox="0 0 24 24" aria-hidden="true">
                      <path d="M7.41 8.59L12 13.17l4.59-4.58L18 10l-6 6-6-6 1.41-1.41z"></path>
                    </svg>
                  </div>
                </div>
              </div>
            </div>
            <div class="Header__search-container">
              <div class="Search__mobile__container">
                <div class="MuiAutocomplete-root" role="combobox" aria-expanded="false">
                  <div class="MuiFormControl-root MuiTextField-root Search__auto-input MuiFormControl-fullWidth">
                    <div
                      class="MuiInputBase-root MuiInput-root MuiInput-underline MuiAutocomplete-inputRoot MuiInputBase-fullWidth MuiInput-fullWidth MuiInputBase-formControl MuiInput-formControl MuiInputBase-adornedStart MuiInputBase-adornedEnd">
                      <div class="MuiInputAdornment-root MuiInputAdornment-positionStart">
                        <div class="MuiFormControl-root">
                          <div
                            class="MuiInputBase-root MuiInput-root MuiInput-underline MuiInputBase-formControl MuiInput-formControl">
                            <div
                              class="MuiSelect-root MuiSelect-select MuiSelect-selectMenu MuiInputBase-input MuiInput-input"
                              tabindex="0" role="button" aria-haspopup="listbox"
                              aria-labelledby="mui-component-select-categoryDropdown"
                              id="mui-component-select-categoryDropdown">All</div><input name="categoryDropdown"
                              aria-hidden="true" tabindex="-1" class="MuiSelect-nativeInput" value="0"><svg
                              class="MuiSvgIcon-root MuiSelect-icon" focusable="false" viewBox="0 0 24 24"
                              aria-hidden="true">
                              <path d="M7 10l5 5 5-5z"></path>
                            </svg>
                          </div>
                        </div>
                      </div><input aria-invalid="false" autocomplete="off" id="grouped-demo"
                        placeholder="Search for any product..." type="text"
                        class="MuiInputBase-input MuiInput-input MuiAutocomplete-input MuiAutocomplete-inputFocused MuiInputBase-inputAdornedStart MuiInputBase-inputAdornedEnd"
                        aria-autocomplete="list" autocapitalize="none" spellcheck="false"
                        value="summer clothes for men">
                      <div class="MuiAutocomplete-endAdornment"></div>
                    </div>
                  </div>
                </div>
              </div>
            </div>
            <form class="Header__right" autocomplete="off">
              <div></div>
              <div class="jss6">
                <div class="Header__locale-menu">
                  <div aria-label="more" aria-controls="country-and-language" aria-haspopup="true"
                    style="display: flex; cursor: pointer;">
                    <div class="Header__account-icon"><button class="MuiButtonBase-root MuiIconButton-root" tabindex="0"
                        type="button"><span class="MuiIconButton-label"><svg class="MuiSvgIcon-root" focusable="false"
                            viewBox="0 0 24 24" aria-hidden="true">
                            <path
                              d="M11.99 2C6.47 2 2 6.48 2 12s4.47 10 9.99 10C17.52 22 22 17.52 22 12S17.52 2 11.99 2zm6.93 6h-2.95c-.32-1.25-.78-2.45-1.38-3.56 1.84.63 3.37 1.91 4.33 3.56zM12 4.04c.83 1.2 1.48 2.53 1.91 3.96h-3.82c.43-1.43 1.08-2.76 1.91-3.96zM4.26 14C4.1 13.36 4 12.69 4 12s.1-1.36.26-2h3.38c-.08.66-.14 1.32-.14 2 0 .68.06 1.34.14 2H4.26zm.82 2h2.95c.32 1.25.78 2.45 1.38 3.56-1.84-.63-3.37-1.9-4.33-3.56zm2.95-8H5.08c.96-1.66 2.49-2.93 4.33-3.56C8.81 5.55 8.35 6.75 8.03 8zM12 19.96c-.83-1.2-1.48-2.53-1.91-3.96h3.82c-.43 1.43-1.08 2.76-1.91 3.96zM14.34 14H9.66c-.09-.66-.16-1.32-.16-2 0-.68.07-1.35.16-2h4.68c.09.65.16 1.32.16 2 0 .68-.07 1.34-.16 2zm.25 5.56c.6-1.11 1.06-2.31 1.38-3.56h2.95c-.96 1.65-2.49 2.93-4.33 3.56zM16.36 14c.08-.66.14-1.32.14-2 0-.68-.06-1.34-.14-2h3.38c.16.64.26 1.31.26 2s-.1 1.36-.26 2h-3.38z">
                            </path>
                          </svg></span><span class="MuiTouchRipple-root"></span></button></div>
                  </div>
                </div>
              </div>
              <div class="jss6">
                <div><span class="Header__right-link">Sign in</span><span>&nbsp;&nbsp;Or&nbsp;&nbsp;</span><span
                    class="Header__right-link">Create an Account</span></div>
              </div>
              <div class="Header__cart"><a href="/cart"><button class="MuiButtonBase-root MuiIconButton-root"
                    tabindex="0" type="button"><span class="MuiIconButton-label"><span
                        class="MuiBadge-root Header__cart-badge"><svg width="23px" height="24px" viewBox="0 0 23 24"
                          xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink"
                          class="Header__cart-icon">
                          <title>Group 25</title>
                          <g id="Page-1" stroke="none" stroke-width="1" fill="none" fill-rule="evenodd">
                            <g id="Nav" transform="translate(-1192.000000, -19.000000)" stroke="#8A9096">
                              <g id="Group-30" transform="translate(1193.000000, 11.000000)">
                                <g id="Group-25" transform="translate(0.000000, 9.000000)">
                                  <path
                                    d="M0.292159072,0.407407407 L1.72616138,0.407407407 C2.20089698,0.407407407 2.61020143,0.741188913 2.70571358,1.2062172 L5.55731969,15.0900791 C5.65283184,15.5551074 6.06213629,15.8888889 6.53687188,15.8888889 L18.5586073,15.8888889 C19.067867,15.8888889 19.4957852,15.5061758 19.5524071,15.0000737 L20.6625294,5.07749982 L20.6625294,5.07749982 L3.91597331,5.07749982"
                                    id="Line-3" stroke-width="2" stroke-linecap="square"></path>
                                  <circle id="Oval" stroke-width="1.5" fill="#8A9096" cx="8.03289981" cy="20.3703704"
                                    r="1.22222222"></circle>
                                  <circle id="Oval" stroke-width="1.5" fill="#8A9096" cx="16.181048" cy="20.3703704"
                                    r="1.22222222"></circle>
                                </g>
                              </g>
                            </g>
                          </g>
                        </svg><span
                          class="MuiBadge-badge MuiBadge-anchorOriginTopRightRectangle MuiBadge-invisible">0</span></span></span><span
                      class="MuiTouchRipple-root"></span></button></a></div>
            </form>
          </div>
        </div>
      </div>
    </div>
    <RouterView />
  </div>

</template>

<style scoped>
header {
  line-height: 1.5;
  max-height: 100vh;
}

.logo {
  display: block;
  margin: 0 auto 2rem;
}

nav {
  width: 100%;
  font-size: 12px;
  text-align: center;
  margin-top: 2rem;
}

nav a.router-link-exact-active {
  color: var(--color-text);
}

nav a.router-link-exact-active:hover {
  background-color: transparent;
}

nav a {
  display: inline-block;
  padding: 0 1rem;
  border-left: 1px solid var(--color-border);
}

nav a:first-of-type {
  border: 0;
}

@media (min-width: 1024px) {
  header {
    display: flex;
    place-items: center;
    padding-right: calc(var(--section-gap) / 2);
  }

  .logo {
    margin: 0 2rem 0 0;
  }

  header .wrapper {
    display: flex;
    place-items: flex-start;
    flex-wrap: wrap;
  }

  nav {
    text-align: left;
    margin-left: -1rem;
    font-size: 1rem;

    padding: 1rem 0;
    margin-top: 1rem;
  }
}
</style>
