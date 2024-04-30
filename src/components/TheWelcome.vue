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

    For now a few helpful links :

    <ul>
      <li>
        <a
          href="https://www.headspace.com/es?utm_source=google&utm_medium=search&utm_campaign=HS_Headspace_Brand-Exact_Search_ES-INT_Google_NA&utm_content=&utm_term=headspace&gad_source=1&gclid=CjwKCAjwrcKxBhBMEiwAIVF8rMM_OS9DaickWC_kh0JWQ-esHhNLJpEZncJLiWqUZ-Zgd8ulSBoWUhoCyYcQAvD_BwE"
          target="_blank"
          rel="noopener"
          class="headspaceliink"
          >Headspace
        </a>
        Is an amazing platform present in Spotify and Netflix with meditations as short as 3 minutes
        if you are in a rush
      </li>
      <li>
        <a
          href="https://open.spotify.com/show/3J16TsZjA8LYpl2KHypHry?si=75a9233cbd534b23"
          target="_blank"
          rel="noopener"
          class="Susandavid-checkingin"
          >The Podcast Checking in with Susan David</a
        >
        is a very useful reminder we need to check in wiht ourselves. Here the author of Emotional
        Agility winds down for 5 minuts what was in her mind durign Covid. Very recomended for any
        kind of uncertain moment, to check in with her and maybe a hot cocoa
      </li>
      <li>
        If you a migrant and are trans within the LGBT spectrum you can reach out to
        <a href="https://migrantia.org/" target="_blank" rel="noopener">Migrantia</a> based in
        Madrid they provide help for migrant trans people, they host free dinners and donate clothes
      </li>
    </ul>
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
    <ul>
      <li>
        <a
          href="https://www.meetup.com/es-ES/lgbt-tech-barcelona/members/?op=leaders"
          target="_blank"
          rel="noopener"
          class="lbgt+tech"
          >Lgbt+ Tech meet up
        </a>
        Iwhere I'm an organizer we foster encounters to show the wonderful individuals who make
        technology in this beautiful city - Barcelona!
      </li>
      <li>
        <a href="https://techfems.org/" target="_blank" rel="noopener" class="techfems"
          >The Techfems iniciative
        </a>

        Henritte and her amazing team bring together women+ (including trans and non-binary) from
        various tech fields, to empower, coach and build a support network. It's the go to place
        when you don't know where to go !
      </li>
      <li>
        If you a migrant and are trans within the LGBT spectrum you can reach out to
        <a href="https://migrantia.org/" target="_blank" rel="noopener">Migrantia</a> based in
        Madrid they provide help for migrant trans people, they host free dinners and donate clothes
      </li>
    </ul>
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
