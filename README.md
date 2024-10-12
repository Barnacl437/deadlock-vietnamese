> [!NOTE]
> Cũng có hướng dẫn trên forum Deadlock tại [đây](https://forums.playdeadlock.com/resources/vietnamese-localisation-b%E1%BA%A3n-%C4%91%E1%BB%8Ba-h%C3%B3a-ti%E1%BA%BFng-vi%E1%BB%87t.23).
>
> also [english readme](https://github.com/Barnacl437/deadlock-vietnamese/blob/main/README-en.md) (may not be consistent with vietnamese one)

# deadlock-vietnamese

Repo này chứa bản dịch tiếng Việt đang phát triển cho [Deadlock](https://store.steampowered.com/app/1422450), một dự án game đang trong quá trình phát triển của [Valve](https://valvesoftware.com/). Dành cho mọi người muốn chơi game bằng tiếng Việt. 


## có gì trong này?

hiện tại có khoảng 5 thư mục chứa 5 file language cấu thành nên các chữ hiện trên hầu hết giao diện của game, vốn là các file rỗng chỉ có vài dòng đầu chỉ báo là ngôn ngữ tiếng Việt, và được giữ chỗ bởi các dòng tiếng Anh. chỉ cần dịch các dòng tiếng Anh bên phải trình editor, bên trái là các biến cú pháp để game nhận dạng nên không nên đụng vào. các file nằm ở `\steamapps\common\Deadlock\game\citadel\resource\localization` với 5 thư mục tương ứng là (citadel_) main, mods, heroes, attributes, và gc.

## hiện giờ...

tập trung tiến độ vào main, cụ thể là file `/citadel_main/citadel_main_vietnamese.txt`, đang tính dịch sang dịch mấy file gc, attributes bla bla. Do game liên tục update trong thời buổi beta playtest nên các bản dịch chưa xong có thể sẽ bị lỗi thời, hiện tại mình đang nghĩ cách để có thể bổ sung hoặc sửa đổi cho phù hợp. Các folder (citadel_) mods, heroes, v.v. chưa có tiến độ dịch và sẽ được để dành, hiện tạm đồng bộ với file lang tiếng Anh.

## to-do
- [X] Dịch sang các file khác ngoài `main`
-  -  [ ] `attributes` (underway)
- [ ] Hoàn thành `main`
- [ ] Hoàn thành `gc`, `mods`
- [ ] Hoàn thành `attributes`, `heroes`
- [ ] Checkpoint #1

## vấn đáp và hướng dẫn

### mình có thể làm gì?

bạn có thể đóng góp (bao gồm việc sửa đoạn đã dịch và dịch các đoạn gốc) nếu muốn, miễn là tốt nhất bạn đã từng chơi game và thông thạo từ vựng của các thể loại game kiểu này. Hiện tại chỉ có mình với ông bạn mình làm trên repo này. Một hoặc một số cá nhân cùng chí hướng có copy repo mình sang để phát triển thêm, có lẽ với tiến độ nhanh hơn, nên việc dùng bản dịch của ai rốt cuộc là lựa chọn của bạn.


### ủa thế cóp cóp file như này có sợ anti-cheat "chộp" không thớt?

Mình chắc chắn là không. Như một thằng đã đi theming TF2 chắc cũng chục lần, copy bừa bãi vào file game, đôi khi là những cái "em yêu khoa học", tuy nhiên đối với mình mà nói, VAC không bắt cái đó (một phần thì engine Source có khả năng mod gần như vô hạn), VAC chủ yếu soi memory với check var những gì quan trọng (như asset game và chỉ số quan trọng trong thi đấu), còn lang file cơ bản là thay đổi chữ trên giao diện mà thôi, nói chung là trừ khi bạn dùng tool gian lận can thiệp quá sâu chứ còn đây là file ngôn ngữ thôi, yên chí 🐧

### trông hay đó, mình thử được không?

được chứ. Tải file zip ở trang [releases](https://github.com/Barnacl437/deadlock-vietnamese/releases), giải nén thư mục `localization` và copy/move vào địa chỉ `[...]\steamapps\common\Deadlock\game\citadel\resource`, trong đó `[...]` là địa chỉ Steam Library của bạn.
![đây nì](https://github.com/user-attachments/assets/e2555dec-0f38-4d87-8cc8-023dcccefeb4)

Nếu có thông báo `5 files with the same names`, bấm `Replace the files` để ghi đè lên các file cũ, như một cách để cập nhật.
![{45D606BF-8132-41A3-8E01-45A464BD10EB}](https://github.com/user-attachments/assets/7ed3660c-ea21-4d7f-a74b-632d993fe53b)


***Cách thứ hai***: Bạn cũng có thể bấm biểu tượng bánh răng trong thư viện client Steam, hoặc chuột phải vào tên game ở panel bên trái, chọn Manage > Browse local files (hoặc trỏ chuột tương ứng nếu bạn dùng Steam bằng tiếng Việt), để vào folder game cho nhanh.

![vẫn đây](https://github.com/user-attachments/assets/6d2e802d-6d76-4b0b-ab0b-820efa980da9)

Và lại theo địa chỉ như trên vào mục `resource`.

Và một bước quan trọng để bắt game hiển thị bằng tiếng ta. Tiếp tục bấm biểu tượng bánh răng trong thư viện client Steam, hoặc chuột phải vào tên game ở panel bên trái, chọn Properties, và dán dòng này vào Launch options: `-language vietnamese` (dán nối tiếp các options trước đó nếu có) và đóng cửa sổ. 

## chụp màn hình
<details>
  <summary>hiện ảnh chụp</summary>
<hr>
  
  **Main menu** (từ khoảng 20/8)
  ![20240820190753_1](https://github.com/user-attachments/assets/5b2e6f85-a45a-447e-b7d9-5062ed392b39)

  **Settings/Graphics** (và các ảnh sau, sau 25/8)
  ![20240830221932_1](https://github.com/user-attachments/assets/41efdc98-e42f-48d3-8285-f12b54c1a277)

  **The Curiosity Store/Build** (item chưa được dịch)
  ![20240829143042_1](https://github.com/user-attachments/assets/c6a659b1-1c5a-4901-a7a8-4c2858ec9369)

  **Mấy cảnh in-game** 
  ![20240829142534_1](https://github.com/user-attachments/assets/9f30cb9b-46ab-4c37-92d9-02385ecb16f3)
  ![20240829142517_1](https://github.com/user-attachments/assets/cddd8c9d-2557-4f68-9361-2d8ab45d0b89)
  
</hr>
</details>

## Licence và thông tin thêm

Bản dịch này được phát hành miễn phí dưới licence *[mi làm cái quái gì cũng được (WTFPL)](http://wtfpl.net)*, nên bạn hoàn toàn có thể chôm chỉa không xin hỏi. Tuy nhiên mình vẫn đánh giá cao nếu bạn credit mình trong một phần dự án của bạn.

Dưới đây là liệt kê các fork repo mình, hoặc dự án khác mình khuyến khích. 
| fork/pj                                                                                  | author                 | licence                      | fork?      | note|
|----------|-----|----------|-----|------|
|  [DeadLock-Vietnamese](https://github.com/TruongDucDuong1109/DeadLock-Vietnamese)          |  truongducduong1109    |  no licence/public domain   |yes        | |  indirect fork |
| [hoanglong's deadlock-vietnamese fork](https://github.com/hoanglong84/deadlock-vietnamese)| hoanglong84           | wtfpl                      |      yes     | |           |

