<script>
  export let nickname;
  export let name;

</script>
<style>
  .Profile-content {
    display: flex;
    align-items: center;
  }
  .Profile-avatar img {
    width: 42px;
    height: 42px;
    border-radius: 50%;
  }
  .Profile-info {
    margin: 0 0 0 0.5em;
  }
  .Profile-info h2 {
    font-size: 14px;
    color: black;
    margin: 0;
    padding: 0;
  }
  .Profile-info span {
    font-size: 12px;
    font-weight: normal;
  }
</style>

<div class="Profile">
    <div class="Profile-content">
        <div class="Profile-avatar">
            <img src="https://es.gravatar.com/avatar/2bd6474c77fd501924adfa0aae631f57" 
            alt="Perfile">

        </div>
        <div class="Profile-info">
            <h2>{nickname}</h2>
            <span>{name}</span>
        </div>
    </div>
</div>