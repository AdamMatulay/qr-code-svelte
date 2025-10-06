<main>
  <article class="qrCard">
    <img src="./images/image-qr-code.png" alt="QR code">
    <h1>Improve your front-end skills by building projects</h1>
    <p>Scan the QR code to visit Frontend Mentor and take your coding skills to the next level</p>
  </article>
</main>

<style>
  :global(body) {
    padding: 0;
    margin: 0;
    display: flex;
    justify-content: center;
    align-items: center;
    background-color: hsl(212, 45%, 89%);
    min-height: 100vh;
    font-size: 15px;
    font-family: 'Outfit', sans-serif;
  }

  .qrCard{
    border-radius: 20px;
    background-color: white;
    max-width: 285px;
    min-height: 460px;
    text-align: center;
    box-shadow: 0px 25px 35px rgba(0,0,0,0.08);
    padding: 1em;
  }

  .qrCard img{
    max-width: 100%;
    border-radius: 10px;
    
  }

  .qrCard h1{
    font-size: 1.4em;
    color:  hsl(217, 16%, 22%); 
  }

  .qrCard p{
    color: hsl(216, 15%, 48%);
    line-height: 1.4em;
  }

  .qrCard p, .qrCard h1{
    padding: 0 15px;
  }

  /* extra maly displej */
@media (max-width: 330px) {
  .qrCard h1 {
    font-size: 1.2em;
  }
  .qrCard p {
    font-size: 0.9em;
  }
  .qrCard{
    max-width: 255px;
  }

}

</style>
