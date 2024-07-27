---
description: Quái trong game có level thấp nhất là 1, cao nhất là 100
---

# Cơ chế xếp hạng quái

Level càng cao thì đồ rớt ra càng nhiều

Thông thường, khi spawn quái sẽ được đặt trên 3 tiêu chí:

* Khoảng cách từ vị trí spawn đến người chơi
* Độ sâu mà quái được sinh ra
* Thời gian chơi của người chơi trong khu vực

### Chi tiết cơ chế đánh level:

1. **Khoảng cách từ spawn**

* Trong vòng khoảng cách từ 250 khối quanh spawn quái sẽ khá yếu, đây sẽ là 1 vùng an toàn để farm quái cho người mới chơi
* Kể từ 250 khối từ spawn thì cứ mối 97 khối, quái sẽ tăng lên 1 level, tối đa level 100 ở 10k block

2. Độ sâu quái được sinh ra

* Càng cao quái sẽ càng yếu còn càng sâu thì quái sẽ càng mạnh
* Ranh giới giữa vùng level tăng và level giảm là Y = 100
* Ở độ sâu -64, quái sẽ là level cao nhất: 100

3. **Thời gian người chơi đó đã ở trong server**

* Về cơ bản, người chơi càng chơi lâu trong server thì quái quanh người đó càng mạnh, việc này để tránh người chơi AFK cả 24 tiếng ở farm gây ảnh hưởng đến chất lượng server
* Nghĩa là việc người chơi có 18 tiếng chơi trong server ở spawn và tạo ra loại quái level cao là điều hết sức lường trước được
