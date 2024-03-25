<template>
  <div>
    <header>
      <div class="header-inner">
        <div class="h-left">
          <div class="about-btn">
            <NuxtLink to="/about">
              <svg
                width="52"
                height="51"
                viewBox="0 0 52 51"
                fill="none"
                xmlns="http://www.w3.org/2000/svg"
              >
                <rect width="52" height="51" rx="25.5" fill="white" />
                <rect
                  x="4"
                  y="4"
                  width="44"
                  height="43"
                  rx="21.5"
                  fill="white"
                />
                <path
                  d="M24.752 31V29.656H26.096V31H24.752ZM22.256 23.144C22.256 21 23.552 19.352 25.968 19.352C27.984 19.352 29.328 20.488 29.328 22.216C29.328 23.64 28.4 24.312 27.584 24.968C26.672 25.736 25.968 26.2 25.968 28.12H24.8C24.8 26.024 25.632 25.32 26.688 24.456C27.472 23.816 28.16 23.32 28.16 22.232C28.16 21.128 27.376 20.392 26 20.392C24.544 20.392 23.424 21.208 23.424 23.144H22.256Z"
                  fill="#0D0B1B"
                />
              </svg>
            </NuxtLink>
          </div>
          <div class="lxl-button">
            <NuxtLink to="/">
              <h3>Line</h3>
              <span>L</span>
              <svg
                width="19"
                height="18"
                viewBox="0 0 19 18"
                fill="none"
                xmlns="http://www.w3.org/2000/svg"
              >
                <path
                  d="M9.4627 0.141602L11.4117 5.45271L16.7792 3.66506L13.842 8.50026L18.5863 11.5822L12.9746 12.3005L13.5231 17.9313L9.4627 13.9918L5.40233 17.9313L5.95076 12.3005L0.339122 11.5822L5.08338 8.50026L2.14616 3.66506L7.51372 5.45271L9.4627 0.141602Z"
                  fill="#FFE774"
                />
              </svg>
              <h3>Line</h3>
              <span>L</span>
            </NuxtLink>
          </div>
        </div>
        <div class="h-right">
          <div class="lxl-button">
            <NuxtLink to="/write"> WRITE </NuxtLink>
            <NuxtLink to="/read-main"> READ </NuxtLink>
          </div>
        </div>
      </div>
    </header>
  </div>
</template>
