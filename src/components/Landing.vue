<script setup>
import Mario from "../assets/mario-avatar.png";
import IconReact from "~icons/simple-icons/react";
import AkarIconsNodeFill from "~icons/akar-icons/node-fill";
import AkarIconsTypescriptFill from "~icons/akar-icons/typescript-fill";
import SimpleIconsNestjs from "~icons/simple-icons/nestjs";
import AkarIconsJavascriptFill from "~icons/akar-icons/javascript-fill";
</script>

<template>
  <section class="landing-section">
    <div class="text-container">
      <h2 class="title">Mario Gutiérrez</h2>
      <h3 class="subtitle">Desarrollador Fullstack JavaScript</h3>
    </div>
    <div class="icons-container">
      <div class="icon-group"></div>
      <div class="icon-group">
        <IconReact color="#7c3aed" width="50" height="50" />
        <AkarIconsNodeFill color="#7c3aed" width="50" height="50" />
        <AkarIconsJavascriptFill color="#7c3aed" width="50" height="50" />
        <AkarIconsTypescriptFill color="#7c3aed" width="50" height="50" />
        <SimpleIconsNestjs color="#7c3aed" width="50" height="50" />
      </div>
    </div>
    <div class="avatar-container">
      <img :src="Mario" alt="avatar" class="avatar" />
    </div>
  </section>
</template>

<style scoped>
.landing-section {
  min-height: 100vh;
  padding-left: 5rem;
  padding-right: 5rem;
  /* background-color: #1a202c; */
  /* color: white; */
  display: flex;
  flex-direction: column;
  align-items: center;
}

.text-container {
  text-align: center;
  /* padding: 2.5rem; */
  /* border: 2px solid black; */
}

.title {
  font-size: 2.25rem;
  line-height: 2.25rem;
  padding-top: 0.5rem;
  padding-bottom: 0.5rem;
  font-weight: 600;
  color: #7c3aed;
}

.subtitle {
  font-size: 1.125rem; /* 18px */
  line-height: 1.75rem; /* 28px */
  padding-top: 0.5rem;
  padding-bottom: 0.5rem;
  /* border: 2px solid red; */
  min-width: 100%;
  color: rgb(93, 100, 109);
}

.description {
  font-size: 1rem;
  padding-top: 0.75rem;
  padding-bottom: 0;
  line-height: 2rem;
  /* color: #e2e8f0; */
}

.icons-container {
  display: flex;
  flex-direction: column;
  justify-content: center;
  gap: 1rem;
  padding: 0.25rem 1.5rem;
  color: #7c3aed;
}

.icon-group {
  display: flex;
  justify-content: center;
  gap: 0.5rem;
  margin-left: 0.5rem;
}

.avatar-container {
  position: relative;
  width: 11rem;
  height: 11rem;
  margin-top: 3rem;
  background: linear-gradient(to bottom, #7c3aed, #6b46c1);
  border-radius: 50%;
  overflow: hidden;
}

.avatar {
  width: 100%;
  height: 100%;
  object-fit: cover;
  margin: 0 auto;
}
</style>
