<script>
  import Card from "../components/Card.svelte";
  import Footer from "../components/Footer.svelte";
  import Header from "../components/Header.svelte";
  import PageHeader from "../components/PageHeader.svelte";
  import Search from "../components/Search.svelte";
  import "../../src/style.css";
</script>

<div>
  <Header />
  <PageHeader />
  <Search />
  <div id="card">
    <Card />
    <Card />
    <Card />
    <Card />
    <Card />
    <Card />
    <Card />
    <Card />
    <Card />
  </div>
  <Footer />
</div>
