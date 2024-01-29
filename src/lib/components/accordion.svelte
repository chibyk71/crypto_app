<script lang="ts">
	import { createAccordion,melt } from "@melt-ui/svelte";
	import { setContext } from "svelte";

    const {
        elements: {content,item,trigger,root},
        helpers:{isSelected}
    } = createAccordion({}) 

    setContext("content",content);
    setContext("trigger",trigger);
    setContext("item",item);
    setContext("isSelected",isSelected)
</script>

<div class="accordion" {...$root}>
	<slot />
</div>
