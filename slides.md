---
theme: seriph
background: https://nekoya.moe.team/img/Carousel_2.webp
class: 'text-center'
highlighter: shiki
lineNumbers: false
info: |
  ## Nekoya
  Presentation slides for Nekoya.
drawings:
  persist: false
---

# Nekoya

E-Commerce

<div class="pt-12">
  <span @click="$slidev.nav.next" class="px-2 py-1 rounded cursor-pointer" hover="bg-white bg-opacity-10">
    Press Space for next page <carbon:arrow-right class="inline"/>
  </span>
</div>

---
layout: image-right
image: https://gitlab.com/nekoya/app/-/design_management/designs/412683/6a4e6acdd7d529280804036388ce08762e067c1e/raw_image
---

# Products Page

Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum.

---

<div grid="~ cols-2 gap-4">
<div>

# Cart Page
Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Eget arcu dictum varius duis at consectetur lorem. Suscipit adipiscing bibendum est ultricies.

</div>
<div>

<img src="https://gitlab.com/nekoya/app/-/design_management/designs/412692/3eb8a90a99fe0d735b4be90ddfd0238a6593722a/raw_image"/>

</div>

<style>
img {
  max-width: 75%;
  height: 70%;
  margin-left: 80px;
}
</style>

</div>

---

<div grid="~ cols-2 gap-4">
<div>

# Live Demo
Lorem ipsum dolor sit amet, consectetur adipiscing elit. Integer suscipit malesuada purus, in vulputate urna aliquam id. Etiam fermentum vel libero non pharetra. Mauris id finibus lectus. Nam ultricies consectetur diam. Suspendisse eu libero fermentum, venenatis lorem eget, sollicitudin nisl. Aliquam dictum imperdiet risus, id maximus sapien tincidunt ut. Nulla facilisi. Vivamus at dictum velit, sed rutrum lectus. In consectetur aliquam diam, a consequat risus posuere eu. Nunc egestas elit dui, vitae varius lorem malesuada a. Nam in lacus vitae leo pharetra convallis eget a risus. 

</div>

<style>
  #wrap {
    width: 400px;
    height: 600px;
    padding: 0;
    overflow: hidden;
    margin-left: 80px;
  }
  #scaled-frame {
    width: 400px;
    height: 650px;
    border: 0px;
  }
  #scaled-frame {
    zoom: 0.75;
    -moz-transform: scale(0.75);
    -moz-transform-origin: 0 0;
    -o-transform: scale(0.75);
    -o-transform-origin: 0 0;
    -webkit-transform: scale(0.75);
    -webkit-transform-origin: 0 0;
  }
  @media screen and (-webkit-min-device-pixel-ratio:0) {
    #scaled-frame {
      zoom: 1;
    }
  }
</style>

<div id="wrap">

<iframe id="scaled-frame" src="https://preview.nekoya.moe.team"></iframe>

</div>
</div>

---
layout: center
class: text-center
---

# Thank You