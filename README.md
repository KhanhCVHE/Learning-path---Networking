# Learning-path - Networking

|   Người thực hiện    | Team |             Chủ đề             |
| :------------------: | :--: | :----------------------------: |
| Chu Văn Khánh |  CyberClass  | Tổng quan về Networking |

# I. Định nghĩa 
### 1. Computer network types
 - Computer network là một tập hợp gồm nhiều máy tính hoặc thiết bị xử lý thông tin được kết nối với nhau qua các đường truyền vật lí theo một kiến trúc mạng nhất định và có sự trao đổi dữ liệu với nhau. Nhờ có mạng máy tính, thông tin từ một máy tính có thể được truyền sang máy tính khác và mạng máy tính bao gồm các loại sau:   
 
    ## LAN (local area network) 
 - Là mạng máy tính nội bộ, giao tiếp này cho phép các thiết bị kết nối với nhau để cùng làm việc và chia sẻ dữ liệu được kết nối qua dây dẫn vật lý (dây LAN) trong một không gian hẹp nên được sử dụng trong mạng gia đình, cơ quan, trường học,...  
  ![image](https://user-images.githubusercontent.com/100344641/159124241-8520d3cc-585f-482c-8637-d72e6a6511e8.png)


    ## WLAN (wireless local area network)
 - Là mạng cục bộ không dây gồm các thiết bị như máy tính, điện thoại liên lạc với nhau bằng sóng vô tuyến. Dùng không gian hẹp nên được phổ biến trong mạng gia đình, nhà hàng, khách sạn,...  
 ![image](https://user-images.githubusercontent.com/100344641/159124257-0720ec0f-211c-4df1-a478-4b7edf52cf9d.png)
  
    ## WAN (wide area network)
 - Là một mạng giao tiếp giúp mở rộng các kết nối trên nhiều khu vực địa lý rộng lớn từ các thành phố, cho tới tiểu bang và các quốc gia. Mạng Wan có thể sử dụng như một mạng riêng tư để kết nối các bộ phận trong một doanh nghiệp hoặc cũng có thể để ở chế độ công khai cho phép kết nối các mạng nhỏ hơn với nhau. Vì hỗ trợ một khoảng cách địa lý xa hơn LAN, do đó việc kết nối các thành phần khác nhau trong mạng WAN khi sử dụng mạng riêng ảo [VPN](https://github.com/KhanhCVHE/Learning-path---Networking/blob/main/README.md#vpn-virtual-private-network)  hoặc Cloud Server được cho là thích hợp nhất.  
        ![image](https://i.imgur.com/ezSikWa.png) 
    ## MAN (metropolitan area network)
 - Hay còn gọi là mạng đô thị liên kết từ nhiều mạng LAN qua dây cáp hoặc các phương tiện truyền dẫn khác,... Khả năng kết nối trong phạm vi lớn như trong một thị trấn, thành phố, tỉnh. Mô hình mạng MAN thường được dùng chủ yếu cho đối tượng là tổ chức, doanh nghiệp nhiều chi nhánh, nhiều bộ phận kết nối với nhau. Mạng Man thường được sử dụng cho doanh nghiệp vì mô hình này này cung cấp nhiều loại dịch vụ như kết nối đường truyền qua voice (thoại), data (dữ liệu), video(hình ảnh), triển khai các ứng dụng dễ dàng. Phạm vi kết nối lớn giúp tương tác giữa các bộ phận doanh nghiệp dễ dàng, hiệu quả,chi phí thấp, tốc độ truyền tải ổn định, bảo mật thông tin, quản lý đơn giản được coi là ưu điểm của mạng MAN.  
  ![image](https://i.imgur.com/XvnkJxT.png)

    ## PAN (personal area network)  
 - Mạn PAN hay còn gọi là mạng cá nhân, có khả năng phát tín hiệu kết nối trong một diện tích nhỏ thông qua các thiết bị định tuyến. Những thiết bị định tuyến này có chức năng tìm đường để truyền dữ liệu tới đích.  
  ![image](https://i.imgur.com/QjeLqCM.png)

    ## SAN (storage area network)  
 - Mạng SAN hay còn gọi là mạng lưu trữ, mạng chuyên dụng, hoàn toàn khác biệt với mạng LAN và mạng WAN. Nghĩa là mạng SAN có khả năng kết nối tất cả các tài nguyên liên quan với nhau trong cùng một mạng. Đặc biệt, tốc độ kết nối và khả năng mở rộng dữ liệu giữa các thiết bị lưu trữ dữ liệu trong mạng SAN sẽ rất cao.SAN đặc biệt hữu ích trong các cài đặt sao lưu và khắc phục. Trong SAN, dữ liệu có thể được chuyển từ thiết bị lưu trữ này sang thiết bị lưu trữ khác mà không cần tương tác với máy chủ. Điều này tăng tốc quá trình sao lưu và loại bỏ sự cần thiết phải sử dụng chu kỳ CPU máy chủ để sao lưu.
 ![image](https://i.imgur.com/RW5gqlE.png)

    ## CAN (campus area network)  
 - Là một mạng máy tính liên kết các tòa nhà và bao gồm hai hoặc nhiều mạng khu vực địa phương (LANs) trong khu vực địa lý hạn chế. Nó có thể là khuôn viên trường đại học, khuôn viên doanh nghiệp, tòa nhà văn phòng, căn cứ quân sự, khu công nghiệp. CAN là một trong những loại MAN (Metropolitan Area Network) trên diện tích nhỏ hơn MAN và hầu hết các CAN kết nối với Internet công cộng.Tại các trường cao đẳng, đại học và các tổ chức giáo dục khác, CAN cung cấp truy cập Internet cho sinh viên và giảng viên. CAN cũng cho phép người dùng được kết nối nhanh chóng chia sẻ tệp và dữ liệu trong mạng: vì dữ liệu không phải rời khỏi CAN, người dùng trải nghiệm độ trễ ít hơn nhiều so với khi gửi và nhận dữ liệu trong MAN hoặc WAN. Giả sử khoa tiếng Anh của một trường đại học yêu cầu bản sao kỹ thuật số của một số cuốn sách từ thư viện trường đại học. Bởi vì những bản sao sách kỹ thuật số đó chỉ phải di chuyển khoảng cách giữa tòa nhà tiếng Anh và tòa nhà thư viện (giả sử cả hai tòa nhà đều có máy chủ riêng), bộ phận tiếng Anh nhận được chúng nhanh hơn nhiều so với nếu thư viện phải gửi các tệp qua Internet công cộng.
  ![image](https://i.imgur.com/vfMpTdL.png)

    ## VPN (virtual private network)
 - Là một mạng riêng ảo mở rộng trên một mạng công cộng và cho phép người dùng gửi và nhận dữ liệu qua các mạng chia sẻ hoặc công cộng như thể các thiết bị máy tính của họ được kết nối trực tiếp với mạng riêng. Lợi ích của VPN bao gồm tăng chức năng, bảo mật và quản lý mạng riêng. Nó cung cấp quyền truy cập vào các tài nguyên không thể truy cập được trên mạng công cộng và thường được sử dụng cho nhân viên làm việc từ xa.
 ![image](https://i.imgur.com/H1MCZsT.png)

