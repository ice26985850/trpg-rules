# 絕地戰場 / Last Stand TRPG — 中英術語對照表 (Bilingual Glossary)

> **用途**：本表鎖定「絕地戰場」（Last Stand TRPG）規則集中所有關鍵術語的官方中→英譯法，供全書翻譯統一使用。
> **說明**：左欄中文為 *參考用原文*（刻意保留，非漏譯）。英譯在本規則集內為 **唯一標準譯法**，後續所有書冊、劇本、圖鑑、角色卡翻譯必須與本表一致。
> **參考作品**：PUBG（絕地求生 / PlayerUnknown's Battlegrounds）大逃殺改編 TRPG。

---

## 0. 規則集英文名（Canonical Display Name）

| 中文 | 英文（鎖定顯示名） | 備註 |
|------|------|------|
| 絕地戰場 | **Last Stand TRPG** | 絕地 = last stand / desperate final stand；戰場 = battlefield。最忠實且自然的譯法，同時與商標「Battlegrounds」區隔。 |

> **命名抉擇說明**：已考量 `Battlegrounds TRPG`（呼應 PUBG 血統、但丟失「絕地」語義）與 `Final Battlefield TRPG`（字面直譯但略生硬）。最終採 **Last Stand TRPG**：完整保留「絕地（last stand）」之絕境意涵，且作為產品名乾淨易讀。全規則集一律使用此名。

---

## 1. 核心系統與骰子（Core System & Dice）

| 中文 | 英文（English Full Name (ABBR)） | 說明 |
|------|------|------|
| 核心判定公式 | Core Check Formula | `d20 + AM + PB ≥ DC` |
| d20 系統 | d20 System | 主要判定骰種 |
| 屬性加值 | Attribute Modifier (AM) | `AM = ⌊(屬性值 − 10) ÷ 2⌋` |
| 熟練加值 | Proficiency Bonus (PB) | 隨等級成長，Lv1–4 = +2 |
| 難度等級 | Difficulty Class (DC) | GM 設定之目標值 |
| 自然骰 1 | Natural 1 | 大失敗（自動失敗） |
| 自然骰 20 | Natural 20 | 必定命中；觸發「精準命中」 |
| 大成功 | Critical Success | 最終結果 ≥ DC+5 |
| 精準命中 | Precision Hit | 自然 20 時傷害骰取最大值 |
| 優勢 | Advantage | 擲兩顆 d20 取高 |
| 劣勢 | Disadvantage | 擲兩顆 d20 取低 |
| 對抗檢定 | Contest Check | 雙方各擲，高者勝 |
| 團隊合作檢定 | Cooperative Check | 主導者 + 協助者（成功給予優勢） |
| 經驗值 | Experience Points (XP) | 升級資源 |
| 信用點數 | Credits (CR) | 購買貨幣 |

---

## 2. 五大屬性（Core Attributes）

| 中文 | 英文（English Full Name (ABBR)） | 含義 |
|------|------|------|
| 槍法 | Aim (AIM) | 遠程武器精準度、彈道控制 |
| 體能 | Physique (PHY) | 身體強度、負重、耐力 |
| 戰術 | Tactics (TAC) | 戰場意識、聽音辨位、圈型預判 |
| 駕駛 | Driving (DRV) | 載具操控與維修 |
| 冷靜 | Calm (CLM) | 壓力下判斷、最終圈心理素質 |

> 屬性加值記法：`AIMmod`、`PHYmod`、`TACmod`、`DRVmod`、`CLMmod`。

---

## 3. 衍生屬性（Derived Stats）

| 中文 | 英文（English Full Name (ABBR)） | 計算公式 |
|------|------|------|
| 生命值 | Hit Points (HP) | Lv1: 10+PHYmod；每級 +1d8(min 5)+PHYmod |
| 負重上限 | Carry Capacity | PHY × 3 + 5 kg |
| 先攻值 | Initiative (INIT) | d20 + TACmod + ⌊½ AIMmod⌋ |
| 聽音範圍 | Hearing Range | TAC × 10 m |
| 壓力閾值 | Stress Threshold | CLM × 2 + 5 |
| 倒地計時 | Downed Timer | 3 回合 |
| 移動速度 | Movement Speed | 正常 30 m/回合；奔跑 60 m/回合 |
| 護甲穿透 | Armor Penetration (AP) | `⌊等級 ÷ 2⌋`，降低敵方有效 DR |
| 部位倍率 | Hit-Location Multiplier | 軀幹 ×1.0 / 四肢 ×0.5 / 頭部 ×2.0 / 要害 ×2.5 |
| 防具減傷 | Damage Reduction (DR) | 依頭盔/護甲等級 |

