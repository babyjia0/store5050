<template>
  <el-table  border style="width: 100%">
    <el-table-column prop="date" label="日期" width="180">
    </el-table-column>
    <el-table-column prop="name" label="姓名" width="180">
    </el-table-column>
    <el-table-column prop="address" label="地址">
    </el-table-column>
    <el-table-column prop="address" label="地址">
    </el-table-column>
    <el-table-column prop="address" label="地址">
    </el-table-column>
    <template slot-scope="scope">
      <!-- <el-button size="mini" @click="handleEdit(scope.$index, scope.row)">编辑</el-button>
      <el-button size="mini" type="danger" @click="handleDelete(scope.$index, scope.row)">删除</el-button> -->
    </template>
  </el-table>
</template>
<script>
export default {

};

</script>
<style>

</style>
