<script setup>
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
    <template #heading>Book your sesh with me </template>
    <a
      href="https://calendar.google.com/calendar/u/0/appointments/schedules/AcZssZ2KHBvpsNrm7H1lAF-3_wBZwFtBzHPXSFHtHvyA1RI9d55sj5QxvCCyf-msOjfXlB4ztsPS-K8R"
      target="_blank"
      rel="noopener"
      >Availabitites</a
    >
    is a hyper link you can book me directly. Introductory sessions are usually 15mn and coaching
    vary from 30 to 45 min.
  </WelcomeItem>

  <WelcomeItem>
    <template #icon>
      <ToolingIcon />
    </template>
    <template #heading>Tooling</template>

    This part is still under construction. Here you'll be able to browse through the tools that I
    use for my sessions.
    <br />
    The goal is to empower you by deconstructing knowledge. My goal is to boraden knowledge and
    organise it in a way that make sense to you. <br />
    You'll find everything from Neuropsychlogy to mindfulness and stress management. Links to state
    funded help like legal advise and imigration policies. <br />
  </WelcomeItem>

  <WelcomeItem>
    <template #icon>
      <EcosystemIcon />
    </template>
    <template #heading>Ecosystem</template>

    The idea is to create a safe space for everyone. <br />
    I celebrated differences therefore it's important to be able to cover a broad span of
    individuals.<br />
    This means the content we will discuss will be tailored to your situation and context. Check
    more in the About section. You can leave your feedback here :

    <a href="https://actn0ul5j8x.typeform.com/to/ERD0fZH6" target="blank" rel="noopener"
      >Feedback form</a
    >
  </WelcomeItem>

  <WelcomeItem>
    <template #icon>
      <CommunityIcon />
    </template>
    <template #heading>Community</template>
    A complete list of safe places for minorities and sexual dissidences in Barcelona.
    <br />
  </WelcomeItem>

  <WelcomeItem>
    <template #icon>
      <SupportIcon />
    </template>
    <template #heading>Support me </template>

    You can buy me a coffee here
    <a href="https://www.paypal.com/paypalme/AndreasertoC" target="_blank" rel="noopener"
      >through my Paypal. </a
    >.
    <br />
    Just remeber is my dead-name for governement reasons.
  </WelcomeItem>
</template>