---

## 4. 技能（Skills，依屬性分組）

**Aim (AIM)**：手槍射擊 Pistol / 衝鋒槍射擊 SMG / 步槍射擊 Rifle / 狙擊射擊 Sniper / 霰彈槍射擊 Shotgun / 輕機槍射擊 LMG / 弩箭射擊 Crossbow / 雙持射擊 Dual-Wield
**Physique (PHY)**：近戰搏鬥 Melee / 奔跑 Sprint / 攀爬 Climb / 游泳 Swim / 負重 Carry
**Tactics (TAC)**：察覺 Perception / 隱匿 Stealth / 追蹤 Track / 圈型預判 Zone Prediction / 戰術指揮 Tactical Command / 先發制人 First Strike / 聽音辨位 Acoustic Location
**Driving (DRV)**：陸地駕駛 Land Driving / 水域駕駛 Water Driving / 飛行駕駛 Flight Driving / 載具維修 Vehicle Repair / 越野駕駛 Off-Road Driving
**Calm (CLM)**：壓力抵抗 Stress Resistance / 被伏擊反應 Ambush Reaction / 最終圈冷靜 Final-Circle Composure / 醫療急救 First Aid / 說服·威嚇 Persuade / Intimidate

---

## 5. 角色背景（Backgrounds / Roles）

| 中文 | 英文 | 背景專長（Background Feat） |
|------|------|------|
| 退伍軍人 | Veteran | 軍事訓練 Military Training |
| 運動員 | Athlete | 爆發體能 Burst Physique |
| 賽車手 | Racer | 人車合一 One with the Machine |
| 獵人 | Hunter | 荒野追跡 Wilderness Tracking |
| 軍醫 | Medic | 戰地急救 Battlefield First Aid |
| 技師 | Technician | 爆破與維修 Demolition & Repair |

---

## 6. 敵方難度級別（Enemy Tiers）

| 中文 | 英文 | 星級 | 說明 |
|------|------|:---:|------|
| 菜鳥 | Rookie | ★ | 新手，不可預測 |
| 穩健 | Steady | ★★ | 受過訓練的熟手 |
| 突擊 | Assault | ★★★ | 主動追殺的獵手 |
| 伏擊 | Ambush | ★★★ | 守株待兔的狙擊者 |
| 職業 | Professional | ★★★★ | 分工明確的軍隊級小隊 |
| 冠軍 | Champion | ★★★★★ | 傳奇，以預判碾壓 |

> 敵方參賽者總稱：**怪物圖鑑**中的「敵方參賽者」= Enemy Contestant。

---

## 7. 宿敵類型（Nemesis Types，單人模式）

| 中文 | 英文 |
|------|------|
| 鏡像宿敵 | Mirror Nemesis |
| 仇敵 | Sworn Enemy |
| 師徒宿敵 | Mentor–Student Nemesis |
| 傳奇狩獵者 | Legendary Hunter |

---

## 8. 模式與參賽者稱謂（Modes & Contestant Terms）

| 中文 | 英文 |
|------|------|
| 單人模式 | Solo Mode |
| 小隊模式 | Squad Mode |
| 參賽者 | Contestant |
| 孤狼 | Lone Wolf |
| 倖存者 | Survivor |
| 吃雞（獲得最終勝利） | Win / "Chicken Dinner" (final victory) |

---

## 9. 地圖名稱（Maps / Battlefield Maps）

| 檔名 | 中文 | 英文（鎖定） | 備註 |
|------|------|------|------|
| M1_Erangel新手島.svg | Erangel 新手島 | **Erangel (Newbie Island)** | 廢棄蘇聯軍事島嶼（PUBG 原名保留） |
| M2_Sanhok叢林城.svg | Sanhok 叢林城 | **Sanhok (Jungle City)** | 熱帶叢林廢棄度假城（PUBG 原名保留） |
| M3_Miramar沙漠.svg | Miramar 沙漠 | **Miramar (Desert)** | 沙漠廢棄軍事基地（PUBG 原名保留） |
| M4_Vikendi雪地.svg | Vikendi 雪地 | **Vikendi (Snowfield)** | 雪原（PUBG 原名保留） |
| M5_眾神黃昏.svg | 眾神黃昏 | **Ragnarök** | 諸神黃昏 / Twilight of the Gods |
| M6_夜霧島.svg | 夜霧島 | **Night Mist Island** | 單人 S6 地圖 |
| M7_鹽漠.svg | 鹽漠 | **Salt Flats** | 單人 S7 地圖 |
| M8_鐵鏽帶工業園區.svg | 鐵鏽帶工業園區 | **Rust Belt Industrial Park** | 單人 S8 地圖 |
| M9_湮沒之都.svg | 湮沒之都 | **Drowned City** | 單人 S9 地圖 |
| M10_天梯競技場.svg | 天梯競技場 | **Ascension Arena** | 單人 S10 地圖 |

