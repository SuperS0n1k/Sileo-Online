<!-- Use preprocessors via the lang attribute! e.g. <template lang="pug"> -->
<template>
  <div id="app">
  <p><headline style="font-size: 3em">hi</headline></p>

  </div>
</template>

<script>
export default {
  data() {
    return {
      message: 'Welcome to Vu!'
    };
  },
  methods: {
    doSomething() {
      alert('Hello!');
    }
  }
};
</script>

<!-- Use preprocessors via the lang attribute! e.g. <style lang="scss"> -->
<style>
#app {
  font-family: -apple-system;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}

a,
button {
  color: #4fc08d;
}

button {
  background: none;
  border: solid 1px;
  border-radius: 2em;
  font: -apple-system-subheadline;
  padding: 0.75em 2em;
}
  sbody { 
font: -apple-system-body
  }
  

  headline { font: -apple-system-headline }

  subheadline { font: -apple-system-subheadline }

  caption1 { font: -apple-system-caption1 }

  caption2 { font: -apple-system-caption2 }

  
  footnote { font: -apple-system-footnote }
  
  short-body { font: -apple-system-short-body }
  
  short-headline { font: -apple-system-short-headline }
  
  short-subheadline { font: -apple-system-short-subheadline }
 
  short-caption1 { font: -apple-system-short-caption1 }

  short-footnote { font: -apple-system-short-footnote }

  tall-body { font: -apple-system-tall-body }
 
</style>
