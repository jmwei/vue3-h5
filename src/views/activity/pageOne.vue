<template>
  <div class="page-one">
    <div class="list-title list-title-1">
      <img src="@/assets/icons/icon-chuangxin.png" alt="" />
      <span>辅助创新</span>
    </div>
    <div class="list-desc list-desc-1">
      数据驱动提高创新效率，智能认知搜索，从专利和文献中抽取技术方案， 利用信息技术进行融合，科研人员只需要输入创新意图，系统帮助科研人员
      从专利和论文文献中寻找创新思路，一件形成技术交底书，提高创新和发明的效率。
    </div>

    <div class="list-title list-title-2">
      <img src="@/assets/icons/icon-jiansuo1.png" alt="" />
      <span>智能检索与分析</span>
    </div>
    <div class="list-desc list-desc-2">
      我们重新定义专利搜索，根据用户的需求自动编辑检索式，
      自动进行数据清理和标引，根据用户的需求自动进行新颖性、无效、FTO、Landscaping检索，
      一键生成查新、稳定性分析、FTO、Landscaping报告，提高专利检索质量和效率。
    </div>

    <div class="list-title list-title-3">
      <img src="@/assets/icons/icon-touzi.png" alt="" />
      <span>投资助手</span>
    </div>
    <div class="list-desc list-desc-3">
      快速了解投资赛道的机会，快速评估一家企业的科研潜力，根据客户的需求，一键形成赛道的报告和企业评估报告，帮助投资者寻找投资机会。
    </div>
  </div>
</template>

<script lang="ts" setup name="ActivityPage"></script>

<style scoped lang="scss">
  .page-one {
    padding: 30px;
    min-height: calc(100vh - 60px);
    background-image: linear-gradient(to bottom, #f3e7e9 0%, #e3eeff 99%, #e3eeff 100%);

    .list-title {
      display: flex;
      align-items: center;
      margin-bottom: 20px;

      img {
        width: 55px;
      }

      span {
        font-size: 45px;
        padding-left: 10px;
        font-weight: bolder;
      }
    }

    .list-desc {
      color: #666;
      font-size: 30px;
      letter-spacing: 3px;
      word-break: normal;
      line-height: 1.7;
      margin-bottom: 60px;
    }
  }
</style>
