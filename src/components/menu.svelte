<script>
    const menu = [
        {
            text: 'Join',
            link: 'join'
        },
        {
            text: 'About',
            link: 'about'
        },
        {
            text: 'Map',
            link: 'map'
        },
    ]

</script>

<div class="menu">
    {#each menu as option}
        <h2>
            <a href={option.link}>
                {option.text}
            </a>
        </h2>
    {/each}

</div>

<style>
    .menu {
        color: #fcccbc;
    }

</style>