<template>
  <div id="app">
    <div class="bg-primary">
      <b-nav pills>
        <b-nav-item active>Home</b-nav-item>
        <b-nav-item active>About</b-nav-item>
        <b-nav-item active>Testi</b-nav-item>
        <b-nav-item active >Sumber Lainnya</b-nav-item>
      </b-nav>
  </div>
    
    <div>       
      <img alt="Vue logo" src="./assets/img1.jpg">
      <HelloWorld msg="Mari Belajar"/>
    </div>

    <div class="container">
      <div class="col-12 col-md-12">
        <div class="font mt-5" style="font-size:25px; font-weight:bold; text-align: center; font-family: Bahnschrift SemiBold">About</div>
      </div>
    </div>

    <div class="container-fluid mt-5">
      <div class="row">
        <div class="col-12 col-md-12">
          <div class="bg" style="background-color: gray; height:350px;">
          <img alt="logo" src="./assets/img3.jpeg" style="padding-top: 30px;">
          <p style="color: white;">"Mari belajar" yang menyediakan bahan belajar serta fasilitas komunikasi yang mendukung interaksi antar komunitas. 
          Mari Belajar hadir sebagai pengganti belajar tatap muka yang dapat dimanfaatkan oleh siswa dan guru Pendidikan Anak Usia Dini (PAUD),
          Sekolah Dasar (SD), Sekolah Menengah Pertama (SMP), Sekolah Menengah Atas/Kejuruan (SMA/SMK) sederajat. Dengan menggunakan Mari Belajar, 
          kita dapat belajar di mana saja, kapan saja dengan siapa saja. Seluruh konten yang ada di Rumah Belajar dapat diakses dan dimanfaatkan secara gratis.</p>
          </div>
      </div>

        <div class="container">
          <div class="row">
        <div class="col-12 col-md-12 mt-5" style="font-size:25px; font-weight:bold; text-align: center; font-family: Bahnschrift SemiBold">Testi</div>
        <img alt="Vue logo" src="./assets/imgd.jpg" style="padding-top: 30px;">
        <div class="col-6" style="font-weight: bold; padding-top:30px;">Bu Mardiana (SMK)<br>
           <p>Lewat HP, saya bisa memanfaatkan Rumah Belajar<br>
           untuk mengerjakan tugas-tugas dari guru,
           semua menjadi mudah, karena HP tidak hanya untuk telepon dan kirim pesan, tapi bisa juga untuk belajar.</p>
        </div>
        <div class="row">
        <img alt="Vue logo" src="./assets/imgc.png" style="padding-top: 50px;">
        <div class="col-6" style="font-weight: bold; padding-top:50px;">Bu ismi (SMA)<br> Saya suka bermain AR Rumah Belajar, sangat menarik, jaman now banget, 
        apalagi yang bagian -bagian sel. Luar biasa.<br>
        Sangat jelas dan benad -benar berasa ada di dekat saya. Gemes pengen saya sentuh sel nya.</div>
        </div>
      </div>
    </div>

        <div class="container">
          <div class="row">
            <img alt="Vue logo" src="./assets/imgba.jpg" style="padding-top: 50px;">
            <div class="col-6" style="font-weight: bold; padding-top: 50px;">Bu Dian (Guru SMP)<br> Cara mudah & murah untuk memulai pembelajaran yg tak kenal waktu, tempat & usia.
                Gunakan cara ini, demi keunggulan Anak Didik Bangsa.</div>
            <div class="row">
            <img alt="Vue logo" src="./assets/imgb.jpg" style="padding-top: 50px;">
            <div class="col-6" style="font-weight: bold; padding-top:50px;">Bu Sri (Guru SD)<br> Dengan belajar di Rumah Belajar Kemdikbud, 
                pembelajaran lebih menarik begitu pula dengan anak- anak. karena rumah belajar kemdikbud
                menyajikan materi- materi pembelajaran berbasis IT, itulah ketertarikan anak- anak.</div>
            </div>
          </div>
        </div>
    </div>

        <div class="container">
          <div class="col-12 col-md-12">
            <div class="font mt-5" style="font-size:25px; font-weight:bold; text-align: center; font-family: Bahnschrift SemiBold">Sumber Belajar Lainnya</div>
          </div>
        </div>
        </div>

          <div class="container-fluid mt-5">
          <div class="row">
          <div class="col">
            <img alt="logo" src="./assets/img4.jpeg">
          </div>
          <div class="col">
          <img alt="logo" src="./assets/img6.png"> 
          </div>
          <div class="col">
          <img alt="logo" src="./assets/img8.jpg"> 
          </div>

        <div class="container-fluid">
          <div class="row">
            <div class="col-sm-6"><img alt="logo" src="./assets/img7.jpg"></div>
            <div class="col-sm-6"><img alt="logo" src="./assets/img5.png"></div>
          </div>
      </div>
  </div>

  <footer class="bg-light text-center text-white">
  <div class="container p-4 pb-0 mt-5">
    <section class="mb-4">
    
      <div class="container-fluid">
                   <div class="font" style="font-size:25px; color:black; text-align: center; font-family: Arial Rounded MT Bold;">Kunjungi Website Kami</div>
              </div>
                <section class="mb-4"></section>
                <div class="baris1" style="color: black;">
                  <p>Maribelajar@kemdikbud.go.id</p><p>Belajar@kemdikbud.go.id</p><p>Telepon (056) 156785</p><p>WA +62 813-5643-8315</p>
                </div>


        <a
          class="btn btn-primary btn-floating m-1"
          style="background-color: #3b5998;"
          href="#!"
          role="button"
          ><i class="fab fa-facebook-f"></i
        ></a>

      
        <a
          class="btn btn-primary btn-floating m-1"
          style="background-color: #55acee;"
          href="#!"
          role="button"
          ><i class="fab fa-twitter"></i
        ></a>

      
        <a
          class="btn btn-primary btn-floating m-1"
          style="background-color: #dd4b39;"
          href="#!"
          role="button"
          ><i class="fab fa-google"></i
        ></a>

      
        <a
          class="btn btn-primary btn-floating m-1"
          style="background-color: #ac2bac;"
          href="#!"
          role="button"
          ><i class="fab fa-instagram"></i
        ></a>

      
        <a
          class="btn btn-primary btn-floating m-1"
          style="background-color: #0082ca;"
          href="#!"
          role="button"
          ><i class="fab fa-linkedin-in"></i
        ></a>

        <a
          class="btn btn-primary btn-floating m-1"
          style="background-color: #333333;"
          href="#!"
          role="button"
          ><i class="fab fa-github"></i
        ></a>
      </section>
    </div>
    <div class="text-center p-3" style="background-color: rgba(0, 0, 0, 0.2);">
      © 2020 Copyright:
      <a class="text-white" href="#">MariBelajar.com</a>
    </div>
  </footer>
  </div>

  </div>
    
</template>

<script>
import HelloWorld from './components/HelloWorld.vue'

export default {
  name: 'App',
  components: {
    HelloWorld
  }
}
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
