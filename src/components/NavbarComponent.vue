<script setup>
import { Navbar, NavbarLogo, NavbarCollapse, NavbarLink } from 'flowbite-vue'
</script>
<template>
    <Navbar solid>
      <template #logo>
        <NavbarLogo link="https://www.google.com/" alt=" logo" image-url="https://media.istockphoto.com/id/1255163297/id/vektor/vektor-ikon-profil-pengguna-simbol-potret-avatar-logo-tanda-orang-bentuk-datar-siluet-hitam.jpg?s=170667a&w=0&k=20&c=XHIj0IgaoxhePW5ocWVnHhquH22vRhwjmlr63hbgAQc=" style="font-style: oblique;"> Alia Putri
        </NavbarLogo>
      </template>
      <template #default="{isShowMenu}">
        <NavbarCollapse :isShowMenu="isShowMenu">
          <NavbarLink is-active>Home</NavbarLink>
          <ul class="text-black-500 dark:text-black-900 font-medium">
                      <li class="mb-2,5">
                          <a href="https://api.whatsapp.com/send?phone=6283120853975" class="hover:underline">Contact</a>
                      </li>
                  </ul>
        </NavbarCollapse>
      </template>
    </Navbar>
</template>