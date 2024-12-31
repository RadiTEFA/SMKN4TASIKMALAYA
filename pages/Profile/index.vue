<template>
  <div class="container-fluid bg">
    <div class="font text-center">
      <p>Profile</p>
    </div>
    <div class="clearfix">
      <img src="/gambar/EC2.jpg" class="col-md-6 float-md-end mb-3 ms-md-3" alt="...">
      <p>A paragraph of placeholder text. We're using it here to show the use of the clearfix class. We're adding quite
        a few meaningless phrases here to demonstrate how the columns interact here with the floated image.</p>
      <p>
        As you can see the paragraphs gracefully wrap around the floated image. Now imagine how this would look with
        some actual content in here, rather than just this boring placeholder text that goes on and on, but actually
        conveys no tangible information at. It simply takes up space and should not really be read.
      </p>
      <p>
        And yet, here you are, still persevering in reading this placeholder text, hoping for some more insights, or
        some hidden easter egg of content. A joke, perhaps. Unfortunately, there's none of that here.
      </p>
    </div>
  </div>
</template>

<style scoped>
@import url('https://fonts.googleapis.com/css2?family=Beau+Rivage&display=swap');

.bg {
  background-color: #EAE7DD;
  display: flex;
  flex-direction: column;
  min-height: 87.7vh;
}

.container-fluid {
  flex: 1;
}

.bg .font p {
  font-size: 4rem;
  padding: 40px 0px 10px 0px;
  font-weight: bold;
  font-family: "Beau Rivage", serif;
}
</style>