> PUBG 系地圖（Erangel / Sanhok / Miramar / Vikendi）為原作專有名詞，保留不譯，僅翻譯中文描述後綴。

---

## 10. 劇本標題（Scenarios）

| 檔名 | 中文 | 英文（鎖定） | 建議等級 | 地圖 |
|------|------|------|:---:|------|
| s01_新手試煉.md | 新手試煉 | **Novice Trial** | 1–2 | Erangel (Newbie Island) |
| s02_叢林城巷戰.md | 叢林城巷戰 | **Jungle City Street War** | 3–4 | Sanhok (Jungle City) |
| s03_沙漠軍事基地.md | 沙漠軍事基地 | **Desert Military Base** | 5–6 | Miramar (Desert) |
| s04_雪地生存競賽.md | 雪地生存競賽 | **Snowfield Survival Contest** | 7–8 | Vikendi (Snowfield) |
| s05_終極戰場.md | 終極戰場 | **The Ultimate Battlefield** | 9–10 | 混合 Mixed |
| s06_倖存者.md | 倖存者 | **The Survivor** | 1–2 | Night Mist Island |
| s07_獵人與獵物.md | 獵人與獵物 | **Hunter and Prey** | 3–4 | Salt Flats |
| s08_孤狼試煉.md | 孤狼試煉 | **Lone Wolf Trial** | 5–6 | Rust Belt Industrial Park |
| s09_最後一場.md | 最後一場 | **The Last Match** | 7–8 | Drowned City |
| s10_傳奇終局.md | 傳奇終局 | **Legendary Endgame** | 9–10 | Ascension Arena |

---

## 11. 圖鑑（Catalogs / Compendiums）

| 中文 | 英文（鎖定） | 說明 |
|------|------|------|
| 怪物圖鑑 | **Monster Compendium** (Enemy Contestant Codex) | 敵方參賽者圖鑑（含 AI 行為） |
| 物品圖鑑 | **Item Compendium** (Equipment Codex) | 武器 / 防具 / 配件 / 消耗品 / 載具 |

---

## 12. 簽名機制與能力（Signature Mechanics & Abilities）

| 中文 | 英文（English Full Name (ABBR)） | 說明 |
|------|------|------|
| 核心循環 | Core Loop | 降落選點 → 搜刮物資 → 遭遇交戰 → 縮圈遷移 → 最終決戰 |
| 壓力系統 | Stress System | 四階段（冷靜 / 緊張 / 恐慌 / 崩潰） |
| 縮圈系統 | Zone System | 安全區逐圈收縮 |
| 安全區（圈型） | Safe Zone (the Circle) | 圈外持續電場傷害 |
| 圈外傷害（電場傷害） | Out-of-Zone Damage (Electric Field Damage) | 無視防具減傷 |
| 單人宿敵 | Solo Nemesis | 單人模式專屬有名字的對手 |
| 動態淘汰系統 | Dynamic Elimination System | NPC 之間的自行交戰 |
| 第三方介入 | Third-Party Intervention | 槍戰引來其他小隊/孤狼 |
| 空投 | Airdrop | 金色物資箱（獨特裝備） |
| 紅區轟炸 | Red Zone Bombing | 隨機區域砲擊 |
| 無線電塔 | Radio Tower | 區域掃描 / 空投標記 / 宿敵位置 |
| 自救注射器 | Self-Revive Syringe | HP 歸零自動觸發，恢復 1 HP |
| 連發射擊 | Burst Fire | 每多一發 DC +1 |
| 火力壓制 | Suppressing Fire | LMG 指定區域壓制 |
| 三發定律 | Three-Round Rule | 遭遇戰 3–8 回合內結束的設計原則 |
| 孤狼直覺 | Lone Wolf Instinct | 危險感知 / 逃生路線 / 資源嗅覺 |
| 聽覺補償 | Auditory Compensation | 單人模式聽力加成 |

---

## 13. 壓力階段（Stress Stages）

| 中文 | 英文 | 壓力值範圍 | 效果 |
|------|------|------|------|
| 冷靜 | Calm | < 閾值 50% | 無負面效果 |
| 緊張 | Tense | 閾值 50–74% | 槍法檢定劣勢 |
| 恐慌 | Panic | 閾值 75–99% | 槍法 + 戰術檢定劣勢 |
| 崩潰 | Breakdown | ≥ 閾值 100% | 每回合 d6 隨機行動 |

