<template>
    <div class="pos">
        <div>
            <el-row>
                <el-col :span="7" class="pos-order">
                    <el-tabs>
                        <el-tab-pane label="点餐">
                            <el-table border style="width: 100%">
                                <el-table-column prop="goodsName" label="商品"></el-table-column>
                                <el-table-column prop="count" label="数量"></el-table-column>
                                <el-table-column prop="price" label="金额"></el-table-column>
                                <el-table-column label="操作" width="100" fixed="right"></el-table-column>
                            </el-table>
                        </el-tab-pane>
                        <el-tab-pane label="挂单">挂单</el-tab-pane>
                        <el-tab-pane label="外卖">外卖</el-tab-pane>
                    </el-tabs>
                </el-col>
                <el-col :span="17">
                    我是产品栏
                </el-col>
            </el-row>
        </div>
    </div>
</template>

<script>
export default {
  name: 'Pos'
}
</script>

<style scoped>
    .pos {
        font-size: 12px;
    }
    .pos-order {
        background-color: #F9FAFC;
        border-right: 1px solid #C0CCDA;
    }
</style>
