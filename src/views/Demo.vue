<template>
<el-container>
  <el-header>
    <tr>
      <td>
        需求内容
      </td>
      <td>
    
        </td>
      <td>
        <el-tag>标签一</el-tag>

      </td>
    </tr>
  </el-header>
  <el-main>
  <tr>
    <td>11111111</td>
    <td></td>
        <td></td>

    <td>1111111111</td>
  </tr>
  <tr>
    <td>2</td>
    <td>2</td>
  </tr>
  <tr>
    <td>3</td>
    <td>3</td>
  </tr>
  <tr>
    <td>4</td>
    <td>4</td>
  </tr>
  <tr>
    <td>5</td>
    <td>5</td>
  </tr>
      <!-- <div class="sideone">
        客户需求的时间
          </div> -->
  </el-main>
  <el-footer>
    <tr>
      <td></td>
      <td></td>
    </tr>
  </el-footer>
</el-container>

</template>

<script>
export default {

}
</script>
 
  
<style scoped>
li{
  width: 800px;
  float: left;
  list-style: none;
}
.sideone{
  float: left;
}
   .el-header, .el-footer {
    background-color: #B3C0D1;
    color: #333;
    text-align: center;
    line-height: 60px;
  }
  
  .el-aside {
    background-color: #D3DCE6;
    color: #333;
    text-align: center;
    line-height: 200px;
  }
  
  .el-main {
    background-color: #E9EEF3;
    color: #333;
    text-align: center;
    line-height: 60px;
  }
  
  body > .el-container {
    margin-bottom: 40px;
  }
  
  .el-container:nth-child(5) .el-aside,
  .el-container:nth-child(6) .el-aside {
    line-height: 260px;
  }
  
  .el-container:nth-child(7) .el-aside {
    line-height: 320px;
  }
</style>