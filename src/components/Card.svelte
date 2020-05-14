<script>
    import Comments from './Comments.svelte';
</script>

<div class="Card">
  <div class="Card-container">
    <div class="Card-header">
      <div class="Card-user">
        <img src="" alt="Imagen de publicación de mascota" />
        <h2>
          Rocky.pug
          <span>Valparaíso, Chile</span>
        </h2>
      </div>
      <div class="Card-settings">
        <i class="fas fa-ellipsis-h" />
      </div>
    </div>
    <div class="Card-photo">
      <figure>
        <img src="" alt="Imagen de publicación de mascota" />
      </figure>
    </div>
    <div class="Card-icons">
      <div class="Card-icons-first">
        <i class="fas fa-heart" />
        <i class="fas fa-paper-plane" />
      </div>
      <div class="Card-icons-second">
        <i class="fas fa-bookmark" />
      </div>
    </div>
    <div class="Card-description">
      <h3>rocky.pug</h3>
      <span>Hola!</span>
    </div>
    <Comments />
  </div>
</div>
