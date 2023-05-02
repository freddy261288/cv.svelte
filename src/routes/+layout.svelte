<svelte:head>
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin="anonymous">
    <link href="https://fonts.googleapis.com/css2?family=Open+Sans&family=Peralta&display=swap" rel="stylesheet">
    <script src="https://kit.fontawesome.com/d0c488930b.js" crossorigin="anonymous"></script>
    <meta name="viewport" content="width=device-width, initial-scale=1">
</svelte:head>

<slot />

<style>
   :global(*) {
    margin: 0;
    padding: 0;
    font-family: "Open Sans";
   }
   :global(html, body) {
    width: 100%;
    height: 100%;
    background-color: #fffde7;
   }
  
</style>