---

## 14. 圈型走向（Zone Shapes）

| 中文 | 英文 |
|------|------|
| 中央收束 | Central Contraction |
| 邊緣漂移 | Edge Drift |
| 跳躍翻轉 | Jump Reversal |
| 水域終結 | Watery End |
| 建築鎖定 | Building Lock |

---

## 15. 狀態效果（Status Effects）

| 中文 | 英文 |
|------|------|
| 倒地 | Downed |
| 減速 | Slowed |
| 燃燒 | Burning |
| 煙霧遮蔽 | Smoke Obscured |
| 疼痛 | Pain |
| 疲勞 | Fatigued |
| 耳鳴 | Ringing Ears |
| 致盲 | Blinded |
| 火力壓制 | Suppressed |
| 虛弱（自救後） | Weakened (post self-revive) |

---

## 16. 天氣（Weather）

| 中文 | 英文 |
|------|------|
| 晴天 | Clear |
| 陰天 | Overcast |
| 濃霧 | Dense Fog |
| 暴雨 | Heavy Rain |
| 沙塵暴 | Sandstorm |
| 暴風雪 | Blizzard |
| 雷暴 | Thunderstorm |

---

## 17. 物資等級（Loot Tiers）

| 中文 | 英文 | 標記色 |
|------|------|------|
| 貧瘠 | Scarce | 灰 Gray |
| 普通 | Common | 綠 Green |
| 豐富 | Abundant | 藍 Blue |
| 軍用 | Military | 紫 Purple |
| 空投 | Airdrop | 金 Gold |

---

## 18. 專長（Feats，編號鎖定）

**槍械專長 (Gunnery Feats, G)**：G1 步槍專精 Rifle Specialization / G2 狙擊精英 Sniper Elite / G3 近戰射手 Close-Quarters Shooter / G4 手槍快手 Quick-Draw Pistol / G5 雙持射手 Dual-Wielder
**生存專長 (Survival Feats, S)**：S1 快速搜刮 Quick Loot / S2 強效醫療 Potent Medicine / S3 隱匿移動 Silent Move / S4 攀爬專家 Climb Expert / S5 鋼鐵意志 Iron Will
**戰術專長 (Tactical Feats, T)**：T1 小隊指揮 Squad Command / T2 先發制人 First Strike / T3 冷靜頭腦 Cool Head / T4 聽音辨位 Acoustic Location / T5 戰術翻滾 Tactical Roll
**駕駛專長 (Driving Feats, D)**：D1 越野駕駛 Off-Road Driving / D2 載具維修 Vehicle Repair / D3 載具戰鬥 Vehicle Combat / D4 飛行執照 Flight License / D5 移動軍火庫 Mobile Arsenal
**巔峰專長 (Pinnacle Feats, P, Lv10)**：P1 戰場死神 Reaper of the Battlefield / P2 不死之身 Immortal / P3 傳奇車手 Legendary Driver

---

## 19. 動作經濟（Action Economy）

| 中文 | 英文 |
|------|------|
| 戰術射擊 | Tactical Shot |
| 精準射擊 | Aimed Shot |
| 壓制射擊 | Suppressing Shot |
| 戰術動作 | Tactical Action |
| 自由動作 | Free Action |
| 附贈動作 | Bonus Action |
| 反應動作 | Reaction |
| 換彈匣 | Reload |
| 救援隊友 | Revive Ally |
| 投擲道具 | Throw Item |

---

## 20. 裝備類別速查（Equipment Categories）

| 中文 | 英文 |
|------|------|
| 武器（手槍 / 衝鋒槍 / 突擊步槍 / 狙擊槍 / 霰彈槍 / 輕機槍 / 十字弩 / 近戰） | Weapon (Pistol / SMG / AR / SR / Shotgun / LMG / Crossbow / Melee) |
| 防具（頭盔 / 軀幹） | Armor (Helmet / Torso) |
| 配件（瞄具 / 槍口 / 彈匣 / 握把 / 槍托） | Attachment (Scope / Muzzle / Magazine / Grip / Stock) |
| 消耗品 | Consumable |
| 載具 | Vehicle |

> 具名槍械（P92、AKM、AWM、M416、Kar98k 等）均為現實槍械專有名詞，**保留原英文名不譯**。

---

*本術語表為「絕地戰場 / Last Stand TRPG」翻譯之唯一權威來源。新增術語請回寫本表以保持一致。*
