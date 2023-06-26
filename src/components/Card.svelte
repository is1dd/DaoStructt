
<div id="container">
  <div id="header">
    <img
      src="https://deepdao-uploads.s3.us-east-2.amazonaws.com/assets/dao/logo/polkadot.png"
      alt="logo first"
    />
    <div>
      <button>Infrastructure</button>
      <button>Media & Commons</button>
      <button>Investments</button>
    </div>
  </div>
  <h2>Polkadot</h2>
  <p>
    Polkadot Is A Fully- Sharded, Layer 0 Blockchain Technology. It Offers The
    Groundwork And Security Needed To Ea...
  </p>
  <div id="footer">
    <img
      alt="left-logo"
      src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcSxkUd3z62gqWXfetFpDK8wE_kj6W00nf32v0JcM04GVXJl6ck1RM5Azu6lmTSJ9VUMX5I&usqp=CAU"
    />
    <div style="display: flex; align-items: center;">
      <p style="font-size: 1.5rem;font-weight:600;padding:0;margin:0;">DOT</p>
      <img
        src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcSxkUd3z62gqWXfetFpDK8wE_kj6W00nf32v0JcM04GVXJl6ck1RM5Azu6lmTSJ9VUMX5I&usqp=CAU"
        alt="right-logo"
      />
    </div>
  </div>
</div>

<style>
  button {
    cursor: pointer;
  }
  #container {
    border: 1px solid gray;
    border-radius: 1rem;
    padding: 1rem;
    padding-top: 2rem;
  }
  #header {
    display: flex;
    position: relative;
    justify-content: flex-end;
  }
  #header > div {
    display: flex;
    flex-direction: column;
    gap: 0.9rem;
  }
  #header button {
    background: none;
    border: 1px solid #dc143c;
    color: #dc143c;
    border-radius: 3px;
    padding: 0.4rem;
  }
  #header > img {
    width: 7rem;
    height: 7rem;
    border-radius: 50%;
    box-shadow: rgba(0, 0, 0, 0.1) 0px 4px 6px -1px,
      rgba(0, 0, 0, 0.06) 0px 2px 4px -1px;
    position: absolute;
    bottom: 4.8rem;
    left: 0.4rem;
  }
  #footer {
    display: flex;
    justify-content: space-between;
  }
  #footer img:first-child {
    width: 2.5rem;
    height: 2.5rem;
  }
  #footer img:last-child {
    width: 2rem;
    height: 2rem;
  }
</style>
