<script lang="ts">
  import { SomeEnum } from "$lib/enums";

  $: initial = true ? SomeEnum.FOO : SomeEnum.BAR;
</script>

<h1>Repro reactive_declaration_non_reactive_property</h1>
<p>
  Visit <a href="https://github.com/sveltejs/eslint-plugin-svelte/issues/896"
    >for the related Github issue.</a
  >
</p>

<h2>See code</h2>
{initial}
