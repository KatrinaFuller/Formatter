<template>
  <div class="home container-fluid">
    <!-- title -->
    <div class="row">
      <div class="col">
        <h1>Formatter</h1>
      </div>
    </div>
    <!-- input area -->
    <div class="row">
      <div class="col-6 border">
        <h4>Input</h4>
        <form action>
          <div class="form-group">
            <!-- <label for="exampleFormControlTextarea1">Example textarea</label> -->
            <textarea class="form-control" id="exampleFormControlTextarea1" rows="25"></textarea>
          </div>
        </form>
      </div>
      <div class="col-6 border">
        <h4>Output</h4>
        <form action>
          <div class="form-group">
            <!-- <label for="exampleFormControlTextarea1">Example textarea</label> -->
            <textarea class="form-control" id="exampleFormControlTextarea1" rows="25"></textarea>
          </div>
        </form>
      </div>
    </div>
  </div>
</template>

<script>
// @ is an alias to /src

export default {
  name: "home",
  components: {}
};
</script>
