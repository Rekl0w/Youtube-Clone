<script setup>
import { ref } from "vue";
</script>

<template>
  <div class="bg-black text-white w-64 h-screen">
    <div class="container overflow-y-auto overflow-x-hidden h-screen">
      <div class="flex items-center justify-center w-full">
        <button class="flex items-center justify-center mt-6">
          <svg
            xmlns="http://www.w3.org/2000/svg"
            class="external-icon"
            viewBox="0 0 97 20"
            style="
              width: 70%;
              pointer-events: none;
              display: block;
              height: 70%;
            "
            focusable="false"
          >
            <svg
              viewBox="0 0 97 20"
              preserveAspectRatio="xMidYMid meet"
              xmlns="http://www.w3.org/2000/svg"
            >
              <g>
                <path
                  d="M27.9704 3.12324C27.6411 1.89323 26.6745 0.926623 25.4445 0.597366C23.2173 2.24288e-07 14.2827 0 14.2827 0C14.2827 0 5.34807 2.24288e-07 3.12088 0.597366C1.89323 0.926623 0.924271 1.89323 0.595014 3.12324C-2.8036e-07 5.35042 0 10 0 10C0 10 -1.57002e-06 14.6496 0.597364 16.8768C0.926621 18.1068 1.89323 19.0734 3.12324 19.4026C5.35042 20 14.285 20 14.285 20C14.285 20 23.2197 20 25.4468 19.4026C26.6769 19.0734 27.6435 18.1068 27.9727 16.8768C28.5701 14.6496 28.5701 10 28.5701 10C28.5701 10 28.5677 5.35042 27.9704 3.12324Z"
                  fill="#FF0000"
                ></path>
                <path
                  d="M11.4275 14.2854L18.8475 10.0004L11.4275 5.71533V14.2854Z"
                  style="fill: white"
                ></path>
              </g>
              <g>
                <path
                  d="M40.0566 6.34524V7.03668C40.0566 10.4915 38.5255 12.5118 35.1742 12.5118H34.6638V18.5583H31.9263V1.42285H35.414C38.6078 1.42285 40.0566 2.7728 40.0566 6.34524ZM37.1779 6.59218C37.1779 4.09924 36.7287 3.50658 35.1765 3.50658H34.6662V10.4727H35.1365C36.6064 10.4727 37.1803 9.40968 37.1803 7.10253L37.1779 6.59218Z"
                  style="fill: white"
                ></path>
                <path
                  d="M46.5336 5.8345L46.3901 9.08238C45.2259 8.83779 44.264 9.02123 43.836 9.77382V18.5579H41.1196V6.0391H43.2857L43.5303 8.75312H43.6337C43.9183 6.77288 44.8379 5.771 46.0232 5.771C46.1949 5.7757 46.3666 5.79687 46.5336 5.8345Z"
                  style="fill: white"
                ></path>
                <path
                  d="M49.6567 13.2456V13.8782C49.6567 16.0842 49.779 16.8415 50.7198 16.8415C51.6182 16.8415 51.8228 16.1501 51.8439 14.7178L54.2734 14.8613C54.4568 17.5565 53.0481 18.763 50.6586 18.763C47.7588 18.763 46.9004 16.8627 46.9004 13.4126V11.223C46.9004 7.58707 47.8599 5.80908 50.7409 5.80908C53.6407 5.80908 54.3769 7.32131 54.3769 11.0984V13.2456H49.6567ZM49.6567 10.6703V11.5687H51.7193V10.675C51.7193 8.37258 51.5547 7.71172 50.6821 7.71172C49.8096 7.71172 49.6567 8.38669 49.6567 10.675V10.6703Z"
                  style="fill: white"
                ></path>
                <path
                  d="M68.4103 9.09902V18.5557H65.5928V9.30834C65.5928 8.28764 65.327 7.77729 64.7132 7.77729C64.2216 7.77729 63.7724 8.06186 63.4667 8.59338C63.4832 8.76271 63.4902 8.93439 63.4879 9.10373V18.5605H60.668V9.30834C60.668 8.28764 60.4022 7.77729 59.7884 7.77729C59.2969 7.77729 58.8665 8.06186 58.5631 8.57456V18.5628H55.7456V6.03929H57.9728L58.2221 7.63383H58.2621C58.8947 6.42969 59.9178 5.77588 61.1219 5.77588C62.3072 5.77588 62.9799 6.36854 63.288 7.43157C63.9418 6.34973 64.9225 5.77588 66.0443 5.77588C67.7564 5.77588 68.4103 7.00119 68.4103 9.09902Z"
                  style="fill: white"
                ></path>
                <path
                  d="M69.8191 2.8338C69.8191 1.4862 70.3106 1.09814 71.3501 1.09814C72.4132 1.09814 72.8812 1.54734 72.8812 2.8338C72.8812 4.22373 72.4108 4.57181 71.3501 4.57181C70.3106 4.56945 69.8191 4.22138 69.8191 2.8338ZM69.9837 6.03935H72.6789V18.5629H69.9837V6.03935Z"
                  style="fill: white"
                ></path>
                <path
                  d="M81.891 6.03955V18.5631H79.6849L79.4403 17.032H79.3792C78.7466 18.2573 77.827 18.7677 76.684 18.7677C75.0095 18.7677 74.2522 17.7046 74.2522 15.3975V6.0419H77.0697V15.2352C77.0697 16.3382 77.3002 16.7874 77.867 16.7874C78.3844 16.7663 78.8477 16.4582 79.0688 15.9902V6.0419H81.891V6.03955Z"
                  style="fill: white"
                ></path>
                <path
                  d="M96.1901 9.09893V18.5557H93.3726V9.30825C93.3726 8.28755 93.1068 7.7772 92.493 7.7772C92.0015 7.7772 91.5523 8.06177 91.2465 8.59329C91.263 8.76027 91.2701 8.9296 91.2677 9.09893V18.5557H88.4502V9.30825C88.4502 8.28755 88.1845 7.7772 87.5706 7.7772C87.0791 7.7772 86.6487 8.06177 86.3453 8.57447V18.5627H83.5278V6.0392H85.7527L85.9973 7.63139H86.0372C86.6699 6.42725 87.6929 5.77344 88.8971 5.77344C90.0824 5.77344 90.755 6.3661 91.0631 7.42913C91.7169 6.34729 92.6976 5.77344 93.8194 5.77344C95.541 5.77579 96.1901 7.0011 96.1901 9.09893Z"
                  style="fill: white"
                ></path>
                <path
                  d="M40.0566 6.34524V7.03668C40.0566 10.4915 38.5255 12.5118 35.1742 12.5118H34.6638V18.5583H31.9263V1.42285H35.414C38.6078 1.42285 40.0566 2.7728 40.0566 6.34524ZM37.1779 6.59218C37.1779 4.09924 36.7287 3.50658 35.1765 3.50658H34.6662V10.4727H35.1365C36.6064 10.4727 37.1803 9.40968 37.1803 7.10253L37.1779 6.59218Z"
                  style="fill: white"
                ></path>
              </g>
            </svg>
          </svg>
        </button>
      </div>

      <div
        class="navbutton flex items-center p-3 mt-5 transition-all duration-500 rounded-2xl ml-6 w-5/6"
        style="background-color: #3c3c3d"
      >
        <button class="flex gap-6 items-center">
          <svg
            xmlns="http://www.w3.org/2000/svg"
            enable-background="new 0 0 24 24"
            height="24"
            viewBox="0 0 24 24"
            width="24"
            focusable="false"
            style="
              pointer-events: none;
              display: block;
              width: 24px;
              height: 24px;
              fill: white;
            "
          >
            <g><path d="M4 21V10.08l8-6.96 8 6.96V21h-6v-6h-4v6H4z"></path></g>
          </svg>
          <p class="">Home Page</p>
        </button>
      </div>
      <div
        class="navbutton flex items-center p-3 transition-all duration-500 rounded-2xl ml-6 w-5/6"
      >
        <button class="flex gap-6 items-center">
          <svg
            xmlns="http://www.w3.org/2000/svg"
            height="24"
            viewBox="0 0 24 24"
            width="24"
            focusable="false"
            style="
              pointer-events: none;
              display: block;
              width: 24px;
              height: 24px;
              fill: white;
            "
          >
            <path
              d="M10 14.65v-5.3L15 12l-5 2.65zm7.77-4.33-1.2-.5L18 9.06c1.84-.96 2.53-3.23 1.56-5.06s-3.24-2.53-5.07-1.56L6 6.94c-1.29.68-2.07 2.04-2 3.49.07 1.42.93 2.67 2.22 3.25.03.01 1.2.5 1.2.5L6 14.93c-1.83.97-2.53 3.24-1.56 5.07.97 1.83 3.24 2.53 5.07 1.56l8.5-4.5c1.29-.68 2.06-2.04 1.99-3.49-.07-1.42-.94-2.68-2.23-3.25zm-.23 5.86-8.5 4.5c-1.34.71-3.01.2-3.72-1.14-.71-1.34-.2-3.01 1.14-3.72l2.04-1.08v-1.21l-.69-.28-1.11-.46c-.99-.41-1.65-1.35-1.7-2.41-.05-1.06.52-2.06 1.46-2.56l8.5-4.5c1.34-.71 3.01-.2 3.72 1.14.71 1.34.2 3.01-1.14 3.72L15.5 9.26v1.21l1.8.74c.99.41 1.65 1.35 1.7 2.41.05 1.06-.52 2.06-1.46 2.56z"
            ></path>
          </svg>
          <p class="">Shorts</p>
        </button>
      </div>
      <div
        class="navbutton flex items-center p-3 transition-all duration-500 rounded-2xl ml-6 w-5/6"
      >
        <button class="flex gap-6 items-center">
          <svg
            xmlns="http://www.w3.org/2000/svg"
            enable-background="new 0 0 24 24"
            height="24"
            viewBox="0 0 24 24"
            width="24"
            focusable="false"
            style="
              pointer-events: none;
              display: block;
              width: 24px;
              height: 24px;
              fill: white;
            "
          >
            <path
              d="M10 18v-6l5 3-5 3zm7-15H7v1h10V3zm3 3H4v1h16V6zm2 3H2v12h20V9zM3 10h18v10H3V10z"
            ></path>
          </svg>
          <p class="">Subscriptions</p>
        </button>
      </div>
      <div
        class="navbutton flex items-center p-3 transition-all duration-500 rounded-2xl ml-6 w-5/6"
      >
        <button class="flex gap-6 items-center">
          <svg
            xmlns="http://www.w3.org/2000/svg"
            height="24"
            viewBox="0 0 24 24"
            width="24"
            focusable="false"
            style="
              pointer-events: none;
              display: block;
              width: 24px;
              height: 24px;
              fill: white;
            "
          >
            <path
              d="M10 9.35 15 12l-5 2.65zM12 7a5 5 0 105 5 5 5 0 00-5-5m0-1a6 6 0 11-6 6 6 6 0 016-6zm0-3a9 9 0 109 9 9 9 0 00-9-9m0-1A10 10 0 112 12 10 10 0 0112 2z"
            ></path>
          </svg>
          <p class="">YouTube Music</p>
        </button>
      </div>
      <div class="line bg-gray-300 ml-4 mt-4 w-5/6"></div>
      <div
        class="navbutton flex items-center p-3 transition-all duration-500 rounded-2xl ml-6 mt-2 w-5/6"
      >
        <button class="flex items-center">
          <p class="mr-2">You</p>
          <svg
            xmlns="http://www.w3.org/2000/svg"
            height="16"
            viewBox="0 0 16 16"
            width="16"
            focusable="false"
            style="
              pointer-events: none;
              display: block;
              width: 20px;
              height: 20px;
              fill: white;
            "
          >
            <path
              d="M4.97 12.65 9.62 8 4.97 3.35l.71-.71L11.03 8l-5.35 5.35-.71-.7z"
            ></path>
          </svg>
        </button>
      </div>
      <div
        class="navbutton flex items-center p-3 transition-all duration-500 rounded-2xl ml-6 w-5/6"
      >
        <button class="flex gap-6 items-center">
          <svg
            xmlns="http://www.w3.org/2000/svg"
            viewBox="0 0 24 24"
            focusable="false"
            style="
              pointer-events: none;
              display: block;
              width: 24px;
              height: 24px;
              fill: white;
            "
          >
            <path
              d="M3,3v18h18V3H3z M4.99,20c0.39-2.62,2.38-5.1,7.01-5.1s6.62,2.48,7.01,5.1H4.99z M9,10c0-1.65,1.35-3,3-3s3,1.35,3,3 c0,1.65-1.35,3-3,3S9,11.65,9,10z M12.72,13.93C14.58,13.59,16,11.96,16,10c0-2.21-1.79-4-4-4c-2.21,0-4,1.79-4,4 c0,1.96,1.42,3.59,3.28,3.93c-4.42,0.25-6.84,2.8-7.28,6V4h16v15.93C19.56,16.73,17.14,14.18,12.72,13.93z"
            ></path>
          </svg>
          <p class="">Your Channel</p>
        </button>
      </div>
      <div
        class="navbutton flex items-center p-3 transition-all duration-500 rounded-2xl ml-6 w-5/6"
      >
        <button class="flex gap-6 items-center">
          <svg
            xmlns="http://www.w3.org/2000/svg"
            height="24"
            style="
              pointer-events: none;
              display: block;
              width: 24px;
              height: 24px;
              fill: white;
            "
            viewBox="0 0 24 24"
            width="24"
            focusable="false"
          >
            <g>
              <path
                d="M14.97 16.95 10 13.87V7h2v5.76l4.03 2.49-1.06 1.7zM22 12c0 5.51-4.49 10-10 10S2 17.51 2 12h1c0 4.96 4.04 9 9 9s9-4.04 9-9-4.04-9-9-9C8.81 3 5.92 4.64 4.28 7.38c-.11.18-.22.37-.31.56L3.94 8H8v1H1.96V3h1v4.74c.04-.09.07-.17.11-.25.11-.22.23-.42.35-.63C5.22 3.86 8.51 2 12 2c5.51 0 10 4.49 10 10z"
              ></path>
            </g>
          </svg>
          <p class="">Recent</p>
        </button>
      </div>
      <div
        class="navbutton flex items-center p-3 transition-all duration-500 rounded-2xl ml-6 w-5/6"
      >
        <button class="flex gap-6 items-center">
          <svg
            xmlns="http://www.w3.org/2000/svg"
            enable-background="new 0 0 24 24"
            height="24"
            viewBox="0 0 24 24"
            width="24"
            focusable="false"
            style="
              pointer-events: none;
              display: block;
              width: 24px;
              height: 24px;
              fill: white;
            "
          >
            <path d="m10 8 6 4-6 4V8zm11-5v18H3V3h18zm-1 1H4v16h16V4z"></path>
          </svg>
          <p class="">Your Videos</p>
        </button>
      </div>
      <div
        class="navbutton flex items-center p-3 transition-all duration-500 rounded-2xl ml-6 w-5/6"
      >
        <button class="flex gap-6 items-center">
          <svg
            xmlns="http://www.w3.org/2000/svg"
            height="24"
            viewBox="0 0 24 24"
            width="24"
            focusable="false"
            style="
              pointer-events: none;
              display: block;
              width: 24px;
              height: 24px;
              fill: white;
            "
          >
            <path
              d="M14.97 16.95 10 13.87V7h2v5.76l4.03 2.49-1.06 1.7zM12 3c-4.96 0-9 4.04-9 9s4.04 9 9 9 9-4.04 9-9-4.04-9-9-9m0-1c5.52 0 10 4.48 10 10s-4.48 10-10 10S2 17.52 2 12 6.48 2 12 2z"
            ></path>
          </svg>
          <p class="">Watch Later</p>
        </button>
      </div>
      <div
        class="navbutton flex items-center p-3 transition-all duration-500 rounded-2xl ml-6 w-5/6"
      >
        <button class="flex gap-6 items-center">
          <svg
            xmlns="http://www.w3.org/2000/svg"
            height="24"
            viewBox="0 0 24 24"
            width="24"
            focusable="false"
            style="
              pointer-events: none;
              display: block;
              width: 24px;
              height: 24px;
              fill: white;
            "
          >
            <path
              d="M17 18v1H6v-1h11zm-.5-6.6-.7-.7-3.8 3.7V4h-1v10.4l-3.8-3.8-.7.7 5 5 5-4.9z"
            ></path>
          </svg>
          <p class="">Downloads</p>
        </button>
      </div>
      <div
        class="navbutton flex items-center p-3 transition-all duration-500 rounded-2xl ml-6"
      >
        <button class="flex gap-6 items-center">
          <svg
            xmlns="http://www.w3.org/2000/svg"
            height="24"
            viewBox="0 0 24 24"
            width="24"
            focusable="false"
            style="
              pointer-events: none;
              display: block;
              width: 24px;
              height: 24px;
              fill: white;
            "
          >
            <path
              d="m18 9.28-6.35 6.35-6.37-6.35.72-.71 5.64 5.65 5.65-5.65z"
            ></path>
          </svg>
          <p class="">Show More</p>
        </button>
      </div>
      <div class="line bg-gray-300 ml-4 mt-4 w-5/6"></div>
      <div
        class="flex items-center p-3 transition-all duration-500 rounded-2xl ml-6 w-5/6"
      >
        <p class="font-bold">Subscriptions</p>
      </div>
      <div
        class="navbutton flex items-center p-3 transition-all duration-500 rounded-2xl ml-6 w-5/6"
      >
        <button class="flex gap-6 items-center">
          <img
            id="img"
            draggable="false"
            class="style-scope yt-img-shadow rounded-full"
            height="24"
            width="24"
            alt=""
            src="https://yt3.ggpht.com/t1gVF0UZb3h6E7KH8ElfWBJuPa5DO0szjSYG1lEXZjRKKLW_g2n8AbEmhPVeZV_Nfwgc8AfISsU=s88-c-k-c0x00ffffff-no-rj"
          />
          <p class="">FunWithGuru</p>
        </button>
      </div>
      <div
        class="navbutton flex items-center p-3 transition-all duration-500 rounded-2xl ml-6 w-5/6"
      >
        <button class="flex gap-6 items-center">
          <img
            id="img"
            draggable="false"
            class="style-scope yt-img-shadow rounded-full"
            height="24"
            width="24"
            alt=""
            src="https://yt3.ggpht.com/nDTo1trLwi1nZPTqS4RjsuC1B2V920Z9jQvrwrlOWqmALdQWLK0FD-OTh2U9o49-16hHrD3N=s88-c-k-c0x00ffffff-no-rj"
          />
          <p class="">videogamedunkey</p>
        </button>
      </div>
      <div
        class="navbutton flex items-center p-3 transition-all duration-500 rounded-2xl ml-6 w-5/6"
      >
        <button class="flex gap-6 items-center">
          <img
            id="img"
            draggable="false"
            class="style-scope yt-img-shadow rounded-full"
            height="24"
            width="24"
            alt=""
            src="https://yt3.ggpht.com/ytc/AIf8zZTDkajQxPa4sjDOW-c3er1szXkSAO-H9TiF4-8u_Q=s88-c-k-c0x00ffffff-no-rj"
          />
          <p class="">freeCodeCamp.org</p>
        </button>
      </div>
      <div
        class="navbutton flex items-center p-3 transition-all duration-500 rounded-2xl ml-6 w-5/6"
      >
        <button class="flex gap-6 items-center">
          <img
            id="img"
            draggable="false"
            class="style-scope yt-img-shadow rounded-full"
            height="24"
            width="24"
            alt=""
            src="https://yt3.ggpht.com/6pw8YF3c0ZGAYzPfEe6ZoUO0yxoa5_ymOSB1_-dkgvS1WWWM3PmRwHV_JK6dLdpJzypGnh3qeQ=s88-c-k-c0x00ffffff-no-rj"
          />
          <p class="">BBC Learning En...</p>
        </button>
      </div>
      <div
        class="navbutton flex items-center p-3 transition-all duration-500 rounded-2xl ml-6 w-5/6"
      >
        <button class="flex gap-6 items-center">
          <img
            id="img"
            draggable="false"
            class="style-scope yt-img-shadow rounded-full"
            height="24"
            width="24"
            alt=""
            src="https://yt3.ggpht.com/a6xDscSdwtQRbBTSVtAqSvdqWWvTjTrWxRqfp4QpyehurIc0-hQY6PB96trHEPb6zVB7fZG4Hc4=s88-c-k-c0x00ffffff-no-rj"
          />
          <p class="">World Table Tennis</p>
        </button>
      </div>
      <div
        class="navbutton flex items-center p-3 transition-all duration-500 rounded-2xl ml-6 w-5/6"
      >
        <button class="flex gap-6 items-center">
          <svg
            xmlns="http://www.w3.org/2000/svg"
            height="24"
            viewBox="0 0 24 24"
            width="24"
            focusable="false"
            style="
              pointer-events: none;
              display: block;
              width: 24px;
              height: 24px;
              fill: white;
            "
          >
            <path
              d="m18 9.28-6.35 6.35-6.37-6.35.72-.71 5.64 5.65 5.65-5.65z"
            ></path>
          </svg>
          <p class="">Show More</p>
        </button>
      </div>
      <div class="line bg-gray-300 ml-4 mt-4 w-5/6"></div>
      <div
        class="flex items-center p-3 transition-all duration-500 rounded-2xl ml-6 w-5/6"
      >
        <p class="font-bold">Explore</p>
      </div>
      <div
        class="navbutton flex items-center p-3 transition-all duration-500 rounded-2xl ml-6 w-5/6"
      >
        <button class="flex gap-6 items-center">
          <svg
            xmlns="http://www.w3.org/2000/svg"
            enable-background="new 0 0 24 24"
            height="24"
            viewBox="0 0 24 24"
            width="24"
            focusable="false"
            style="
              pointer-events: none;
              display: block;
              width: 24px;
              height: 24px;
              fill: white;
            "
          >
            <path
              d="M19 3.87v9.77C19 17.7 15.86 21 12 21s-7-3.3-7-7.37v-.13c0-1.06.22-2.13.62-3.09.5-1.19 1.29-2.21 2.27-2.97.85-.66 1.83-1.14 2.87-1.65.39-.19.77-.38 1.15-.58.36-.19.72-.38 1.08-.56v3.22l1.55-1.04L19 3.87M20 2l-6 4V3c-.85.44-1.7.88-2.55 1.33-1.41.74-2.9 1.34-4.17 2.32-1.13.87-2.02 2.05-2.58 3.37-.46 1.09-.7 2.29-.7 3.48v.14C4 18.26 7.58 22 12 22s8-3.74 8-8.36V2zM9.45 12.89 14 10v5.7c0 1.82-1.34 3.3-3 3.3s-3-1.47-3-3.3c0-1.19.58-2.23 1.45-2.81z"
            ></path>
          </svg>
          <p class="">Trends</p>
        </button>
      </div>
      <div
        class="navbutton flex items-center p-3 transition-all duration-500 rounded-2xl ml-6 w-5/6"
      >
        <button class="flex gap-6 items-center">
          <svg
            xmlns="http://www.w3.org/2000/svg"
            enable-background="new 0 0 24 24"
            height="24"
            viewBox="0 0 24 24"
            width="24"
            focusable="false"
            style="
              pointer-events: none;
              display: block;
              width: 24px;
              height: 24px;
              fill: white;
            "
          >
            <path
              d="M12 4v9.38c-.73-.84-1.8-1.38-3-1.38-2.21 0-4 1.79-4 4s1.79 4 4 4 4-1.79 4-4V8h6V4h-7zM9 19c-1.66 0-3-1.34-3-3s1.34-3 3-3 3 1.34 3 3-1.34 3-3 3zm9-12h-5V5h5v2z"
            ></path>
          </svg>
          <p class="">Music</p>
        </button>
      </div>
      <div
        class="navbutton flex items-center p-3 transition-all duration-500 rounded-2xl ml-6 w-5/6"
      >
        <button class="flex gap-6 items-center">
          <svg
            xmlns="http://www.w3.org/2000/svg"
            enable-background="new 0 0 24 24"
            height="24"
            viewBox="0 0 24 24"
            width="24"
            focusable="false"
            style="
              pointer-events: none;
              display: block;
              width: 24px;
              height: 24px;
              fill: white;
            "
          >
            <g>
              <path
                d="M14 12c0 1.1-.9 2-2 2s-2-.9-2-2 .9-2 2-2 2 .9 2 2zM8.48 8.45l-.71-.7C6.68 8.83 6 10.34 6 12s.68 3.17 1.77 4.25l.71-.71C7.57 14.64 7 13.39 7 12s.57-2.64 1.48-3.55zm7.75-.7-.71.71c.91.9 1.48 2.15 1.48 3.54s-.57 2.64-1.48 3.55l.71.71C17.32 15.17 18 13.66 18 12s-.68-3.17-1.77-4.25zM5.65 5.63l-.7-.71C3.13 6.73 2 9.24 2 12s1.13 5.27 2.95 7.08l.71-.71C4.02 16.74 3 14.49 3 12s1.02-4.74 2.65-6.37zm13.4-.71-.71.71C19.98 7.26 21 9.51 21 12s-1.02 4.74-2.65 6.37l.71.71C20.87 17.27 22 14.76 22 12s-1.13-5.27-2.95-7.08z"
              ></path>
            </g>
          </svg>
          <p class="">Live</p>
        </button>
      </div>
      <div
        class="navbutton flex items-center p-3 transition-all duration-500 rounded-2xl ml-6 w-5/6"
      >
        <button class="flex gap-6 items-center">
          <svg
            xmlns="http://www.w3.org/2000/svg"
            enable-background="new 0 0 24 24"
            height="24"
            viewBox="0 0 24 24"
            width="24"
            focusable="false"
            style="
              pointer-events: none;
              display: block;
              width: 24px;
              height: 24px;
              fill: white;
            "
          >
            <path
              d="M10 12H8v2H6v-2H4v-2h2V8h2v2h2v2zm7 .5c0-.83-.67-1.5-1.5-1.5s-1.5.67-1.5 1.5.67 1.5 1.5 1.5 1.5-.67 1.5-1.5zm3-3c0-.83-.67-1.5-1.5-1.5S17 8.67 17 9.5s.67 1.5 1.5 1.5 1.5-.67 1.5-1.5zm-3.03-4.35-4.5 2.53-.49.27-.49-.27-4.5-2.53L3 7.39v6.43l8.98 5.04 8.98-5.04V7.39l-3.99-2.24m0-1.15 4.99 2.8v7.6L11.98 20 2 14.4V6.8L6.99 4l4.99 2.8L16.97 4z"
            ></path>
          </svg>
          <p class="">Game</p>
        </button>
      </div>
      <div
        class="navbutton flex items-center p-3 transition-all duration-500 rounded-2xl ml-6 w-5/6"
      >
        <button class="flex gap-6 items-center">
          <svg
            xmlns="http://www.w3.org/2000/svg"
            height="24"
            viewBox="0 0 24 24"
            width="24"
            focusable="false"
            style="
              pointer-events: none;
              display: block;
              width: 24px;
              height: 24px;
              fill: white;
            "
          >
            <path
              d="M18 5V2H6v3H3v6l3.23 1.61c.7 2.5 2.97 4.34 5.69 4.38L8 19v3h8v-3l-3.92-2.01c2.72-.04 4.99-1.88 5.69-4.38L21 11V5h-3zM6 11.38l-2-1V6h2v5.38zM15 21H9v-1.39l3-1.54 3 1.54V21zm2-10c0 2.76-2.24 5-5 5s-5-2.24-5-5V3h10v8zm3-.62-2 1V6h2v4.38z"
            ></path>
          </svg>
          <p class="">Sports</p>
        </button>
      </div>
      <div
        class="navbutton flex items-center p-3 transition-all duration-500 rounded-2xl ml-6 w-5/6"
      >
        <button class="flex gap-6 items-center">
          <svg
            xmlns="http://www.w3.org/2000/svg"
            enable-background="new 0 0 24 24"
            height="24"
            viewBox="0 0 24 24"
            width="24"
            focusable="false"
            style="
              pointer-events: none;
              display: block;
              width: 24px;
              height: 24px;
              fill: white;
            "
          >
            <path
              d="M7.5 3.63c-.01.07-.01.14-.02.22-.01.06-.02.11-.03.16-.01.05-.02.1-.04.15-.01.04-.02.09-.04.13-.02.05-.04.09-.06.14-.07.15-.15.28-.25.41-.11.15-.24.29-.37.42-.14.14-.28.27-.43.39-.13.12-.27.23-.4.35-.15.14-.31.28-.46.42-.12.11-.24.23-.35.36-.1.1-.19.21-.27.32-.09.11-.17.22-.25.33-.01.01-.02.02-.02.03-.01.02-.02.01-.03 0-.02-.03-.05-.06-.07-.1-.06-.07-.12-.15-.18-.23-.13-.17-.28-.33-.44-.49-.1-.1-.21-.21-.32-.3l-.6-.54-.3-.27-.37-.34c-.1-.09-.19-.2-.27-.31-.06-.08-.11-.16-.16-.25-.04-.08-.07-.16-.11-.24-.03-.07-.05-.13-.07-.2-.02-.04-.03-.09-.04-.14l-.03-.13c0-.02-.01-.05-.01-.08-.01-.1-.02-.21-.01-.31.01-.06.01-.12.02-.18 0-.04.01-.07.02-.11.01-.05.03-.11.05-.16.03-.08.06-.15.09-.22.05-.09.1-.18.16-.26.1-.12.22-.23.35-.32.1-.06.2-.12.31-.16.08-.02.15-.05.22-.07.16-.04.33-.06.5-.05.08 0 .15.01.23.03.05.01.11.02.16.04.06.02.12.04.18.07.09.04.18.09.27.15.11.07.21.16.29.25.04.05.09.1.13.15.01.02.02.02.03 0 .05-.05.09-.11.14-.16.08-.09.18-.18.28-.24.07-.05.14-.09.22-.13.06-.03.12-.05.19-.07l.18-.06c.03-.01.07-.01.1-.01.06-.01.12-.01.18-.02.07 0 .14 0 .2.01.05 0 .09.01.14.01.02 0 .04.01.06.01.05.01.11.03.16.04l.15.06c.07.04.14.07.2.1.1.06.19.13.28.21.06.06.12.12.17.19.05.06.09.13.13.19.03.05.06.11.08.16.03.05.04.11.06.17.01.03.02.07.03.11 0 .02.01.04.01.06 0 .03.01.07.01.1.01.06.01.13.02.21zm7.05 9.87v-3L12 9l-2.55 1.5v3L12 15l2.55-1.5zm8.2 5.5L21 17h-3l-1.75 2 3.25 3 3.25-3zm-3.25-8.5c.83 0 1.5.67 1.5 1.5s-.67 1.5-1.5 1.5S18 12.83 18 12s.67-1.5 1.5-1.5m0-1c-1.38 0-2.5 1.12-2.5 2.5s1.12 2.5 2.5 2.5S22 13.38 22 12s-1.12-2.5-2.5-2.5zm0-6.5c.83 0 1.5.67 1.5 1.5S20.33 6 19.5 6 18 5.33 18 4.5 18.67 3 19.5 3m0-1C18.12 2 17 3.12 17 4.5S18.12 7 19.5 7 22 5.88 22 4.5 20.88 2 19.5 2zm-15 16c.83 0 1.5.67 1.5 1.5S5.33 21 4.5 21 3 20.33 3 19.5 3.67 18 4.5 18m0-1C3.12 17 2 18.12 2 19.5S3.12 22 4.5 22 7 20.88 7 19.5 5.88 17 4.5 17zM12 3c.83 0 1.5.67 1.5 1.5S12.83 6 12 6s-1.5-.67-1.5-1.5S11.17 3 12 3m0-1c-1.38 0-2.5 1.12-2.5 2.5S10.62 7 12 7s2.5-1.12 2.5-2.5S13.38 2 12 2zm0 16c.83 0 1.5.67 1.5 1.5S12.83 21 12 21s-1.5-.67-1.5-1.5.67-1.5 1.5-1.5m0-1c-1.38 0-2.5 1.12-2.5 2.5S10.62 22 12 22s2.5-1.12 2.5-2.5S13.38 17 12 17zm-7.5-6.5c.83 0 1.5.67 1.5 1.5s-.67 1.5-1.5 1.5S3 12.83 3 12s.67-1.5 1.5-1.5m0-1C3.12 9.5 2 10.62 2 12s1.12 2.5 2.5 2.5S7 13.38 7 12 5.88 9.5 4.5 9.5z"
            ></path>
          </svg>
          <p class="">Playable Games</p>
        </button>
      </div>
      <div class="line bg-gray-300 ml-4 mt-4 w-5/6"></div>
      <div
        class="flex items-center p-3 transition-all duration-500 rounded-2xl ml-6 w-5/6"
      >
        <p class="font-bold">More From Youtube...</p>
      </div>
      <div
        class="navbutton flex items-center p-3 transition-all duration-500 rounded-2xl ml-6 w-5/6"
      >
        <button class="flex gap-6 items-center">
          <svg
            xmlns="http://www.w3.org/2000/svg"
            viewBox="0 0 24 24"
            focusable="false"
            style="
              pointer-events: none;
              display: block;
              width: 24px;
              height: 24px;
            "
          >
            <path
              fill="red"
              d="M11.13 1.21c.48-.28 1.26-.28 1.74 0l8.01 4.64c.48.28.87.97.87 1.53v9.24c0 .56-.39 1.25-.87 1.53l-8.01 4.64c-.48.28-1.26.28-1.74 0l-8.01-4.64c-.48-.28-.87-.97-.87-1.53V7.38c0-.56.39-1.25.87-1.53l8.01-4.64z"
            ></path>
            <path
              fill="#fff"
              d="m12.71 18.98 4.9-2.83c.41-.24.64-.77.64-1.24V9.24c0-.47-.23-1-.64-1.24l-4.9-2.82c-.41-.23-1.02-.23-1.42 0L6.39 8c-.4.23-.64.77-.64 1.24v5.67c0 .47.24 1 .64 1.24l4.9 2.83c.2.12.46.18.71.18.26-.01.51-.07.71-.18z"
            ></path>
            <path
              fill="red"
              d="m12.32 5.73 4.89 2.83c.16.09.41.31.41.67v5.67c0 .37-.25.54-.41.64l-4.89 2.83c-.16.09-.48.09-.64 0l-4.89-2.83c-.16-.09-.41-.34-.41-.64V9.24c.02-.37.25-.58.41-.68l4.89-2.83c.08-.05.2-.07.32-.07s.24.02.32.07z"
            ></path>
            <path fill="#fff" d="M9.88 15.25 15.5 12 9.88 8.75z"></path>
          </svg>
          <p class="">Youtube Studio</p>
        </button>
      </div>
      <div
        class="navbutton flex items-center p-3 transition-all duration-500 rounded-2xl ml-6 w-5/6"
      >
        <button class="flex gap-6 items-center">
          <svg
            xmlns="http://www.w3.org/2000/svg"
            viewBox="0 0 24 24"
            focusable="false"
            style="
              pointer-events: none;
              display: block;
              width: 24px;
              height: 24px;
            "
          >
            <circle fill="#FF0000" cx="12" cy="12" r="10"></circle>
            <polygon fill="#FFFFFF" points="10,14.65 10,9.35 15,12 "></polygon>
            <path
              fill="#FFFFFF"
              d="M12,7c2.76,0,5,2.24,5,5s-2.24,5-5,5s-5-2.24-5-5S9.24,7,12,7 M12,6c-3.31,0-6,2.69-6,6s2.69,6,6,6s6-2.69,6-6 S15.31,6,12,6L12,6z"
            ></path>
          </svg>
          <p class="">Youtube Music</p>
        </button>
      </div>
      <div
        class="navbutton flex items-center p-3 transition-all duration-500 rounded-2xl ml-6 w-5/6"
      >
        <button class="flex gap-6 items-center">
          <svg
            xmlns="http://www.w3.org/2000/svg"
            viewBox="0 0 24 24"
            focusable="false"
            style="
              pointer-events: none;
              display: block;
              width: 24px;
              height: 24px;
            "
          >
            <path
              fill="#FF0000"
              d="M21.39,13.19c0-0.08,0-0.15,0-0.22c-0.01-0.86-0.5-5-0.78-5.74c-0.32-0.85-0.76-1.5-1.31-1.91 c-0.9-0.67-1.66-0.82-2.6-0.84l-0.02,0c-0.4,0-3.01,0.32-5.2,0.62C9.28,5.4,6.53,5.8,5.88,6.04c-0.9,0.33-1.62,0.77-2.19,1.33 c-1.05,1.04-1.18,2.11-1.04,3.51c0.1,1.09,0.69,5.37,1.02,6.35c0.45,1.32,1.33,2.12,2.47,2.24c0.28,0.03,0.55,0.05,0.82,0.05 c1,0,1.8-0.21,2.72-0.46c1.45-0.39,3.25-0.87,6.97-0.87l0.09,0h0.02c0.91,0,3.14-0.2,4.16-2.07C21.44,15.12,21.41,13.91,21.39,13.19 z"
            ></path>
            <path
              fill="#000"
              d="M21.99,13.26c0-0.08,0-0.16-0.01-0.24c-0.01-0.92-0.54-5.32-0.83-6.11c-0.34-0.91-0.81-1.59-1.4-2.03 C18.81,4.17,17.99,4.02,17,4l-0.02,0c-0.43,0-3.21,0.34-5.54,0.66c-2.33,0.32-5.25,0.75-5.95,1C4.53,6.01,3.76,6.48,3.16,7.08 c-1.12,1.1-1.25,2.25-1.11,3.74c0.11,1.16,0.73,5.71,1.08,6.75c0.48,1.41,1.41,2.25,2.63,2.38C6.06,19.98,6.34,20,6.63,20 c1.07,0,1.91-0.23,2.89-0.49c1.54-0.41,3.46-0.93,7.41-0.93l0.1,0h0.02c0.97,0,3.34-0.21,4.42-2.2 C22.04,15.32,22.01,14.03,21.99,13.26z M20.59,15.91c-0.82,1.51-2.75,1.68-3.56,1.68l-0.1,0c-4.09,0-6.07,0.53-7.67,0.96 C8.31,18.8,7.56,19,6.63,19c-0.25,0-0.5-0.01-0.76-0.04c-1.04-0.11-1.54-0.99-1.79-1.71c-0.3-0.88-0.91-5.21-1.04-6.53 C2.9,9.25,3.1,8.54,3.86,7.79c0.5-0.5,1.15-0.89,1.97-1.19c0.17-0.06,1.1-0.32,5.74-0.95C14.2,5.29,16.64,5.01,16.99,5 c0.83,0.02,1.43,0.13,2.17,0.69c0.43,0.32,0.79,0.86,1.06,1.58c0.22,0.58,0.76,4.78,0.77,5.77l0.01,0.25 C21.01,13.96,21.04,15.08,20.59,15.91z"
            ></path>
            <path
              fill="#000"
              d="M11.59,14.76c-0.48,0.36-0.8,0.45-1.01,0.45c-0.16,0-0.25-0.05-0.3-0.08c-0.34-0.18-0.42-0.61-0.5-1.2l-0.01-0.1 c-0.04-0.31-0.26-2.1-0.38-3.16L9.3,9.94C9.26,9.66,9.2,9.19,9.54,8.94c0.32-0.23,0.75-0.09,0.96-0.03c0.53,0.17,3.6,1.23,4.59,1.73 c0.21,0.09,0.67,0.28,0.68,0.83c0.01,0.5-0.38,0.74-0.53,0.82L11.59,14.76z"
            ></path>
            <path
              fill="#FFF"
              d="M10.3,9.89c0,0,0.5,4.08,0.51,4.19c0.06-0.04,3.79-2.58,3.79-2.58C13.71,11.07,11.07,10.14,10.3,9.89z"
            ></path>
          </svg>
          <p class="">Youtube Kids</p>
        </button>
      </div>
      <div class="line bg-gray-300 ml-4 mt-4 mb-2 w-5/6"></div>
      <div
        class="navbutton flex items-center p-3 transition-all duration-500 rounded-2xl ml-6 w-5/6"
      >
        <button class="flex gap-6 items-center">
          <svg
            xmlns="http://www.w3.org/2000/svg"
            enable-background="new 0 0 24 24"
            height="24"
            viewBox="0 0 24 24"
            width="24"
            focusable="false"
            style="
              pointer-events: none;
              display: block;
              width: 24px;
              height: 24px;
              fill: white;
            "
          >
            <path
              d="M12 9.5c1.38 0 2.5 1.12 2.5 2.5s-1.12 2.5-2.5 2.5-2.5-1.12-2.5-2.5 1.12-2.5 2.5-2.5m0-1c-1.93 0-3.5 1.57-3.5 3.5s1.57 3.5 3.5 3.5 3.5-1.57 3.5-3.5-1.57-3.5-3.5-3.5zM13.22 3l.55 2.2.13.51.5.18c.61.23 1.19.56 1.72.98l.4.32.5-.14 2.17-.62 1.22 2.11-1.63 1.59-.37.36.08.51c.05.32.08.64.08.98s-.03.66-.08.98l-.08.51.37.36 1.63 1.59-1.22 2.11-2.17-.62-.5-.14-.4.32c-.53.43-1.11.76-1.72.98l-.5.18-.13.51-.55 2.24h-2.44l-.55-2.2-.13-.51-.5-.18c-.6-.23-1.18-.56-1.72-.99l-.4-.32-.5.14-2.17.62-1.21-2.12 1.63-1.59.37-.36-.08-.51c-.05-.32-.08-.65-.08-.98s.03-.66.08-.98l.08-.51-.37-.36L3.6 8.56l1.22-2.11 2.17.62.5.14.4-.32c.53-.44 1.11-.77 1.72-.99l.5-.18.13-.51.54-2.21h2.44M14 2h-4l-.74 2.96c-.73.27-1.4.66-2 1.14l-2.92-.83-2 3.46 2.19 2.13c-.06.37-.09.75-.09 1.14s.03.77.09 1.14l-2.19 2.13 2 3.46 2.92-.83c.6.48 1.27.87 2 1.14L10 22h4l.74-2.96c.73-.27 1.4-.66 2-1.14l2.92.83 2-3.46-2.19-2.13c.06-.37.09-.75.09-1.14s-.03-.77-.09-1.14l2.19-2.13-2-3.46-2.92.83c-.6-.48-1.27-.87-2-1.14L14 2z"
            ></path>
          </svg>
          <p class="">Settings</p>
        </button>
      </div>
      <div
        class="navbutton flex items-center p-3 transition-all duration-500 rounded-2xl ml-6 w-5/6"
      >
        <button class="flex gap-6 items-center">
          <svg
            xmlns="http://www.w3.org/2000/svg"
            enable-background="new 0 0 24 24"
            height="24"
            viewBox="0 0 24 24"
            width="24"
            focusable="false"
            style="
              pointer-events: none;
              display: block;
              width: 24px;
              height: 24px;
              fill: white;
            "
          >
            <path
              d="m13.18 4 .24 1.2.16.8H19v7h-5.18l-.24-1.2-.16-.8H6V4h7.18M14 3H5v18h1v-9h6.6l.4 2h7V5h-5.6L14 3z"
            ></path>
          </svg>
          <p class="">Content Report...</p>
        </button>
      </div>
      <div
        class="navbutton flex items-center p-3 transition-all duration-500 rounded-2xl ml-6 w-5/6"
      >
        <button class="flex gap-6 items-center">
          <svg
            xmlns="http://www.w3.org/2000/svg"
            enable-background="new 0 0 24 24"
            height="24"
            viewBox="0 0 24 24"
            width="24"
            focusable="false"
            style="
              pointer-events: none;
              display: block;
              width: 24px;
              height: 24px;
              fill: white;
            "
          >
            <path
              d="M15.36 9.96c0 1.09-.67 1.67-1.31 2.24-.53.47-1.03.9-1.16 1.6l-.04.2H11.1l.03-.28c.14-1.17.8-1.76 1.47-2.27.52-.4 1.01-.77 1.01-1.49 0-.51-.23-.97-.63-1.29-.4-.31-.92-.42-1.42-.29-.59.15-1.05.67-1.19 1.34l-.05.28H8.57l.06-.42c.2-1.4 1.15-2.53 2.42-2.87 1.05-.29 2.14-.08 2.98.57.85.64 1.33 1.62 1.33 2.68zM12 18c.55 0 1-.45 1-1s-.45-1-1-1-1 .45-1 1 .45 1 1 1zm0-15c-4.96 0-9 4.04-9 9s4.04 9 9 9 9-4.04 9-9-4.04-9-9-9m0-1c5.52 0 10 4.48 10 10s-4.48 10-10 10S2 17.52 2 12 6.48 2 12 2z"
            ></path>
          </svg>
          <p class="">Help</p>
        </button>
      </div>
      <div
        class="navbutton flex items-center p-3 transition-all duration-500 rounded-2xl ml-6 w-5/6"
      >
        <button class="flex gap-6 items-center">
          <svg
            xmlns="http://www.w3.org/2000/svg"
            enable-background="new 0 0 24 24"
            height="24"
            viewBox="0 0 24 24"
            width="24"
            focusable="false"
            style="
              pointer-events: none;
              display: block;
              width: 24px;
              height: 24px;
              fill: white;
            "
          >
            <path
              d="M13 14h-2v-2h2v2zm0-9h-2v6h2V5zm6-2H5v16.59l3.29-3.29.3-.3H19V3m1-1v15H9l-5 5V2h16z"
            ></path>
          </svg>
          <p class="">Send Feedback</p>
        </button>
      </div>
      <div class="line bg-gray-300 ml-4 mt-4 mb-2 w-5/6"></div>
      <div
        class="flex items-center p-3 transition-all duration-500 rounded-2xl ml-6 w-4/6 text-gray-400 text-sm"
      >
        © 2024 Rekl0w
      </div>
    </div>
  </div>
</template>

<style scoped>
.navbutton:hover {
  background-color: #3c3c3d;
  cursor: pointer;
}

.line {
  background-color: #3f3f3f;
  height: 1px;
}

.container::-webkit-scrollbar {
  width: 8px;
  background-color: transparent;
  border-radius: 20px;
}

.container:hover::-webkit-scrollbar-thumb {
  background-color: #888;
  border-radius: 20px;
  height: 60%;
}
</style>
