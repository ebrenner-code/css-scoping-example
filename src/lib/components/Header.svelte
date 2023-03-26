<header>
    <a href="/" class="title">CSS Scoping Example</a>
    <nav>
        <ul>
            <li><a href="/">Home</a></li>
            <li><a href="/test-1">Test 1</a></li>
            <li><a href="/test-2">Test 2</a></li>
        </ul>
    </nav>
</header>

<style>
    header{
        display: flex;
        align-items: center;
    }

    .title {
        font-size: 1.25rem
    }

    nav {
        display: flex;
        justify-content: flex-end;
    }

    ul {
        display: flex;
        list-style: none;
    }

    li {
        margin-left: 1rem;
    }

    a{
        color: inherit;
    }
</style>