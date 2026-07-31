<template>
  <div class="min-h-screen bg-white text-gray-900">

    <!-- Header -->
    <header>
      <div class="mx-auto flex max-w-6xl items-center justify-between px-6 py-6">
        <div>
          <h1 class="text-xl font-semibold tracking-tight">
            Quantum Ripple
          </h1>
          <p class="mt-1 text-sm text-gray-500">
            Building technology for communities.
          </p>
        </div>

        <router-link
          to="/contact"
          class="rounded-md border border-gray-300 px-4 py-2 text-sm font-medium transition hover:bg-gray-100"
        >
          Contact
        </router-link>
      </div>
    </header>

    <!-- Hero -->
    <section class="mx-auto max-w-4xl px-6 pt-24 pb-28">

      <p class="mb-5 text-sm font-semibold uppercase tracking-[0.2em] text-gray-500">
        Community-Driven Software Initiative
      </p>

      <h2 class="text-5xl font-bold leading-tight tracking-tight md:text-6xl">
        Solving problems<br>
        through technology.
      </h2>

      <p class="mt-10 max-w-3xl text-xl leading-9 text-gray-600">
        Quantum Ripple is a community-driven software initiative bringing together
        experienced engineers who contribute their skills to build digital
        solutions that strengthen communities, empower organizations, and improve lives.
      </p>

      <p class="mt-8 max-w-3xl text-lg leading-8 text-gray-600">
        We believe technology is more than software.
        It is a tool for solving real-world challenges, creating opportunities,
        and making everyday life better.
      </p>

      <div class="mt-14 flex flex-wrap gap-4">

        <router-link
          to="/contact"
          class="rounded-md bg-gray-900 px-6 py-3 font-medium text-white transition hover:bg-black"
        >
          Have a Problem Worth Solving?
        </router-link>

        <a
          href="mailto:hello@quantumripple.co.ke"
          class="rounded-md border border-gray-300 px-6 py-3 transition hover:bg-gray-100"
        >
          Email Us
        </a>

      </div>

    </section>

    <!-- Why -->
    <section class="mx-auto max-w-4xl px-6 py-24">

      <h3 class="text-3xl font-semibold tracking-tight">
        Why we exist
      </h3>

      <p class="mt-10 text-lg leading-9 text-gray-600">
        Every community has problems.
      </p>

      <p class="mt-4 text-lg leading-9 text-gray-600">
        Some are solved through policy.
        Others through education.
        Many can be solved through technology.
      </p>

      <p class="mt-8 text-lg leading-9 text-gray-600">
        Yet countless schools, organizations, startups and community initiatives
        never build the systems they need because quality software is often
        expensive and inaccessible.
      </p>

      <p class="mt-8 text-lg leading-9 text-gray-600">
        Quantum Ripple exists to change that.
        We bring together experienced engineers who freely contribute their
        knowledge to create practical digital solutions that make a lasting impact.
      </p>

    </section>

    <!-- Philosophy -->
    <section class="bg-gray-50">

      <div class="mx-auto max-w-4xl px-6 py-24">

        <h3 class="text-3xl font-semibold tracking-tight">
          What we believe
        </h3>

        <div class="mt-16 space-y-14">

          <div>
            <h4 class="text-2xl font-semibold">
              Technology should serve people.
            </h4>

            <p class="mt-3 text-lg leading-8 text-gray-600">
              The best technology isn't the most complicated.
              It's the technology that quietly makes life better.
            </p>
          </div>

          <div>
            <h4 class="text-2xl font-semibold">
              Great ideas deserve great software.
            </h4>

            <p class="mt-3 text-lg leading-8 text-gray-600">
              Limited resources should never prevent meaningful ideas from
              becoming reality.
            </p>
          </div>

          <div>
            <h4 class="text-2xl font-semibold">
              Communities grow when knowledge is shared.
            </h4>

            <p class="mt-3 text-lg leading-8 text-gray-600">
              Our greatest contribution isn't just software.
              It's people coming together to build a better future.
            </p>
          </div>

        </div>

      </div>

    </section>

    <!-- Quote -->

    <section class="mx-auto max-w-3xl px-6 py-28 text-center">

      <blockquote class="text-4xl font-semibold leading-relaxed tracking-tight text-gray-900 md:text-5xl">
        "Technology should improve lives before it improves profits."
      </blockquote>

    </section>

    <!-- Contact -->

    <section
      id="contact"
      class="mx-auto max-w-4xl px-6 pb-28"
    >

      <h3 class="text-4xl font-bold tracking-tight">
        Have a problem worth solving?
      </h3>

      <p class="mt-8 max-w-2xl text-lg leading-8 text-gray-600">
        Whether you're a school, community initiative, organization,
        startup or small business, we'd love to hear your idea.
      </p>

      <div class="mt-12 space-y-4 text-lg">

        <p>
          <strong>Email</strong><br>
          hello@quantumripple.co.ke | quantumrippleltd@gmail.com
        </p>

        <p>
          <strong>Phone</strong><br>
          +254 714 474 770 | +254 796 663 544
        </p>

        <p>
          <strong>Location</strong><br>
          Machakos, Kenya
        </p>

      </div>

    </section>

    <!-- Footer -->

    <footer class="border-t border-gray-200">

      <div class="mx-auto flex max-w-6xl flex-col justify-between gap-3 px-6 py-8 text-sm text-gray-500 md:flex-row">

        <p>
          © {{ year }} Quantum Ripple.
        </p>

        <p>
          Building technology for communities.
        </p>

      </div>

    </footer>

  </div>
</template>

<script setup>
const year = new Date().getFullYear()
</script>