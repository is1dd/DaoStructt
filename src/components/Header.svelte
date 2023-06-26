<script>
</script>

<div id="header">
  <img
    alt="daos logo"
    src="https://www.daostruct.xyz/_next/image?url=%2Fimages%2Flogos%2Fdao_struct.png&w=640&q=75"
  />
  <div>
    <button class="header-btn"> Discover </button>
    <button class="header-btn"> Knowledge Hub </button>
    <button disabled="true" id="connect">Connect Wallet</button>
  </div>
</div>

<style>
  #header {
    position: sticky;
    top: 0;
    padding: 1rem;
    display: flex;
    justify-content: space-between;
    background-color: white;
    z-index: 1;
  }
  #connect {
    border: 1px solid black;
    border-radius: 2rem;
    padding: 0.7rem 0.8rem;
    font-size: 0.8rem;
    background: white;
    color: #d3bcbc;
    cursor: pointer;
  }
  .header-btn {
    font-size: 1rem;
    padding: 0.5rem 1rem;
    background: none;
    border: none;
    align-items: center;
    cursor: pointer;
  }
  .header-btn:hover {
    background-color: rgb(221, 221, 221);
    border-radius: 5px;
  }
  .header-btn:first-child {
    color: rgb(9, 65, 213);
  }
  .header-btn:last-child {
  }
  #header > div {
    display: flex;
    align-items: center;
    gap: 1rem;
  }
</style>
