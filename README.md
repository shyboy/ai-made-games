# AI 游戏收录

收录 AI 参与制作的网页版和单机版游戏，按玩法分组，方便找想玩的类型。当前共有 **50 个游戏条目**：13 个 HTML 游戏保存在本仓库，可以在线玩或下载；37 个外部条目提供原作者的试玩或获取地址。

**2026-11-11 更新**：新增 12 款，新增条目均于当日核验可访问。本轮核心是 Claude Opus 5.5 的四款作品（Simon Willison，2026-10-28 称十月为氛围编程做游戏的拐点：一句“Make it a LOT more fun”真的能让游戏变好玩），以及 10 月中旬后走红的 PokéBonk（上线不久玩家破百万）、V2EX 10 月底至 11 月初的中文新作（LLM 塔防、大航海群像志、AI 代打 SLG、GLM-5.3 刹车小游戏）和两款联机新作。

**[打开可视化游戏目录](https://shyboy.github.io/ai-made-games/)**

## 仓库内的游戏

这 13 款均为单文件 HTML，点击“开始游戏”可在线玩，也可下载文件在电脑上打开。其中 6 款由杨老师提供，作者署名为微信昵称 **朱斌**；收录时只将文件改名为各目录下的 `index.html`，未修改游戏内容。另 6 款署名为 **杨老师玩AI · AI 生成**。《SWARM》署名原作者 **Nerabwyn**，单独采用 MIT 许可。

我把自己做的 6 款小游戏重新打磨了一遍：《锦鲤消消》换上锦鲤池和瓷片棋子，《夜市叠箱》《灯会翻牌》加入灯火夜景、木箱与花灯卡面，其余三款也更新了场景和界面。图片已嵌入 HTML，下载后仍可直接打开；音效默认关闭，可在游戏内开启。

### 策略与经营

| 游戏 | 作者 | 在线游玩 | 文件 |
| --- | --- | --- | --- |
| 楚河·军阵 II · 千军入局 | 朱斌 | [开始游戏](https://shyboy.github.io/ai-made-games/games/chuhe-army/) | [`games/chuhe-army/index.html`](games/chuhe-army/index.html) |
| 星主俱乐部 V3.0 · 画线转位版 | 朱斌 | [开始游戏](https://shyboy.github.io/ai-made-games/games/star-club-football/) | [`games/star-club-football/index.html`](games/star-club-football/index.html) |
| 十一王国 · 诸侯争锋 | 朱斌 | [开始游戏](https://shyboy.github.io/ai-made-games/games/eleven-kingdoms/) | [`games/eleven-kingdoms/index.html`](games/eleven-kingdoms/index.html) |
| 星环防线 V3 · 超载舰队 | 朱斌 | [开始游戏](https://shyboy.github.io/ai-made-games/games/star-ring-defense/) | [`games/star-ring-defense/index.html`](games/star-ring-defense/index.html) |

### 动作、射击与闯关

| 游戏 | 作者 | 在线游玩 | 文件 |
| --- | --- | --- | --- |
| 星刃共鸣 V3 · 刀环乱斗 | 朱斌 | [开始游戏](https://shyboy.github.io/ai-made-games/games/starblade-resonance/) | [`games/starblade-resonance/index.html`](games/starblade-resonance/index.html) |
| 夜市冲刺 | 杨老师玩AI · AI 生成 | [开始游戏](https://shyboy.github.io/ai-made-games/games/night-market-dash/) | [`games/night-market-dash/index.html`](games/night-market-dash/index.html) |
| 纸飞机防线 | 杨老师玩AI · AI 生成 | [开始游戏](https://shyboy.github.io/ai-made-games/games/paper-plane-line/) | [`games/paper-plane-line/index.html`](games/paper-plane-line/index.html) |
| SWARM · 虫潮生存 | Nerabwyn（MIT） | [开始游戏](https://shyboy.github.io/ai-made-games/games/swarm/) | [`games/swarm/index.html`](games/swarm/index.html) |

### 益智与休闲

| 游戏 | 作者 | 在线游玩 | 文件 |
| --- | --- | --- | --- |
| 锦鲤消消 | 杨老师玩AI · AI 生成 | [开始游戏](https://shyboy.github.io/ai-made-games/games/koi-match/) | [`games/koi-match/index.html`](games/koi-match/index.html) |
| 夜市叠箱 | 杨老师玩AI · AI 生成 | [开始游戏](https://shyboy.github.io/ai-made-games/games/night-crate/) | [`games/night-crate/index.html`](games/night-crate/index.html) |
| 灯会翻牌 | 杨老师玩AI · AI 生成 | [开始游戏](https://shyboy.github.io/ai-made-games/games/lantern-memory/) | [`games/lantern-memory/index.html`](games/lantern-memory/index.html) |

### 模拟与文字冒险

| 游戏 | 作者 | 在线游玩 | 文件 |
| --- | --- | --- | --- |
| 回到客厅 · FC 网页游戏机 | 朱斌 | [开始游戏](https://shyboy.github.io/ai-made-games/games/living-room-fc/) | [`games/living-room-fc/index.html`](games/living-room-fc/index.html) |
| 雨巷书摊 | 杨老师玩AI · AI 生成 | [开始游戏](https://shyboy.github.io/ai-made-games/games/rain-bookstall/) | [`games/rain-bookstall/index.html`](games/rain-bookstall/index.html) |

“回到客厅”内置原创测试游戏；导入其他 `.nes` 文件时，请使用自己有权使用的文件。它的内置模拟核心可离线运行，可选的 JSNES 标准核心需要联网加载。

《SWARM》由 Nerabwyn 以 MIT 许可发布，玩法接近 Vampire Survivors，属非官方同人。本仓库托管副本的界面为简体中文，上游原版为英文；[原仓库](https://github.com/Nerabwyn/swarm)及[许可文件](games/swarm/LICENSE)可供核对。

## 外部游戏

这些作品保留在原作者处，本仓库只收录入口和出处。AI 参与制作的信息依据创作者的公开说明；少数作品需要下载后在本地运行。

### 策略、塔防与经营

| 游戏 | 作者／发布者 | 试玩／获取 | 出处 |
| --- | --- | --- | --- |
| 夜潮 Nightide | [defiabell](https://www.v2ex.com/member/defiabell) | [开始游戏](https://defiabell.github.io/nightide/) | [作者发布帖](https://www.v2ex.com/t/1229945) |
| 修仙掌门生涯（Demo） | [aeli](https://www.v2ex.com/member/aeli) | [开始游戏](https://xiuxian.safafish.com/) | [作者发布帖](https://www.v2ex.com/t/1195159) |
| 晴湾防线 | [iiduce](https://www.v2ex.com/member/iiduce) | [开始游戏](https://tz100.com/zh/games/sunharbor-defense) | [作者发布帖](https://www.v2ex.com/t/1243393) |
| 晴湾防线无尽版（终局地图上的无限波次，按守住的波数排行） | [iiduce](https://www.v2ex.com/member/iiduce) | [开始游戏](https://tz100.com/zh/games/sunharbor-endless) | [作者发布帖](https://www.v2ex.com/t/1243393) |
| 象棋（与分级电脑对弈，或开房和好友下） | [iiduce](https://www.v2ex.com/member/iiduce) | [开始游戏](https://tz100.com/zh/games/xiangqi) | [作者发布帖](https://www.v2ex.com/t/1243393) |
| EPOCH（从石器时代打到太空的单文件塔防，英文界面） | [okturan](https://github.com/okturan) | [开始游戏](https://okturan.github.io/epoch-td/) | [原仓库](https://github.com/okturan/epoch-td) |
| Battle Drones（Claude Opus 5.5 做的 3D 即时战略，2–4 人联机、AI 对战，英文界面，Apache 2.0） | [Simon Willison](https://simonwillison.net/2026/Oct/20/battledrones/) | [开始游戏](https://simonw.github.io/battledrones/) | [原仓库](https://github.com/simonw/battledrones) |
| 大航海群像志（挂机网页游戏，大航海时代 4 骨架，可委托 AI 自动经营，模拟三天半结算排行） | T800ai | [开始游戏](https://dhh.funnyai.wiki) | [作者发布帖](https://www.v2ex.com/t/1252024) |
| Quarter Sun Cove · 南瓜农场（Claude Opus 5.5 做的南瓜农场经营模拟，英文界面） | Simon Willison | [开始游戏](https://simonw.github.io/pumpkin-farmer/) | [原仓库](https://github.com/simonw/pumpkin-farmer) |
| AI 替我打的策略 SLG（把操作复制给 Claude / ChatGPT 代打建城练兵，MIT 开源，需登录） | xltc20 | [开始游戏](https://slg.yuntianyou.cc) | [作者发布帖](https://www.v2ex.com/t/1255182) |
| LLM 塔防（招 Claude、GPT、DeepSeek、Qwen 当炮塔守可用性；Web 版加载较慢，以下载客户端为主） | ninvfeng | [官网及下载](https://llmtd.ninvfeng.com) | [作者发布帖](https://www.v2ex.com/t/1252432) |

### 动作、射击与竞速

| 游戏 | 作者／发布者 | 试玩／获取 | 出处 |
| --- | --- | --- | --- |
| 鹈鹕骑自行车 | [riba2534](https://github.com/riba2534) | [开始游戏](https://claude-opus-5-5.riba2534.cn/) | [Claude Opus 5.5 Demo](https://github.com/riba2534/claude-opus-5-5-demo) |
| 穿越火线·运输船 | [riba2534](https://github.com/riba2534) | [开始游戏](https://claude-opus-5-5-cf-transport-ship.pages.dev/) | [Claude Opus 5.5 Demo](https://github.com/riba2534/claude-opus-5-5-demo) |
| QQ 飞车 | [riba2534](https://github.com/riba2534) | [开始游戏](https://claude-opus-5-5-qqfeiche3d.pages.dev/) | [Claude Opus 5.5 Demo](https://github.com/riba2534/claude-opus-5-5-demo) |
| 星环滚滚 Star Ring Roll | [AI Game Studio / PocketKit](https://www.pokitx.com/zh/html-games/) | [开始游戏](https://www.pokitx.com/zh/html-games/star-ring) | [游戏说明](https://www.pokitx.com/zh/html-games/star-ring) |
| 棱镜交火（三分钟竞技场射击，在掩体间换位并切换枪械） | [iiduce](https://www.v2ex.com/member/iiduce) | [开始游戏](https://tz100.com/zh/games/prism-arena) | [作者发布帖](https://www.v2ex.com/t/1243393) |
| Spy Hunter（Claude 版，同提示词对照试玩，英文） | [Daniel Lemire](https://github.com/lemire) | [开始游戏](https://lemire.me/spyhunter/claude/) | [Grok 对照](https://lemire.me/spyhunter/grok/) |
| Spy Hunter（Grok 版，同提示词对照试玩，英文） | [Daniel Lemire](https://github.com/lemire) | [开始游戏](https://lemire.me/spyhunter/grok/) | [Claude 对照](https://lemire.me/spyhunter/claude/) |
| PokéBonk（宝可梦 + 3D 割草生存同人，AI 做美术与音乐，上线不久玩家破百万，含简体中文） | Charcher | [开始游戏](https://pokebonk.top) | [作者发布帖](https://www.v2ex.com/t/1251268) |
| 刹车小游戏（智谱 GLM-5.3 一把成型，手机游玩更佳） | ha0719 | [开始游戏](https://t.baozangapp.com/brake-test/) | [作者发布帖](https://www.v2ex.com/t/1247818) |
| PumpkinLab · 南瓜实验室（11 岁孩子口述 + Claude Code 做的万圣节打南瓜，英 / 荷双语） | [roytomeij](https://github.com/roytomeij) | [开始游戏](https://pumpkinlab.tomeij.net/) | [原仓库](https://github.com/roytomeij/pumpkinlab) |

### 角色扮演与文字冒险

| 游戏 | 作者／发布者 | 试玩／获取 | 出处 |
| --- | --- | --- | --- |
| 天命人·黑风山（《黑神话：悟空》同人） | [oneoyn](https://www.v2ex.com/member/oneoyn) | [开始游戏](https://wukong.cnmwx.com/) | [作者发布帖](https://www.v2ex.com/t/1244710) |
| 起源 Origin | [DFarm6](https://github.com/DFarm6) | [开始游戏](https://dfarm6.github.io/origin-16bit-arpg/) | [原仓库](https://github.com/DFarm6/origin-16bit-arpg) |
| 天际5（需本地运行） | [zexadev](https://github.com/zexadev) | [下载及运行说明](https://github.com/zexadev/tianjie5#快速开始) | [原仓库](https://github.com/zexadev/tianjie5) |
| 归零协议（只带三件现代物品，从崇祯元年或道光年间走出不同结局） | [ddter](https://www.v2ex.com/member/ddter) | [开始游戏](https://zero.flyabc.fun/) | [作者发布帖](https://www.v2ex.com/t/1224184) |
| Emberwick（Claude Opus 5.5 做的奇幻村庄 RPG，约 15 分钟剧情，含关卡编辑器，英文界面） | Simon Willison | [开始游戏](https://simonw.github.io/emberwick/v11/emberwick.html) | [作者文章](https://simonw.substack.com/p/the-october-inflection-point-for) |

### 益智与休闲

| 游戏 | 作者／发布者 | 试玩／获取 | 出处 |
| --- | --- | --- | --- |
| Color Tiles | [winterscott999](https://www.v2ex.com/member/winterscott999) | [开始游戏](https://colortilesgame.net/) | [作者发布帖](https://www.v2ex.com/t/1228585) |
| Clauding · 动词猎人（抓 Claude Code 转圈动词，零依赖，MIT；界面英文，帮助含中文） | [BIGBALLON](https://github.com/BIGBALLON) | [开始游戏](https://bigballon.github.io/clauding_hacker/) | [原仓库](https://github.com/BIGBALLON/clauding_hacker) |
| Tree Appreciator · 赏树（Claude Opus 5.5 一次成型，3D 找茬：两棵同源树找三处不同，英文界面） | Simon Willison | [开始游戏](https://tools.simonwillison.net/tree-appreciator) | [作者文章](https://simonw.substack.com/p/the-october-inflection-point-for) |

### 联机与游戏合集

| 游戏 | 作者／发布者 | 试玩／获取 | 出处 |
| --- | --- | --- | --- |
| Parti 联机小游戏合集 | [wheelg](https://www.v2ex.com/member/wheelg) | [打开游戏平台](https://parti.linkai.work/) | [作者发布帖](https://edge.v2ex.com/t/1227945) |
| 100 Games（AI 一天做出的 100 个单文件小游戏，英文界面） | [Srikanth-AD](https://github.com/Srikanth-AD) | [开始游戏](https://100games.net/) | [原仓库](https://github.com/Srikanth-AD/100games) |
| LittleJS Arcade（五十多款 MIT 单文件街机，英文界面） | [KilledByAPixel](https://github.com/KilledByAPixel) | [开始游戏](https://killedbyapixel.github.io/LittleJSArcade/) | [原仓库](https://github.com/KilledByAPixel/LittleJSArcade) |
| 街机口袋 · Party Pocket Arcade（六款中文双人游戏，需本机 Node 启动） | [火山哥](https://github.com/huoshantao7-hub) | [下载及运行说明](https://github.com/huoshantao7-hub/party-pocket-arcade#一分钟开始) | [作者发布帖](https://x.com/huoshan007/status/2103035709485437105) |
| Clawd Arcade · 螃蟹街机（中英双语像素街机合集） | [kirenath](https://github.com/kirenath) | [开始游戏](https://kirenath.github.io/clawd-arcade/) | [原仓库](https://github.com/kirenath/clawd-arcade) |
| hollowlullaby 小游戏合集（中文 vibe-coding 的 WASM 作品集） | [maweis](https://github.com/maweis1981) | [开始游戏](https://maweis.com/rust_bevy_lua_game/) | [原仓库](https://github.com/maweis1981/rust_bevy_lua_game) |
| Eyrie（Claude Code 做的联机合作 Roguelike，抓精灵守神社抗波次，英文界面） | — | [开始游戏](https://playeyrie.com) | [收录来源](https://vibecodedapps.dev/games/) |
| Fly（100% AI 制作的多人在线飞行模拟，可空战，英文界面） | — | [开始游戏](https://fly.pieter.com) | [收录来源](https://vibecodedapps.dev/games/) |

### 游玩前说明

- **需要本地运行**：《天际5》按原仓库说明启动，尚无已核实的在线试玩地址；《街机口袋》需 Node.js 20 或更新版本，运行 `node server.mjs`。《LLM 塔防》Web 版加载较慢，作者建议以下载客户端为主。
- **加载与访问**：《修仙掌门生涯》首次加载可能较慢；两则 Spy Hunter 试玩偶发人机验证。《AI 替我打的策略 SLG》需 Google 或 GitHub 登录。
- **语言与时长**：《100 Games》《LittleJS Arcade》《EPOCH》和 Spy Hunter 为英文界面；《Clauding》界面英文、帮助含中文，《Clawd Arcade》为中英双语，《hollowlullaby》为中文作品集。《归零协议》单局约二三十分钟。新增的 Battle Drones、Emberwick、Tree Appreciator、Quarter Sun Cove、Eyrie、Fly 均为英文界面；《PumpkinLab》为英 / 荷双语；《PokéBonk》含简体中文。
- **版本与同人**：《晴湾防线无尽版》《棱镜交火》《象棋》与《晴湾防线》同属 iiduce 的游戏站，无尽版难度更高。《穿越火线》《QQ 飞车》《黑神话：悟空》《天际5》《Spy Hunter》《PokéBonk》相关条目为非官方同人或致敬作品，与原游戏厂商无关。

以上外部链接中，新增 12 条于 2026-11-11 检查可访问；其余旧条目上次检查为 2026-09-28，本次未逐条复核。游戏内容及后续可用性以原作者网站为准。

## 署名与使用

仓库内游戏未收到统一的再使用许可，因此本仓库不附加统一的开源许可证。《SWARM》单独附有原作者的 [MIT 许可](games/swarm/LICENSE)，署名仍为 Nerabwyn。游戏与商标的权利归各自权利人；收录不代表可任意复制或商用。署名或链接需要更正时，请提交 Issue。

## 提交新游戏

欢迎把用 AI 制作的游戏发给我。扫码添加微信时请备注「AI 游戏投稿」，并附上游戏名称、可玩或下载地址、作者署名，以及是否允许本仓库托管游戏文件。我核对后会更新收录。

<img src="assets/wechat-qr.jpg" alt="杨老师个人微信二维码" width="300">

微信号：`dreamger`。也可以直接[提交 Issue](https://github.com/shyboy/ai-made-games/issues)。
