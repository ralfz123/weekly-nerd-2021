<script>
	import Header from './components/header/header.svelte'
	import Footer from './components/footer/footer.svelte'
  import ArticleList from './components/article/article.svelte';
</script>

<main>
	<Header />
	<ArticleList />
	<Footer />
</main>
	
<style>
  main {
    text-align: center;
    padding: 1em;
    max-width: 240px;
    margin: 0 auto;
  }

  h1 {
    color: #ff3e00;
    text-transform: uppercase;
    font-size: 4em;
    font-weight: 100;
  }

  @media (min-width: 640px) {
    main {
      max-width: none;
    }
  }
</style>
