<template>
  <article class="markdown-body">
    <h1 id="rest-countries-api">Journey Mentor REST Countries API</h1>
    <div class="figure">
      <img
        src="/designs/desktop-preview.jpg"
        alt="Design preview for the REST Countries API with color theme switcher coding challenge"
      />
      <p class="caption">
        Design preview for the REST Countries API with color theme switcher
        coding challenge
      </p>
    </div>
    <h2 id="the-challenge">The challenge</h2>
    <p>
      Your task is to build a project using the provided design files, integrate
      with the
      <a href="https://restcountries.com/#api-endpoints-v2"
        >REST Countries V2 API</a
      >
      to pull country data, and display it as demonstrated in the provided
      designs. You will find both a mobile and desktop version in light and dark
      mode color schemes for each page. Note that the final implementation
      doesn't have to be pixel perfect and anything close to the photos will
      suffice.
    </p>
    <h2 id="where-to-find-everything">Where to find everything</h2>
    <p>
      The design files, which are located in the
      <a href="#designs">designs</a> section below, are in JPG static format.
      This will mean that you'll need to use your best judgment for styles such
      as <code>font-size</code>, <code>padding</code> and <code>margin</code>.
    </p>
    <p>
      There are no assets for this challenge, as the country flags will be
      pulled from the
      <a href="https://restcountries.com/#api-endpoints-v2"
        >REST Countries V2 API</a
      >
      and you can use an icon font library for the icons.
    </p>
    <p>
      There is a
      <a href="./style-guide.md"><code>style-guide.md</code></a> file, which
      contains the information you'll need, such as the color palette and fonts.
    </p>
    <h2 id="the-challenge">Requirements</h2>
    <p>
      For the frontend framework, it is required to use
      <a href="https://vuejs.org" target="_blank">Vue</a> along with
      <a href="https://www.typescriptlang.org" target="_blank">TypeScript</a>
      and Vue 3 Composition API. You have the flexibility to choose the packages
      you need for tasks such as making HTTP requests or styling your project.
      Additionally, having a clean project structure will be considered a bonus.
    </p>
    <h2 id="designs">Designs</h2>
    <h3 id="mobile">Mobile</h3>
    <ul>
      <li><a href="/designs/mobile-design-home-light.jpg">Home Page</a></li>
      <li>
        <a href="/designs/mobile-design-home-dark.jpg">Home Page [Dark]</a>
      </li>
      <li><a href="/designs/mobile-design-detail-light.jpg">Detail Page</a></li>
      <li>
        <a href="/designs/mobile-design-detail-dark.jpg">Detail Page [Dark]</a>
      </li>
    </ul>
    <h3 id="desktop">Desktop</h3>
    <ul>
      <li><a href="/designs/desktop-design-home-light.jpg">Home Page</a></li>
      <li>
        <a href="/designs/desktop-design-home-dark.jpg">Home Page [Dark]</a>
      </li>
      <li>
        <a href="/designs/desktop-design-detail-light.jpg">Detail Page</a>
      </li>
      <li>
        <a href="/designs/desktop-design-detail-dark.jpg">Detail Page [Dark]</a>
      </li>
    </ul>
    <p>
      You can also download all the design files zipped
      <a href="/sources/design.zip">here</a>.
    </p>
    <h2 id="your-users-should-be-able-to">Your users should be able to</h2>
    <ul>
      <li>See all countries from the API on the homepage</li>
      <li>Search for a country using an <code>input</code> field</li>
      <li>Filter countries by region</li>
      <li>
        Click on a country to see more detailed information on a separate page
        (client-side routing)
      </li>
      <li>
        Clicking on border countries on the detail page should link the user to
        the detail of those countries
      </li>
    </ul>
    <h2 id="project-bonuses">Project bonuses</h2>
    <ul>
      <li>
        <strong>Bonus:</strong> Toggle the color scheme between light and dark
        mode <strong>without using any 3rd party libraries</strong>
      </li>
      <li>
        <strong>Bonus:</strong> Searching using the keywords
        <code>Grmany</code> or <code>Grmny</code> should also work
      </li>
      <li>
        <strong>Bonus:</strong> Add sort functionality for both
        <code>Population</code> and <code>Country Name</code>
      </li>
      <li>
        <strong>Bonus:</strong> Make all content server-side rendered and also
        have a fallback if the server-side render faces an error
      </li>
      <li>
        <strong>Bonus:</strong> Make sure the ratio for the country flags is 4:3
        or any other ratio you find suitable
      </li>
      <li><strong>Bonus:</strong> Add unit tests for components</li>
      <li>
        <strong>Bonus:</strong> Store the filters in the URL query strings and
        sync it with the component filter object
      </li>
      <li>
        <strong>Bonus:</strong> Add lazy loading for country images and list
      </li>
    </ul>
    <h2 id="deploying-your-project">Deploying your project</h2>
    <p>
      There are a number of ways to host your project for free. Please choose
      one and deploy it somewhere.
    </p>
    <h2 id="sharing-your-solution">Sharing your solution</h2>
    <p>
      Please reply to the email you received with a link to a GitHub repository
      that contains your code. This repository needs a
      <code>README.md</code> file that explains everything we need to know
      (including a link to the demo)
    </p>
    <h2 id="giving-feedback">Giving feedback</h2>
    <p>
      Feedback is always welcome, so if you have any to give on this challenge
      please email
      <a href="mailto:hassan@journeymentor.net"
        >Hassan[at]JourneyMentor[dot]Net</a
      >.
    </p>
    <p><strong>Have fun building!</strong> 🚀</p>
  </article>
</template>
