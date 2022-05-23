<script>
    import { page } from "$app/stores";
</script>

<svelte:head>
    <script src="https://kit.fontawesome.com/9af48a40fc.js" crossorigin="anonymous"></script>
</svelte:head>

<body>

<nav class="nav-class">
    <div>&nbsp;</div>
    <ul>
        <li>Discover</li>
        <li>Components</li>
        <li>Pages</li>
        <li>Chats</li>
    </ul>
</nav>

</body>
<slot />
<style>
    body {
        margin: 0;
        font-family: "Inter",sans-serif;
        font-size: 15px;
        line-height: 2.55rem;
        letter-spacing: -.015rem;
    }
    ul {
        display: flex;
        list-style: none;
        padding-left: 45 0px;
        justify-content: center;
    }
    li {
        margin-right: 50px;
        font-weight: 700;
        font-size: 20px;
        text-decoration: none;
        color: white;
        
    }
    li:hover {
        text-decoration: underline; 
    }
    .nav-class {
        display: flex;
        background-color: #1E74FD;
        margin: 0;
        height: 50px 20px;
        justify-content: center;
    }
</style>