<script setup lang="ts">
import WelcomeItem from './WelcomeItem.vue'
import DocumentationIcon from './icons/IconDocumentation.vue'
import ToolingIcon from './icons/IconTooling.vue'
import EcosystemIcon from './icons/IconEcosystem.vue'
import CommunityIcon from './icons/IconCommunity.vue'
import SupportIcon from './icons/IconSupport.vue'
</script>

<template>
  <WelcomeItem>
    <template #icon>
      <DocumentationIcon />
    </template>
    <template #heading>Tentang Saya</template>
    Saya adalah mahasiswa di kampus universitas islam riau yang terletak di jalan Kaharuddin Nst
    Pekanbaru. Saat ini saya berada di semester 4 jurusan Teknik Informatika Universitas Islam Riau.
    Saya Berasal dari Kabupaten Indragiri Hulu, Kecamatan Lubuk Batu Jaya Provinsi Riau.
    Saya lahir di desa <a href="https://id.wikipedia.org/wiki/Lubuk_Batu_Tinggal,_Lubuk_Batu_Jaya,_Indragiri_Hulu://sekolah.data.kemdikbud.go.id/index.php/chome/profil/BF7D3C2F-FCA2-4602-BD1F-BEA817EFB01D" target="_blank" rel="noopener">Lubuk Batu Tinggal</a> pada 09 Oktober 2003

  </WelcomeItem>
  <hr />
  <WelcomeItem>
    <template #icon>
      <ToolingIcon />
    </template>
    <template #heading>Pendidikan</template>

    Saat ini saya kuliah di salah satu Kampus swasta di Riau yaitu
    <a href="https://uir.ac.id/" target="_blank" rel="noopener">Universitas Islam Riau</a>.
    Sebelumnya masuk ke Kampus ini saya lulusan dari
    <a href="https://sekolah.data.kemdikbud.go.id/index.php/chome/profil/BF7D3C2F-FCA2-4602-BD1F-BEA817EFB01D" target="_blank" rel="noopener">SMKN 1 Lubuk Batu Jaya</a>
  </WelcomeItem>
  <hr />
  <WelcomeItem>
    <template #icon>
      <EcosystemIcon />
    </template>
    <template #heading>HOBI</template>
    Saya memiliki beberapa hobi atau kegiatan untuk mengisi waktu luang saya
    <ul>
      <li>Bernyanyi</li>
      <li>Renang</li>
      <li>Jogging</li>
    </ul>
  </WelcomeItem>
  <hr />
  <WelcomeItem>
    <template #icon>
      <SupportIcon />
    </template>
    <template #heading>Skill</template>
    <ul>
      <li>HTML</li>
      <li>PHP</li>
      <li>C++</li>
      <li>MySql</li>
    </ul>
  </WelcomeItem>
  <hr />
  <WelcomeItem>
    <template #icon>
      <CommunityIcon />
    </template>
    <template #heading>Social Media</template>

    Instagram :<a href="https://www.instagram.com/rkaylnd_/" target="_blank">rkaylnd_ </a
    ><br />
  </WelcomeItem>
</template>