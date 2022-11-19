---
layout: post
title: Làm gì để trở thành “Siêu Lập Trình Viên”?
subtitle: Siêu Lập Trình Viên liệu có khó?
cover-img: /assets/img/supper-code.jpg
thumbnail-img: /assets/img/supper-code.jpg
share-img: /assets/img/supper-code.jpg
tags: [technologies]
---

Gần đây tôi có đọc được 1 câu hỏi khá "trẻ trâu" nhưng lại rất thú vị:"Làm thế nào để trở thành 1 "siêu Lập trình viên"?". Nhiều người mới bắt đầu học về công nghệ thông tin thường hay hỏi và băn khoăn, nhằm là mơ ước biến thành 1 ông nào đó pro tầm cỡ bill gates hay đại loại thế. Nhưng này, theo quan điểm của cá nhân tôi thì Bill Gates nên được gọi là một nhà doanh nhân thành đạt hơn là một lập trình viên tầm cỡ. Những lập trình viên có thể nói là tầm cỡ thì nên nhắc đến những cái tên như Linus Torvalds hay Dennis Ritchie sẽ phù hợp hơn.

Quay trở lại với câu hỏi "Làm thế nào để trở thành 1 "siêu lập trình viên?"". Lúc đầu tôi vẫn cho rằng câu hỏi này thực sự rất viển vông bởi vì cái ham muốn điên rồ của cái người hỏi câu này (đã được tôi nói ở phía trên). Tuy nhiên tôi nghĩ lại rằng:"Ở, kể ra cũng có gì đáng để bàn ở đây đó chứ", thế nên tôi quyết định viết cái note này, không phải để chỉ bạn cách làm sao để trờ thành như Bill Gates, tiền không đếm mà toàn tính theo cân (kg), mà sẽ giúp bạn định hướng con đường mình cần đi để - cho dù không trở nên nổi tiếng đi chăng nữa - thì cũng đủ để bạn biến mình thành 1 cái gì đó "pro". Cũng nên lưu ý 1 chút nữa là trong bài viết này tôi sẽ không nói về các ngôn ngữ lập trình, bởi vì mỗi ngôn ngữ có đặc trưng và sức mạnh riêng của chúng, không có ngôn ngữ nào hoàn hảo cả, mà tối sẽ chỉ nêu ra hướng bạn cần đi để trở thành một "pro", theo các suy nghĩ, kinh nghiệm và quan điểm của cá nhân tôi (mặc dù tôi là dân tài chính chứ không phải theo công nghệ thông tin, hoàn toàn là 1 "trái tim bên lề"

. Sẵn sàng chưa, hãy bắt đầu nào.

Con đường của tôi chọn là:

**Programming -> Debugging -> System Programming/Kernel Programming -> Hacking and security**

Tôi sẽ phân tích từng giai đoạn một ở dưới đây

**1.Programming**

Đã gọi là "siêu lập trình viên" rồi thì chắc chắn là phải biết lập trình chứ. Programming ở đây, bạn cần phải nắm THẬT vững một ngôn ngữ nào đó. Và hãy tiến hành code các ứng dụng, tiện ích từ nhỏ cho đến lớn, trước hết là phục vụ nhu cầu của mình đã, rồi phục vụ nhu cầu của người khác. VD như cứ đi dần từ việc viết mấy cái chương trình để lòe con gái, lòe cái lũ bạn "cờ hó" đến việc viết các ứng dụng thiết thực hơn như quản lý bán hàng, kế toán hoặc các phần mềm xử lý và mô phỏng đồ họa (cớ như photoshop, autocad hay premier thì càng tốt). Và ngoài ngôn ngữ mình thuần thục ra, hãy bỏ thêm thời gian để tìm hiểu và sử dụng một vài ngôn ngữ khác nữa, càng nhiều thì càng tốt, nhưng hay lượng sức mình kẻo bị "tẩu hỏa nhập ma". Việc lập trình này giúp cho bạn có kiến thức vững vàng về các ngôn ngữ lập trình và các thuật toán, giải thuật cũng như cách xây dựng 1 chương trình.

**2.Debugging**

Thực chất thì debugging là 1 phần không thể tách rời của programming, nhưng trong quan điểm của tôi thì tôi vẫn chia nó ra thành 1 phần riêng, bởi vì tính quan trọng của nó. Nhiều người (đặc biệt là các bạn mới học lập trình) hay có suy nghĩ kiểu "debug chỉ là gỡ lỗi cho chương trình thôi, mục đích cuối cùng cũng chỉ là tìm cách để bấm F9/F5 là chương trình chạy phà phà mà không có lỗi", nhưng đối với cá nhân tôi, debug còn mang theo nhiều thứ hơn là việc gỡ lỗi. Bằng việc debug, tôi nhìn thấy được máy tính đang hoạt động như thế nào với mỗi đoạn code được viết ra, điều này khiến tôi hiểu thêm rất nhiều thứ về hoạt động của máy tính. Việc tôi nhìn thấy cái cách mà chương trình gọi hàm như thế nào, push và pop các giá trị từ stack như thế nào, các registers và các flag của cpu thay đổi thế nào, các ô nhớ trong memory lưu trữ ra sao, hay chỉ đơn giản là câu lệnh assembly trông như thế nào khi chuyển từ các ngôn ngữ bậc cao sang... Tất cả chúng đều rất thú vị. Tôi vẫn debug cả tất cả các chương trình, kể cả chúng có lỗi hay không có lỗi, chỉ để quan sát những điều trên, thật sự rất hữu ích cho việc lập trình của tôi, để tôi không còn đặt những câu hỏi đại loại như "thế nào là 32 bit?/ thế nào là 64 bit?" và nhận được những câu trả lời rất chi là uyên thâm, đầy đủ đến mức hoàn hảo, mà cuối cùng vẫn chả hiểu thực sự nó là cái gì. Nói chung, việc debug giúp chúng ta có một cái nhìn thật sâu sắc và toàn diện hơn về cấu trúc máy tính, cách hoạt động của một chương trình chứ không chỉ dừng lại ở việc gỡ lỗi đơn thuần

P/s cho phần này: có vài lần tôi dùng một vài IDE hiện đại ngày nay thấy việc debug bằng các debugger tích hợp trong IDE khá là tẻ nhạt khi đa số chỉ cho phép xem và trace theo giá trị của các biến. Tuy vẫn có thể debug kèm theo nhiều thông tin hơn, nhưng như vậy thì vẫn khá là nhạt, tôi vẫn thích dùng mấy cái "hàng nóng" như olly hay gdb hơn, có vẻ rất đã tay

. Có lẽ nào khi debug bằng các IDE quá nhiều nên bây giờ có nhiều người không coi trọng việc debug (thậm chí có nhiều người coi debug chỉ như một thao tác mang tính chất thủ tục) như vậy chăng?

**3. System Programming / Kernel Programming**

Con đường gian truân bắt đầu từ đây. Sau khi bạn đã có đủ kiến thức về hệ thống cũng như kiến thức về lập trình, thì bạn hãy bắt đầu với phần này. Có thể bạn sẽ thắc mắc "phần 1 và phần 3 này khác gì nhau?". Thế thì tôi xin giải thích 1 chút:

Như các bạn đã thấy trong phần 1 tôi khuyến khích các bạn lập trình ra các chương trình phục vụ cho công việc hàng ngày của các bạn cũng như của mọi người, cứ tạm gọi là Application programming đi, thì cái các bạn đang làm đó mới chỉ là cầu nối trung gian cho việc giao tiếp giữa máy tính và người dùng bình thường, và tìm cách khai thác máy tính như một công cụ hữu ích để phục vụ cho nhu cầu của mọi người. Còn system programming lại hoàn toàn khác, bạn cần tìm cách để "làm bạn" với máy vi tính, lắng nghe nó, hiểu nó để biết nó làm được những gì, và tiến tới điều khiển và tận dụng sức mạnh của nó một cách hoàn toàn. Nôm na lại là chủ yếu trong phần này các bạn sẽ cố gắng tìm cách để lập trình tương tác với phần cứng cũng như nhân của hệ điều hành và điều khiển các thành phần này hoạt động theo ý muốn của bạn. Ví dụ như viết một vài driver cho thiết bị ngoại vi, viết ra 1 compiler/debugger cho riêng mình, viêt và submit được một vài bản patch cho linux kernel, code trên các hệ thống nhúng,.... tiến xa hơn nữa thì tự tạo hẳn một cái hệ điều hành mới

. Các công việc này rất chi là gian nan vì bên cạnh khả năng lập trình tốt và hiểu rõ cách hoạt động của máy tính cũng như hệ điều hành thì còn phải có kiến thức thật tốt về cấu trúc phần cứng (và cũng một phần, không phải là ít về điện và điện tử). Đến được mức này thì bạn cũng thuộc vào hạng "thần thánh" rồi chứ không phải bình thường nữa

**4. Hacking and Security**

Phần này là phần cuối, nhưng thực tế thì chỉ là phần "ăn theo" của các phân trên nhưng lại là cảnh giới tối thượng của một lập trình viên. Một lập trình viên giỏi cũng gần như có nghĩa là anh ta là 1 hacker cứng tay. Tuy nhiên, có nhiều quan điểm về hacking and security khác nhau, bởi vì các quan điểm đó nhiều khi được đặt trên các góc độ quy chiếu khác nhau cho nên không đồng nhất. Trong góc độ lập trình, tôi chỉ xem xét "hacking and security" là biểu trưng cho 2 mục đích chính, là ưu tiên hàng đầu và tối quan trọng của một lập trình viên:

- Độ hiệu quả của code và chương trình
- Độ tin cậy và an toàn của code và chươn trình

Có một câu chuyện bịa đặt trắng trợn như sau

Thời sinh viên....

Tôi có code ra một chương trình nho nhỏ, một cái chương trình chat để thi thoảng tâm sự với nhỏ bạn gái, 2 đứa thủ thỉ với nhau cho tiện lợi

. Mọi chuyện diễn ra hết sức tốt đẹp, tối nào cũng thế, tin đi tin về rầm rầm, mùi mẫn muốn chết đi được

. Tuy nhiên dạo gần đây nhỏ đó than phiền rằng sao máy của nhỏ dạo này cứ khi chat chit với tôi là lại chạy chậm và lag lắm. Thế là tôi nghi là chương trình chat của tôi có vấn đề. Kiểm tra lại thấy code vẫn ổn, các tính năng của chương trình vẫn hoạt động tốt, tuy nhiên xem xét kĩ hơn thì thấy chương trình chiếm quá nhiều memory cũng như CPU Usage. À, thì ra bị chậm và lag là do đây. Thế là tôi phải tìm cách chỉnh sửa lại code, để nó trở nên tối ưu hơn, khi chạy chiếm ít CPU và RAM hơn. Việc chỉnh sửa code này nhằm giúp cho chương trình hoạt động hiệu quả hơn, chính là việc tôi đang "hack" vào code để đáp ứng đúng cho nhu cầu của tôi (và tất nhiên của nhỏ bạn gái kia nữa hehe). Tôi mày mò xây dựng lại chương trình, áp dụng các thuật toán tốt hơn và nghĩ ra các thuật toán mới linh động hơn, cuối cùng đã thành công. Từ đó tôi và nhỏ lại chat chit tưng bừng.

Cái chuyện tình yêu tình báo nhiều khi cũng phải giấu kín để tránh cho thiên hạ soi mói (mà nhiều khi lũ bạn biết mình có "gấu" nó lại bắt khao thì khổ). Cả tôi và nhỏ đều dấu nhẹm đi, để chờ thời cơ rồi công khai cho bàn dân thiên hạ biết. Thế nhưng mà giờ G chưa đến mà đã bị mấy thằng bạn phát hiện ra, thế là khổ thân cái ví của tôi, đã chả có gì để mà bồi bổ, giờ lại phải khao nên chuyển sang trạng thái suy dinh dưỡng nặng. Tôi tự hỏi "tại sao chúng nó lại biết được nhỉ?". Tôi lần mò tìm hiểu, à thì ra chúng nó thấy tối suốt ngày ngồi cặm cụi gõ gõ bấm bấm, rồi thi thoảng lại ngồi dòm cái màn vi tính rồi cười tủm tỉm một mình, nên chúng nó sinh nghi, ngấm ngầm capture các packets trên mạng và túm được một mớ các gói tin của tôi gửi đi thông qua cái chương trình chat kia, ở dạng plain text. Thế nên chúng nó mới phát hiện ra. Suy ra là, code của tôi không an toàn và đã để lộ thông tin, khiến cho tôi bị thiệt hại nặng về kinh tế và nhỏ thì "xí hổ" nặng khi sau này thi thoảng chúng tôi vẫn bị lũ bạn tôi trêu đùa.

Tuy việc đã lộ nhưng tôi vẫn muốn hoàn thiện chương trình chat của mình để nó trở nên an toàn và bảo mật tốt hơn. Tôi áp dụng encrypt các tin nhắn rồi mới gửi đi, sang đến bên nhỏ bạn thì tiến hành decrypt ra, sau đó tiến hành kiểm tra lại thì thấy chỉ túm được một mớ packets chứa các tin nhắn đã được encrypt. Phù, thế là an toàn rồi.

Đó chỉ là câu chuyện để mô phỏng cho một phần vô cùng nhỏ của "hacking and security". Để làm được hacking and security toàn diện thì các bạn cần phải có kiến thức rất rộng lớn, về cả lập trình, hệ thống máy tính lẫn kiến thức về mạng cũng như phần cứng. Việc nâng cao hiệu quả và độ tin cậy của một sản phầm phần mềm cũng như phần cứng rất khó khăn và tốn nhiều thời gian, đòi hỏi nhiều kiến thức cũng như công sức bỏ ra, cần nhất là bạn cần phải hiểu nguyên lý hoạt động của các thành phần liên quan. Viết được code, run được chương trình, xây dựng 1 hệ thống hoạt động được là chưa đủ, cần phải làm sao để cho những thứ đó chạy thật "mượt", thật an toàn nữa. Mà cái công đoạn tối ưu chương trình này, không phải chỉ diễn ra một lần là xong, mà còn phải thực hiện rất rất nhiều lần. Sau mỗi lần chỉnh sửa nâng cấp, chương trình sẽ càng trở nên hoàn thiện hơn và an toàn hơn... Đó là lý do tại sao hacking and security là cảnh giới tối thượng của một lập trình viên, theo ý kiến cá nhân của tôi.

Kết bài thì đơn giản thôi, một người viết ra chương trình hoàn thiện nhất chính là lập trình viên giỏi nhất, bất kể anh ta dùng cách nào đi chăng nữa.

P/s: vì tôi là dân nghiệp dư, các kiến thức đều do gom góp tự học nên sẽ không tránh khỏi sai sót, nên rất mong được mọi người bổ sung và góp ý để hoàn thiện hơn
