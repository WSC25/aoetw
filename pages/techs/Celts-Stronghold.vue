<template>
  <div class="container">
    <div class="row padtop">
      <div class="col-md-12">
        <h1>堡壘</h1>
        <div class="hrn1"></div>
      </div>
      <div class="col-md-8">
        <div class="n1">
          <p>
            堡壘是賽爾特的特殊科技，可於城堡時代在城堡研發。研發後城堡和箭塔射速+25%。
          </p>
        </div>
        <h3>戰術要點</h3>
        <div class="hrn1"></div>
        <div class="n1">
          <ul>
            <li>
              堡壘雖然可讓賽爾特人的防守能力增強。
              不幸的是，大部分敢於圍攻城堡的部隊已經不怕城堡傷害，或者是能從遠距離摧毀城堡。
              儘管如此，堡壘仍然是一項有價值的技術。
              搭配預熱射擊能對船隻造成更多傷害。
            </li>
          </ul>
        </div>
        <h3>團隊加成</h3>
        <div class="hrn1"></div>
        <div class="n1">
          <ul>
            <li>
              <nuxt-link to="/civs/Berbers">柏柏</nuxt-link>：<nuxt-link
                to="/techs/Kasbah"
                >聚居堡壘</nuxt-link
              >能夠加速堡壘的研究時間(快25%)。
            </li>
          </ul>
        </div>
      </div>
      <div class="col-md-4">
        <table class="table-bordered" width="100%">
          <tr>
            <td class="unit" colspan="2" style="background-color:#31b0d5;">
              <div class="unititle2">堡壘</div>
            </td>
          </tr>
          <tr>
            <td colspan="2">
              <div class="unititle">
                <img src="~assets/CastleAgeUnique.png" width="45" alt="" />
              </div>
            </td>
          </tr>
          <tr>
            <td class="unit" colspan="2" style="background-color:#31b0d5;">
              <div class="unititle2">
                <nuxt-link to="/techs">科技介紹</nuxt-link>
              </div>
            </td>
          </tr>
          <tr>
            <td class="unit3">文明</td>
            <td class="unit4">賽爾特</td>
          </tr>
          <tr>
            <td class="unit3">時代</td>
            <td class="unit4">城堡時代</td>
          </tr>
          <tr>
            <td class="unit3">研發於</td>
            <td class="unit4">城堡</td>
          </tr>
          <tr>
            <td class="unit3">研發時間</td>
            <td class="unit4">30秒</td>
          </tr>
          <tr>
            <td class="unit" colspan="2" style="background-color:#31b0d5;">
              <div class="unititle2">成本</div>
            </td>
          </tr>
          <tr>
            <td class="unit3">食物</td>
            <td class="unit4">250</td>
          </tr>
          <tr>
            <td class="unit3">黃金</td>
            <td class="unit4">200</td>
          </tr>
          <tr>
            <td class="unit" colspan="2" style="background-color:#31b0d5;">
              <div class="unititle2">影響</div>
            </td>
          </tr>
          <tr>
            <td class="unit3">影響</td>
            <td class="unit4">城堡和箭塔射速+25%。</td>
          </tr>
        </table>

        <div class="thanks">感謝! 此頁面由賜齡協助編輯</div>
      </div>
    </div>
  </div>
</template>
<script>
export default {
  layout: 'alltech',
  components: {}
}
</script>
<style></style>
