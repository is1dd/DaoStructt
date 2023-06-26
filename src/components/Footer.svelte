<footer>
  <div id="first">
    <div id="second">
      <div style="display: flex;flex-direction:row;gap:4rem;">
        <img
          alt="daos logo"
          src="https://www.daostruct.xyz/_next/image?url=%2Fimages%2Flogos%2Fdao_struct.png&w=640&q=75"
        />
        <div
          style="display:flex;flex-direction: column;gap: 1.5rem;
        "
        >
          <p class="head">Legal</p>
          <a href={"/privacypolicies"}> Privacy Policy </a>
          <a href={"/termsconditions"}> Terms & Conditions </a>
        </div>
      </div>
      <div>
        <p class="head">Company</p>
        <a href={"/about"}> About </a>
        <a href={"/services"}> Services </a>
        <a href={"/about"}> Portfolio </a>
      </div>
      <div>
        <p class="head">Contact</p>
        <a
          color={"#ABAFC7"}
          _hover={{
            textDecoration: "none",
            color: "rgb(243 218 139 / 95%)",
          }}
          href="tel: +91 9988776614"
        >
          +91 9988776614
        </a>
        <a
          color={"#ABAFC7"}
          _hover={{
            textDecoration: "none",
            color: "rgb(243 218 139 / 95%)",
          }}
          href={"/about"}
        >
          info@daostruct.com
        </a>
        <a
          color={"#ABAFC7"}
          _hover={{
            textDecoration: "none",
            color: "rgb(243 218 139 / 95%)",
          }}
          href={"/about"}
        >
          Contact Us
        </a>
      </div>
    </div>
    <div
      style="display: flex;gap:1rem;width:80%;padding:1.4rem 0;justify-content:space-between;align-items:center;"
    >
      <p style="color:white">
        Copyright © 2023 Daostruct. All Rights Reserved.
      </p>
      <div style="display: flex;gap:1rem;">
        <a target="_blank" href={"https://instagram.com/"}
          >IG
          <!-- <BsInstagram /> -->
        </a>
        <a target="_blank" href={"https://instagram.com/"}>
          <!-- <FaaedinIn /> -->
          FB
        </a>
        <a target="_blank" href={"https://instagram.com/"}>
          LK
          <!-- <FaFacebookF /> -->
        </a>
      </div>
    </div>
  </div>
</footer>

<style>
  footer {
    background-color: rgb(10, 69, 213);
    color: rgb(254, 255, 254);
  }
  #first {
    display: flex;
    flex-direction: column;
    align-items: center;
  }
  #second {
    border-bottom: 1px solid #abafc7;
    display: flex;
    width: 80%;
    align-items: start;
    gap: 4rem;
    padding: 3rem 0rem;
  }
  a {
    color: white;
    text-decoration: none;
  }
  #second > div {
    display: flex;
    flex-direction: column;
    align-items: start;
    gap: 1.5rem;
  }
  a:hover {
    text-decoration: "none";
    color: black;
  }
  .head {
    font-size: 1.4rem;
    color: white;
    margin-bottom: 1rem;
  }
</style>
