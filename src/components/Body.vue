<template>
  <div>
    <b-card>
        <b-embed
        type="iframe"
        aspect="4by3"
        src="https://www.youtube.com/embed/zpOULjyy-n8?rel=0">
        </b-embed>
    </b-card>
  </div>
</template>

<script>
export default {
  name: "Body",
  props: {
    msg: String
  }
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
b-embed {
    height: 100px;
    wight: 100px;
}
</style>