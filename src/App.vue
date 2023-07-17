<template>
  <div class="layout">
    <div class="top_header_v1">
      <div class="header-socialmedia">
        <div style="padding-right: 10px">
          language
          <svg
            height="20"
            width="20"
            viewBox="0 0 496 512"
            xmlns="http://www.w3.org/2000/svg"
            style="float: right; padding-left: 10px"
          >
            <path
              d="m336.5 160c-14.5-89.3-48.7-152-88.5-152s-74 62.7-88.5 152zm-184.5 96c0 22.2 1.2 43.5 3.3 64h185.3c2.1-20.5 3.3-41.8 3.3-64s-1.2-43.5-3.3-64h-185.3c-2.1 20.5-3.3 41.8-3.3 64zm324.7-96c-28.6-67.9-86.5-120.4-158-141.6 24.4 33.8 41.2 84.7 50 141.6zm-299.5-141.6c-71.4 21.2-129.4 73.7-157.9 141.6h108c8.7-56.9 25.5-107.8 49.9-141.6zm310.2 173.6h-114.7c2.1 21 3.3 42.5 3.3 64s-1.2 43-3.3 64h114.6c5.5-20.5 8.6-41.8 8.6-64s-3.1-43.5-8.5-64zm-367.4 64c0-21.5 1.2-43 3.3-64h-114.7c-5.4 20.5-8.6 41.8-8.6 64s3.2 43.5 8.6 64h114.6c-2-21-3.2-42.5-3.2-64zm39.5 96c14.5 89.3 48.7 152 88.5 152s74-62.7 88.5-152zm159.3 141.6c71.4-21.2 129.4-73.7 158-141.6h-108c-8.8 56.9-25.6 107.8-50 141.6zm-299.5-141.6c28.6 67.9 86.5 120.4 158 141.6-24.4-33.8-41.2-84.7-50-141.6z"
            />
          </svg>
        </div>

        <div style="padding-right: 10px">
          Currency
          <img
            src="src/assets/social-media-headers/coin.png"
            style="padding-left: 10px; height: auto; width: 20px"
          />
        </div>
        <div class="marginLeft">
          <!-- facebook -->
          <svg
            xmlns="http://www.w3.org/2000/svg"
            width="24"
            height="24"
            viewBox="0 0 24 24"
            fill="none"
            stroke="currentColor"
            stroke-width="2"
            stroke-linecap="round"
            stroke-linejoin="round"
            class="feather feather-facebook"
          >
            <path
              d="M18 2h-3a5 5 0 0 0-5 5v3H7v4h3v8h4v-8h3l1-4h-4V7a1 1 0 0 1 1-1h3z"
            ></path>
          </svg>
          <!-- instagram -->
          <svg
            xmlns="http://www.w3.org/2000/svg"
            width="24"
            height="24"
            viewBox="0 0 24 24"
            fill="none"
            stroke="currentColor"
            stroke-width="2"
            stroke-linecap="round"
            stroke-linejoin="round"
            class="feather feather-instagram"
          >
            <rect x="2" y="2" width="20" height="20" rx="5" ry="5"></rect>
            <path d="M16 11.37A4 4 0 1 1 12.63 8 4 4 0 0 1 16 11.37z"></path>
            <line x1="17.5" y1="6.5" x2="17.51" y2="6.5"></line>
          </svg>
          <!-- linkedin -->
          <svg
            xmlns="http://www.w3.org/2000/svg"
            width="24"
            height="24"
            viewBox="0 0 24 24"
            fill="none"
            stroke="currentColor"
            stroke-width="2"
            stroke-linecap="round"
            stroke-linejoin="round"
            class="feather feather-linkedin"
          >
            <path
              d="M16 8a6 6 0 0 1 6 6v7h-4v-7a2 2 0 0 0-2-2 2 2 0 0 0-2 2v7h-4v-7a6 6 0 0 1 6-6z"
            ></path>
            <rect x="2" y="9" width="4" height="12"></rect>
            <circle cx="4" cy="4" r="2"></circle>
          </svg>
          <!-- twitter -->
          <svg
            xmlns="http://www.w3.org/2000/svg"
            width="24"
            height="24"
            viewBox="0 0 24 24"
            fill="none"
            stroke="currentColor"
            stroke-width="2"
            stroke-linecap="round"
            stroke-linejoin="round"
            class="feather feather-twitter"
          >
            <path
              d="M23 3a10.9 10.9 0 0 1-3.14 1.53 4.48 4.48 0 0 0-7.86 3v1A10.66 10.66 0 0 1 3 4s-4 9 5 13a11.64 11.64 0 0 1-7 2c9 5 20 0 20-11.5a4.5 4.5 0 0 0-.08-.83A7.72 7.72 0 0 0 23 3z"
            ></path>
          </svg>
          <!-- youtube -->
          <svg
            xmlns="http://www.w3.org/2000/svg"
            width="24"
            height="24"
            viewBox="0 0 24 24"
            fill="none"
            stroke="currentColor"
            stroke-width="2"
            stroke-linecap="round"
            stroke-linejoin="round"
            class="feather feather-youtube"
          >
            <path
              d="M22.54 6.42a2.78 2.78 0 0 0-1.94-2C18.88 4 12 4 12 4s-6.88 0-8.6.46a2.78 2.78 0 0 0-1.94 2A29 29 0 0 0 1 11.75a29 29 0 0 0 .46 5.33A2.78 2.78 0 0 0 3.4 19c1.72.46 8.6.46 8.6.46s6.88 0 8.6-.46a2.78 2.78 0 0 0 1.94-2 29 29 0 0 0 .46-5.25 29 29 0 0 0-.46-5.33z"
            ></path>
            <polygon
              points="9.75 15.02 15.5 11.75 9.75 8.48 9.75 15.02"
            ></polygon>
          </svg>

          <div style="display: flex; align-items: center">
            <!-- location -->
            <svg
              xmlns="http://www.w3.org/2000/svg"
              viewBox="0 0 24 24"
              fill="none"
              stroke="currentColor"
              stroke-width="2"
              stroke-linecap="round"
              stroke-linejoin="round"
              class="feather feather-map-pin"
              style="height: 24px; height: 24px; padding-right: 20px;"
            >
              <path d="M21 10c0 7-9 13-9 13s-9-6-9-13a9 9 0 0 1 18 0z"></path>
              <circle cx="12" cy="10" r="3"></circle>
            </svg>
            <!-- shop -->
            <img src="src/assets/social-media-headers/shop.png" style="height: 24px; height: 24px; padding-right: 20px;" />
            Shop
            <!-- settings -->
            <img src="src/assets/social-media-headers/settings.png" style="height: 24px; height: 24px;" />
            Settings
          </div>
        </div>
      </div>
    </div>
    <div class="Header_v1">
      <div class="header-search">
        <div class="logo-search">
          <svg
            xmlns="http://www.w3.org/2000/svg"
            width="24"
            height="24"
            viewBox="0 0 24 24"
            fill="none"
            stroke="currentColor"
            stroke-width="2"
            stroke-linecap="round"
            stroke-linejoin="round"
            class="feather feather-align-justify"
            style="padding: 0 10px"
          >
            <line x1="21" y1="10" x2="3" y2="10"></line>
            <line x1="21" y1="6" x2="3" y2="6"></line>
            <line x1="21" y1="14" x2="3" y2="14"></line>
            <line x1="21" y1="18" x2="3" y2="18"></line>
          </svg>
          <img
            src="src/assets/social-media-headers/shoperz.jpg"
            style="height: 50px; padding-right: 15%"
          />
          <div class="InputContainer">
            <input
              type="text"
              name="text"
              class="input"
              id="input"
              placeholder="Search for products"
            />

            <label for="input" class="labelforsearch">All Categories </label>

            <button class="searchButton">
              <img
                src="src/assets/social-media-headers/icons8-search-50.png"
                style="height: 20px"
              />
            </button>
          </div>
          <div class="marginLeft">
            <svg
              xmlns="http://www.w3.org/2000/svg"
              width="15"
              height="15"
              viewBox="0 0 24 24"
              fill="none"
              stroke="currentColor"
              stroke-width="2"
              stroke-linecap="round"
              stroke-linejoin="round"
              class="feather feather-user"
              style="padding-right: 5%; padding-left: 5%"
            >
              <path d="M20 21v-2a4 4 0 0 0-4-4H8a4 4 0 0 0-4 4v2"></path>
              <circle cx="12" cy="7" r="4"></circle>
            </svg>

            <svg
              viewBox="0 0 72 72"
              xmlns="http://www.w3.org/2000/svg"
              width="15"
              height="15"
              style="padding-right: 5%; padding-left: 5%"
            >
              <g
                style="
                  fill: none;
                  stroke: #000;
                  stroke-linecap: round;
                  stroke-linejoin: round;
                  stroke-miterlimit: 10;
                  stroke-width: 2;
                "
              >
                <path
                  d="m40.3774 40.4583 6.9093 6.9332c1.6139 1.6195 4.0955 2.5668 6.7244 2.5668h12.7749"
                />
                <path
                  d="m5 21.9583h12.7749c2.6288 0 5.1104.9473 6.7244 2.5668l7.0229 7.0473"
                />
                <path
                  d="m5 49.9583h12.7749c2.6288 0 5.1104-.9473 6.7244-2.5668l22.7874-22.8664c1.6139-1.6195 4.0955-2.5668 6.7244-2.5668h12.7749"
                />
                <path d="m66.7859 21.9583-8.1854-8.2139" />
                <path d="m58.6005 30.1722 8.1854-8.2139" />
                <path d="m66.7859 49.9583-8.1854-8.2139" />
                <path d="m58.6005 58.1722 8.1854-8.2139" />
              </g>
            </svg>

            <svg
              xmlns="http://www.w3.org/2000/svg"
              width="15"
              height="15"
              viewBox="0 0 24 24"
              fill="none"
              stroke="currentColor"
              stroke-width="2"
              stroke-linecap="round"
              stroke-linejoin="round"
              class="feather feather-heart"
              style="padding-right: 5%; padding-left: 5%"
            >
              <path
                d="M20.84 4.61a5.5 5.5 0 0 0-7.78 0L12 5.67l-1.06-1.06a5.5 5.5 0 0 0-7.78 7.78l1.06 1.06L12 21.23l7.78-7.78 1.06-1.06a5.5 5.5 0 0 0 0-7.78z"
              ></path>
            </svg>

            <img
              src="src/assets/social-media-headers/shopping-bag.jpg"
              style="
                width: 15px;
                height: 15px;
                padding-right: 5%;
                padding-left: 5%;
              "
            />
          </div>
        </div>

        <div class="filtre-bar">
          <div>TV & Audio</div>
          <div>Smartphones</div>
          <div>Laptops & PCs</div>
          <div>Gadgets</div>
          <div>Photo & Video</div>
          <div>Gifts</div>
          <div>Books</div>
          <div>Toys</div>
        </div>
      </div>
    </div>
    <div class="Page_category_v1">
      <div class="filters">
        <div>Categories</div>
        <div>Brands</div>
      </div>
    </div>
    <div class="Page_header_v1">
      <div class="header-produse">
        <div>1</div>
        <div>2</div>
      </div>
    </div>
    <div class="Product_list_home_page">
      <div class="produse">
        <produse />
      </div>
    </div>
  </div>
</template>

<script>
import produse from "./assets/produse/produse.vue";

export default {
  name: "App",
  components: {
    produse,
  },
};
</script>
