<template>
 <div class="box">
   <ul>
     <li>
       <div>
       <div class="topone">内容需求</div>
        <div class="toptwo"><el-tag>标签一</el-tag></div>
       </div>
       <div class="topthree"><el-tag>标签一</el-tag></div>

       </li>
     <li><div class="sideone">
       客户于什么时间发布该内容
       </div></li>

     <li><div>
       <div class="sideone">需求标题</div>
       <div class="sidetwo">我需要摄影后期，短视频剪辑，一对一线下培训</div>
       
       </div></li>
       
     <li><div>
       <div class="sideone">需求标题</div>
       <div class="sidetwo">我需要摄影后期，短视频剪辑，一对一线下培训</div>
       </div></li>

       
     <li><div>
       <div class="sideone">需求标题</div>
       <div class="sidetwo">我需要摄影后期，短视频剪辑，一对一线下培训</div>
       </div></li>

       
     <li><div>
       <div class="sideone">需求标题</div>
       <div class="sidetwo">我需要摄影后期，短视频剪辑，一对一线下培训</div>
       </div></li>


     <li><div>
       <div class="btnone"><el-row><el-button>默认按钮</el-button></el-row></div>
       <div class="btntwo"><el-row>  <el-button type="warning">警告按钮</el-button></el-row></div>
       <div class="btnthree"><a>查看更多类似需求></a></div>
       </div></li>
     <li><div></div></li>
   </ul>

 

 
   </div>
</template>

<script>
export default {

}
</script>

<style>
 .school{
   color: aqua;
 }

 .box{
   width: 1000px;
   height: 400px;
   margin: auto;
   border: 1px solid black;
   background-color: #F2F6FC;
   box-shadow: 0 2px 4px rgba(0, 0, 0, .12), 0 0 6px rgba(0, 0, 0, .04)
 }
 /* .boxt{
   position: absolute;
 } */
 li{
   list-style: none;
   margin-top: 20px;
 }
 .topone{
   float: left;
  font-weight: bold;
  font-size: 22px;
 }
 .toptwo{
   float: left;
   margin-left: 20px;
   /* margin-top: -2px; */
 }
 .topthree{
   float:right;

 }
 .sideone{
   float: left;
   color: #B1B1AE;
 }
 .sidetwo{
   float: left;
   margin-left: 30px;
 }
 .btnone{
   float: left;
 }
 .btntwo{
   float: left;
 }
 .btnthree{
   float: right;
 }
 .btnthree a{
   color: #FF6900;
 }
 
</style>
