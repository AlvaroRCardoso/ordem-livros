<script>
  import ConteudoAutor from "../../../components/autor/ConteudoAutor.svelte";
  import { page } from "$app/stores";
</script>

<ConteudoAutor autor={$page.data.autor} />
