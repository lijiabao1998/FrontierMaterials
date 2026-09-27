# 材料科學驗證契約

每個子任務先凍結 composition/structure、溫壓、phase reference、property definition、data license、DFT/ML method、cutoff 與 uncertainty。
- formation energy、hull distance、phonon stability、mechanical stability、synthesizability 分開。
- ML label 與實驗 measurement 分開；不得用訓練資料中的同構／近重複結構作 held-out success。
- 生成候選至少做組成/價態/幾何 sanity check；新奇度與穩定性分開。
- 實驗未做即標 computation-only；實驗成功也只在該材料與條件成立。
- 付費 DFT/GPU 或濕實驗需另授權。
