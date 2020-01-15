先前失敗原因:
•	Carracing 這個遊戲的action為連續動作,方向為(-1~1) 油門為(0~1) 煞車為(0~1),連續動作使用sarsa模型訓練需要先將動作離散化,但這會消耗大量的效能以及影響準確度

改進方法:
      使用DQL 模型進行訓練
      
程式執行步驟:
1.	導入BOX.2D套件
2.	導入相關函式庫
3.	導入Video 相關套件
4.	宣告ExperienceHistory
5.	宣告Agent
6.	宣告test_experienceHistory
7.	執行Main主程式

