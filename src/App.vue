<template>
  <div>
    <create-note-form></create-note-form>
    <notes></notes>
  </div>
</template>
<script>
import Notes from './components/notes/Index'
import CreateNoteForm from './components/notes/Create'
export default {
  components: {
    Notes,
    CreateNoteForm
  }
}
</script>
<style>
*{
  padding: 0;
  margin: 0;
  box-sizing: border-box;
}
html{
  position: relative;
  min-height: 100%;
  font-family: sans-serif;
}
body{
  background: #C0D2D7;
  min-height: 100%;
}
body > div{
  padding: 16px 16px 50px;
  min-height: 88vh;
  background: #C0D2D7;
  position: relative;
  margin-bottom: 50px;
  z-index: 1;

}
footer{
  background: #333;
  color: #fff;
  text-align: center;
  padding: 12px 0 10px;
  position: fixed;
  bottom: 0;
  height: 50px;
  width: 100%;
}
footer a{
  color: #e03c3c;
}
footer .fa-heart{
  margin: 0 10px 0 0;
}
footer iframe{
  position: relative;
  top: 4px;
}
</style>
