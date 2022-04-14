<template>
  <nav class="flex px-5 py-1 text-white bg-[#202020] sticky items-center top-0 z-10">
    <div class="flex w-full lg:w-80 py-2">
      <svg class="mr-5 w-6 h-6 fill-white" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg">
        <g class="style-scope yt-icon">
          <path d="M21,6H3V5h18V6z M21,11H3v1h18V11z M21,17H3v1h18V17z" class="style-scope yt-icon"></path>
        </g>
      </svg>
      <svg class="w-24 h-6 fill-white" viewBox="0 0 90 20" xmlns="http://www.w3.org/2000/svg">
        <g viewBox="0 0 90 20" preserveAspectRatio="xMidYMid meet" class="style-scope yt-icon">
          <g class="style-scope yt-icon">
            <path
              d="M27.9727 3.12324C27.6435 1.89323 26.6768 0.926623 25.4468 0.597366C23.2197 2.24288e-07 14.285 0 14.285 0C14.285 0 5.35042 2.24288e-07 3.12323 0.597366C1.89323 0.926623 0.926623 1.89323 0.597366 3.12324C2.24288e-07 5.35042 0 10 0 10C0 10 2.24288e-07 14.6496 0.597366 16.8768C0.926623 18.1068 1.89323 19.0734 3.12323 19.4026C5.35042 20 14.285 20 14.285 20C14.285 20 23.2197 20 25.4468 19.4026C26.6768 19.0734 27.6435 18.1068 27.9727 16.8768C28.5701 14.6496 28.5701 10 28.5701 10C28.5701 10 28.5677 5.35042 27.9727 3.12324Z"
              fill="#FF0000" class="style-scope yt-icon"></path>
            <path d="M11.4253 14.2854L18.8477 10.0004L11.4253 5.71533V14.2854Z" fill="white"
              class="style-scope yt-icon"></path>
          </g>
          <g class="style-scope yt-icon">
            <g id="youtube-paths" class="style-scope yt-icon">
              <path
                d="M34.6024 13.0036L31.3945 1.41846H34.1932L35.3174 6.6701C35.6043 7.96361 35.8136 9.06662 35.95 9.97913H36.0323C36.1264 9.32532 36.3381 8.22937 36.665 6.68892L37.8291 1.41846H40.6278L37.3799 13.0036V18.561H34.6001V13.0036H34.6024Z"
                class="style-scope yt-icon"></path>
              <path
                d="M41.4697 18.1937C40.9053 17.8127 40.5031 17.22 40.2632 16.4157C40.0257 15.6114 39.9058 14.5437 39.9058 13.2078V11.3898C39.9058 10.0422 40.0422 8.95805 40.315 8.14196C40.5878 7.32588 41.0135 6.72851 41.592 6.35457C42.1706 5.98063 42.9302 5.79248 43.871 5.79248C44.7976 5.79248 45.5384 5.98298 46.0981 6.36398C46.6555 6.74497 47.0647 7.34234 47.3234 8.15137C47.5821 8.96275 47.7115 10.0422 47.7115 11.3898V13.2078C47.7115 14.5437 47.5845 15.6161 47.3329 16.4251C47.0812 17.2365 46.672 17.8292 46.1075 18.2031C45.5431 18.5771 44.7764 18.7652 43.8098 18.7652C42.8126 18.7675 42.0342 18.5747 41.4697 18.1937ZM44.6353 16.2323C44.7905 15.8231 44.8705 15.1575 44.8705 14.2309V10.3292C44.8705 9.43077 44.7929 8.77225 44.6353 8.35833C44.4777 7.94206 44.2026 7.7351 43.8074 7.7351C43.4265 7.7351 43.156 7.94206 43.0008 8.35833C42.8432 8.77461 42.7656 9.43077 42.7656 10.3292V14.2309C42.7656 15.1575 42.8408 15.8254 42.9914 16.2323C43.1419 16.6415 43.4123 16.8461 43.8074 16.8461C44.2026 16.8461 44.4777 16.6415 44.6353 16.2323Z"
                class="style-scope yt-icon"></path>
              <path
                d="M56.8154 18.5634H54.6094L54.3648 17.03H54.3037C53.7039 18.1871 52.8055 18.7656 51.6061 18.7656C50.7759 18.7656 50.1621 18.4928 49.767 17.9496C49.3719 17.4039 49.1743 16.5526 49.1743 15.3955V6.03751H51.9942V15.2308C51.9942 15.7906 52.0553 16.188 52.1776 16.4256C52.2999 16.6631 52.5045 16.783 52.7914 16.783C53.036 16.783 53.2712 16.7078 53.497 16.5573C53.7228 16.4067 53.8874 16.2162 53.9979 15.9858V6.03516H56.8154V18.5634Z"
                class="style-scope yt-icon"></path>
              <path d="M64.4755 3.68758H61.6768V18.5629H58.9181V3.68758H56.1194V1.42041H64.4755V3.68758Z"
                class="style-scope yt-icon"></path>
              <path
                d="M71.2768 18.5634H69.0708L68.8262 17.03H68.7651C68.1654 18.1871 67.267 18.7656 66.0675 18.7656C65.2373 18.7656 64.6235 18.4928 64.2284 17.9496C63.8333 17.4039 63.6357 16.5526 63.6357 15.3955V6.03751H66.4556V15.2308C66.4556 15.7906 66.5167 16.188 66.639 16.4256C66.7613 16.6631 66.9659 16.783 67.2529 16.783C67.4974 16.783 67.7326 16.7078 67.9584 16.5573C68.1842 16.4067 68.3488 16.2162 68.4593 15.9858V6.03516H71.2768V18.5634Z"
                class="style-scope yt-icon"></path>
              <path
                d="M80.609 8.0387C80.4373 7.24849 80.1621 6.67699 79.7812 6.32186C79.4002 5.96674 78.8757 5.79035 78.2078 5.79035C77.6904 5.79035 77.2059 5.93616 76.7567 6.23014C76.3075 6.52412 75.9594 6.90747 75.7148 7.38489H75.6937V0.785645H72.9773V18.5608H75.3056L75.5925 17.3755H75.6537C75.8724 17.7988 76.1993 18.1304 76.6344 18.3774C77.0695 18.622 77.554 18.7443 78.0855 18.7443C79.038 18.7443 79.7412 18.3045 80.1904 17.4272C80.6396 16.5476 80.8653 15.1765 80.8653 13.3092V11.3266C80.8653 9.92722 80.7783 8.82892 80.609 8.0387ZM78.0243 13.1492C78.0243 14.0617 77.9867 14.7767 77.9114 15.2941C77.8362 15.8115 77.7115 16.1808 77.5328 16.3971C77.3564 16.6158 77.1165 16.724 76.8178 16.724C76.585 16.724 76.371 16.6699 76.1734 16.5594C75.9759 16.4512 75.816 16.2866 75.6937 16.0702V8.96062C75.7877 8.6196 75.9524 8.34209 76.1852 8.12337C76.4157 7.90465 76.6697 7.79646 76.9401 7.79646C77.2271 7.79646 77.4481 7.90935 77.6034 8.13278C77.7609 8.35855 77.8691 8.73485 77.9303 9.26636C77.9914 9.79787 78.022 10.5528 78.022 11.5335V13.1492H78.0243Z"
                class="style-scope yt-icon"></path>
              <path
                d="M84.8657 13.8712C84.8657 14.6755 84.8892 15.2776 84.9363 15.6798C84.9833 16.0819 85.0821 16.3736 85.2326 16.5594C85.3831 16.7428 85.6136 16.8345 85.9264 16.8345C86.3474 16.8345 86.639 16.6699 86.7942 16.343C86.9518 16.0161 87.0365 15.4705 87.0506 14.7085L89.4824 14.8519C89.4965 14.9601 89.5035 15.1106 89.5035 15.3011C89.5035 16.4582 89.186 17.3237 88.5534 17.8952C87.9208 18.4667 87.0247 18.7536 85.8676 18.7536C84.4777 18.7536 83.504 18.3185 82.9466 17.446C82.3869 16.5735 82.1094 15.2259 82.1094 13.4008V11.2136C82.1094 9.33452 82.3987 7.96105 82.9772 7.09558C83.5558 6.2301 84.5459 5.79736 85.9499 5.79736C86.9165 5.79736 87.6597 5.97375 88.1771 6.32888C88.6945 6.684 89.059 7.23433 89.2707 7.98457C89.4824 8.7348 89.5882 9.76961 89.5882 11.0913V13.2362H84.8657V13.8712ZM85.2232 7.96811C85.0797 8.14449 84.9857 8.43377 84.9363 8.83593C84.8892 9.2381 84.8657 9.84722 84.8657 10.6657V11.5641H86.9283V10.6657C86.9283 9.86133 86.9001 9.25221 86.846 8.83593C86.7919 8.41966 86.6931 8.12803 86.5496 7.95635C86.4062 7.78702 86.1851 7.7 85.8864 7.7C85.5854 7.70235 85.3643 7.79172 85.2232 7.96811Z"
                class="style-scope yt-icon"></path>
            </g>
          </g>
        </g>
      </svg>

    </div>

    <div class="flex-1 items-center justify-center">
      <div class="flex relative text-gray-600 justify-center gap-2 items-center">
        <input class="h-10 bg-[#181818] p-2 border border-[#3a3a3a] focus:border-[#3a3a3a] hidden lg:flex w-1/2" type="search" name="search"
          placeholder="Search">

        <button type="submit" class="lg:w-16 flex items-center justify-center lg:bg-[#323232]">
          <svg class="w-5 h-5 fill-white" viewBox="0 0 20 20" xmlns="http://www.w3.org/2000/svg">
            <g class="style-scope yt-icon">
              <path
                d="M20.87,20.17l-5.59-5.59C16.35,13.35,17,11.75,17,10c0-3.87-3.13-7-7-7s-7,3.13-7,7s3.13,7,7,7c1.75,0,3.35-0.65,4.58-1.71 l5.59,5.59L20.87,20.17z M10,16c-3.31,0-6-2.69-6-6s2.69-6,6-6s6,2.69,6,6S13.31,16,10,16z"
                class="style-scope yt-icon"></path>
            </g>
          </svg>
        </button>

        <button class="ml-2 w-10 h-10 flex items-center justify-center rounded-full lg:bg-[#131212]">
          <svg class="w-6 h-6 fill-white" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg">
            <g class="style-scope yt-icon"><path d="M12 3C10.34 3 9 4.37 9 6.07V11.93C9 13.63 10.34 15 12 15C13.66 15 15 13.63 15 11.93V6.07C15 4.37 13.66 3 12 3ZM18.5 12H17.5C17.5 15.03 15.03 17.5 12 17.5C8.97 17.5 6.5 15.03 6.5 12H5.5C5.5 15.24 7.89 17.93 11 18.41V21H13V18.41C16.11 17.93 18.5 15.24 18.5 12Z" class="style-scope yt-icon"></path></g>
          </svg>
        </button>
      </div>

    </div>

    <div class="w-11/12 lg:w-80 flex justify-end">
      <ul class="flex justify-center items-center space-x-6">
        <li class="cursor-pointer">
          <svg class="w-6 h-6 fill-white" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg">
            <g class="style-scope yt-icon"><path d="M14,13h-3v3H9v-3H6v-2h3V8h2v3h3V13z M17,6H3v12h14v-6.39l4,1.83V8.56l-4,1.83V6 M18,5v3.83L22,7v8l-4-1.83V19H2V5H18L18,5 z" class="style-scope yt-icon"></path></g>
          </svg>
        </li>
        <li class="cursor-pointer">
          <svg class="w-6 h-6 fill-white" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg">
            <g class="style-scope yt-icon"><path d="M16,4v4h4V4H16z M19,7h-2V5h2V7z M16,10v4h4v-4H16z M19,13h-2v-2h2V13z M10,4v4h4V4H10z M13,7h-2V5h2V7z M10,10v4h4v-4H10z M13,13h-2v-2h2V13z M16,16v4h4v-4H16z M19,19h-2v-2h2V19z M10,16v4h4v-4H10z M13,19h-2v-2h2V19z M4,4v4h4V4H4z M7,7H5V5h2V7z M4,10 v4h4v-4H4z M7,13H5v-2h2V13z M4,16v4h4v-4H4z M7,19H5v-2h2V19z" class="style-scope yt-icon"></path></g>
          </svg>
        </li>
        <li class="relative cursor-pointer">
          <svg class="w-6 h-6 fill-white" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg">
            <g class="style-scope yt-icon"><path d="M10,20h4c0,1.1-0.9,2-2,2S10,21.1,10,20z M20,17.35V19H4v-1.65l2-1.88v-5.15c0-2.92,1.56-5.22,4-5.98V3.96 c0-1.42,1.49-2.5,2.99-1.76C13.64,2.52,14,3.23,14,3.96l0,0.39c2.44,0.75,4,3.06,4,5.98v5.15L20,17.35z M19,17.77l-2-1.88v-5.47 c0-2.47-1.19-4.36-3.13-5.1c-1.26-0.53-2.64-0.5-3.84,0.03C8.15,6.11,7,7.99,7,10.42v5.47l-2,1.88V18h14V17.77z" class="style-scope yt-icon"></path></g>
          </svg>
          <span style="font-size: 12px; padding-left: 3px; padding-right: 3px;" class="absolute -right-1 -top-2 rounded-full bg-red-600">02</span>
        </li>
        <li>
          <div class="dropdown dropdown-end">
            <label tabindex="0" class="btn-ghost">
              <img class="rounded-full w-auto h-7" src="https://avatars.githubusercontent.com/u/57138108?v=4" />
            </label>
            <ul style="overflow: auto" tabindex="0" class="dropdown-content shadow bg-base-100 rounded-box w-52">
              <li class="px-4 pt-4">
                <div class="flex flex-row gap-4 items-center mb-4">
                  <div>
                    <img class="rounded-full w-12 h-12" src="https://avatars.githubusercontent.com/u/57138108?v=4"/>
                  </div>
                  <div class="flex flex-col gap-2">
                    <h3>Alexis Yehadji</h3>
                    <button class="text-sm text-blue-400">Manage your Google Account</button>
                  </div>
                </div>
              </li>

              <li class="flex justify-center">
                <div class="w-full bg-gray-600 h-[1px]"></div>
              </li>

              <li class="px-4 py-2 cursor-pointer hover:bg-[#363636] text-sm mt-2">
                <div class="flex flex-row gap-4 items-center">
                  <div class="w-7 h-7">
                    <svg viewBox="0 0 24 24" preserveAspectRatio="xMidYMid meet" focusable="false" class="style-scope" fill="white" style="pointer-events: none; display: block; width: 100%; height: 100%;"><g class="style-scope yt-icon"><path d="M3,3v18h18V3H3z M4.99,20c0.39-2.62,2.38-5.1,7.01-5.1s6.62,2.48,7.01,5.1H4.99z M9,10c0-1.65,1.35-3,3-3s3,1.35,3,3 c0,1.65-1.35,3-3,3S9,11.65,9,10z M12.72,13.93C14.58,13.59,16,11.96,16,10c0-2.21-1.79-4-4-4c-2.21,0-4,1.79-4,4 c0,1.96,1.42,3.59,3.28,3.93c-4.42,0.25-6.84,2.8-7.28,6V4h16v15.93C19.56,16.73,17.14,14.18,12.72,13.93z" class="style-scope yt-icon"></path></g></svg>
                  </div>
                  <div>Your channel</div>
                </div>
              </li>
              <li class="px-4 py-2 cursor-pointer hover:bg-[#363636] text-sm">
                <div class="flex flex-row gap-4 items-center">
                  <div class="w-7 h-7">
                    <svg viewBox="0 0 24 24" preserveAspectRatio="xMidYMid meet" focusable="false" fill="white" class="style-scope yt-icon" style="pointer-events: none; display: block; width: 100%; height: 100%;"><g class="style-scope yt-icon"><path d="M12,3c4.96,0,9,4.04,9,9s-4.04,9-9,9s-9-4.04-9-9S7.04,3,12,3 M12,2C6.48,2,2,6.48,2,12s4.48,10,10,10s10-4.48,10-10 S17.52,2,12,2L12,2z M12.45,10.95c-0.67-0.22-1.18-0.47-1.52-0.72c-0.34-0.26-0.52-0.57-0.52-0.95c0-0.41,0.15-0.73,0.44-0.98 c0.29-0.25,0.71-0.37,1.24-0.37c0.55,0,1.23,0.15,1.53,0.44C13.8,8.53,13.93,8.75,14,9h2c-0.07-0.46-0.26-0.88-0.49-1.27 c-0.33-0.55-0.78-0.98-1.37-1.28C13.79,6.27,13.41,6.17,13,6.09V5h-2v1.12c-0.31,0.07-0.62,0.16-0.9,0.29 C9.5,6.7,9.04,7.08,8.72,7.58C8.4,8.07,8.24,8.63,8.24,9.26c0,1.21,0.6,2.18,1.8,2.9c0.44,0.26,1.04,0.53,1.79,0.8 c0.75,0.27,1.27,0.53,1.56,0.77c0.29,0.24,0.43,0.59,0.43,1.05c0,0.42-0.14,0.74-0.43,0.97c-0.29,0.23-0.69,0.35-1.21,0.35 c-1.05,0-1.92-0.37-2.18-1.1H8c0.08,0.42,0.22,0.81,0.44,1.16c0.35,0.57,0.86,1.02,1.52,1.35c0.33,0.16,0.67,0.28,1.04,0.37V19h2 v-1.05c0.79-0.11,1.45-0.38,1.97-0.81c0.69-0.57,1.03-1.37,1.03-2.38c0-0.91-0.28-1.67-0.85-2.28S13.69,11.36,12.45,10.95z" class="style-scope yt-icon"></path></g></svg>
                  </div>
                  <div>Purchases and memberships</div>
                </div>
              </li>
              <li class="px-4 py-2 cursor-pointer hover:bg-[#363636] text-sm">
                <div class="flex flex-row gap-4 items-center">
                  <div class="w-7 h-7">
                    <svg viewBox="0 0 24 24" preserveAspectRatio="xMidYMid meet"  fill="white" focusable="false" class="style-scope yt-icon" style="pointer-events: none; display: block; width: 100%; height: 100%;"><g class="style-scope yt-icon"><path d="M10,9l5.2,3L10,15V9z M13.22,3h-2.44l-0.55,2.2L10.1,5.71L9.61,5.9C9,6.12,8.42,6.45,7.88,6.88L7.48,7.2l-0.5-0.14 L4.82,6.44L3.6,8.56l1.63,1.59l0.37,0.36l-0.08,0.51C5.47,11.34,5.44,11.67,5.44,12s0.03,0.66,0.08,0.98l0.08,0.51l-0.37,0.36 L3.6,15.44l1.22,2.11l2.17-0.62l0.5-0.14l0.4,0.32C8.42,17.55,9,17.88,9.61,18.1l0.5,0.18l0.13,0.51l0.55,2.2h2.44l0.55-2.2 l0.13-0.51l0.5-0.18c0.61-0.23,1.19-0.56,1.72-0.98l0.4-0.32l0.5,0.14l2.17,0.62l1.22-2.11l-1.63-1.59l-0.37-0.36l0.08-0.51 c0.05-0.32,0.08-0.64,0.08-0.98s-0.03-0.66-0.08-0.98l-0.08-0.51l0.37-0.36l1.63-1.59l-1.22-2.11l-2.17,0.62l-0.5,0.14l-0.4-0.32 C15.58,6.45,15,6.12,14.39,5.9l-0.5-0.18L13.77,5.2L13.22,3 M14,2l0.74,2.96c0.73,0.27,1.4,0.66,2,1.14l2.92-0.83l2,3.46l-2.19,2.13 c0.06,0.37,0.09,0.75,0.09,1.14s-0.03,0.77-0.09,1.14l2.19,2.13l-2,3.46l-2.92-0.83c-0.6,0.48-1.27,0.87-2,1.14L14,22h-4l-0.74-2.96 c-0.73-0.27-1.4-0.66-2-1.14l-2.92,0.83l-2-3.46l2.19-2.13C4.47,12.77,4.44,12.39,4.44,12s0.03-0.77,0.09-1.14L2.34,8.73l2-3.46 L7.26,6.1c0.6-0.48,1.27-0.87,2-1.14L10,2H14L14,2z" class="style-scope yt-icon"></path></g></svg>
                  </div>
                  <div>Youtube Studio</div>
                </div>
              </li>
              <li class="px-4 py-2 cursor-pointer hover:bg-[#363636] text-sm">
                <div class="flex flex-row gap-4 items-center relative">
                  <div class="w-7 h-7">
                    <svg viewBox="0 0 24 24" preserveAspectRatio="xMidYMid meet" fill="white" focusable="false" class="style-scope yt-icon" style="pointer-events: none; display: block; width: 100%; height: 100%;"><g class="style-scope yt-icon"><path d="M4,20h14v1H3V6h1V20z M6,3v15h15V3H6z M8.02,17c0.36-2.13,1.93-4.1,5.48-4.1s5.12,1.97,5.48,4.1H8.02z M11,8.5 C11,7.12,12.12,6,13.5,6S16,7.12,16,8.5c0,1.38-1.12,2.5-2.5,2.5S11,9.88,11,8.5z M14.21,11.93C15.8,11.6,17,10.19,17,8.5 C17,6.57,15.43,5,13.5,5S10,6.57,10,8.5c0,1.69,1.2,3.1,2.79,3.43c-3.48,0.26-5.4,2.42-5.78,5.07H7V4h13v13h-0.01 C19.61,14.35,17.68,12.19,14.21,11.93z" class="style-scope yt-icon"></path></g></svg>
                  </div>
                  <div>Switch account</div>
                  <div class="absolute right-2 w-7 h-7">
                    <svg  fill="white" viewBox="0 0 24 24" preserveAspectRatio="xMidYMid meet" focusable="false" class="style-scope yt-icon" style="pointer-events: none; display: block; width: 100%; height: 100%;"><g mirror-in-rtl="" class="style-scope yt-icon"><path d="M9.4,18.4l-0.7-0.7l5.6-5.6L8.6,6.4l0.7-0.7l6.4,6.4L9.4,18.4z" class="style-scope yt-icon"></path></g></svg>
                  </div>
                </div>
              </li>
              <li class="px-4 py-2 cursor-pointer hover:bg-[#363636] text-sm">
                <div class="flex flex-row gap-4 items-center">
                  <div class="w-7 h-7">
                    <svg fill="white" viewBox="0 0 24 24" preserveAspectRatio="xMidYMid meet" focusable="false" class="style-scope yt-icon" style="pointer-events: none; display: block; width: 100%; height: 100%;"><g class="style-scope yt-icon"><path d="M20,3v18H8v-1h11V4H8V3H20z M11.1,15.1l0.7,0.7l4.4-4.4l-4.4-4.4l-0.7,0.7l3.1,3.1H3v1h11.3L11.1,15.1z" class="style-scope yt-icon"></path></g></svg>
                  </div>
                  <div>Sign out</div>
                </div>
              </li>

              <li class="flex justify-center">
                <div class="w-full bg-gray-600 h-[1px]"></div>
              </li>

              <li class="px-4 py-2 cursor-pointer hover:bg-[#363636] text-sm">
                <div class="flex flex-row gap-4 items-center relative">
                  <div class="w-7 h-7">
                    <svg viewBox="0 0 24 24" fill="white" preserveAspectRatio="xMidYMid meet" focusable="false" class="style-scope yt-icon" style="pointer-events: none; display: block; width: 100%; height: 100%;"><g class="style-scope yt-icon"><path d="M12 22C10.93 22 9.86998 21.83 8.83998 21.48L7.41998 21.01L8.83998 20.54C12.53 19.31 15 15.88 15 12C15 8.12 12.53 4.69 8.83998 3.47L7.41998 2.99L8.83998 2.52C9.86998 2.17 10.93 2 12 2C17.51 2 22 6.49 22 12C22 17.51 17.51 22 12 22ZM10.58 20.89C11.05 20.96 11.53 21 12 21C16.96 21 21 16.96 21 12C21 7.04 16.96 3 12 3C11.53 3 11.05 3.04 10.58 3.11C13.88 4.81 16 8.21 16 12C16 15.79 13.88 19.19 10.58 20.89Z" class="style-scope yt-icon"></path></g></svg>
                  </div>
                  <div>Appearance: Dark</div>
                  <div class="absolute right-2 w-7 h-7">
                    <svg  fill="white" viewBox="0 0 24 24" preserveAspectRatio="xMidYMid meet" focusable="false" class="style-scope yt-icon" style="pointer-events: none; display: block; width: 100%; height: 100%;"><g mirror-in-rtl="" class="style-scope yt-icon"><path d="M9.4,18.4l-0.7-0.7l5.6-5.6L8.6,6.4l0.7-0.7l6.4,6.4L9.4,18.4z" class="style-scope yt-icon"></path></g></svg>
                  </div>
                </div>
              </li>
              <li class="px-4 py-2 cursor-pointer hover:bg-[#363636] text-sm">
                <div class="flex flex-row gap-4 items-center relative">
                  <div class="w-7 h-7">
                    <svg fill="white" viewBox="0 0 24 24" preserveAspectRatio="xMidYMid meet" focusable="false" class="style-scope yt-icon" style="pointer-events: none; display: block; width: 100%; height: 100%;"><g class="style-scope yt-icon"><path d="M12.26,16.18l-2.93-2.87c-0.8,0.86-1.64,1.71-2.48,2.54L4.6,18.1L3.9,17.4l2.25-2.25c0.84-0.84,1.68-1.69,2.48-2.55 c-1.18-1.23-2.17-2.64-2.9-4.18L5.73,8.4h1.14c0.65,1.26,1.47,2.43,2.44,3.45c1.59-1.81,2.89-3.69,3.43-5.7H2.08v-1h6.65V3h1v2.15 h6.78v1h-2.73c-0.54,2.32-2.01,4.42-3.77,6.42l2.63,2.58C12.51,15.5,12.39,15.82,12.26,16.18z M21.51,21.01h-0.95l-1.12-3.04h-4.91 l-1.11,3.04h-0.96l4.09-10.81h0.87L21.51,21.01z M19.15,17.2l-2.17-5.89l-2.17,5.89H19.15z" class="style-scope yt-icon"></path></g></svg>
                  </div>
                  <div>Language: English</div>
                  <div class="absolute right-2 w-7 h-7">
                    <svg  fill="white" viewBox="0 0 24 24" preserveAspectRatio="xMidYMid meet" focusable="false" class="style-scope yt-icon" style="pointer-events: none; display: block; width: 100%; height: 100%;"><g mirror-in-rtl="" class="style-scope yt-icon"><path d="M9.4,18.4l-0.7-0.7l5.6-5.6L8.6,6.4l0.7-0.7l6.4,6.4L9.4,18.4z" class="style-scope yt-icon"></path></g></svg>
                  </div>
                </div>
              </li>
              <li class="px-4 py-2 cursor-pointer hover:bg-[#363636] text-sm">
                <div class="flex flex-row gap-4 items-center relative">
                  <div class="w-7 h-7">
                    <svg fill="white" viewBox="0 0 24 24" preserveAspectRatio="xMidYMid meet" focusable="false" class="style-scope yt-icon" style="pointer-events: none; display: block; width: 100%; height: 100%;"><g class="style-scope yt-icon"><path d="M11.99,1.98C6.46,1.98,1.98,6.47,1.98,12s4.48,10.02,10.01,10.02c5.54,0,10.03-4.49,10.03-10.02S17.53,1.98,11.99,1.98z M8.86,14.5c-0.16-0.82-0.25-1.65-0.25-2.5c0-0.87,0.09-1.72,0.26-2.55h6.27c0.17,0.83,0.26,1.68,0.26,2.55 c0,0.85-0.09,1.68-0.25,2.5H8.86z M14.89,15.5c-0.54,1.89-1.52,3.64-2.89,5.15c-1.37-1.5-2.35-3.25-2.89-5.15H14.89z M9.12,8.45 c0.54-1.87,1.52-3.61,2.88-5.1c1.36,1.49,2.34,3.22,2.88,5.1H9.12z M16.15,9.45h4.5c0.24,0.81,0.37,1.66,0.37,2.55 c0,0.87-0.13,1.71-0.36,2.5h-4.51c0.15-0.82,0.24-1.65,0.24-2.5C16.39,11.13,16.3,10.28,16.15,9.45z M20.29,8.45h-4.38 c-0.53-1.97-1.47-3.81-2.83-5.4C16.33,3.45,19.04,5.56,20.29,8.45z M10.92,3.05c-1.35,1.59-2.3,3.43-2.83,5.4H3.71 C4.95,5.55,7.67,3.44,10.92,3.05z M3.35,9.45h4.5C7.7,10.28,7.61,11.13,7.61,12c0,0.85,0.09,1.68,0.24,2.5H3.34 c-0.23-0.79-0.36-1.63-0.36-2.5C2.98,11.11,3.11,10.26,3.35,9.45z M3.69,15.5h4.39c0.52,1.99,1.48,3.85,2.84,5.45 C7.65,20.56,4.92,18.42,3.69,15.5z M13.09,20.95c1.36-1.6,2.32-3.46,2.84-5.45h4.39C19.08,18.42,16.35,20.55,13.09,20.95z" class="style-scope yt-icon"></path></g></svg>
                  </div>
                  <div>Location: United states</div>
                  <div class="absolute right-2 w-7 h-7">
                    <svg  fill="white" viewBox="0 0 24 24" preserveAspectRatio="xMidYMid meet" focusable="false" class="style-scope yt-icon" style="pointer-events: none; display: block; width: 100%; height: 100%;"><g mirror-in-rtl="" class="style-scope yt-icon"><path d="M9.4,18.4l-0.7-0.7l5.6-5.6L8.6,6.4l0.7-0.7l6.4,6.4L9.4,18.4z" class="style-scope yt-icon"></path></g></svg>
                  </div>
                </div>
              </li>
              <li class="px-4 py-2 cursor-pointer hover:bg-[#363636] text-sm">
                <div class="flex flex-row gap-4 items-center relative">
                  <div class="w-7 h-7">
                    <svg fill="white" viewBox="0 0 24 24" preserveAspectRatio="xMidYMid meet" focusable="false" class="style-scope yt-icon" style="pointer-events: none; display: block; width: 100%; height: 100%;"><g class="style-scope yt-icon"><path d="M12,9c1.65,0,3,1.35,3,3s-1.35,3-3,3s-3-1.35-3-3S10.35,9,12,9 M12,8c-2.21,0-4,1.79-4,4s1.79,4,4,4s4-1.79,4-4 S14.21,8,12,8L12,8z M13.22,3l0.55,2.2l0.13,0.51l0.5,0.18c0.61,0.23,1.19,0.56,1.72,0.98l0.4,0.32l0.5-0.14l2.17-0.62l1.22,2.11 l-1.63,1.59l-0.37,0.36l0.08,0.51c0.05,0.32,0.08,0.64,0.08,0.98s-0.03,0.66-0.08,0.98l-0.08,0.51l0.37,0.36l1.63,1.59l-1.22,2.11 l-2.17-0.62l-0.5-0.14l-0.4,0.32c-0.53,0.43-1.11,0.76-1.72,0.98l-0.5,0.18l-0.13,0.51L13.22,21h-2.44l-0.55-2.2l-0.13-0.51 l-0.5-0.18C9,17.88,8.42,17.55,7.88,17.12l-0.4-0.32l-0.5,0.14l-2.17,0.62L3.6,15.44l1.63-1.59l0.37-0.36l-0.08-0.51 C5.47,12.66,5.44,12.33,5.44,12s0.03-0.66,0.08-0.98l0.08-0.51l-0.37-0.36L3.6,8.56l1.22-2.11l2.17,0.62l0.5,0.14l0.4-0.32 C8.42,6.45,9,6.12,9.61,5.9l0.5-0.18l0.13-0.51L10.78,3H13.22 M14,2h-4L9.26,4.96c-0.73,0.27-1.4,0.66-2,1.14L4.34,5.27l-2,3.46 l2.19,2.13C4.47,11.23,4.44,11.61,4.44,12s0.03,0.77,0.09,1.14l-2.19,2.13l2,3.46l2.92-0.83c0.6,0.48,1.27,0.87,2,1.14L10,22h4 l0.74-2.96c0.73-0.27,1.4-0.66,2-1.14l2.92,0.83l2-3.46l-2.19-2.13c0.06-0.37,0.09-0.75,0.09-1.14s-0.03-0.77-0.09-1.14l2.19-2.13 l-2-3.46L16.74,6.1c-0.6-0.48-1.27-0.87-2-1.14L14,2L14,2z" class="style-scope yt-icon"></path></g></svg>
                  </div>
                  <div>Settings</div>
                </div>
              </li>
              <li class="px-4 py-2 cursor-pointer hover:bg-[#363636] text-sm">
                <div class="flex flex-row gap-4 items-center">
                  <div class="w-7 h-7">
                    <svg fill="white" viewBox="0 0 24 24" preserveAspectRatio="xMidYMid meet" focusable="false" class="style-scope yt-icon" style="pointer-events: none; display: block; width: 100%; height: 100%;"><g class="style-scope yt-icon"><path d="M12,3.06l7,3.21v4.84c0,1.3-0.25,2.6-0.75,3.86c-0.15,0.37-0.33,0.76-0.55,1.17c-0.15,0.27-0.31,0.54-0.48,0.81 c-1.32,2.01-3.17,3.42-5.23,3.98c-2.06-0.56-3.91-1.97-5.23-3.98c-0.17-0.27-0.33-0.54-0.48-0.81c-0.22-0.41-0.4-0.79-0.55-1.17 C5.25,13.71,5,12.41,5,11.11V6.27L12,3.06 M12,1.96L4,5.63v5.49c0,1.47,0.3,2.9,0.81,4.22c0.17,0.44,0.37,0.86,0.6,1.28 c0.16,0.3,0.34,0.6,0.52,0.88c1.42,2.17,3.52,3.82,5.95,4.44L12,21.96l0.12-0.03c2.43-0.61,4.53-2.26,5.95-4.43 c0.19-0.29,0.36-0.58,0.52-0.88c0.22-0.41,0.43-0.84,0.6-1.28C19.7,14.01,20,12.58,20,11.11V5.63L12,1.96L12,1.96z M13.08,12.11 c-0.32-0.06-0.64-0.11-0.96-0.12C13.72,11.92,15,10.62,15,9c0-1.66-1.34-3-3-3S9,7.34,9,9c0,1.62,1.28,2.92,2.88,2.99 c-0.32,0.01-0.64,0.06-0.96,0.12h0C8.64,12.58,7,14.62,7,17h10C17,14.62,15.36,12.58,13.08,12.11z M10,9c0-1.1,0.9-2,2-2s2,0.9,2,2 s-0.9,2-2,2S10,10.1,10,9z M11.12,13.09c0.37-0.08,0.64-0.11,0.88-0.11s0.51,0.03,0.88,0.11c1.48,0.3,2.63,1.46,3,2.91H8.12 C8.49,14.55,9.64,13.39,11.12,13.09z" class="style-scope yt-icon"></path></g></svg>
                  </div>
                  <div>Your data in YouTube</div>
                </div>
              </li>
              <li class="px-4 py-2 cursor-pointer hover:bg-[#363636] text-sm">
                <div class="flex flex-row gap-4 items-center">
                  <div class="w-7 h-7">
                    <svg fill="white" viewBox="0 0 24 24" preserveAspectRatio="xMidYMid meet" focusable="false" class="style-scope yt-icon" style="pointer-events: none; display: block; width: 100%; height: 100%;"><g class="style-scope yt-icon"><path d="M15.36,9.96c0,1.09-0.67,1.67-1.31,2.24c-0.53,0.47-1.03,0.9-1.16,1.6L12.85,14h-1.75l0.03-0.28 c0.14-1.17,0.8-1.76,1.47-2.27c0.52-0.4,1.01-0.77,1.01-1.49c0-0.51-0.23-0.97-0.63-1.29c-0.4-0.31-0.92-0.42-1.42-0.29 c-0.59,0.15-1.05,0.67-1.19,1.34L10.32,10H8.57l0.06-0.42c0.2-1.4,1.15-2.53,2.42-2.87c1.05-0.29,2.14-0.08,2.98,0.57 C14.88,7.92,15.36,8.9,15.36,9.96z M12,18c0.55,0,1-0.45,1-1s-0.45-1-1-1s-1,0.45-1,1S11.45,18,12,18z M12,3c-4.96,0-9,4.04-9,9 s4.04,9,9,9s9-4.04,9-9S16.96,3,12,3 M12,2c5.52,0,10,4.48,10,10s-4.48,10-10,10S2,17.52,2,12S6.48,2,12,2L12,2z" class="style-scope yt-icon"></path></g></svg>
                  </div>
                  <div>Help</div>
                </div>
              </li>
              <li class="px-4 py-2 cursor-pointer hover:bg-[#363636] text-sm">
                <div class="flex flex-row gap-4 items-center">
                  <div class="w-7 h-7">
                    <svg fill="white" viewBox="0 0 24 24" preserveAspectRatio="xMidYMid meet" focusable="false" class="style-scope yt-icon" style="pointer-events: none; display: block; width: 100%; height: 100%;"><g class="style-scope yt-icon"><path d="M13,14h-2v-2h2V14z M13,5h-2v6h2V5z M19,3H5v16.59l3.29-3.29L8.59,16H9h10V3 M20,2v15H9l-5,5V2H20L20,2z" class="style-scope yt-icon"></path></g></svg>
                  </div>
                  <div>Send feedback</div>
                </div>
              </li>
              <li class="px-4 py-2 cursor-pointer hover:bg-[#363636] text-sm">
                <div class="flex flex-row gap-4 items-center">
                  <div class="w-7 h-7">
                    <svg fill="white" viewBox="0 0 24 24" preserveAspectRatio="xMidYMid meet" focusable="false" class="style-scope yt-icon" style="pointer-events: none; display: block; width: 100%; height: 100%;"><g class="style-scope yt-icon"><path d="M16,16H8v-2h8V16z M16,11h-2v2h2V11z M19,11h-2v2h2V11z M13,11h-2v2h2V11z M10,11H8v2h2V11z M7,11H5v2h2V11z M16,8h-2v2h2V8 z M19,8h-2v2h2V8z M13,8h-2v2h2V8z M10,8H8v2h2V8z M7,8H5v2h2V8z M22,5v14H2V5H22z M21,6H3v12h18V6z" class="style-scope yt-icon"></path></g></svg>
                  </div>
                  <div>Keyboard shortcuts</div>
                </div>
              </li>

              <li class="flex justify-center">
                <div class="w-full bg-gray-600 h-[1px]"></div>
              </li>

              <li class="px-4 py-4 cursor-pointer hover:bg-[#363636] text-sm">
                <div class="flex flex-row gap-4 items-center relative">
                  <div>Restricted Mode: Off</div>
                  <div class="absolute right-2 w-7 h-7">
                    <svg  fill="white" viewBox="0 0 24 24" preserveAspectRatio="xMidYMid meet" focusable="false" class="style-scope yt-icon" style="pointer-events: none; display: block; width: 100%; height: 100%;"><g mirror-in-rtl="" class="style-scope yt-icon"><path d="M9.4,18.4l-0.7-0.7l5.6-5.6L8.6,6.4l0.7-0.7l6.4,6.4L9.4,18.4z" class="style-scope yt-icon"></path></g></svg>
                  </div>
                </div>
              </li>

            </ul>
          </div>
        </li>

      </ul>
    </div>

  </nav>
</template>

<style>
 .dropdown-content{
   @apply bg-[#202020] border border-gray-600 rounded-sm w-[350px] flex flex-col -mt-4 mb-0;
 }
</style>
