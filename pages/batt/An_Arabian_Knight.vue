<template>
  <div class="container">
    <div class="row padtop">
      <div class="col-md-12">
        <h1>阿拉伯騎士</h1>
        <div class="hrn1"></div>
      </div>
      <div class="col-md-8">
        <div class="n1">
          <p>
            <b>阿拉伯騎士</b
            >為沙拉丁戰役的第一關劇情關卡，此關描述沙拉丁率領軍隊逐出在埃及的法國十字軍。
          </p>
        </div>
        <h2>玩家</h2>
        <div class="hrn1"></div>
        <div class="n1">
          <h3>基本資訊</h3>
          <table class="table-bordered" width="100%">
            <tr>
              <td class="tc1" width="14%">起始時代：</td>
              <td class="tc2" width="14%">城堡時代</td>
              <td class="tc1" width="14%">起始資源：</td>
              <td class="tc2">1,000木頭，1,000食物，1,000黃金，1,000石頭</td>
              <td class="tc1" width="14%">人口上限：</td>
              <td class="tc2" width="5%">75</td>
            </tr>
          </table>

          <p></p>
          <h3>AI</h3>
          <!--<span class="glyphicon glyphicon-star" aria-hidden="true" style="color: #ff911d; margin-left: 5px;"></span>:中立</p>!-->
          <table class="table-bordered" width="100%">
            <tr>
              <td class="tc4" colspan="4" style="background: #2980b9;">
                玩家本身
              </td>
            </tr>
            <tr>
              <td class="tc6"><div class="p3">玩家1</div></td>
              <td class="tc6" colspan="3">薩拉森人（綠色）</td>
            </tr>
            <tr>
              <td class="tc4" colspan="4" style="background: #27ae60;">同盟</td>
            </tr>
            <tr>
              <td class="tc6" width="12%"><div class="p2">玩家2</div></td>
              <td class="tc6" colspan="3">埃及人（紅色）薩拉森</td>
            </tr>
            <tr>
              <td class="tc4" colspan="4" style="background:#ea6153;">敵對</td>
            </tr>
            <tr>
              <td class="tc6" width="12%"><div class="p1">玩家3</div></td>
              <td class="tc6" width="38%">西法蘭克人（藍色）法蘭克</td>
              <td class="tc6" width="12%"><div class="p5">玩家4</div></td>
              <td class="tc6" width="38%">東法蘭克人（藍綠色）法蘭克</td>
            </tr>
          </table>

          <br />
          <dl class="dl-horizontal">
            <dt>開場：</dt>
            <dd>
              16位輕騎兵、12位駱駝騎兵、2位阿拉伯奴隸兵、12位裝甲步兵、2台重型弩砲。
            </dd>
            <dt>大地之母單位：</dt>
            <dd>2位駱駝騎兵、6位馬弓騎兵，1艘火砲戰船，1台重型衝撞車</dd>
          </dl>
          <h2>主要任務</h2>
          <div class="hrn1"></div>
          <div class="n1">
            <ol>
              <li>讓你的士兵到開羅的清真寺。</li>
              <li>打敗在開羅的西法蘭克人。</li>
              <li>要打敗開羅的西法蘭克人，可先破壞他們的城鎮中心。</li>
            </ol>
          </div>
        </div>
        <h2>任務提示</h2>
        <div class="hrn1"></div>
        <div class="n1">
          <ul>
            <li>利用你輕騎兵的視野以避免不必要的衝突。</li>
          </ul>
        </div>
      </div>
      <div class="col-md-4">
        <table class="table-bordered" width="100%">
          <tr>
            <td class="unit" colspan="2" style="background-color:#375d96;">
              <div class="unititle2">
                阿拉伯騎士
              </div>
            </td>
          </tr>
          <tr>
            <td colspan="2">
              <div class="unititle">
                <img src="~assets/An_arabian_knight.png" alt="" />
              </div>
            </td>
          </tr>
          <tr>
            <td class="unit" colspan="2" style="background-color:#375d96;">
              <div class="unititle2">
                情景信息
              </div>
            </td>
          </tr>
          <tr>
            <td class="unit3">版本</td>
            <td class="unit4">
              <nuxt-link to="/games/aok">帝王世紀</nuxt-link>
            </td>
          </tr>
          <tr>
            <td class="unit3">戰役</td>
            <td class="unit4">
              <nuxt-link to="/batt/Saladina">沙拉丁</nuxt-link>
            </td>
          </tr>
          <tr>
            <td class="unit3">文明</td>
            <td class="unit4">
              <nuxt-link to="/civs/Saracens">薩拉森人</nuxt-link>
            </td>
          </tr>
          <tr>
            <td class="unit" colspan="2" style="background-color:#375d96;">
              <div class="unititle2">
                戰役關卡編號
              </div>
            </td>
          </tr>
          <tr>
            <td class="unit3">章節</td>
            <td class="unit4">帝王世紀第三章之一</td>
          </tr>
          <tr>
            <td class="unit3">上一關</td>
            <td class="unit4">N/A</td>
          </tr>
          <tr>
            <td class="unit3">下一關</td>
            <td class="unit4">
              <nuxt-link to="/batt/Lord_of_Arabia">阿拉伯之主</nuxt-link>
            </td>
          </tr>
        </table>

        <div class="thanks">感謝！此頁面由裕暉、亞諭協助編輯。</div>
      </div>
    </div>
  </div>
</template>
<script>
export default {
  layout: 'allbatt',
  components: {}
}
</script>
<style></style>
