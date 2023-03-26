<h1>Test 1</h1>
<p>This page has styles applied to the header via the :global() selector.</p>
<p>When you navigate back to the homepage, this css will still be affecting the header.</p>
<p>In order to remove this css, you need to navigate back to the homepage and refresh the site. I'm not even sure there is any way to programatically remove this CSS.</p>

<style>
    :global(header) {
        color: white;
        background-color: black;
    }
</style>
