<template>
  <div clas="container">
    <div class="row gy-2 justify-content-center">
      <div class="col">
        <img src="../assets/IMG_1521.jpg" alt="Kevin Munoz" />
      </div>
      <div class="col card">
        <div class="card-body">
          <p>
            I'm Kevin Munoz and I am currently a Junior Software Developer for
            Zumasys Inc in San Clemente, CA. I graduated with my Bacholers from
            UC Santa Cruz, Go Slugs!
          </p>
          <p>
            When it comes to coding, I am most proficient in Javascript, Java,
            HTML and CSS. I also have experience in other languages such as C#
            and Python. Although, the bulk of my experience has been with the
            first mentioned languages.
          </p>
          <div style="text-align: left">Kevin Munoz</div>
          <div style="text-align: left">munozk341@gmail.com</div>
        </div>
      </div>
    </div>
    <div class="row m-5">
      <div class="col-12">
        <h3>Reading List</h3>
      </div>
    </div>
    <div class="row justify-content-center">
      <div class="col-10">
        <div class="card">
          <div class="card-body">
            <div class="row">
              <div class="col-4">
                <img
                  src="../assets/allaboutlove.jpeg"
                  alt="All About Love"
                  class="img-fluid"
                />
              </div>
              <div class="col-8">
                <h4>All About Love</h4>
                <div class="text-start">
                <p>
                  All about love is unsurprisingly, a book about love! This novel digs deep into the different meanings of love. 
                  Ourt first thought goes straight to romantic love. In actuality, we need to redefine what love truly means. It can also
                  take different forms. We can shoew love within our family, to ourselves, to friends, and also to our partners. This book is in a way like
                  talking tio a therapist. This book really made me think about the love that I gave to others and most importantly the love that I gave to myself. 
                  Believe it or not, there is a connection between those two. This book helps us make that connection. It is a very important connection to make because
                   I think the more we work on loving ourselves, the more we respect ourselves and can determine which love we want in our lives. You respect yourself to
                   cut out those who don't truly show you the love that you deserve and <b>want</b>. This has helped me work on loving myself, and it has 
                   cascaded into my love for my friends and family. Iv'e been loving myself more and have felt more love for thers as well. This is a great 
                   book to read if you want to learn about love but also are on your own self-love journey. 
                  </p>
                  </div>
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script lang="ts">
import { Component, Prop, Vue } from "vue-property-decorator";
@Component
export default class Profile extends Vue {}
</script>
