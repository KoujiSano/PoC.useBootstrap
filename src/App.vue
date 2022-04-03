<script setup lang="ts">
// This starter template is using Vue 3 <script setup> SFCs
// Check out https://v3.vuejs.org/api/sfc-script-setup.html#sfc-script-setup
import HelloWorld from './components/HelloWorld.vue'
</script>

<template>
  <img alt="Vue logo" src="./assets/logo.png" />
   <BvBadge background-color="secondary">New</BvBadge>
     <BvAccordion parent>
    <BvAccordionItem active>
      <BvAccordionHeader level="2">
        <BvAccordionButton>Accordion Item #1</BvAccordionButton>
      </BvAccordionHeader>
      <BvAccordionCollapse>
        <BvAccordionBody>
          <strong>This is the first item's accordion body.</strong> It is shown by default, until the collapse plugin adds the appropriate classes that we use to style each element. These classes control the overall appearance, as well as the showing and hiding via CSS transitions. You can modify any of this with custom CSS or overriding our default variables. It's also worth noting that just about any HTML can go within the
          <code>.accordion-body</code>, though the transition does limit overflow.
        </BvAccordionBody>
      </BvAccordionCollapse>
    </BvAccordionItem>
    <BvAccordionItem>
      <BvAccordionHeader level="2">
        <BvAccordionButton>Accordion Item #2</BvAccordionButton>
      </BvAccordionHeader>
      <BvAccordionCollapse>
        <BvAccordionBody>
          <strong>This is the second item's accordion body.</strong> It is hidden by default, until the collapse plugin adds the appropriate classes that we use to style each element. These classes control the overall appearance, as well as the showing and hiding via CSS transitions. You can modify any of this with custom CSS or overriding our default variables. It's also worth noting that just about any HTML can go within the
          <code>.accordion-body</code>, though the transition does limit overflow.
        </BvAccordionBody>
      </BvAccordionCollapse>
    </BvAccordionItem>
    <BvAccordionItem>
      <BvAccordionHeader level="2">
        <BvAccordionButton>Accordion Item #3</BvAccordionButton>
      </BvAccordionHeader>
      <BvAccordionCollapse>
        <BvAccordionBody>
          <strong>This is the third item's accordion body.</strong> It is hidden by default, until the collapse plugin adds the appropriate classes that we use to style each element. These classes control the overall appearance, as well as the showing and hiding via CSS transitions. You can modify any of this with custom CSS or overriding our default variables. It's also worth noting that just about any HTML can go within the
          <code>.accordion-body</code>, though the transition does limit overflow.
        </BvAccordionBody>
      </BvAccordionCollapse>
    </BvAccordionItem>
  </BvAccordion>
  <HelloWorld msg="Hello Vue 3 + TypeScript + Vite" />
</template>

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
