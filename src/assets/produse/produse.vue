<template>
  <div class="item-info" v-for="produs in produse" :key="produs.produs" style="height: 403px">
    <p class="tip-produs">{{ produs.tip_produs }}</p>
    <p class="produs-name">{{ produs.produs }}</p>
    <img class="image-css" :src="produs.image" alt="Product Image" />

    <div class="pret-buy">
      <p class="price">{{ produs.price }}</p>
      <button @click="handleButtonClick" class="button-buy">
        <img src="src/assets/social-media-headers/shopping-bag.jpg" style="height: 25px" />
      </button>
    </div>
  </div>
</template>

<script>
export default {
  data() {
    return {
      produse: [
        {
          image: "/src/assets/produse-img/iphone_14_pro.jpg",
          tip_produs: "Smartphone",
          produs: "Apple iPhone 14 Pro, LTPO Super Retina XDR OLED 6.1",
          price: "$1,200.00",
        },
        {
          image: "/src/assets/produse-img/nokia 8210.jpg",
          tip_produs: "Smartphone",
          produs: "Mobile Phone Nokia 8210, Dual SIM, 4G",
          price: "$60.00",
        },
        {
          image: "/src/assets/produse-img/srsxv900.jpg",
          tip_produs: "TV & Audio",
          produs: "SONY SRSXV900, Wireless Party Speaker, MEGA BASS",
          price: "$1,200.00",
        },
        {
          image: "/src/assets/produse-img/headphones.jpg",
          tip_produs: "TV & Audio",
          produs: "Headphones, Noise cancelling, Bluetooth 5.0",
          price: "$920.00",
        },
        {
          image: "/src/assets/produse-img/D-SLR Canon EOS R10.jpg",
          tip_produs: "Photo & Video",
          produs: "D-SLR Canon EOS R10, 4k, DIGIC X, RF-S 18-45mm",
          price: "$1,100.00",
        },
        {
          image: "/src/assets/produse-img/PC DELL Vostro 3910 MT.jpg",
          tip_produs: "Laptops & PCs",
          produs: "PC DELL Vostro 3910 MT, (Intel® Core™ i5-12400)",
          price: "$600.00",
        },
        {
          image:
            "/src/assets/produse-img/Laptop 2in1 Asus VivoBook S 14 Flip TP3402ZA Intel® Core™.jpg",
          tip_produs: "Laptops & PCs",
          produs: "Laptop 2in1 Asus VivoBook S 14 Flip TP3402ZA Intel® Core™",
          price: "$1,000.00",
        },
        {
          image: "/src/assets/produse-img/Sony SRS-XP700.jpg",
          tip_produs: "TV & Audio",
          produs: "Sony SRS-XP700, MEGA BASS, Bluetooth, LDAC, Wireless, IPX4",
          price: "$600.00",
        },
        ],
    };
  },
  methods: {
    handleButtonClick() {
      this.$emit('increment');
    },
  },
};
</script>