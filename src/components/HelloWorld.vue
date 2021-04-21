<template>
  <div class="hello">
    <h1>{{ msg }}</h1>
    <p>
      Mari tingkatkan belajar dan tanamkan semangat sejak dini...<br>
     "Menjadi juara bukan berarti harus menjadi yang pertama. Menjadi juara artinya kamu melakukan sesuatu yang lebih baik dari sebelumnya dengan belajar."<br>
      Dan kerja keras yang kamu.2 lakukan hari ini bisa menjadi kekuatan untukmu besok. Setiap hal yang kamu pikir tantangan, adalah kesempatanmu untuk berkembang
    </p>
    
    
    
    
   
  </div>
</template>

<script>
export default {
  name: 'HelloWorld',
  props: {
    msg: String
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
h1{
  font-weight: bold;
}
h3 {
  margin: 40px 0 0;
}
li {
  display: inline-block;
  margin: 0 10px;
}
a {
  color: #42b983;
}
</style>
