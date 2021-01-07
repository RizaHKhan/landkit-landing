<template>
  <b-container class="main">
    <div class="clippy"></div>
    <Header />

    <b-container class="mt-5 pt-5" fluid>
      <b-row>
        <b-col cols="12" lg="7">
          <b-img
            v-bind="imageProps"
            src="~/assets/images/main.svg"
            alt="Image 1"
          ></b-img>
        </b-col>
        <b-col cols="12" lg="5">
          <h1 class="smart-text">Word Smart, Not Hard.</h1>
          <p>
            Lorem ipsum dolor sit amet consectetur, adipisicing elit. In ex ipsa
            odio quia similique iure vero cum laborum enim cupiditate illo
            maxime quibusdam, sit beatae repellendus explicabo reprehenderit
            incidunt pariatur! A qui ex incidunt ullam aliquam, repudiandae
            optio praesentium perferendis minus illo tempora facilis rerum
            architecto vero, sapiente laborum ipsam.
          </p>
        </b-col>
      </b-row>
    </b-container>

    <b-container class="mt-5 pt-5">
      <b-row class="mt-5 pt-5 sm-border-container justify-content-center">
        <span class="sm-border"></span>
        <b-col cols="12">
          <h3 class="text-center">The hub for your team and your work</h3>
        </b-col>
        <b-col cols="10">
          <p class="text-center">
            Lorem ipsum dolor sit amet consectetur, adipisicing elit. Dolores
            velit ipsa minima doloribus perspiciatis at rem aliquid esse quis
            dolorem alias corrupti suscipit, dolore ullam amet similique quas
            quam exercitationem atque hic tempora eaque nesciunt ea. Quae neque
            rem reiciendis.
          </p>
        </b-col>
      </b-row>
    </b-container>

    <b-container class="mt-5 py-5">
      <b-row class="mt-5">
        <b-col cols="12" lg="6">
          <b-row>
            <b-col cols="12" md="5">
              <b-img src="~/assets/images/card.png"></b-img>
            </b-col>
            <b-col>
              <h4>Rapid Transport</h4>
              <p>
                Lorem ipsum dolor sit amet consectetur adipisicing elit.
                Temporibus iste illum ut quis, asperiores corrupti officiis
                commodi fuga minus laboriosam harum ad atque sequi quas
                doloremque tenetur esse aspernatur mollitia.
              </p>
            </b-col>
          </b-row>
        </b-col>
        <b-col cols="12" lg="6">
          <b-row>
            <b-col cols="12" md="5">
              <b-img src="~/assets/images/card.png"></b-img>
            </b-col>
            <b-col>
              <h4>Rapid Transport</h4>
              <p>
                Lorem ipsum dolor sit amet consectetur adipisicing elit.
                Temporibus iste illum ut quis, asperiores corrupti officiis
                commodi fuga minus laboriosam harum ad atque sequi quas
                doloremque tenetur esse aspernatur mollitia.
              </p>
            </b-col>
          </b-row>
        </b-col>
      </b-row>
      <b-row class="mt-5">
        <b-col cols="12" lg="6">
          <b-row>
            <b-col cols="12" md="5">
              <b-img src="~/assets/images/card.png"></b-img>
            </b-col>
            <b-col>
              <h4>Rapid Transport</h4>
              <p>
                Lorem ipsum dolor sit amet consectetur adipisicing elit.
                Temporibus iste illum ut quis, asperiores corrupti officiis
                commodi fuga minus laboriosam harum ad atque sequi quas
                doloremque tenetur esse aspernatur mollitia.
              </p>
            </b-col>
          </b-row>
        </b-col>
        <b-col cols="12" lg="6">
          <b-row>
            <b-col cols="12" md="5">
              <b-img src="~/assets/images/card.png"></b-img>
            </b-col>
            <b-col>
              <h4>Rapid Transport</h4>
              <p>
                Lorem ipsum dolor sit amet consectetur adipisicing elit.
                Temporibus iste illum ut quis, asperiores corrupti officiis
                commodi fuga minus laboriosam harum ad atque sequi quas
                doloremque tenetur esse aspernatur mollitia.
              </p>
            </b-col>
          </b-row>
        </b-col>
      </b-row>
    </b-container>
  </b-container>
</template>

<script>
import Header from '@/components/Header'
export default {
  components: {
    Header,
  },
  data() {
    return {
      imageProps: {
        center: true,
        fluidGrow: true,
        class: 'my-5',
      },
    }
  },
}
</script>

<style lang="scss" scoped>
.smart-text {
  font-size: 4rem;

  @media (max-width: 1200px) {
    font-size: 3rem;
  }

  @media (max-width: 900px) {
    font-size: 2rem;
  }
}

.sm-border-container {
  position: relative;
}

.sm-border {
  left: 50%;
  top: 0px;
  transform: translateX(-50%);
  position: absolute;
  border-top: 2px solid #cfdae5;
  height: 2px;
  width: 72px;
}

.clippy {
  position: absolute;
  top: 0;
  left: 0;
  height: 70vh;
  width: 65%;
  background-color: #f6f6ff;
  clip-path: polygon(100% 0, 74% 30%, 49% 78%, 0 100%, 0 0);
}
</style>
