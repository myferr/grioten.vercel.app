<script>
  import Layout from "../layout/Layout.svelte";
  import "./social-icons.scss";

  import Discord from "./assets/Discord.png";
  import X from "./assets/X.png";
</script>

<div id="background" />

<Layout>
  <div id="content-container">
    <div id="content">
      <img
        src="https://cdn.discordapp.com/avatars/999550667972673619/30cc570e003409fc0f06d2224c811f2f.webp?size=1024&format=webp&width=0&height=414"
        alt="User Avatar"
        class="avatar"
        width="100px"
        height="100px"
      />
      <h2>Grioten</h2>
      <div class="social-icon-wrapper">
        <div class="social-icon-container">
          <a href="https://x.com/woodsjoshu42723" target="_blank">
            <img
              src={X}
              width={18}
              height={20}
              alt="X"
              class="social-icon with-push"
            />
          </a>
          <a
            href="https://discord.com/users/999550667972673619"
            target="_blank"
          >
            <img
              src={Discord}
              width={25}
              height={20}
              alt="Discord"
              class="social-icon with-push"
            />
          </a>
        </div>
      </div>
    </div>
    <a class="credit" href="https://myferr.foo.ng" target="_blank"
      >created by myferr</a
    >
  </div>
</Layout>
