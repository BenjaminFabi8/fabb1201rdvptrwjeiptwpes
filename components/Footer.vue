<template>
  <footer class="my-20" role="contentinfo">
    <p class="text-sm text-center text-zinc-600">
      Copyright &copy; {{ new Date().getFullYear() }} rdvptrwjeiptwpes. Powered by 
      <a href="https://www.netlify.com/" class="underline" rel="nofollow">Netlify</a>.
    </p>

    <div class="mt-8">
      <h1 style="text-align: center;">Change Log</h1>
      <table class="table-auto mx-auto text-sm text-zinc-600 border-collapse border border-zinc-300">
        <thead>
          <tr>
            <th class="border border-zinc-300 px-4 py-2">Date</th>
            <th class="border border-zinc-300 px-4 py-2">Change</th>
          </tr>
        </thead>
        <tbody>
          <tr>
            <td class="border border-zinc-300 px-4 py-2">January 16, 2025</td>
            <td class="border border-zinc-300 px-4 py-2">added .txt file with keyword</td>
          </tr>
          <tr>
            <td class="border border-zinc-300 px-4 py-2">February 8, 2025</td>
            <td class="border border-zinc-300 px-4 py-2">Nuxt Compression, keywords and image</td>
          </tr>
        </tbody>
      </table>
    </div>
  </footer>
</template>

<script>
export default {
  name: "Footer",
};
</script>
