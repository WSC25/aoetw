<template>
  <div class="container">
    <div class="row padtop">
      <div class="col-md-12">
        <h1>城堡</h1>
        <div class="hrn1"></div>
      </div>
      <div class="col-md-8">
        <div class="n1">
          城堡能夠在城堡時代建築，在遊戲中期及後期是非常重要的建築，提供強大的防禦和獨特的技術與單位。
          <br />不能被招降、駐軍可達20人。
          <br />弒君模式遊戲中，遊戲開始時，每位玩家都會在城鎮中心附近擁有一座城堡。
          <br />不同的文明城堡的建築風格會有不同
        </div>
        <h3>可生產單位與可研發科技</h3>
        <div class="hrn1"></div>
        <div class="row">
          <div class="col-md-6">
            <div class="n1">
              <h4>
                <nuxt-link to="/techs/age/Castle_Age"></nuxt-link>城堡時代
              </h4>
              <ul>
                <li>
                  <img
                    class="gg"
                    src="~assets/Elite-unique-research.jpg"
                    width="30"
                    alt=""
                  /><nuxt-link to="/units/Unique_Unit">特殊單位</nuxt-link>
                </li>
                <li>
                  <img
                    class="gg"
                    src="~assets/PetardIcon.jpg"
                    width="30"
                    alt=""
                  /><nuxt-link to="/units/Petard">爆炸桶</nuxt-link>
                </li>
                <li>
                  <img
                    class="gg"
                    src="~assets/CastleAgeUnique.png"
                    width="30"
                    alt=""
                  /><nuxt-link to="/techs/untech">城堡特殊科技</nuxt-link>
                </li>
              </ul>
            </div>
          </div>
          <div class="col-md-6">
            <div class="n1">
              <h4>
                <nuxt-link to="/techs/age/Imperial_Age"></nuxt-link>帝王時代
              </h4>
              <ul>
                <li>
                  <img
                    class="gg"
                    src="~assets/Elite-unique-research.jpg"
                    width="30"
                    alt=""
                  /><nuxt-link to="/units/Unique_Unit">精銳特殊單位</nuxt-link>
                </li>
                <li>
                  <img
                    class="gg"
                    src="~assets/TrebuchetPackedIcon.jpg"
                    width="30"
                    alt=""
                  /><nuxt-link to="/units/Trebuchet">巨型投石機</nuxt-link>
                </li>
                <li>
                  <img
                    class="gg"
                    src="~assets/Unique-tech.jpg"
                    width="30"
                    alt=""
                  /><nuxt-link to="/techs/untech">帝王特殊科技</nuxt-link>
                </li>
                <li>
                  <img
                    class="gg"
                    src="~assets/Hoardings.jpg"
                    width="30"
                    alt=""
                  /><nuxt-link to="/techs/Hoardings">外架式柵樓</nuxt-link>
                </li>
                <li>
                  <img
                    class="gg"
                    src="~assets/Sappers.jpg"
                    width="30"
                    alt=""
                  /><nuxt-link to="/techs/Sappers">坑道工兵</nuxt-link>
                </li>
                <li>
                  <img
                    class="gg"
                    src="~assets/Conscription.jpg"
                    width="30"
                    alt=""
                  /><nuxt-link to="/techs/Conscription">徵兵制度</nuxt-link>
                </li>
                <li>
                  <img
                    class="gg"
                    src="~assets/Spiestreason.jpg"
                    width="30"
                    alt=""
                  /><nuxt-link to="/techs/Spies">間諜</nuxt-link>
                </li>
              </ul>
            </div>
          </div>
        </div>
        <h3>文明加成</h3>
        <div class="hrn1"></div>
        <div class="n1">
          <ul>
            <li>
              <nuxt-link to="/civs/Aztecs">阿茲特克</nuxt-link
              >：城堡生產速度提高15％。
            </li>
            <li>
              <nuxt-link to="/civs/Burmese">緬甸</nuxt-link>：研究<nuxt-link
                to="/techs/Herbal_Medicine"
                >草藥學</nuxt-link
              >便宜50％。
            </li>
            <li>
              <nuxt-link to="/civs/Byzantines">拜占庭</nuxt-link
              >：黑暗/封建/城堡/帝國時代的 城堡HP分別增加10%/20%/30%/40%。
              <nuxt-link to="/techs/Town_Watch">城鎮瞭望</nuxt-link>免費。
            </li>
            <li>
              <nuxt-link to="/civs/Franks">法蘭克</nuxt-link>：城堡便宜25％。
            </li>
            <li>
              <nuxt-link to="/civs/Incas">印加</nuxt-link>：城堡便宜15％。
            </li>
            <li>
              <nuxt-link to="/civs/Koreans">韓國</nuxt-link>：建築速度提高了33％
              。
            </li>
            <li>
              <nuxt-link to="/civs/Spanish">西班牙</nuxt-link
              >：建築速度提高了30％。
            </li>
            <li>
              <nuxt-link to="/civs/Teutons">條頓</nuxt-link>：<nuxt-link
                to="/techs/Murder_Holes"
                >垛孔</nuxt-link
              >免費。
            </li>
            <li>
              <nuxt-link to="/civs/Vietnamese">越南</nuxt-link>：<nuxt-link
                to="/techs/Conscription"
                >徵兵制度</nuxt-link
              >免費。
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
              >可提高城堡的工作效率25%。
            </li>
            <li>
              <nuxt-link to="/civs/Malians">馬利</nuxt-link>：<nuxt-link
                to="/building/University"
                >學院</nuxt-link
              >裡對城堡有加成的科技研發速度快80%。
            </li>
          </ul>
        </div>
        <h3>戰術和建築位置</h3>
        <div class="hrn1"></div>
        <div class="n1">
          <ul>
            <li>
              城堡位置有時攸關整場勝負，請謹慎思考，一般來說如果是生產較慢速的城堡兵如不列顛長弓兵與土耳其火槍兵，城堡可蓋前線，如果是快速移動的部隊則盡可能蓋自己家防守，如：馬雅羽毛箭射手、
              <nuxt-link to="/units/Conquistador">西班牙征服者</nuxt-link
              >、緬甸飛鏢騎兵。中國高手大屌哥就曾因為城堡蓋錯位置，輸了整場比賽。當然影響建築位置的原因很多，這只是其中一點。
            </li>
            <li>
              通常來說，建立在高地的城堡會比低地的城堡更加難以攻陷。應該說城堡請一定要蓋在高地。
            </li>
            <li>
              衝撞車系能對城堡造成毀滅性破壞，部署你的近戰單位來保護城堡，在城堡時代僵持時，最好在城堡後面出投石車以防大量衝撞車來襲。
            </li>
            <li>
              投石機是城堡最大的威脅，善用你的騎兵去摧毀正在攻擊的投石機。
            </li>
            <li>
              城堡是非常強大的防禦建築，但同時也耗費高昂，在市場買進石頭的費用非常不划算，所以，封鎖敵方的石頭來源就能制止敵方建築城堡。
            </li>
            <li>
              城堡通常會建設在基地外圍，作為圍牆的一部分保護基地內的生產單位。
            </li>
            <li>
              你也可以將城堡建設在基地內，以防止敵人的快速部隊繞過外圍防禦工事進入基地屠殺生產單位。
            </li>
            <li>
              當有經濟優勢時，選擇在敵方的資源點附近建設城堡也是不錯的選擇，但是要注意保護你的村民，讓他們不在城堡還沒建造起來前就被殺死。
            </li>
            <li>
              河流地圖的城堡通常建設在各河道的交叉點附近，以制止敵方船艦入侵。
            </li>
          </ul>
        </div>
        <h3>箭數</h3>
        <div class="hrn1"></div>
        <div class="n1">
          <p>
            城堡可以根據駐紮單位來提升射箭數量，沒有任何駐紮時可以射出4支箭。每支箭造成11傷害(根據被傷害單位遠程護甲減少)。
          </p>
          <p>以下列出駐紮達最大時，不同單位提供的箭數量。</p>
          <table class="table-bordered" width="100%">
            <tr class="tta">
              <td>單位類型</td>
              <td>單位數量</td>
              <td>箭數</td>
            </tr>
            <tr>
              <td class="tta1">
                <img
                  class="gg"
                  src="~assets/VillagerMaleIcon.jpg"
                  width="30"
                  alt=""
                /><nuxt-link to="/units/Villager">村民</nuxt-link>
              </td>
              <td class="tta2">20</td>
              <td class="tta3">13(額外9)</td>
            </tr>
            <tr>
              <td class="tta1">
                <img
                  class="gg"
                  src="~assets/ArcherIcon.jpg"
                  width="30"
                  alt=""
                /><nuxt-link to="/units/Archer">弓兵</nuxt-link>
              </td>
              <td class="tta2">20</td>
              <td class="tta3">11(額外7)</td>
            </tr>
            <tr>
              <td class="tta1">
                <img
                  class="gg"
                  src="~assets/CrossbowmanIcon.jpg"
                  width="30"
                  alt=""
                /><nuxt-link to="/units/Crossbowman">弩兵</nuxt-link>
              </td>
              <td class="tta2">20</td>
              <td class="tta3">14(額外10)</td>
            </tr>
            <tr>
              <td class="tta1">
                <img
                  class="gg"
                  src="~assets/ArbalestIcon.jpg"
                  width="30"
                  alt=""
                /><nuxt-link to="/units/Arbalest">強弩兵</nuxt-link>
                <img
                  class="gg"
                  src="~assets/CavalryArcherIcon.jpg"
                  width="30"
                  alt=""
                /><nuxt-link to="/units/Cavalry_Archer">馬弓騎兵</nuxt-link>
              </td>
              <td class="tta2">20</td>
              <td class="tta3">16(額外12)</td>
            </tr>
            <tr>
              <td class="tta1">
                <img
                  class="gg"
                  src="~assets/HandCannoneerIcon.jpg"
                  width="30"
                  alt=""
                /><nuxt-link to="/units/Hand_Cannoneer">火槍兵</nuxt-link>
              </td>
              <td class="tta2">18</td>
              <td class="tta3">19(額外15)</td>
            </tr>
          </table>

          條頓的特殊技術：<strong
            ><nuxt-link to="/techs/Crenellations">垛口</nuxt-link></strong
          >，讓步兵駐紮也有增加箭數效果，同種類的步兵駐紮滿20人可以增加7支箭。
        </div>
        <h3>更多數據</h3>
        <div class="hrn1"></div>
        <div class="n1"></div>
        <table class="table-bordered" width="100%">
          <tr class="tta">
            <td class="unit" colspan="2" style="text-align: center;">
              <div class="unititle">劣勢與優勢</div>
            </td>
          </tr>
          <tr>
            <td class="tta1">強勢(容易對抗)</td>
            <td class="tta4">
              <nuxt-link to="/units/Naval_Vessels">船隻</nuxt-link>，<nuxt-link
                to="/units/Archer_Units"
                >弓兵系</nuxt-link
              >， <nuxt-link to="/units/Monk">僧侶</nuxt-link>，虛弱的近戰單位。
            </td>
          </tr>
          <tr>
            <td class="tta1">劣勢(不易對抗)</td>
            <td class="tta4">
              <nuxt-link to="/units/Siege_Weapons">攻城武器</nuxt-link
              >，<nuxt-link to="/units/Tarkan">韃靼騎兵</nuxt-link>，
              <nuxt-link to="/units/Huskarl">哥德衛隊</nuxt-link>，<nuxt-link
                to="/units/War_Elephant"
                >戰象</nuxt-link
              >，<nuxt-link to="/units/Cannon_Galleon">火砲戰船</nuxt-link>。
            </td>
          </tr>
          <tr class="tta">
            <td class="unit" colspan="2" style="text-align: center;">
              <div class="unititle">升級</div>
            </td>
          </tr>
          <tr>
            <td class="tta1" style="width:20%">生命值</td>
            <td class="tta4">
              <img
                class="gg"
                src="~assets/Masonry.jpg"
                width="30"
                alt=""
              /><nuxt-link to="/techs/Masonry">磚瓦技術</nuxt-link>(+10%) <br />
              <img
                class="gg"
                src="~assets/Architecture.jpg"
                width="30"
                alt=""
              /><nuxt-link to="/techs/Architecture">建築學</nuxt-link>(+10%)
              <br />
              <img
                class="gg"
                src="~assets/Hoardings.jpg"
                width="30"
                alt=""
              /><nuxt-link to="/techs/Hoardings">外架式柵樓</nuxt-link>(+1000)
            </td>
          </tr>
          <tr>
            <td class="tta1">攻擊力</td>
            <td class="tta4">
              <img
                class="gg"
                src="~assets/Fletching.jpg"
                width="30"
                alt=""
              /><nuxt-link to="/techs/Fletching">箭羽</nuxt-link>(+1) <br />
              <img
                class="gg"
                src="~assets/Bodkinarrow.jpg"
                width="30"
                alt=""
              /><nuxt-link to="/techs/Bodkin_Arrow">錐狀箭頭</nuxt-link>(+1)
              <br />
              <img
                class="gg"
                src="~assets/Bracer.jpg"
                width="30"
                alt=""
              /><nuxt-link to="/techs/Bracer">護腕</nuxt-link>(+1) <br />
              <img
                class="gg"
                src="~assets/Chemistry.jpg"
                width="30"
                alt=""
              /><nuxt-link to="/techs/Chemistry">化學</nuxt-link>(+1) <br />
              <img
                class="gg"
                src="~assets/Heatedshot.png"
                width="30"
                alt=""
              /><nuxt-link to="/techs/Heated_Shot">預熱射擊</nuxt-link
              >(+4，僅對<nuxt-link to="/units/Naval_Vessels">船隻</nuxt-link>)
              <br />
              <img
                class="gg"
                src="~assets/CastleAgeUnique.png"
                width="30"
                alt=""
              /><nuxt-link to="/techs/Boiling_Oil">沸油</nuxt-link
              >(+9僅對衝撞車系，<nuxt-link to="/civs/Persians">波斯</nuxt-link
              >限定)
            </td>
          </tr>
          <tr>
            <td class="tta1">範圍</td>
            <td class="tta4">
              <img
                class="gg"
                src="~assets/Fletching.jpg"
                width="30"
                alt=""
              /><nuxt-link to="/techs/Fletching">箭羽</nuxt-link>(+1) <br />
              <img
                class="gg"
                src="~assets/Bodkinarrow.jpg"
                width="30"
                alt=""
              /><nuxt-link to="/techs/Bodkin_Arrow">錐狀箭頭</nuxt-link>(+1)
              <br />
              <img
                class="gg"
                src="~assets/Bracer.jpg"
                width="30"
                alt=""
              /><nuxt-link to="/techs/Bracer">護腕</nuxt-link>(+1) <br />
              <img
                class="gg"
                src="~assets/Murderholes.jpg"
                width="30"
                alt=""
              /><nuxt-link to="/techs/Murder_Holes">垛孔</nuxt-link
              >:消除最小射程 <br />
              <img
                class="gg"
                src="~assets/Unique-tech.jpg"
                width="30"
                alt=""
              /><nuxt-link to="/techs/Crenellations">垛口</nuxt-link
              >(+3，<nuxt-link to="/civs/Teutons">條頓</nuxt-link>限定)
            </td>
          </tr>
          <tr>
            <td class="tta1">射箭頻率</td>
            <td class="tta4">
              <img
                class="gg"
                src="~assets/CastleAgeUnique.png"
                width="30"
                alt=""
              /><nuxt-link to="/techs/Stronghold">堡壘</nuxt-link
              >(+25%，<nuxt-link to="/civs/Celts">賽爾特</nuxt-link>限定)
            </td>
          </tr>
          <tr>
            <td class="tta1">準確度</td>
            <td class="tta4">
              <img
                class="gg"
                src="~assets/Ballistics.jpg"
                width="30"
                alt=""
              /><nuxt-link to="/techs/Ballistics">彈道學</nuxt-link
              >:較易擊中移動目標
            </td>
          </tr>
          <tr>
            <td class="tta1">護甲</td>
            <td class="tta4">
              <img
                class="gg"
                src="~assets/Masonry.jpg"
                width="30"
                alt=""
              /><nuxt-link to="/techs/Masonry">磚瓦技術</nuxt-link
              >(+1/+1，+3建築護甲) <br />
              <img
                class="gg"
                src="~assets/Architecture.jpg"
                width="30"
                alt=""
              /><nuxt-link to="/techs/Architecture">建築學</nuxt-link
              >(+1/+1，+3建築護甲)
            </td>
          </tr>
          <tr>
            <td class="tta1">視野</td>
            <td class="tta4">
              <img
                class="gg"
                src="~assets/Townwatch.jpg"
                width="30"
                alt=""
              /><nuxt-link to="/techs/Town_Watch">城鎮瞭望</nuxt-link>(+4)
              <br />
              <img
                class="gg"
                src="~assets/Townpatrol.jpg"
                width="30"
                alt=""
              /><nuxt-link to="/techs/Town_Patrol">城鎮巡邏</nuxt-link>(+4)
            </td>
          </tr>
          <tr>
            <td class="tta1">建造速度</td>
            <td class="tta4">
              <img
                class="gg"
                src="~assets/Treadmillcrane.jpg"
                width="30"
                alt=""
              /><nuxt-link to="/techs/Treadmill_Crane">滑輪起重機</nuxt-link
              >(+20%)
            </td>
          </tr>
          <tr>
            <td class="tta1">工作效率</td>
            <td class="tta4">
              <img
                class="gg"
                src="~assets/Conscription.jpg"
                width="30"
                alt=""
              /><nuxt-link to="/techs/Conscription">徵兵制度</nuxt-link>(+33%)
              <br />
              <img
                class="gg"
                src="~assets/CastleAgeUnique.png"
                width="30"
                alt=""
              /><nuxt-link to="/techs/Kasbah">聚居堡壘</nuxt-link
              >(+25%，<nuxt-link to="/civs/Berbers">柏柏</nuxt-link
              >與其同盟限定)
            </td>
          </tr>
          <tr>
            <td class="tta1">其他</td>
            <td class="tta4">
              <img
                class="gg"
                src="~assets/Herbalmedicine.png"
                width="30"
                alt=""
              /><nuxt-link to="/techs/Herbal_Medicine">草藥學</nuxt-link
              >:駐紮單位治療速度加快 <br />
              <img
                class="gg"
                src="~assets/CastleAgeUnique.png"
                width="30"
                alt=""
              /><nuxt-link to="/techs/Crenellations">垛口</nuxt-link
              >:駐紮步兵可增加箭數
            </td>
          </tr>
        </table>

        <h3>更新日誌</h3>
        <div class="hrn1"></div>
        <div class="n1">
          <h3>
            <em><nuxt-link to="/games/aok">帝王世紀</nuxt-link></em>
          </h3>
          <ul>
            <li>城堡視野+10。</li>
          </ul>
          <h3>
            <em><nuxt-link to="/games/aoc">征服者入侵</nuxt-link></em>
          </h3>
          <ul>
            <li>
              引入<nuxt-link to="/techs/Herbal_Medicine">草藥學</nuxt-link>。
            </li>
            <li>
              <nuxt-link to="/civs/Teutons">條頓</nuxt-link>:引入<nuxt-link
                to="/techs/Crenellations"
                >垛口</nuxt-link
              >。
            </li>
          </ul>
          <h3>
            <em><nuxt-link to="/games/aof">失落的帝國</nuxt-link></em>
          </h3>
          <ul>
            <li>城堡現在有11的視野範圍。</li>
            <li>
              <nuxt-link to="/techs/Chemistry">化學</nuxt-link
              >現在會加成城堡的攻擊。
            </li>
            <li>
              <nuxt-link to="/civs/Celts">賽爾特</nuxt-link>:引入<nuxt-link
                to="/techs/Stronghold"
                >堡壘</nuxt-link
              >。
            </li>
            <li>
              <nuxt-link to="/civs/Koreans">韓國</nuxt-link>:城堡建造速度快33%。
            </li>
            <li>
              <nuxt-link to="/civs/Persians">波斯</nuxt-link>:引入<nuxt-link
                to="/techs/Boiling_Oil"
                >沸油</nuxt-link
              >。
            </li>
          </ul>
        </div>
        <h3>建築風格</h3>
        <div class="hrn1"></div>
        <div class="n1">
          <ul>
            <li>西歐城堡類似英格蘭博丁安城堡正門。</li>
            <li>
              中歐城堡擁有塊狀的結構，有四座高碉樓和兩座矮碉樓，跟英格蘭的羅切斯特城堡有著相似之處(雖然這座城堡屬於西歐)。
            </li>
            <li>東歐的城堡類似於波蘭的馬爾堡城堡，擁有土褐色的外表。</li>
            <li>南歐城堡似乎是建立在意大利帕爾馬的Torrechiara城堡。</li>
            <li>
              東亞城堡與日本大阪城的天守閣有著相似之處，即使中國、韓國與蒙古表示黑人問號。
            </li>
            <li>
              美洲城堡近似於馬雅文明的金字塔神廟祭壇，但不是任何一座現實中的城堡。
            </li>
            <li>中東城堡最像敘利亞的騎士堡。</li>
            <li>印度城堡最有可能參考德里紅堡(雖然遊戲中不是紅色的)。</li>
            <li>東南亞城堡似乎建立在一個寺廟上，有明顯的佛教風格。</li>
            <li>跟美洲文明一樣，非洲城堡似乎沒有現實建築長那樣的。</li>
          </ul>
        </div>
        <h3>趣事</h3>
        <div class="hrn1"></div>
        <div class="n1">
          <ul>
            <li>城堡是最貴的軍事建築。</li>
            <li>東亞文明的城堡擺明就是木頭做的，卻還是要花費650石頭。</li>
            <li>
              南美城堡看起來是金字塔神廟祭壇，因為南美文明從來沒有真正建造過城堡來防禦。（歷史中戰俘會被帶上金字塔頂部的神殿，祭師當場剖開「祭品」的胸膛，取出血淋淋還在跳動的心臟獻給神）。
            </li>
          </ul>
        </div>
        <h3>歷史</h3>
        <div class="hrn1"></div>
        <div class="n1">
          <div class="ien">
            <em
              >"第一座城堡出現於公元9世紀的歐洲，是對當地主要堡壘的改善。城堡在戰術上是防禦性的，但也具有戰略上的攻擊性。因為如果有防禦妥當它們是難以奪取的。它們也提供了一個安全的基地，武裝部隊可以透過這個基地擴大對地方的控制。一位領主都有他們專屬的武裝部隊效忠於他。十世紀到十一世紀時城堡遍布歐洲，以應付來自北部和東部的軟弱的中央政權和野蠻人的襲擊。國王花費了中世紀的剩餘時間試圖奪回當地領主手中的城堡控制權。十五世紀的火砲發展終於讓城堡變得不再是那麼無堅不摧。"</em
            >
            <p style="text-align: right;margin-top: 10px;">-世紀帝國II手稿。</p>
          </div>
        </div>
      </div>
      <div class="col-md-4">
        <table class="table-bordered" width="100%">
          <tr>
            <td class="unit" colspan="2" style="background-color:#3c763d;">
              <div class="unititle2">
                城堡
              </div>
            </td>
          </tr>
          <tr>
            <td colspan="2">
              <div class="unititle">
                <img src="~assets/Castleicon.png" width="45" alt="" />
              </div>
            </td>
          </tr>
          <tr>
            <td class="unit" colspan="2" style="background-color:#3c763d;">
              <div class="unititle2">概要</div>
            </td>
          </tr>
          <tr>
            <td class="unit3">類型</td>
            <td class="unit4">軍事 <br />防禦建築</td>
          </tr>
          <tr>
            <td class="unit3">文明</td>
            <td class="unit4">所有文明</td>
          </tr>
          <tr>
            <td class="unit3">時代</td>
            <td class="unit4">
              <nuxt-link to="/techs/age/Castle_Age">城堡時代</nuxt-link>
            </td>
          </tr>
          <tr>
            <td class="unit3">建築時間</td>
            <td class="unit4">200秒</td>
          </tr>
          <tr>
            <td class="unit" colspan="2" style="background-color:#3c763d;">
              <div class="unititle2">成本</div>
            </td>
          </tr>
          <tr>
            <td class="unit3">石頭</td>
            <td class="unit4">650</td>
          </tr>
          <tr>
            <td class="unit" colspan="2" style="background-color:#3c763d;">
              <div class="unititle2"><nuxt-link to="">數據</nuxt-link></div>
            </td>
          </tr>
          <tr>
            <td class="unit3">尺寸</td>
            <td class="unit4">4x4</td>
          </tr>
          <tr>
            <td class="unit3">生命值</td>
            <td class="unit4">4800</td>
          </tr>
          <tr>
            <td class="unit3">駐軍</td>
            <td class="unit4">20</td>
          </tr>
          <tr>
            <td class="unit3">攻擊</td>
            <td class="unit4">11(遠程)</td>
          </tr>
          <tr>
            <td class="unit3">攻擊加成</td>
            <td class="unit4">
              對<nuxt-link to="/armor/Armor_Class_Spearman">長槍兵</nuxt-link>+2
            </td>
          </tr>
          <tr>
            <td class="unit3">射速</td>
            <td class="unit4">2.03</td>
          </tr>
          <tr>
            <td class="unit3">範圍</td>
            <td class="unit4">8</td>
          </tr>
          <tr>
            <td class="unit3">最小範圍</td>
            <td class="unit4">1</td>
          </tr>
          <tr>
            <td class="unit3">準確性</td>
            <td class="unit4">100%</td>
          </tr>
          <tr>
            <td class="unit3">投射物速度</td>
            <td class="unit4">7</td>
          </tr>
          <tr>
            <td class="unit3">近防</td>
            <td class="unit4">8</td>
          </tr>
          <tr>
            <td class="unit3">遠防</td>
            <td class="unit4">11</td>
          </tr>
          <tr>
            <td class="unit3">護甲分類</td>
            <td class="unit4">
              <nuxt-link to="/armor/Armor_Class_Building">建築</nuxt-link>（+8）
              <br />
              <nuxt-link to="/armor/Armor_Class_Standard_Building"
                >標準建築</nuxt-link
              >
              <br />
              <nuxt-link to="/armor/Armor_Class_Castle">城堡</nuxt-link>
            </td>
          </tr>
          <tr>
            <td class="unit3">視野</td>
            <td class="unit4">11</td>
          </tr>
        </table>

        <div class="thanks">感謝！本頁面由順宗與Dennis協助完成。</div>
      </div>
    </div>
    <div class="col-md-12">
      <h3>圖庫</h3>
      <div class="hrn1"></div>
      <div class="n1">
        <div class="col-md-4">
          <gallery
            ><img
              class="imgn hg"
              width="180"
              src="~assets/Castleaokaoc.jpg"
              alt=""
          /></gallery>
          <div class="lightbox-caption" style="width:220px">
            <p><em>所有城堡(帝王世紀和征服者入侵資料片)。</em></p>
          </div>
        </div>
        <div class="col-md-4">
          <gallery
            ><img class="imgn hg" width="200" src="~assets/Castlehd.jpg" alt=""
          /></gallery>
          <div class="lightbox-caption" style="width:220px">
            <p><em>所有城堡(HD擴充資料片)。</em></p>
          </div>
        </div>
        <div class="col-md-4">
          <gallery
            ><img
              class="imgn hg"
              width="200"
              src="~assets/Spritesheet_castle.jpg"
              alt=""
          /></gallery>
          <div class="lightbox-caption" style="width:185px">
            <p><em>城堡在一般地圖/下雪地圖和駐紮單位時的樣子。</em></p>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>
<script>
export default {
  layout: 'allbuilding',
  components: {}
}
</script>
<style></style>
