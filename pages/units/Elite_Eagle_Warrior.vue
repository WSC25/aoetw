<template>
  <div class="container">
    <div class="row padtop">
      <div class="col-md-12">
        <h1>精銳鷹勇士</h1>
        <div class="hrn1"></div>
      </div>
      <div class="col-md-8">
        <div class="n1">
          <p>
            南美文明限定，<nuxt-link to="/civs/Mayans">馬雅</nuxt-link
            >、<nuxt-link to="/civs/Aztecs">阿茲特克</nuxt-link>、<nuxt-link
              to="/civs/Incas"
              >印加</nuxt-link
            >，鷹斥候的最高等級。
          </p>
        </div>
        <h3>戰術</h3>
        <div class="hrn1"></div>
        <div class="n1">
          <p>
            可以根據三個文明不同而打出不同戰術，而相同的是鷹勇士克制所有的攻城武器與僧侶，對騎兵部隊有加成。但幾乎所有的步兵都對鷹勇士有額外的傷。從根本上說，鷹勇士彌補了南美文明沒有馬的不足。
          </p>
          <strong><nuxt-link to="/civs/Aztecs">阿茲特克</nuxt-link></strong>
          <p>
            <nuxt-link to="/techs/Garland_Wars">榮冠戰爭</nuxt-link
            >為他們的所有步兵加4攻擊，這攻擊讓他們更佳強大，只要三下即可殺死一位村民。配合豹勇士殺步兵，與鷹勇士相輔相成。
          </p>
          <strong><nuxt-link to="/civs/Mayans">馬雅</nuxt-link></strong>
          <p>
            <nuxt-link to="/techs/El_Dorado">黃金國</nuxt-link
            >為他們的鷹勇士加40生命，這生命讓他們可以更坦。配合速度快的羽毛箭射手讓人聞風喪膽。
          </p>
          <strong><nuxt-link to="/civs/Incas">印加</nuxt-link></strong>
          <p>
            <nuxt-link to="/techs/Couriers">信使</nuxt-link
            >為他們的鷹勇士加防禦，這防禦讓他們可以不用怕任何弓(含<nuxt-link
              to="/building/Castle"
              >城堡</nuxt-link
            >)。高防禦鷹勇士配合印加的
            <nuxt-link to="/units/Kamayuk">槍隊長</nuxt-link>與<nuxt-link
              to="/units/Slinger"
              >投石手</nuxt-link
            >，組成了印加堅不可破的防線，除了遇到<nuxt-link
              to="/units/Hand_Cannoneer"
              >火槍兵</nuxt-link
            >以外。
          </p>
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
            <td class="tta1" style="width:30%">強勢(容易對抗)</td>
            <td class="tta4">
              <nuxt-link to="/units/Archer_Units">弓兵</nuxt-link>、<nuxt-link
                to="/units/Siege_Weapons"
                >攻城單位</nuxt-link
              >、 <nuxt-link to="/units/Monk">僧侶</nuxt-link>。
            </td>
          </tr>
          <tr>
            <td class="tta1" style="width:30%">劣勢(不易對抗)</td>
            <td class="tta4">
              <nuxt-link to="/units/Cataphract">聖騎兵</nuxt-link>、<nuxt-link
                to="/units/Boyar"
                >貴族鐵騎</nuxt-link
              >、<nuxt-link to="/units/Janissary">土耳其火槍兵</nuxt-link>、
              <nuxt-link to="/units/Infantry_Units">步兵</nuxt-link>、<nuxt-link
                to="/units/Slinger"
                >投石手</nuxt-link
              >。
            </td>
          </tr>
          <tr class="tta">
            <td colspan="2" style="text-align: center;">
              <div class="unititle">升級</div>
            </td>
          </tr>
          <tr>
            <td class="tta1" style="width:10%">生命值</td>
            <td class="tta4">
              <img src="~assets/Unique-tech.jpg" class="gg" alt="" /><nuxt-link
                to="/batt/El_Doradoa"
                >黃金國</nuxt-link
              >(+40，<nuxt-link to="/civs/Mayans">馬雅</nuxt-link>限定)
            </td>
          </tr>
          <tr>
            <td class="tta1" style="width:10%">攻擊力</td>
            <td class="tta4">
              <img
                class="gg"
                src="~assets/Forging.jpg"
                width="30"
                alt=""
              /><nuxt-link to="/techs/Forging">鍛造</nuxt-link>(+1) <br />
              <img
                class="gg"
                src="~assets/Ironcasting.jpg"
                width="30"
                alt=""
              /><nuxt-link to="/techs/Iron_Casting">鑄造</nuxt-link>(+1) <br />
              <img
                class="gg"
                src="~assets/Blastfurnace.jpg"
                width="30"
                alt=""
              /><nuxt-link to="/techs/Blast_Furnace">鼓風爐</nuxt-link>(+2)
              <br />
              <img
                class="gg"
                src="~assets/Arson.jpg"
                width="30"
                alt=""
              /><nuxt-link to="/techs/Arson">縱火</nuxt-link
              >:步兵+2攻擊vs<nuxt-link to="/armor/Armor_Class_Standard_Building"
                >標準建築</nuxt-link
              >
              <br />
              <img
                class="gg"
                src="~assets/Unique-tech.jpg"
                width="30"
                alt=""
              /><nuxt-link to="/techs/Garland_Wars">榮冠戰爭</nuxt-link
              >:步兵攻擊+4，<nuxt-link to="/civs/Aztecs">阿茲特克</nuxt-link
              >限定。
            </td>
          </tr>
          <tr>
            <td class="tta1" style="width:10%">防禦</td>
            <td class="tta4">
              <img
                class="gg"
                src="~assets/Scalemailarmor.jpg"
                width="30"
                alt=""
              /><nuxt-link to="/techs/Scale_Mail_Armor">步兵鱗甲</nuxt-link
              >(+1/+1) <br />
              <img
                class="gg"
                src="~assets/Chainmailarmor.jpg"
                width="30"
                alt=""
              /><nuxt-link to="/techs/Chain_Mail_Armor">步兵鎖甲</nuxt-link
              >(+1/+1) <br />
              <img
                class="gg"
                src="~assets/Platemailarmor.jpg"
                width="30"
                alt=""
              /><nuxt-link to="/techs/Plate_Mail_Armor">步兵板甲</nuxt-link
              >(+1/+2) <br />
              <img src="~assets/Unique-tech.jpg" class="gg" alt="" /><nuxt-link
                to="/techs/Couriers"
                >信使</nuxt-link
              >(+1/+2，<nuxt-link to="/civs/Incas">印加</nuxt-link
              >，從<nuxt-link to="/games/ak">非洲王朝</nuxt-link>資料片開始)
            </td>
          </tr>
          <tr>
            <td class="tta1" style="width:10%">速度</td>
            <td class="tta4">
              <img
                class="gg"
                src="~assets/Squires.jpg"
                width="30"
                alt=""
              /><nuxt-link to="/techs/Squires">護衛</nuxt-link>(+10%) <br />
              <img class="gg" src="~assets/Unique-tech.jpg" alt="" /><nuxt-link
                to="/techs/Couriers"
                >信使</nuxt-link
              >(+10%，<nuxt-link to="/civs/Incas">印加</nuxt-link
              >限定，只在<nuxt-link to="/games/aof">失落的帝國</nuxt-link
              >資料片有)
            </td>
          </tr>
          <tr>
            <td class="tta1" style="width:10%">視野</td>
            <td class="tta4">
              <img
                class="gg"
                src="~assets/Tracking.jpg"
                width="30"
                alt=""
              /><nuxt-link to="/techs/Tracking">追蹤技術</nuxt-link>(+2)
            </td>
          </tr>
          <tr>
            <td class="tta1" style="width:10%">招降抵抗</td>
            <td class="tta4">
              <img
                class="gg"
                src="~assets/Faith.jpg"
                width="30"
                alt=""
              /><nuxt-link to="/techs/Faith">忠誠信仰</nuxt-link> <br />
              <img
                class="gg"
                src="~assets/Heresy.png"
                width="30"
                alt=""
              /><nuxt-link to="/techs/Heresy">異端邪說</nuxt-link>
            </td>
          </tr>
          <tr>
            <td class="tta1" style="width:10%">生產速度</td>
            <td class="tta4">
              <img
                class="gg"
                src="~assets/Conscription.jpg"
                width="30"
                alt=""
              /><nuxt-link to="/techs/Conscription">徵兵制度</nuxt-link>(+33%)
            </td>
          </tr>
        </table>

        <h3>剋鷹勇士的單位</h3>
        <div class="hrn1"></div>
        <div class="n1">
          以下單位擁有對鷹勇士系的額外傷害，按造傷殺力排列。一般來說，大多數的
          <nuxt-link to="/armor/Armor_Class_Infantry">步兵單位</nuxt-link
          >都有加成。
          <div class="n1">
            <div class="row">
              <div class="col-md-6">
                <div style="margin:12px 0px;"><strong>+8攻擊</strong></div>
                <ul>
                  <li>
                    <img
                      class="gg"
                      src="~assets/2HandedswordsmanIcon.jpg"
                      alt=""
                    />
                    <nuxt-link to="/units/Two-Handed_Swordsman"
                      >雙手劍兵</nuxt-link
                    >→ <img class="gg" src="~assets/ChampionIcon.jpg" alt="" />
                    <nuxt-link to="/units/Champion">劍兵勇士</nuxt-link>
                  </li>
                </ul>
                <div style="margin:12px 0px;"><strong>+6攻擊</strong></div>
                <ul>
                  <li>
                    <img
                      class="gg"
                      src="~assets/LongswordsManIcon.jpg"
                      alt=""
                    />
                    <nuxt-link to="/units/Long_Swordsman">長劍兵</nuxt-link>
                  </li>
                </ul>
                <div style="margin:12px 0px;"><strong>+4攻擊</strong></div>
                <ul>
                  <li>
                    <img class="gg" src="~assets/Crusade_avatar.png" alt="" />
                    <nuxt-link to="/units/Teutonic_Knight">條頓武士</nuxt-link>
                    <img
                      class="gg"
                      src="~assets/Crusade_avatar.png"
                      alt=""
                    /><nuxt-link to="/units/Teutonic_Knight"
                      >精銳條頓武士</nuxt-link
                    >
                  </li>
                </ul>
                <div style="margin:12px 0px;"><strong>+3攻擊</strong></div>
                <ul>
                  <li>
                    <img class="gg" src="~assets/WBRSK.jpg" alt="" />
                    <nuxt-link to="/units/Woad_Raider">精銳菘藍武士</nuxt-link>
                  </li>
                  <li>
                    <img class="gg" src="~assets/SMURI.jpg" alt="" /><nuxt-link
                      to="/units/Samurai"
                      >精銳日本武士</nuxt-link
                    >
                    <br />
                  </li>
                  <li>
                    <img
                      class="gg"
                      src="~assets/HuskarlIcon.jpg"
                      alt=""
                    /><nuxt-link to="/units/Huskarl">精銳哥德衛隊</nuxt-link>
                  </li>
                  <li>
                    <img class="gg" src="~assets/VBRSK.jpg" alt="" /><nuxt-link
                      to="/units/Berserk"
                      >精銳狂戰士</nuxt-link
                    >
                  </li>
                </ul>
              </div>
              <div class="col-md-6">
                <div style="margin:12px 0px;"><strong>+2攻擊</strong></div>
                <ul>
                  <li>
                    <img
                      class="gg"
                      src="~assets/ManAtArmsIcon.jpg"
                      alt=""
                      width="22"
                    />
                    <nuxt-link to="/units/Man-at-Arms">裝甲步兵</nuxt-link>
                  </li>
                  <li>
                    <img class="gg" src="~assets/WBRSK.jpg" alt="" /><nuxt-link
                      to="/units/Woad_Raider"
                      >菘藍武士</nuxt-link
                    >
                  </li>
                  <li>
                    <img class="gg" src="~assets/SMURI.jpg" alt="" /><nuxt-link
                      to="/units/Samurai"
                      >日本武士</nuxt-link
                    >
                  </li>
                  <li>
                    <img
                      class="gg"
                      src="~assets/HuskarlIcon.jpg"
                      alt=""
                    /><nuxt-link to="/units/Huskarl">哥德衛隊</nuxt-link>
                  </li>
                  <li>
                    <img class="gg" src="~assets/VBRSK.jpg" alt="" /><nuxt-link
                      to="/units/Berserk"
                      >狂戰士</nuxt-link
                    >
                  </li>
                  <li>
                    <img class="gg" src="~assets/TAXEM.jpg" alt="" /><nuxt-link
                      to="/units/Throwing_Axeman"
                      >精銳擲斧兵</nuxt-link
                    >
                  </li>
                  <li>
                    <img
                      class="gg"
                      src="~assets/Karambitwarrioricon.png"
                      alt=""
                    /><nuxt-link to="/units/Karambit_Warrior"
                      >爪刀勇士</nuxt-link
                    >→
                    <img
                      class="gg"
                      src="~assets/Karambitwarrioricon.png"
                      alt=""
                    />
                    <nuxt-link to="/units/Karambit_Warrior"
                      >精銳爪刀勇士</nuxt-link
                    >
                  </li>
                  <li>
                    <img
                      class="gg"
                      src="~assets/ShotelIcon.png"
                      alt=""
                    /><nuxt-link to="/units/Shotel_Warrior">彎刀勇士</nuxt-link
                    >→ <img class="gg" src="~assets/ShotelIcon.png" alt="" />
                    <nuxt-link to="/units/Shotel_Warrior"
                      >精銳彎刀勇士</nuxt-link
                    >
                  </li>
                  <li>
                    <img
                      class="gg"
                      src="~assets/JaguarWarriorIcon.jpg"
                      alt=""
                    /><nuxt-link to="/units/Jaguar_Warrior">豹勇士</nuxt-link>→
                    <img
                      class="gg"
                      src="~assets/JaguarWarriorIcon.jpg"
                      alt=""
                    /><nuxt-link to="/units/Jaguar_Warrior"
                      >精銳豹勇士</nuxt-link
                    >
                  </li>
                </ul>
                <div style="margin:12px 0px;"><strong>+1攻擊</strong></div>
                <ul>
                  <li>
                    <img class="gg" src="~assets/SpearmanIcon.jpg" alt="" />
                    <nuxt-link to="/units/Spearman">長槍兵</nuxt-link>→
                    <img class="gg" src="~assets/PikemanIcon.jpg" alt="" />
                    <nuxt-link to="/units/Pikeman">重裝長槍兵</nuxt-link>→
                    <img class="gg" src="~assets/HalberdierIcon.jpg" alt="" />
                    <nuxt-link to="/units/Halberdier">戟兵</nuxt-link>
                  </li>
                  <li>
                    <img class="gg" src="~assets/TAXEM.jpg" alt="" /><nuxt-link
                      to="/units/Throwing_Axeman"
                      >擲斧兵</nuxt-link
                    >
                  </li>
                  <li>
                    <img
                      class="gg"
                      src="~assets/GbetoIcon.png"
                      alt=""
                    /><nuxt-link to="/units/Gbeto">飛刀女獵手</nuxt-link>→
                    <img class="gg" src="~assets/GbetoIcon.png" alt="" />
                    <nuxt-link to="/units/Gbeto">精銳飛刀女獵手</nuxt-link>
                  </li>
                </ul>
              </div>
            </div>
          </div>
        </div>
        <h3>文明加成</h3>
        <div class="hrn1"></div>
        <div class="n1">
          <ul>
            <li>
              <nuxt-link to="/civs/Aztecs">阿茲特克</nuxt-link
              >：精銳鷹勇士生產速度提高15％。
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
              >能夠加速<nuxt-link to="/techs/Conscription">徵兵制度</nuxt-link
              >、的研究時間(快25%)。
            </li>
            <li>
              <nuxt-link to="/civs/Goths">哥德</nuxt-link
              >：精銳鷹勇士訓練和升級快20%。研發<nuxt-link to="/techs/Tracking"
                >追蹤技術</nuxt-link
              >、 <nuxt-link to="/techs/Squires">護衛</nuxt-link>、<nuxt-link
                to="/techs/Arson"
                >縱火</nuxt-link
              >科技的時間快20%。
            </li>
            <li>
              <nuxt-link to="/civs/Teutons">條頓</nuxt-link
              >：精銳鷹勇士更不容易被招降。
            </li>
          </ul>
        </div>
        <h3>更新日誌</h3>
        <div class="hrn1"></div>
        <div class="n1">
          <h3>
            <em><nuxt-link to="/games/aof">失落的帝國</nuxt-link></em>
          </h3>
          <ul>
            <li>精銳鷹勇士改變外觀。</li>
            <li>
              精銳鷹勇士對<nuxt-link to="/armor/Armor_Class_Camel"
                >駱駝</nuxt-link
              >攻擊+2。
            </li>
            <li>
              <nuxt-link to="/civs/Incas">印加</nuxt-link>:<nuxt-link
                to="/techs/Couriers"
                >信使</nuxt-link
              >給予精銳鷹勇士+10％的移動速度。
            </li>
          </ul>
          <h3>
            <em><nuxt-link to="/games/ak">非洲王國</nuxt-link></em>
          </h3>
          <ul>
            <li>升級到鷹勇士為200食物/200黃金。</li>
            <li>速度由1.1升級到1.2。</li>
            <li>
              <nuxt-link to="/civs/Incas">印加</nuxt-link>:<nuxt-link
                to="/techs/Couriers"
                >信使</nuxt-link
              >給予精銳鷹勇士+1/+2的防禦。移除+10％的速度。
            </li>
          </ul>
          <h3>
            <em><nuxt-link to="/games/aor">王者崛起</nuxt-link></em>
          </h3>
          <ul>
            <li>
              5.7版本後鷹勇士現在對<nuxt-link to="/armor/Armor_Class_Camel"
                >駱駝單位</nuxt-link
              >攻擊+3。
            </li>
          </ul>
        </div>
        <h3>趣事</h3>
        <div class="hrn1"></div>
        <div class="n1">
          <ul>
            <li>鷹勇士是最貴的黃金步兵單位，但也是最便宜的食物步兵單位。</li>
          </ul>
        </div>
      </div>
      <div class="col-md-4">
        <table class="table-bordered" width="100%">
          <tr>
            <td class="unit" colspan="2" style="background-color:#3c763d;">
              <div class="unititle2">
                精銳鷹勇士
              </div>
            </td>
          </tr>
          <tr>
            <td colspan="2">
              <div class="unititle">
                <img
                  src="~assets/EliteEagleWarriorIcon.jpg"
                  width="45"
                  alt=""
                />
              </div>
            </td>
          </tr>
          <tr>
            <td class="unit" colspan="2" style="background-color:#3c763d;">
              <div class="unititle2">單位介紹</div>
            </td>
          </tr>
          <tr>
            <td class="unit3">類型</td>
            <td class="unit4">
              <nuxt-link to="/units/Infantry_Units">步兵</nuxt-link>
            </td>
          </tr>
          <tr>
            <td class="unit3">文明</td>
            <td class="unit4">
              <nuxt-link to="/civs/Aztecs">阿茲特克</nuxt-link> <br />
              <nuxt-link to="/civs/Incas">印加</nuxt-link> <br />
              <nuxt-link to="/civs/Mayans">馬雅</nuxt-link>
            </td>
          </tr>
          <tr>
            <td class="unit3">時代</td>
            <td class="unit4">
              <img
                class="gg"
                src="~assets/Imperial-age-research.jpg"
                alt=""
              /><nuxt-link to="/techs/age/Imperial_Age">帝王時代</nuxt-link>
            </td>
          </tr>
          <tr>
            <td class="unit3">訓練於</td>
            <td class="unit4">
              <img
                class="gg"
                src="~assets/Barracks-logo.jpg"
                alt=""
              /><nuxt-link to="/building/Barracks">軍營</nuxt-link>
            </td>
          </tr>
          <tr>
            <td class="unit3">訓練時間</td>
            <td class="unit4">20秒</td>
          </tr>
          <tr>
            <td class="unit" colspan="2" style="background-color:#3c763d;">
              <div class="unititle2">成本</div>
            </td>
          </tr>
          <tr>
            <td class="unit3">金</td>
            <td class="unit4">50</td>
          </tr>
          <tr>
            <td class="unit3">肉</td>
            <td class="unit4">20</td>
          </tr>
          <tr>
            <td class="unit" colspan="2" style="background-color:#3c763d;">
              <div class="unititle2"><nuxt-link to="">數據</nuxt-link></div>
            </td>
          </tr>
          <tr>
            <td class="unit3">血量</td>
            <td class="unit4">60</td>
          </tr>
          <tr>
            <td class="unit3">攻擊</td>
            <td class="unit4">9(近戰)</td>
          </tr>
          <tr>
            <td class="unit3">攻擊加成</td>
            <td class="unit4">
              +10 vs <nuxt-link to="/armor/Armor_Class_Monk">僧侶</nuxt-link>
              <br />+5 vs<nuxt-link to="/armor/Armor_Class_Siege_Weapon"
                >攻城武器</nuxt-link
              >
              <br />+4 vs
              <nuxt-link to="/armor/Armor_Class_Cavalry">騎兵</nuxt-link>
              <br />+3 vs
              <nuxt-link to="/armor/Armor_Class_Camel">駱駝騎兵</nuxt-link>
              <br />+2 vs
              <nuxt-link to="/armor/Armor_Class_Ship">船隻</nuxt-link>
            </td>
          </tr>
          <tr>
            <td class="unit3">攻擊速度</td>
            <td class="unit4">2.03</td>
          </tr>
          <tr>
            <td class="unit3">近防</td>
            <td class="unit4">0</td>
          </tr>
          <tr>
            <td class="unit3">遠防</td>
            <td class="unit4">4</td>
          </tr>
          <tr>
            <td class="unit3"><nuxt-link to="/armor">防禦類型</nuxt-link></td>
            <td class="unit4">
              <nuxt-link to="/armor/Armor_Class_Infantry">步兵</nuxt-link>
              <br />
              <nuxt-link to="/armor/Armor_Class_Eagle_Warrior"
                >鷹勇士</nuxt-link
              >
            </td>
          </tr>
          <tr>
            <td class="unit3">跑速</td>
            <td class="unit4">1.3</td>
          </tr>
          <tr>
            <td class="unit3">視野</td>
            <td class="unit4">6</td>
          </tr>
          <tr>
            <td class="unit" colspan="2" style="background-color:#3c763d;">
              <div class="unititle2"><nuxt-link to="">單位演變</nuxt-link></div>
            </td>
          </tr>
          <tr>
            <td class="unit3">從升級</td>
            <td class="unit4">
              <img
                class="gg"
                src="~assets/EagleWarriorIcon.jpg"
                alt=""
              /><nuxt-link to="/units/Eagle_Warrior">鷹勇士</nuxt-link>
            </td>
          </tr>
        </table>

        <div class="thanks">感謝! 此頁面由眠的觀眾協助編輯</div>
      </div>
    </div>
    <div class="col-md-12">
      <h3>圖庫</h3>
      <div class="hrn1"></div>
      <div class="n1">
        <div class="col-md-4">
          <gallery
            ><img class="imgn hg" src="~assets/Eagleline.png" alt=""
          /></gallery>
          <p><em>鷹勇士系列</em></p>
        </div>
        <div class="col-md-4">
          <gallery
            ><img class="imgn hg" src="~assets/Eaglescout.png" alt=""
          /></gallery>
          <p><em>一群精銳鷹勇士(《世紀帝國II:征服者入侵》資料片)</em></p>
        </div>
        <div class="col-md-4">
          <gallery
            ><img class="imgn hg" src="~assets/Eaglewarrior.png" alt=""
          /></gallery>
          <p><em>一群精銳鷹勇士(《世紀帝國II:失落的帝國》資料片)</em></p>
        </div>
      </div>
    </div>
  </div>
</template>
<script>
export default {
  layout: 'allunit',
  components: {}
}
</script>
<style></style>
