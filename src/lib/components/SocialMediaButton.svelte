<script lang="ts">
	export let name: string;
	export let link: string;
	export let svgPath: string;
	export let viewBox: string;
</script>

<li class="mr-5 text-xs">
	<a class="block hover:text-slate-200" href={link} target="_blank" rel="noreferrer"
		><span class="sr-only">{name}</span><svg
			xmlns="http://www.w3.org/2000/svg"
			{viewBox}
			fill="currentColor"
			class="h-6 w-6"
			aria-hidden="true"><path d={svgPath}></path></svg
		></a
	>
</li>
