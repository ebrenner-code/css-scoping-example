<div>
    <h1>About</h1>
    <p>This page has styles applied to the header by putting the style block into the html (not at the top level) and without using the :global() selector.</p>
    <p>This works great, with the only downside being it is not an official svelte solution and feels hacky. It also means this css is reloaded everytime a component or page is mounted which would hinder performance with large blocks of css.</p>
    
    <style>
        header {
            color: white;
            background-color: navy;
        }
    </style>
</div>
