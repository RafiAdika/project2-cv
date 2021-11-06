<template>
    <div class="all">
        <h2>CV-2</h2>
    <div class="bg"></div>
<div class="res">RESUME</div>
<div class="jud">
  <div class="gb">
      <div class="p"><h1>Rafi<br>Adika</h1></div>
    <img class="gm" src="photo.jpg">
</div>
</div>
<div class="j"><h2>GRAPHIC ARTIST<hr style="border:1px solid black"></h2></div>
<div class="j"><h2>WORK EXPERIENCE<hr style="border: 1px dashed;"></h2></div>
<div class="k"><h2>Profile</h2></div>
<div class="g">
    <hr style="border: 1px dashed;">
</div>
<div class="ka"><h3>NAME</h3></div>
<div class="ki"><p><b>RAFI ADIKA ROJA</b></p></div>
<div class="kk"><h3>DATE OF BIRTH</h3></div>
<p style="margin-left: 68px;margin-top: -10px;"><b>05 JANUARI 2005</b></p>
<h3 style="margin-left: 130px;margin-top: 10px;">ADDRESS</h3>
<p style="margin-left: 80px;margin-top: -20px;"><b>Jl.karanggayam<br>Mangkang Wetan<br>RT 03 RW 04<br>Semarang</b></p>
<h3 style="margin-left: 130px;margin-top: -5px;">WEBSITE</h3>
<p style="margin-left: 50px;margin-top: -20px;"><b>rafiadikaroja.com</b></p>
<h2 style="font-family: 'Courier New', Courier, monospace;margin-left: 130px;">AWARDS<hr style="border: 1px dashed"></h2>
</div>
</template>
<script>
export default {
    name: 'CvSatu',
    computed: {
        listCv() {
            return this.$store.state.listCv
        }
    }
}
</script>



