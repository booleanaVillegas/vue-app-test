<script>
export default {
  data() {
    return {
      isSelected: true,
    };
  },
};
</script>

<template>
  <section>
    <h2>Data, Methods, Computed</h2>
    <p>
      Lorem ipsum dolor sit amet consectetur adipisicing elit. Totam dolorum
      itaque aperiam quos harum enim veritatis, possimus ipsa distinctio
      repellat, tenetur esse earum voluptatibus consectetur repellendus nam non
      consequuntur pariatur!
    </p>
    <pre>
  <code>{
    data() {
      return {
        isSelected: true
        }
    }</code>
    </pre>
  </section>
</template>

<style scoped>
section {
  margin: 20px;
  padding: 20px;
  background-color: #eee;
  width: 1000px;
  height: fit-content;
}
p {
  margin-bottom: 16px;
}
pre {
  border-radius: 5px;
  padding: 8px;
  background-color: #dfdfdf;
}
</style>
