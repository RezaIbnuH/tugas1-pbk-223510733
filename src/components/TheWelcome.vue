<script setup lang="ts">
import WelcomeItem from './WelcomeItem.vue'
import CommunityIcon from './icons/IconCommunity.vue'
import DocumentationIcon from './icons/IconDocumentation.vue'
import EcosystemIcon from './icons/IconEcosystem.vue'
import SupportIcon from './icons/IconSupport.vue'
import ToolingIcon from './icons/IconTooling.vue'
</script>

<template>
  <WelcomeItem>
    <template #icon>
      <DocumentationIcon />
    </template>
    <template #heading>Pendidikan</template>

    Saat ini saya kuliah di salah satu Kampus swasta di Riau yaitu <a href="https://uir.ac.id/" target="_blank">Universitas Islam Riau</a>. Sebelumnya saya bersekolah di <a href="https://smanegeri1kubu.sch.id/#" target="_blank">SMA NEGERI 1 KUBU</a>
  </WelcomeItem>

  <WelcomeItem>
    <template #icon>
      <ToolingIcon />
    </template>
    <template #heading>Tempat, Tanggal Lahir</template>

    Saya lahir di sebuah kecamatan kubu jln. datuk kancil Kabupaten <a href="https://id.wikipedia.org/wiki/Kabupaten_Rokan_Hilir" target="_blank">Rokan Hilir</a> Provinsi<a href="https://id.wikipedia.org/wiki/Riau" target="_blank">Riau</a> pada tanggal 7 Juni 2004.
  </WelcomeItem>

  <WelcomeItem>
    <template #icon>
      <EcosystemIcon />
    </template>
    <template #heading>Jurusan</template>

    Prodi atau Jurusan Kuliah Saya mengambil Program didik Teknik Informatika atau biasa disebut IT , dan saya sekarang berada di semester 4
  </WelcomeItem>

  <WelcomeItem>
    <template #icon>
      <CommunityIcon />
    </template>
    <template #heading>Hobi</template>

    <ul>
      <li>Futsal</li>
      <li>Sepak bola</li>
      <li>Badminton</li>
      <li>Voly</li>
      <li>Renang</li>
      <li>Lari</li>
      <li>Gitar</li>
    </ul>
  </WelcomeItem>

  <WelcomeItem>
    <template #icon>
      <SupportIcon />
    </template>
    <template #heading>Social Media</template>
    
    <ul>
      <li>Instagram   : <a href="https://www.instagram.com/nanda_alfiranda/#" target="_blank">Nanda Alfiranda</a></li>
      <li>Facebook    : <a href="https://www.facebook.com/Nanda.alfiranda.984" target="_blank">Nanda Alfiranda</a></li>
      <li>WhatsApp    : 0897-7476-390</li>
    </ul>
  </WelcomeItem>
</template>
