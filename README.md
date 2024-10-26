
<style>
    * {
        margin: 0;
        padding: 0;
        box-sizing: border-box;
    }

    body {
        display: flex;
        justify-content: center;
        align-items: center;
        min-height: 100vh;
        background: #111;
        overflow: hidden;
        font-family: Arial, sans-serif;
    }

    .name {
        font-size: 6rem;
        font-weight: bold;
        background: linear-gradient(90deg, #ff6b6b, #5f27cd, #10ac84, #feca57);
        background-size: 300%;
        -webkit-background-clip: text;
        color: transparent;
        animation: animateBackground 8s linear infinite, flicker 1.5s ease-in-out infinite;
    }

    @keyframes animateBackground {
        0% { background-position: 0% 50%; }
        50% { background-position: 100% 50%; }
        100% { background-position: 0% 50%; }
    }

    @keyframes flicker {
        0%, 100% { opacity: 1; }
        50% { opacity: 0.8; }
    }
</style>

<h1 class="name">Dakhani Usman</h1>

<!---
DakhaniUsman/DakhaniUsman is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
