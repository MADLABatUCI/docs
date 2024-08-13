---
type: docs
title: Examples
weight: 1
#sidebar:
#  open: true

sections:
  - block: hero
    content:
      title: Packages/Libraries
      text: 'View examples from packages and libraries created by the MADLAB group'
      primary_action:
        #icon: brands/x
        text: MADLAB Website
        url: "https://steyvers.socsci.uci.edu/madlab/"
      secondary_action:
        text: Dr. Mark Steyvers (MADLAB P.I.)
        url: https://steyvers.socsci.uci.edu/
    design:
      no_padding: true
      spacing:
        padding: [0, 0, 0, 0]
        margin: [0, 0, 0, 0]
  - block: collection
    content:
      title: 'MPLib.js'
      text: 'Multiplayer Gaming Library'
      filters:
        folders:
          - examples
        tag: 'mplib'
    design:
      view: card
      spacing:
        padding: ['3rem', 0, '6rem', 0]
---

<style>
  a {
    text-decoration: none !important;
  }
  .example-card {
    margin: 20px 0px 20px 0px;
  }
  .example-image {
    height: 100%;
    margin-top: 0px;
    margin-bottom: 0px;
  }
</style>

<div class="example-card container max-w-[65ch] mx-auto bg-white dark:bg-zinc-900 rounded-xl border-gray-100 dark:border-gray-700 border shadow-md overflow-hidden my-5">
  <a href="https://madlabatuci.github.io/mplib/examples/pong/mppong.html?minPlayersNeeded=2&amp;maxPlayersNeeded=2&amp;fps=60" target="_blank" rel="noopener" class="mb-5">
    <div class="md:flex">
      <div class="md:flex-shrink-0 overflow-hidden">
        <img class="example-image h-48 w-full object-cover md:w-48 hover:scale-125 transition duration-500 cursor-pointer object-cover" loading="lazy" src="/examples/mplib/pong/featured.png" height="655" width="655" alt="2-Player Pong">
      </div>
      <div class="p-8">
        <div class="uppercase tracking-wide text-md text-primary-700 dark:text-primary-200 font-semibold">
          2-Player Pong
        </div>
        <p class="block mt-1 text-sm leading-tight font-medium text-black dark:text-white">
          A two-player pong game.
        </p>
        <p class="mt-2 text-gray-500 dark:text-gray-400 text-sm">
          <b>Game Type</b>: Continuous
        </p>
      </div>
    </div>
  </a>
</div>
<div class="example-card container max-w-[65ch] mx-auto bg-white dark:bg-zinc-900 rounded-xl border-gray-100 dark:border-gray-700 border shadow-md overflow-hidden my-5">
  <a href="https://madlabatuci.github.io/mplib/examples/gridworld/gridworld.html" target="_blank" rel="noopener" class="mb-5">
    <div class="md:flex">
      <div class="md:flex-shrink-0 overflow-hidden">
        <img class="example-image h-48 w-full object-cover md:w-48 hover:scale-125 transition duration-500 cursor-pointer object-cover" loading="lazy" src="/examples/mplib/gridworld/featured.png" height="655" width="655" alt="Grid World">
      </div>
      <div class="p-8">
        <div class="uppercase tracking-wide text-md text-primary-700 dark:text-primary-200 font-semibold">
          Grid World
        </div>
        <p class="block mt-1 text-sm leading-tight font-medium text-black dark:text-white">
          A grid world game where you need to collect tokens (there can be multiple participants at once).
        </p>
        <p class="mt-2 text-gray-500 dark:text-gray-400 text-sm">
          <b>Game Type</b>: Continuous
        </p>
      </div>
    </div>
  </a>
</div>
<div class="example-card container max-w-[65ch] mx-auto bg-white dark:bg-zinc-900 rounded-xl border-gray-100 dark:border-gray-700 border shadow-md overflow-hidden my-5">
  <a href="https://madlabatuci.github.io/mplib/examples/tictactoe/tictactoe.html" target="_blank" rel="noopener" class="mb-5">
    <div class="md:flex">
      <div class="md:flex-shrink-0 overflow-hidden">
        <img class="example-image h-48 w-full object-cover md:w-48 hover:scale-125 transition duration-500 cursor-pointer object-cover" loading="lazy" src="/examples/mplib/tictactoe/featured.png" height="655" width="655" alt="Tic-Tac-Toe">
      </div>
      <div class="p-8">
        <div class="uppercase tracking-wide text-md text-primary-700 dark:text-primary-200 font-semibold">
          Tic-Tac-Toe
        </div>
        <p class="block mt-1 text-sm leading-tight font-medium text-black dark:text-white">
          A two-player turn-taking game.
        </p>
        <p class="mt-2 text-gray-500 dark:text-gray-400 text-sm">
          <b>Game Type</b>: Turn-Taking
        </p>
      </div>
    </div>
  </a>
</div>
<div class="example-card container max-w-[65ch] mx-auto bg-white dark:bg-zinc-900 rounded-xl border-gray-100 dark:border-gray-700 border shadow-md overflow-hidden my-5">
  <a href="https://madlabatuci.github.io/mplib/examples/virtualworld/virtualworld.html" target="_blank" rel="noopener" class="mb-5">
    <div class="md:flex">
      <div class="md:flex-shrink-0 overflow-hidden">
        <img class="example-image h-48 w-full object-cover md:w-48 hover:scale-125 transition duration-500 cursor-pointer object-cover" loading="lazy" src="/examples/mplib/virtual3dworld/featured.png" height="655" width="655" alt="Virtual 3D World">
      </div>
      <div class="p-8">
        <div class="uppercase tracking-wide text-md text-primary-700 dark:text-primary-200 font-semibold">
          Virtual 3D World
        </div>
        <p class="block mt-1 text-sm leading-tight font-medium text-black dark:text-white">
          A virtual 3D world that is VR compatable.
        </p>
        <p class="mt-2 text-gray-500 dark:text-gray-400 text-sm">
          <b>Game Type</b>: Continuous
        </p>
      </div>
    </div>
  </a>
</div>
<div class="example-card container max-w-[65ch] mx-auto bg-white dark:bg-zinc-900 rounded-xl border-gray-100 dark:border-gray-700 border shadow-md overflow-hidden my-5">
  <a href="https://madlabatuci.github.io/mplib/examples/groupestimation/groupestimation.html" target="_blank" rel="noopener" class="mb-5">
    <div class="md:flex">
      <div class="md:flex-shrink-0 overflow-hidden">
        <img class="example-image h-48 w-full object-cover md:w-48 hover:scale-125 transition duration-500 cursor-pointer object-cover" loading="lazy" src="/examples/mplib/groupestimation/featured.png" height="655" width="655" alt="Group Estimation">
      </div>
      <div class="p-8">
        <div class="uppercase tracking-wide text-md text-primary-700 dark:text-primary-200 font-semibold">
          Group Estimation
        </div>
        <p class="block mt-1 text-sm leading-tight font-medium text-black dark:text-white">
          A 2-5 player group estimation game.
        </p>
        <p class="mt-2 text-gray-500 dark:text-gray-400 text-sm">
          <b>Game Type</b>: Continuous Turn-Taking
        </p>
      </div>
    </div>
  </a>
</div>

{{< cards >}}
  {{< card url="project-structure" title="Project Structure" icon="document-duplicate" >}}
  {{< card url="configuration" title="Configuration" icon="adjustments-vertical" >}}
{{< /cards >}}
