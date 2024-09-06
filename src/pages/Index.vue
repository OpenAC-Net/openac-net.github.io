<template>
  <Layout>
    <div class="pt-8 md:pt-16">
      <div class="flex flex-col items-center">
        <div class="flex flex-col items-center mb-2 text-ui-primary">
          <Logo :width="80" />
          <h2 class="text-3xl text-6xl font-black tracking-tighter border-none">
            OpenAC .Net
          </h2>
        </div>
        <h1 class="text-4xl text-center lg:text-5xl">
          Automação Comercial em .Net.
        </h1>
        <p class="text-xl font-medium text-center">
          Componentes para ajudar na sua automação comercial em .Net.
          <br>
          <strong class="text-ui-primary">Tem um minuto?</strong>
        </p>

        <div class="flex justify-center mt-8">
          <g-link
            to="/docs/"
            class="flex items-center px-6 py-4 ml-auto text-2xl font-bold leading-none text-white border rounded-lg shadow-lg bg-ui-primary border-ui-primary transition-all duration-200 ease-out transform hover:shadow-xl hover:-translate-y-1"
          >
            Iniciar
            <ArrowRightCircleIcon class="ml-4" size="1x" />
          </g-link>
        </div>

        <p class="mt-8 text-center">
          Open Source. MIT License. <span class="border-b border-dashed border-ui-primary text-ui-primary">Make it your own</span>.
        </p>

      </div>

      <div class="pt-8 mx-auto mt-8 border-t md:mt-16 md:pt-16 border-top border-ui-border max-w-screen-sm"></div>

      <div class="flex flex-wrap justify-center -mx-4">
        <div class="flex flex-col items-center w-full px-4 mb-8 text-center md:w-1/3">
          <ZapIcon size="3x" class="mb-6 text-ui-primary" />
          <h3 class="font-bold tracking-wide uppercase text-ui-primary">
            Bibliotecas
          </h3>
          <p class="text-lg text-left">
            Utilizando a Plataforma .Net. você pode utilizar os componentes em qualquer linguagem .Net. <span class="border-b border-dashed border-ui-primary text-ui-primary">Inclusive VB .Net ou IronPython</span>.
          </p>
        </div>

        <div class="flex flex-col items-center w-full px-4 mb-8 text-center md:w-1/3">
          <SearchIcon size="3x" class="mb-6 text-ui-primary" />
          <h3 class="font-bold tracking-wide uppercase text-ui-primary">
            Execute em qualquer lugar
          </h3>
          <p class="text-lg text-left">
            Apesar do foco em aplicações desktop, você pode utilizar as mesma em qualquer aplicação web. <span class="border-b border-dashed border-ui-primary text-ui-primary">Em qualquer sistema operacional</span>.
          </p>
        </div>

        <div class="flex flex-col items-center w-full px-4 mb-8 text-center md:w-1/3">
          <MoonIcon size="3x" class="mb-6 text-ui-primary" />
          <h3 class="font-bold tracking-wide uppercase text-ui-primary">
            Frameworks Suportados
          </h3>
          <p class="text-lg text-left">
            Atualmente os componentes suportam os seguintes frameworks.
            <span class="border-b border-dashed border-ui-primary text-ui-primary">
              NET Framework 4.6.2 ou superior, Net 6 ou superior e Net Standard 2.0
            </span>.
          </p>
        </div>
      </div>

    </div>
  </Layout>
</template>

<script>
import Logo from '@/components/Logo';
import { ArrowRightCircleIcon, ZapIcon, CodeIcon, MoonIcon, SearchIcon } from 'vue-feather-icons';

export default {
  components: {
    Logo,
    ArrowRightCircleIcon,
    ZapIcon,
    CodeIcon,
    MoonIcon,
    SearchIcon
  },

  metaInfo() {
    const title = 'Pagina Inicial';
    const description = 'Documentação do componentes do Projeto OpenAC .Net!';

    return {
      title: title,
      meta: [
        {
          name: 'description',
          content: description
        },
        {
          key: 'og:title',
          name: 'og:title',
          content: title,
        },
        {
          key: 'twitter:title',
          name: 'twitter:title',
          content: title,
        },
        {
          key: 'og:description',
          name: 'og:description',
          content: description,
        },
        {
          key: 'twitter:description',
          name: 'twitter:description',
          content: description,
        },
      ]
    }
  }
}
</script>

<style>
.home-links a {
  margin-right: 1rem;
}
</style>
