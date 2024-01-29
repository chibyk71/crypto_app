<script>
	import { melt } from "@melt-ui/svelte";
	import { getContext } from "svelte";
	import { slide } from "svelte/transition";
    const id = Math.round(Math.random()*Date.now()).toString(32)
    const item = getContext("item");
    const trigger = getContext("trigger");
    const content = getContext("content");
    const isSelected = getContext("isSelected");
     /**
	 * @type {any}
	 */
      export let title;
</script>
<div class="accordion-item" use:melt={$item(id)}>
    <h5 class="accordion-header lgtxt">
        <button use:melt={$trigger(id)} class="accordion-button w-full text-left relative {(!$isSelected(id))?"collapsed":""}" type="button">
            {@html title}
        </button>
    </h5>
    {#if $isSelected(id)}
        <div class="accordion-collapse" transition:slide use:melt={$content(id)}>
            <div class="accordion-body">
                <slot />
            </div>
        </div>
    {/if}
</div>