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
        <div class="font mt-5" style="font-size:25px; font-weight:bold; text-align: center; font-family:Lucida Calligraphy">About</div>
    </div>
    
    <div class="container-fluid">
      <div class="row">
        <div class="bg-info mt-3">
          <div class="col mt-3">
              <img alt="Vue logo" src="./assets/img3.jpeg">
          </div>
          <div class="col mt-3" style="color: white;">
          "Mari belajar" yang menyediakan bahan belajar serta fasilitas komunikasi yang mendukung interaksi antar komunitas. 
          Mari Belajar hadir sebagai pengganti belajar tatap muka yang dapat dimanfaatkan oleh siswa dan guru Pendidikan Anak Usia Dini (PAUD),
          Sekolah Dasar (SD), Sekolah Menengah Pertama (SMP), Sekolah Menengah Atas/Kejuruan (SMA/SMK) sederajat. Dengan menggunakan Mari Belajar, 
          kita dapat belajar di mana saja, kapan saja dengan siapa saja. Seluruh konten yang ada di Rumah Belajar dapat diakses dan dimanfaatkan secara gratis.
          </div>
        </div>

      <div class="container">
        <div class="font mt-5" style="font-size:25px; font-weight:bold; text-align: center;  font-family:Arial Black">Testi</div>
      </div>
        
      <div class="col-6 mt-5">
          <img alt="Vue logo" src="./assets/imgd.jpg">
        </div>
        <div class="col-6 mt-5">
          <div class="font mt-2" style="font-weight:bold;">
            <p>Bu Mardiana (Guru SMK)</p>
          Saya suka bermain AR Rumah Belajar, sangat menarik, jaman now banget, apalagi yang bagian -bagian sel. Luar biasa. Sangat jelas,
          dan benad -benar berasa ada di dekat saya. Gemes pengen saya sentuh sel nya.
          </div>
        </div>
        

        <div class="col-6 mt-5">
          <img alt="Vue logo" src="./assets/imgc.png">
        </div>
        <div class="col-6 mt-5">
          <div class="font mt-3" style="font-weight:bold;">
            <p>Bu Ismi (Guru SMA)</p>
          Lewat HP, saya bisa memanfaatkan Rumah Belajar untuk mengerjakan tugas-tugas dari guru,
           semua menjadi mudah, karena HP tidak hanya untuk telepon dan kirim pesan, tapi bisa juga untuk belajar.
          </div>
        </div>


        <div class="col-6 mt-5">
          <img alt="Vue logo" src="./assets/imgb.jpg">
        </div>
        <div class="col-6 mt-5">
          <div class="font mt-3" style="font-weight: bold;">
            <p>Bu Dian (Guru SMP)</p>
           Cara mudah & murah untuk memulai pembelajaran yg tak kenal waktu, tempat & usia.
            Gunakan cara ini, demi keunggulan Anak Didik Bangsa.
          </div>
        </div>

        <div class="col-6 mt-5">
              <img alt="Vue logo" src="./assets/imga.jpg">
            </div>
        <div class="col mt-5">
            <div class="font mt-3" style="font-weight: bold;">
            <p>Bu Sri (Guru SD)</p>
            <p>Dengan belajar di Rumah Belajar Kemdikbud, pembelajaran lebih menarik begitu pula dengan anak- anak. karena rumah belajar kemdikbud
                menyajikan materi- materi pembelajaran berbasis IT, itulah ketertarikan anak- anak.</p>
            </div>
        </div>

      </div>
      
  
        <div class="container">
        <div class="row">
        <div class="container">
          <div class="font mt-5" style="font-size:25px; font-weight:bold; text-align: center; font-family: Lucida Calligraphy;">Sumber Belajar Lainya</div>
        </div>

          <div class="container">
          <div class="row">
             <div class="col align-self-start mt-5">
              <img alt="logo" src="./assets/img4.jpeg">
             </div>
            <div class="col align-self-center mt-5">
              <img alt="logo" src="./assets/img6.png"> 
            </div>
            <div class="col align-self-end mt-5">
              <img alt="logo" src="./assets/img8.jpg"> 
            </div>
            <div class="col-6 align-self-end mt-5">
              <img alt="logo" src="./assets/img7.jpg"> 
            </div>
            <div class="col-6 align-self-end mt-5">
               <img alt="logo" src="./assets/img5.png"> 
            </div>

         </div>

        </div>

        <div class="container-fluid">
        <footer class="text-center text-white mt-5" style="background-color: #f1f1f1;">
            <div class="container pt-4">
               <div class="container">
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
                    style="background-color: #ac2bac;"
                    href="#!"
                    role="button"
                    ><i class="fab fa-instagram"></i
                ></a>
            </div>
            
            <div class="text-center text-dark p-3" style="background-color: rgba(0, 0, 0, 0.2);">
              © 2020 Copyright:
              <a class="text-dark" href="https://mdbootstrap.com/">MDBootstrap.com</a>
            </div>
       </footer>
        
        </div>
        </div>
      </div>
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
