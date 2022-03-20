# Learning-path - Networking

|   Người thực hiện    | Team |             Chủ đề             |
| :------------------: | :--: | :----------------------------: |
| Chu Văn Khánh |  CyberClass  | Tổng quan về Networking |

# I. Computer network types
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

# II. Terms and concepts	

## IP address, MAC, Subnetmask
  -  IP address là một đại diện số xác định duy nhất một giao diện cụ thể trên mạng. Địa chỉ trong IPv4 dài 32 bit. Điều này cho phép tối đa 4,294,967,296 (2^32) địa chỉ duy nhất. Địa chỉ trong IPv6 là 128 bit, cho phép các địa chỉ duy nhất 3,4 x 10^38 (2^128). Tổng số địa chỉ có thể sử dụng của cả hai phiên bản được giảm bởi các địa chỉ dành riêng khác nhau và các cân nhắc khác. Địa chỉ IP là số nhị phân nhưng thường được thể hiện ở dạng thập phân (IPv4) hoặc dạng thập lục phân (IPv6) để giúp việc đọc và sử dụng chúng dễ dàng hơn cho con người.
  -  MAC address là số nhận dạng phần cứng xác định duy nhất (không thể thay đổi) cho từng thiết bị trên mạng được sản xuất vào card mạng, card Ethernet hoặc card Wi-Fi.
  - Subnet mark là một số dạng 32 bit được tạo bằng cách đặt tất cả các host bit thành số 0 và đặt tất cả các network bit thành các số 1. Bằng cách này, subnet mask phân tách địa chỉ IP thành địa chỉ mạng và địa chỉ host. Mỗi thiết bị có một địa chỉ IP với hai phần: máy khách hoặc địa chỉ máy chủ và máy chủ hoặc địa chỉ mạng. Địa chỉ IP được cấu hình bởi máy chủ DHCP hoặc được cấu hình thủ công (địa chỉ IP tĩnh). Subnet mask chia địa chỉ IP thành địa chỉ máy chủ và địa chỉ mạng, từ đó xác định phần nào của địa chỉ IP thuộc về thiết bị và phần nào thuộc về mạng.
   ![image](https://i.imgur.com/MNpb0rJ.png)

## Nodes
 - Trong network, nodes là điểm kết nối, điểm phân phối lại nếu không là điểm cuối giao tiếp. Trong khoa học máy tính, đây là những điểm dữ liệu hoặc thiết bị trên một mạng lớn như máy tính cá nhân, máy in hoặc điện thoại. Nói chung, các nút được lập trình để xác định, xử lý nếu không truyền dữ liệu từ nút này sang nút khác. Vì vậy, node là một điểm khác nhau bất cứ nơi nào một kết nối diễn ra. Khái niệm về các nút này đến từ việc sử dụng các mạng phân tán cũng như chuyển mạch gói. Vì vậy, các nút này thực hiện nhiều chức năng khác nhau dựa trên ứng dụng. Mỗi thiết bị được sử dụng trên mạng bao gồm một địa chỉ IP duy nhất, được gọi là nút. Khi một nút được kết nối trong mạng, nó phải có địa chỉ [MAC](https://github.com/KhanhCVHE/Learning-path---Networking/blob/main/README.md#IP-address-MAC-Subnetmask). Nó là một định danh duy nhất được phân bổ bởi các nhà sản xuất thiết bị cho một NIC (thẻ giao diện mạng) dành cho thông tin liên lạc trong một mạng.
 ![image](https://i.imgur.com/aPWn30o.png)

## Routers
 - Router là một thiết bị mạng chuyển tiếp các gói dữ liệu giữa các mạng máy tính. Router thực hiện các chức năng chỉ đạo lưu lượng truy cập trên Internet. Dữ liệu được gửi qua internet, chẳng hạn như trang web hoặc email, ở dạng gói dữ liệu. Một gói thường được chuyển tiếp từ bộ định tuyến này sang bộ định tuyến khác thông qua các mạng tạo thành internetwork (ví dụ: Internet) cho đến khi nó đạt đến nút đích.
  ![image](https://i.imgur.com/yI2pbfE.png)

## Switches
 - Switches là một thiết bị trong mạng máy tính kết nối các thiết bị khác với nhau. Nhiều cáp dữ liệu được cắm vào một công tắc để cho phép giao tiếp giữa các thiết bị mạng khác nhau. Các thiết bị chuyển mạch quản lý luồng dữ liệu qua mạng bằng cách truyền một gói mạng nhận được chỉ đến một hoặc nhiều thiết bị mà gói được dự định. Mỗi thiết bị nối mạng được kết nối với một công tắc có thể được xác định bởi địa chỉ mạng của nó, cho phép chuyển đổi để chỉ đạo luồng lưu lượng truy cập tối đa hóa bảo mật và hiệu quả của mạng. Nói nôm na switches là thiết bị chia từ 1 nguồn mạng input ra thành nhiều để các thiết bị có thể sử dụng được internet.
  ![image](https://i.imgur.com/waEXwE0.png)

## Ports
 - Ports là điểm kết nối vật lý bằng cách sử dụng mà một thiết bị bên ngoài có thể được kết nối với máy tính. Nó cũng có thể là điểm kết nối lập trình thông qua đó thông tin đi từ một chương trình đến máy tính hoặc qua Internet. Một port mạng được cung cấp bởi các giao thức Transport Layer của bộ Giao thức Internet, chẳng hạn như Giao thức điều khiển truyền dẫn (TCP) và Giao thức sơ đồ người dùng (UDP) là một số phục vụ giao tiếp điểm cuối giữa hai máy tính.

|Số cổng|Giao thức|Tên dịch vụ|
|-|-|-|
|20,21|TCP|File Transfer Protocol|
|23|TCP|Telnet|
|25|TCP|File Transfer Protocol|
|53|TCP and UDP|Domain Name System(DNS)|
|110|TCP|Post Office Protocol(POP3)|
|123|UDP|Network Time Protocol(NTP)|

## Network cable types
 - Network cable types là phần cứng mạng được sử dụng để kết nối một thiết bị mạng với các thiết bị mạng khác hoặc để kết nối hai hoặc nhiều máy tính để chia sẻ máy in, máy quét, v.v. Các loại cáp mạng khác nhau, chẳng hạn như cáp đồng trục, cáp quang và cáp cặp xoắn, được sử dụng tùy thuộc vào lớp vật lý, topology và kích thước của mạng. Các thiết bị có thể cách nhau vài mét (ví dụ: thông qua Ethernet) hoặc khoảng cách gần như không giới hạn (ví dụ: thông qua các kết nối của Internet).  
![image](https://i.imgur.com/QhJz5VY.png)
![image](https://i.imgur.com/PZhrQDc.png)
![image](https://i.imgur.com/MVdrk66.png)
# III. Architecture	
 ## Network topology	
 - Là sự sắp xếp của một mạng bao gồm các nodes và đường kết nối thông qua người gửi và người nhận được gọi là tô pô mạng. Các topologies mạng khác nhau là:
	- Cấu trúc liên kết lưới:
	Trong cấu trúc liên kết lưới, mỗi thiết bị được kết nối với một thiết bị khác thông qua một kênh cụ thể.
    Ưu điểm của nó là rất mạnh mẽ. Lỗi được chẩn đoán dễ dàng. Dữ liệu là đáng tin cậy vì dữ liệu được truyền giữa các thiết bị thông qua các kênh hoặc liên kết chuyên dụng. Cung cấp bảo mật và quyền riêng tư.
    Nhược điểm là cài đặt và cấu hình rất khó khăn. Chi phí cáp cao vì cần có hệ thống dây điện số lượng lớn, do đó phù hợp với số lượng thiết bị ít hơn. Chi phí bảo trì rất cao.  
	![image](https://i.imgur.com/k0Grd6x.png)
    - Star Topology
	Trong Star Topology, tất cả các thiết bị được kết nối với một trung tâm duy nhất thông qua cáp. Hub này là nút trung tâm và tất cả các nút khác được kết nối với nút trung tâm. Trung tâm có thể thụ động trong tự nhiên, tức là không phải là một trung tâm thông minh như các thiết bị phát sóng, đồng thời trung tâm có thể thông minh được gọi là trung tâm hoạt động. Các trung tâm hoạt động có bộ lặp trong đó.
    Ưu điểm là nếu các thiết bị N được kết nối với nhau trong cấu trúc liên kết sao, thì số lượng cáp cần thiết để kết nối chúng là N. Vì vậy, nó rất dễ dàng để thiết lập. Mỗi thiết bị chỉ cần 1 cổng tức là để kết nối với trung tâm, do đó tổng số cổng cần thiết là N. 
    Nhược điểm là cài đặt và cấu hình rất khó khăn. Chi phí cáp cao vì cần có hệ thống dây điện số lượng lớn, do đó phù hợp với số lượng thiết bị ít hơn. Chi phí bảo trì rất cao.  
	![image](https://i.imgur.com/w0qpFOh.png)
    - Bus Topology
    Bus Topology là một loại mạng trong đó mỗi máy tính và thiết bị mạng được kết nối với một cáp duy nhất. Nó truyền dữ liệu từ đầu này sang đầu kia theo một hướng duy nhất. Không có tính năng hai chiều là trong Bus Topology. Nó là một kết nối đa điểm và một Topology không mạnh mẽ bởi vì nếu xương sống thất bại, Topology sẽ sụp đổ.
    Ưu điểm là nếu các thiết bị N được kết nối với nhau trong cấu trúc liên kết Bus, thì số lượng cáp cần thiết để kết nối chúng là 1, được gọi là cáp xương sống và đường thả N là bắt buộc. Chi phí của cáp ít hơn so với các topologies khác, nhưng nó được sử dụng để xây dựng các mạng nhỏ.
    Nhược điểm là nếu cáp bị hỏng, thì toàn bộ hệ thống sẽ sụp đổ. Nếu lưu lượng mạng nặng, nó làm tăng va chạm trong mạng. Để tránh điều này, các giao thức khác nhau được sử dụng trong lớp MAC được gọi là Pure Aloha, Slotted Aloha, CSMA / CD, v.v. An ninh rất thấp.  
    ![image](https://i.imgur.com/YYNLJ3z.png)

    - Cấu trúc liên kết 
    Trong cấu trúc liên kết này, nó tạo thành một vòng kết nối các thiết bị với chính xác hai thiết bị lân cận của nó.Một số bộ lặp được sử dụng cho cấu trúc liên kết Ring với số lượng lớn các nút, bởi vì nếu ai đó muốn gửi một số dữ liệu đến nút cuối cùng trong cấu trúc liên kết vòng với 100 nút, thì dữ liệu sẽ phải đi qua 99 nút để đến nút thứ 100. Do đó để ngăn chặn bộ lặp mất dữ liệu được sử dụng trong mạng.Việc truyền tải là một chiều, nhưng nó có thể được thực hiện hai chiều bằng cách có 2 kết nối giữa mỗi Nút mạng, nó được gọi là Dual Ring Topology.
    Ưu điểm là khả năng sảy ra va chạm là rất ít trong loại Topology này.Giá rẻ để cài đặt và mở rộng.
    Nhược điểm là khắc phục sự cố rất khó khăn trong cấu trúc liên kết này. Việc bổ sung các trạm ở giữa hoặc loại bỏ các trạm có thể làm xáo trộn toàn bộ Topology. Ít an toàn hơn.  
    ![image](https://i.imgur.com/VgiodQH.png)
    - Tree Topology
    Topology này là biến thể của Star Topology. Cấu trúc liên kết này có một luồng dữ liệu phân cấp.  
![image](https://i.imgur.com/jo2bYIk.png)
## OSI và TCP/IP
- Sự tương đồng giữa OSI và TCP / IP
     Cả hai mô hình tham chiếu đều dựa trên kiến trúc nhiều lớp.
     Các lớp trong các mô hình được so sánh với nhau. Lớp vật lý và lớp liên kết dữ liệu của mô hình OSI tương ứng với lớp liên kết của mô hình TCP / IP.
     Các lớp mạng và các lớp vận chuyển là như nhau trong cả hai mô hình. Lớp phiên, lớp trình bày và lớp ứng dụng của mô hình OSI cùng nhau tạo thành lớp ứng dụng của mô hình TCP / IP.
     Trong cả hai mô hình, các giao thức được xác định một cách khôn ngoan theo lớp.
     Trong cả hai mô hình, dữ liệu được chia thành các gói và mỗi gói có thể đi theo tuyến đường riêng lẻ từ nguồn đến đích.
- Sự khác biệt giữa OSI và TCP / IP
    Mô hình OSI là một mô hình chung dựa trên các chức năng của từng lớp. Mô hình TCP /IP là một tiêu chuẩn định hướng giao thức.
    Mô hình OSI phân biệt ba khái niệm, cụ thể là dịch vụ, giao diện và giao thức. TCP/IP không có sự phân biệt rõ ràng giữa ba loại này.
    Mô hình OSI đưa ra các hướng dẫn về cách giao tiếp cần phải được thực hiện, trong khi các tiêu chuẩn bố trí giao thức TCP / IP mà Internet được phát triển. Vì vậy, TCP /IP là một mô hình thực tế hơn.
    Trong OSI, mô hình được phát triển đầu tiên và sau đó các giao thức trong mỗi lớp được phát triển. Trong bộ TCP / IP, các giao thức được phát triển đầu tiên và sau đó mô hình được phát triển.
    OSI có bảy lớp trong khi TCP / IP có bốn lớp.  
    ![image](https://i.imgur.com/C41Cgyr.png)
## Network Protocol
 - UDP (User Datagram Protocol) là một giao thức truyền thông được sử dụng trên Internet, UDP được ưu điểm là có tốc độ nhanh, chẳng hạn như phát lại video hoặc tra cứu DNS. Nó tăng tốc độ liên lạc bằng cách không chính thức thiết lập kết nối trước khi dữ liệu được truyền. Điều này cho phép dữ liệu được truyền rất nhanh chóng, nhưng nó cũng có thể khiến các gói tin bị thất lạc trong quá trình trao đổi.  
 ![image](https://i.imgur.com/Dw1axLo.png)
 - TCP (Transmission Control Protocol) là một trong những giao thức chính của bộ giao thức Internet. Nó bắt nguồn từ việc triển khai mạng ban đầu, trong đó nó bổ sung cho Giao thức Internet (IP). Các ứng dụng internet lớn như World Wide Web, email, quản trị từ xa và truyền tệp dựa vào TCP. Trong một giao tiếp TCP, hai máy tính bắt đầu bằng cách thiết lập một kết nối thông qua một quá trình tự động được gọi là "bắt tay". Chỉ khi cái bắt tay này được hoàn thành, một máy tính mới thực sự chuyển các gói dữ liệu sang máy tính khác. Vậy nên TCP có tốc độ chậm hơn UDP nhưng lại ổn định hơn UDP.  
  ![image](https://i.imgur.com/qqbt23e.png)

 - DNS (Domain Name System) được coi là danh bạ điện thoại của Internet. Con người truy cập thông tin trực tuyến thông qua tên miền, như facebook.com hoặc youtube.com. Trình duyệt web tương tác thông qua các địa chỉ Giao thức Internet (IP). DNS dịch tên miền sang địa chỉ IP để trình duyệt có thể tải tài nguyên Internet. Mỗi thiết bị được kết nối với Internet có một địa chỉ IP duy nhất mà các máy khác sử dụng để tìm thiết bị. Máy chủ DNS loại bỏ sự cần thiết của con người để ghi nhớ các địa chỉ IP như 192.168.1.1 (trong IPv4), hoặc các địa chỉ IP chữ số mới hơn phức tạp hơn như 2400:cb00:2048:1::c629:d7a2 (trong IPv6). Nôm na DNS sẽ chuyển đổi tên máy chủ (chẳng hạn như www.example.com) thành địa chỉ IP thân thiện với máy tính (chẳng hạn như 192.168.1.1) và ngược lại khi ta cần truy cập vào một trang web thì chỉ cần nhập (example.com) thay vì nhập (192.168.1.1)  
  ![](https://i.imgur.com/z7nToRh.png)
 - DHCP (Dynamic Host Configuration Protocol) là một giao thức cung cấp quản lý nhanh chóng, tự động và trung tâm để phân phối địa chỉ IP trong mạng. Nó cũng được sử dụng để cấu hình subnet mask, default gateway và thông tin máy chủ DNS trên thiết bị. DHCP cấp địa chỉ IP duy nhất và tự động cấu hình thông tin mạng khác. Trong hầu hết các gia đình và doanh nghiệp nhỏ, bộ định tuyến hoạt động như máy chủ DHCP. Trong các mạng lớn, một máy tính duy nhất có thể đảm nhận vai trò đó.
 ![image](https://i.imgur.com/w85hVn2.png)  
