<script setup>
import Header from "../components/Header.vue";
import Banner from "../components/Banner.vue";
import Sidebar from "../components/Sidebar.vue";
</script>

<template>
  <Header />
  <Banner />

  <main class="flex">
    <Sidebar />

    <div class="flex-1 p-10">
      <p class="text-3xl font-semibold">Visi & Misi Desa</p>
      <p class="text-lg font-semibold">Visi</p>
      <p>
        “Terwujudnya Masyarakat Desa Dan Pemerintahaan Desa Purwabakti Yang Bersatu,Mandiri,Sejahtera,Aman,Dan Damai ”
      </p>
      <p class="text-lg font-semibold">Misi</p>
      <ul>
        <li>
          1. Meningkatkan Kualitas Sumberdaya manusia melalui program pendidikan dan kesehatan serta pengamalan ajaran agama
          kepada masyarakat sesuai dengan palsafah, Pancasila dan Undang-undang Negara Republik Indonesia;
        </li>
        <li>
          2. Meningkatkan partisipasi masyarakat dalam pembangunan desa sehinga dapat meningkatkan kesadaran dan kemandirian
          dalam pembangunan Desa berkelanjutan;
        </li>
        <li>
          3. Mengoptimalkan kinerja aparat pemerintahan desa secara maksimal sesuai tugas pko dan pungsi agar masyarakat
          mendapatkan pelayanan yang maksimal, pelayan yang lebih baik,ramah,cepat dan tepat;
        </li>
        <li>
          4. Meningkatkan ketahanan ekonomi dengan menggalakan usaha ekonomi kerakyatan melalui program strategis dibidang
          produksi pertanian, perkebunan,peternakan,perikanan dan pariwisata;
        </li>
        <li>
          5. Mendorong pengembangan koprasi usaha kecil dan menengah serta Badan Usaha Milik Desa;
        </li>
        <li>
          6. Mendorong majunya Pendidikan formal maupun nonformal seperti
          pesantren, LPK, diklat serta penyuluhan pertanian yang mudah diakses
          dan dinikmati seluruh warga masyarakat, guna menghasilkan insan
          intelektual, berakhlak mulia, inovatif dan entrepreneur;
        </li>
        <li>
          7. Menyalurkan segala bentuk bantuan dari Pemerintah Kabupaten,
          Provinsi dan Pusat sesuai dengan peruntukannya dan mencegah terjadinya
          penyimpangan dan kebocoran;
        </li>
        <li>
          8. Menjalin sinergitas dengan instansi atau Lembaga terkait dan pihak
          swasta guna optimalisasi suatu tujuan lebih baik dan lebih maksimal;
        </li>
        <li>
          9. Responsive dan aspiratif atas segala bentuk kebutuhan atau
          keinginan dan permasalahan yang terjadi ditengah masyarakat yang
          majemuk dan dinamis;
        </li>
        <li>
          10. Membina dan memantapkankehidupan gotong royongsebagai basis dan
          modal dasar pembangunan desa, yang pada hakikatnyajuga merupakan
          karakter dasar dari masyarakat desa dan juga bangsa Indonesia.
        </li>
      </ul>
    </div>
  </main>
</template>

<style>
body {
  background: #f1f1f1;
}
</style>
