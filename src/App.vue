<script>
export default {
  mpType: 'app'
}

</script>
<style>
body {
  width: 100%;
  height: 100%;
  background-color: #f9f9f9;
}

html {
  width: 100%;
  height: 100%;
  background-color: #f9f9f9;
}

* {
  margin: 0;
  padding: 0;
  border: none;
  text-decoration: none;
  font-family: "Droid Sans Fallback", Rotobo, "冬青黑和华文黑体", HelveticaNeue;
  font-size: 14px;
  font-weight: normal;
  outline: none;
  line-height: normal
}

img {
  display: block;
}


/*
.container {
  width: 100%;
  min-height: 100vh;
  display: flex;
  flex-direction: column;
  align-items: center;
  justify-content: flex-start;
  box-sizing: border-box;
}
*/

.column_box {
  height: 46px;
  line-height: 46px;
  background-color: #fff;
  padding-left: 4%;
  padding-right: 4%;
  position: relative
}

.column_box input {
  height: 46px;
  color: #191919;
  font-size: 16px;
  float: left;
  margin-left: 12px;
  width: 90%;
}

.column_box textarea {
  color: #191919;
  font-size: 16px;
  float: left;
  margin-left: 12px;
  width: 90%;
}

.column_img {
  float: left;
  margin-top: 14px;
}

.column_img img {
  width: 18px;
  height: 18px;
}

.border_bottom {
  background-image: -webkit-linear-gradient(bottom, #d3d3d3 33.3%, transparent 66.7%);
  background-size: 100% 1px;
  background-repeat: no-repeat;
  background-position: bottom;
  position: absolute;
  height: 1px;
  width: 100%;
  left: 0;
  bottom: 0;
}

</style>
