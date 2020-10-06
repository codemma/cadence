<template>
  <div class="graph-container">
    <div class="graph-code">
      <Content slot-key="graph-code" />
    </div>
    <div class="graph">
      <iframe
        width="100%"
        height="800px"
        src="https://codemma.github.io/cadenceDecisionTree/#/tree/524629a5-f63e-47b0-a7b1-5e74304d9da3"
        frameborder="0"
        allowfullscreen
      ></iframe>
    </div>
  </div>
</template>
<script>
export default {
  name: "graph-sample",
};
</script>
<style lang="styl" scoped>
.graph-code {
  height: 100%;
  overflow-y: scroll;
}

.graph-container {
  display: flex;
  width: 100%;
  height: 800px;
}
.graph {
  flex: 1;
  margin-left: 10px;
}
.graph-code {
  flex: 1;
}
</style>

