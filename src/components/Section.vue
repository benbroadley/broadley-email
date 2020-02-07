<template>
  <div class="bg">
    <div class="header" v-if="title">
      <h1>{{ title }}</h1>
    </div>
    <div
      class="content"
    >{ about: "Experienced Technical Specialist with a demonstrated history of working in the information technology and services industry. Skilled in Node.js / JavaScript, MEKN/MEVN stack, SQL, HTML, CSS, C#, Java, CSS and Python along with customer management, communication, technical leadership and team leadership. Business domain knowledge in Financial Services and Retail areas. Strong information technology professional graduated with a 1st Class (with Honours) in Computer Science from the University of Newcastle-upon-Tyne." }</div>

    <div class="content">
      {
      <br />projects: [
      <br />{ name: "
      <a href="https://twitter.com/EverydayAinsley">@EverydayAinsley</a>" desc: "Tweets the same picture everyday, hosted on an AWS EC2, written in Node.js v12." },
      <br />{ name: "
      <a href="https://twitter.com/AutoHorseNAPS">@AutoHorseNaps</a>" desc: "Automated horse tips, hosted on an AWS EC2, scheduled with cron, written in Node.js v12."},
      <br />],
      <br />}
      <br />
    </div>

    <div class="content">
      Lorem ipsum dolor sit, amet consectetur adipisicing elit. Sint itaque excepturi culpa eum veniam, dicta atque et facere tempora ad reiciendis voluptatibus commodi delectus! Eveniet beatae tempore cupiditate sit nemo cumque velit laborum praesentium fugiat quibusdam placeat illum provident quisquam sequi adipisci, nesciunt assumenda quod incidunt et, non iste libero! Nobis, ducimus quo. Autem dolorum rerum quam at ducimus quod sequi placeat facilis distinctio sunt, a obcaecati consequuntur reprehenderit non ea doloribus consectetur? Earum suscipit consectetur porro at ab. Placeat cum facilis quisquam ipsam, molestias consectetur voluptates fugiat excepturi tenetur velit et dolores, sed iste omnis, sunt debitis aperiam. Recusandae!
    </div>
    <div class="content">
      Lorem ipsum dolor sit, amet consectetur adipisicing elit. Sint itaque excepturi culpa eum veniam, dicta atque et facere tempora ad reiciendis voluptatibus commodi delectus! Eveniet beatae tempore cupiditate sit nemo cumque velit laborum praesentium fugiat quibusdam placeat illum provident quisquam sequi adipisci, nesciunt assumenda quod incidunt et, non iste libero! Nobis, ducimus quo. Autem dolorum rerum quam at ducimus quod sequi placeat facilis distinctio sunt, a obcaecati consequuntur reprehenderit non ea doloribus consectetur? Earum suscipit consectetur porro at ab. Placeat cum facilis quisquam ipsam, molestias consectetur voluptates fugiat excepturi tenetur velit et dolores, sed iste omnis, sunt debitis aperiam. Recusandae!
    </div>
  </div>
</template>

<script>
export default {
  name: 'Section',
  props: {
    title: String,
  },
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
.header {
  padding: 15px;
  text-align: center;
  -webkit-box-shadow: 0px 5px 15px 1px rgba(0, 0, 0, 0.5);
  -moz-box-shadow: 0px 5px 15px 1px rgba(0, 0, 0, 0.5);
  box-shadow: 0px 5px 15px 1px rgba(0, 0, 0, 0.5);
  background-color: #262626;
  color: #d3d3d3;
  position: sticky;
  top: 0;
}

.content {
  margin: 5% 15%;
  font-size: 1.2em;
}

.bg {
  /* The image used */
  /* background-image: url('../assets/bk.png'); */

  /* Full height */
  height: 95vh;

  /* Center and scale the image nicely */
  background-position: center;
  background-repeat: repeat;
  background-size: cover;
}
</style>