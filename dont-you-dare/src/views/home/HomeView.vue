<template>
  <div class="home">
    <header class="pt-5 pb-5">
      <nav class="navbar navbar-expand-lg">
        <div class="container-fluid">
          <a href="#" class="navbar-brand ps-5">Don't You Dare</a>
          <button
            class="navbar-toggler"
            type="button"
            data-bs-toggle="collapse"
            data-bs-target="#navbarNav"
            aria-controls="navbarNav"
            aria-expanded="false"
            aria-label="Toggle navigation"
          >
            <span class="navbar-toggler-icon"></span>
          </button>
          <div
            class="collapse navbar-collapse justify-content-end ps-5"
            id="navbarNav"
          >
            <ul class="navbar-nav">
              <li class="nav-item pe-3"><a href="#About">About</a></li>
              <li class="nav-item pe-3">
                <a href="#Instruction">Instruction</a>
              </li>
              <li class="nav-item pe-3"><a href="#Rules">Rules</a></li>
              <li class="nav-item pe-3">
                <a href="#Start">Get Started</a>
              </li>
            </ul>
          </div>
        </div>
      </nav>
    </header>
    <hr />
    <section id="About" class="pt-5 pb-5 container-fluid">
      <div class="row justify-content-center">
        <div class="col col-9 col-sm-6">
          <h2 class="text-center text-md-start">About</h2>
          <p class="pt-3">
            Don't you Dare is a Technical quiz challenge where you will be
            competing with world wide techies to stand first in the leaderboard
          </p>
        </div>
      </div>
    </section>
    <hr />
    <section id="Instruction" class="pt-5 pb-5 container-fluid">
      <div class="row justify-content-center">
        <div class="col col-9 col-sm-6">
          <h2 class="text-center text-md-start">How to Compete</h2>
          <ul class="pt-3">
            <li>Click on Get Started</li>
            <li>Enter your name</li>
            <li>Choose the technology you want to challenge yourself</li>
            <li>Click on Let's do it</li>
          </ul>
        </div>
      </div>
    </section>
    <hr />
    <section id="Rules" class="pt-5 pb-5 container-fluid">
      <div class="row justify-content-center">
        <div class="col col-9 col-sm-6">
          <h2 class="text-center text-md-start">Rules</h2>
          <ul class="pt-3">
            <li>
              You will be provided with 10 tokens at the beginning of the
              challenge
            </li>
            <li>
              To attempt each question, 2 tokens will be charged. You will have
              1 min to answer the question
            </li>
            <li>
              If the selected answer is correct, the tokens charged for the
              attempt + 1 token will be rewarded
            </li>
            <li>
              If the selected answer is incorrect, the tokens charged for the
              attempt + 1 token will be deducted
            </li>
            <li>
              If you want to attempt the same question again, you will be
              charged 2 tokens and the overall time per question will be reduced
              by 5 seconds by then
            </li>
          </ul>
        </div>
      </div>
    </section>
    <hr />
    <section id="Start" class="pt-5 pb-5 container-fluid">
      <div class="row justify-content-center">
        <div class="col col-9 col-sm-6">
          <h2 class="text-center">Do You Dare?</h2>
          <div class="text-center pt-3">
            <button>Get Started</button>
          </div>
        </div>
      </div>
    </section>
    <hr />
    <footer class="pt-5 pb-5">
      <div class="row justify-content-center">
        <div class="col col-9 col-sm-6">
          <h4 class="text-center">Contact Me</h4>
          <div class="text-center pt-3">
            <a
              href="https://www.linkedin.com/in/mithun-mani-22630b175/"
              class="pe-2 ps-2"
              >LinkedIn</a
            >
            <a href="mailto:mmithunsai@gmail.com" class="pe-2 ps-2">GMail</a>
            <a href="https://github.com/mithunsai" class="pe-2 ps-2">GitHub</a>
          </div>
        </div>
      </div>
    </footer>
  </div>
</template>
<script>
export default {
  setup() {},
  name: "HomeView",
};
</script>
<style></style>
