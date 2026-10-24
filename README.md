# 一路推到底

台灣人行道輪椅挑戰：手機 3D 小遊戲。只有「左手推」「右手推」兩顆按鈕，閃過違停機車、攤販、路人和腳踏車，摔下人行道就得在馬路上找坡道才能回來。

試玩：https://aa547689.github.io/wheelchair-push/

關卡：
1. 巷口早餐店：一般人行道，終點是路底的早餐店
2. 三和夜市：兩旁都是攤位，人潮、會變長變短的排隊人龍、偶爾穿過的機車，終點是夜市牛排
3. 捷運站：快車道旁的窄人行道 → S 型上坡坡道 → 等無障礙電梯 → 地下大廳一般閘門過不去，沿長走道到無障礙閘門 → 導引台

- `index.html`：整個遊戲（Three.js r128，單一檔案）
- `bgm.mp3`：背景音樂
- `models/manifest.json`：選用的 GLB 模型清單；放入 `.glb` 並登記後，會自動取代內建模型（可用的 key：ped、phone、elder、bike、scooter、stall、mailbox、tree、plant、ebox、cone、aboard）
