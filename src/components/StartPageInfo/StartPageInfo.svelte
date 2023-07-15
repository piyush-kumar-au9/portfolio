<script>
  import styles from "./startpage.module.css";
</script>

<div class={styles.infoTxt}>
  <div>
    Hi! I Am <span class={styles.roleBtn}>FSD</span>
  </div>
  <div>Piyush Kumar</div>

  <p>Developing Full stack applications for over <b>3 years</b></p>
  <p>as a Software Engineer</p>
  <br />

  <span>
    <button
      type="submit"
      class={styles.submitBtn}
      on:click={() => {
        alert("Hire Me Clicked!!!");
      }}>Hire Me</button
    >
    <span class={styles.projectsLink}> <a href="#top"> Projects &#x2197 </a> </span>
  </span>
</div>
