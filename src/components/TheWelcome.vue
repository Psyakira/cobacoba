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
    <template #heading>About me</template>

    I am a student informatics engineering at UIN SUSKA RIAU
    Now i am in 3rd Semester
  </WelcomeItem>

  <WelcomeItem>
    <template #icon>
      <ToolingIcon />
    </template>
    <template #heading>See me in Linkedin</template>
    <a href="https://linkedin.com/putrisyakirawirdiani" target="_blank" rel="noopener">Clickhere</a>
  </WelcomeItem>

  <WelcomeItem>
    <template #icon>
      <EcosystemIcon />
    </template>
    <template #heading>Contact Me in Instagram</template>

    <a href="https://instagram.com/Psyakira_w" target="_blank" rel="noopener">Contact Here</a>
  </WelcomeItem>

  <WelcomeItem>
    <template #icon>
      <SupportIcon />
    </template>
    <template #heading>This Page</template>

    This page make for Assignment Programming Web in 4B Class and make with Love by syakira:)
  </WelcomeItem>
</template>
