This project was mostly developed by the IPFS organization.

It is a package for developers to embed an IPFS node in any webpage.

----------------------------------------------------------------------------------------------------

All you need to do to start the ndoe in your webpage is:

1. Git clone this repo.
2. Add the following lines of code in the <head> tag. Make sure they are linking to the right files or else this will not work!

    <script src="index.min.js" defer></script>
    <script src="./src/index.js" type="module" defer></script>
    <link rel="stylesheet" href="index.css">

3. Optionally, you can add the following lines of code to your <body> to create a status indicator for the node. You can edit the index.css as you like.

    <div class="block">
      <h1>IPFS Node</h1>
      <h2 id="status">Node status: offline</h2>
    </div>

Now, you can look at the console, and you should see a "IPFS node online" indicator.

----------------------------------------------------------------------------------------------------

Make sure to like this project and shoutout to the IPFS developers who made the backend!