<script>
    import LinkItem from "./LinkItem.svelte"
    const dummyLinks = [
        {title: "Google", url: "https://www.google.com"}
    ]
</script>

{#each dummyLinks as link}
    <LinkItem title={link.title} url={link.url} />
{/each}