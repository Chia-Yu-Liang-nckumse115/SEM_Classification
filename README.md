10 類 SEM 微結構自動分類模型」

只要給它一張新 SEM 圖：

它會輸出這張圖分別屬於 Biological / Fibres / Films_Coated_Surface / MEMS_devices_and_electrodes / Nanowires / Particles / Patterned_surface / Porous_Sponge / Powder / Tips 的機率分布

你可以取 np.argmax 當「預測類別」

在實務上的用途可以是：

快速整理大量 SEM 圖

幾千張 SEM 自動分成 10 類，不用助教或學生一張一張搬

材料表徵自動化

例如看到 Powder / Porous_Sponge / Nanowires 的比例

在不同製程條件下比較某類微結構的出現頻率

品質管制（QA）初步篩選

例如 MEMS devices 的電極 SEM 有沒有出現特定 Patterned_surface 或 Powder 類缺陷
