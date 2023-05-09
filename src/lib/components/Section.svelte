<script lang="ts">
    import Icon from "svelte-awesome";
    import type { IconType } from "svelte-awesome/components/Icon.svelte";

    export let iconData:IconType;
    export let title: string;
</script>

<div.class="container">
<div class="section-title">
    <Icon data={user} />
    {title}
</div>
<slot/>
</div>

<style>
    .container {
        display: flex;
        flex-direction: column;
        gap: 16px;
    }
    .section-title {
		display: flex;
		flex-direction: row;
		align-items: center;
		gap: 15px;
		background-color: #ffeb3b;
		border-left: 4px solid #fbc02d;
		color: black;
		padding: 8px 16px;
		text-transform: UPPERCASE;
		font-weight: 500;
	}
</style>