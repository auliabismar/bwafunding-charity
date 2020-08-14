<script>
  import CharityList from '../components/CharityList.svelte';
  import {charities} from '../data/charity';
  import Header from '../components/Header.svelte';
  import Footer from '../components/Footer.svelte';
  import Promo from '../components/Promo.svelte';
  import Welcome from '../components/Welcome.svelte';
</script>

<Header />
<Welcome />
<CharityList {charities}/>
<Promo />
<Footer />