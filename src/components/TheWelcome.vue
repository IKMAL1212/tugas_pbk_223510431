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
    Saya Berasal dari Kabupaten Kuantan Singingi, Kecamatan Kuantan Tengah, Kota Taluk Kuantan Provinsi Riau
  </WelcomeItem>
  <hr />
  <WelcomeItem>
    <template #icon>
      <ToolingIcon />
    </template>
    <template #heading>Pendidikan</template>

    SDN 006 Kuantan Singingi, Taluk Kuantan 2009-2015<br />
    SMPS PEMBANGUNAN BAGAN SINEMBAH 2015-2018<br />
    SMKS PEMBANGUNAN BAGAN SINEMBAH 2018-2021<br />
    UNIVERSITAS ISLAM RIAU 2022-NOW
  </WelcomeItem>
  <hr />
  <WelcomeItem>
    <template #icon>
      <EcosystemIcon />
    </template>
    <template #heading>Pengalaman</template>
    bekerja di SUN caffe&Eatery
    <ul>
      <li>Menjadi barista</li>
      <li>Memasak makanan siap saji</li>
    </ul>
  </WelcomeItem>
  <hr />
  <WelcomeItem>
    <template #icon>
      <SupportIcon />
    </template>
    <template #heading>Skill</template>
    <ul>
      <li>Css</li>
      <li>HTML</li>
      <li>My sql</li>
      <li>Topologi Jaringan</li>
    </ul>
  </WelcomeItem>
  <hr />
  <WelcomeItem>
    <template #icon>
      <CommunityIcon />
    </template>
    <template #heading>Hubungi Saya</template>

    Instagram :<a href="https://www.instagram.com/reevvvyy?igsh=bjhqcGwwZGZyY3hl&utm_source=qr" target="_blank">Reevvvyy </a
    ><br />
    Email : revim1809@gmail.com<br />
    No HP : 223510431
  </WelcomeItem>
</template>