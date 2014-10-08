Chat-Cascada-Style

body{
  Background:#52B3D9;
  margin:0px;
  font-family:Arial;
}

.user-box{
  position:fixed;
  bottom:0px;
  background:White;
  width:250px;
  height:545px;

  border-radius:5px 5px 0px 0px;
}

.user-head{
  cursor:pointer;
  Background:#CF000F;
  padding:20px 70px;
  color:White;

  border-radius:5px 5px 0px 0px;
}

.user-body{
  height: 450px;
}

.username{
  padding:20px 30px;
  background:#ECECEC;
  position:relative;
}

.username:hover{
  cursor:pointer;
  background:White;
}

.username:before{
  content:"";
  position:absolute;
  background:#26C281;
  width:7px;
  height:7px;
  left:7px;
  top:25px;
}

.msg_box{
  position:fixed;
  bottom:0px;
  background:white;
  height:385px;
  width:250px;
  left:345px;
}

.msg_box_head{
  Background:#CF000F;
  padding:20px 50px;
  color:White;
  position:relative;
}

.close{
  color:white;
  margin-top:-40px;
  right:20px;
  float:right;
  position:relative;
}

.close:hover{
  cursor:pointer;
}

.msg_box_body{
  height:275px;
  overflow:auto;
  overflow-x:hidden;
}

.msg_a{
  margin-top:15px;
  margin-left:15px;
  margin-right:15px;
  padding:15px;
  background:#ECECEC;

  border-radius:10px 10px 10px 10px;
}

.msg_b{
  margin-top:15px;
  margin-left:15px;
  margin-right:15px;
  padding:15px;
  background:#F5D76E;

  border-radius:10px 10px 10px 10px;
}

.msg_input{
  position:relative;
  border:transparent;
  border-top:1px solid #6C7A89;
  width:100%;
  -webkit-box-sizing:border-box;
  -moz-box-sizing:border-box;
  box-sizing:border-box;
  bottom:1px;
}
