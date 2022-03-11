<script lang="ts">
</script>

<div class="wrapper">
  <header>
    <img src="mountain.jpg" alt="" class="background" />
    <img src="Forest-Tree-Transparent-PNG.png" alt="" class="foreground" />
    <h1 class="title">Welcome!</h1>
  </header>
  <section>
    Lorem ipsum dolor sit amet consectetur adipisicing elit. Officiis et
    consectetur cum minus esse laboriosam totam adipisci consequatur,
    reprehenderit eos maxime molestias, natus, illum dignissimos! Vitae eum
    blanditiis iste suscipit error magnam sequi dolores, nostrum facere? Vero
    voluptatem corporis amet et asperiores rerum repellat minima perspiciatis
    quibusdam. Officia eaque dignissimos impedit blanditiis necessitatibus ea
    nemo aliquid est fugit. Perferendis similique quia placeat at repellat
    minima obcaecati, fuga, tempora ipsam aliquam fugiat maxime eum magni aut
    pariatur aliquid sed corrupti consequatur. Nostrum omnis quaerat in
    consequuntur ad laborum ipsam minus aspernatur libero consequatur hic, optio
    similique! Impedit nobis architecto repellendus consequatur odio explicabo
    laborum, officiis numquam laudantium nemo, neque non inventore sapiente
    incidunt aut praesentium? Porro aperiam magni velit non quibusdam illo
    consequuntur, consectetur ex doloribus ipsam aut quo labore, recusandae
    libero ratione tempora blanditiis neque pariatur voluptates explicabo
    dolore, exercitationem atque facilis aliquid. Ut consectetur dolores
    corporis velit dolorem, pariatur qui aperiam dolorum expedita? Ullam magnam
    harum sequi pariatur laborum aspernatur, commodi mollitia maxime ad
    voluptatibus natus accusantium qui velit eaque obcaecati quibusdam esse nam
    soluta beatae fuga consequatur deserunt cum maiores. Enim assumenda nesciunt
    quod maiores, nostrum labore. Deleniti, quis ab suscipit sunt sapiente
    quidem tempora doloribus fugit inventore nesciunt delectus autem maxime
    mollitia pariatur odit fuga animi tempore sed praesentium possimus
    excepturi. Debitis sequi officia ad fuga in magnam, praesentium facere quo
    corporis dolore dolorem quos, unde aperiam nostrum consequatur perferendis
    cum aliquid ratione optio deserunt inventore nobis recusandae. Laudantium,
    exercitationem similique asperiores deserunt ab non assumenda a. Dolores,
    dignissimos ipsam! Nam laboriosam porro laborum minus adipisci deserunt
    accusantium sequi vero corrupti non voluptatem, delectus quis magnam dicta
    debitis rem iure fuga in nobis tenetur. Esse voluptatum dignissimos
    perferendis quas. Laboriosam totam voluptatibus fugit sunt in quod
    reiciendis odit? Veniam, excepturi blanditiis. Voluptates ea rerum accusamus
    consectetur quas.
  </section>
</div>

<style>
  :global(body) {
    margin: 0;
    padding: 0;
  }

  .wrapper {
    height: 100vh;
    overflow-y: auto;
    overflow-x: hidden;
    perspective: 10px;
  }

  header {
    position: relative;
    display: flex;
    justify-content: center;
    align-items: center;
    height: 100%;
    transform-style: preserve-3d;
    z-index: -1;
  }

  .background {
    transform: translateZ(-20px) scale(3);
  }

  .foreground {
    transform: translateZ(-10px) scale(2);
  }
  .background,
  .foreground {
    position: absolute;
    height: 100%;
    width: 100%;
    object-fit: cover;
    z-index: -1;
  }
  .title {
    font-size: 7rem;
    color: white;
    text-shadow: 0 0 5px black;
  }

  section {
    font-size: 2rem;
    padding: 2rem;
    background-color: #333;
    color: white;
  }
</style>
