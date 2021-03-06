<script>
  import { data } from '../../data.js';
</script>

{#each data as { id, title, question, content }}
  <h2>
    <a href="#{title}">#{id} - {title}</a>
  </h2>

  <details>
    <summary>Artikel</summary>
    <p>{question}</p>
    <p>
      {content}
    </p>
  </details>
{/each}

<style>
 
</style>
