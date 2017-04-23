<html>
<style>

  html {
            height: 100%;
        }

        body {
            background-image: url(http://s7d2.scene7.com/is/image/PetSmart/PB0101_HERO-SmallPet-Food-20160818?$sclp-banner-main_small$);
            background-repeat: no-repeat;
            background-attachment: fixed;
            background-position: center;
            background-size: cover;
        }
  
  
</style>
<head>

</head>
<body background="http://s7d2.scene7.com/is/image/PetSmart/PB0101_HERO-SmallPet-Food-20160818?$sclp-banner-main_small$" percentage="30" >

<center>
<b>
<p style= "font-size:35px;" >
關於黃莎涴
</p>
<p style= "font-size:25px;" >
興趣:
</p>



<ol style= "font-size:8;">
<li><font size="7" color="orange">吃很多好吃的
<li><font color="blue">找好吃的食物
<li><font color="purple">花錢買好吃的東西
<li><font color="red">想著等一下要吃甚麼好吃的

<script>
  $(document).ready(function() {
    $("#target1").css("color", "red");
    $("#target1").prop("disabled", true);
    $("#target4").remove();
    $("#target2").appendTo("#right-well");
    $("#target5").clone().appendTo("#left-well");
    $("#target1").parent().css("background-color", "red");
    $("#right-well").children().css("color", "orange");
    $("#left-well").children().css("color", "green");
    $(".target:nth-child(2)").addClass("animated bounce");
    $(".target:even").addClass("animated shake");
$("body").addClass("animated hinge");
  });

<!-- Only change code above this line. -->
<script type="Text/JavaScript" src="http://ajax.googleapis.com/ajax/libs/jquery/1.6/jquery.min.js"></script>
<script type='text/javascript'>
$(function(){
$("#clickme").click(function(){
$("#test").toggle();
});
 });
</script>


<div id="clickme">點我吧!</div>
<div id="test">
我是莎涴 , 你看到了嗎?
</div>
<div class="container-fluid">
  <h3 class="text-primary text-center">jQuery Playground</h3>
  <div class="row">
    <div class="col-xs-6">
      <h4>#left-well</h4>
      <div class="well" id="left-well">
        <button class="btn btn-default target" id="target1">#target1</button>
        <button class="btn btn-default target" id="target2">#target2</button>
        <button class="btn btn-default target" id="target3">#target3</button>
      </div>
    </div>
    <div class="col-xs-6">
      <h4>#right-well</h4>
      <div class="well" id="right-well">
        <button class="btn btn-default target" id="target4">#target4</button>
        <button class="btn btn-default target" id="target5">#target5</button>
        <button class="btn btn-default target" id="target6">#target6</button>
      </div>
    </div>
  </div>
</div>

