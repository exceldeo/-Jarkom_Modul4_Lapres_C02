# Jarkom_Modul4_Lapres_C02
Laporan Resmi Modul 4 Praktikum Jaringan Komputer
## Kelompok C02
* Aulia Ihza Hendradi (05111840000089)
* Excel Deo Cornelius (05111840000117)

## CIDR

Pembagian subnet di CIDR dimulai dari yag terjauh dari cloud agar
mempermudah routing sehingga didapatkan subnet sebagai berikut

**Class A**

![image](https://user-images.githubusercontent.com/52096462/102014511-ed3d5b80-3d88-11eb-833d-9f35a7b8bd02.png)

**Class B**

![image](https://user-images.githubusercontent.com/52096462/102014927-1d85f980-3d8b-11eb-9d8d-25e1c42189d6.png)

**Class C**

![image (1)](https://user-images.githubusercontent.com/52096462/102014925-1bbc3600-3d8b-11eb-93c4-b53cb13e7a85.png)

**Class D**

![image (2)](https://user-images.githubusercontent.com/52096462/102014920-1828af00-3d8b-11eb-8ae8-399dbfe2610d.png)

**Class E**

![image (3)](https://user-images.githubusercontent.com/52096462/102014933-2080ea00-3d8b-11eb-8fb2-9298066b8ed6.png)

**Class F**

![image (4)](https://user-images.githubusercontent.com/52096462/102014929-1eb72680-3d8b-11eb-86bb-837456f60f07.png)

**Dari pembagian di atas didapatkan tree sebagai berikut**

![image](https://user-images.githubusercontent.com/52096462/102014486-d39c1400-3d88-11eb-902e-8819ad896488.png)

![image](https://user-images.githubusercontent.com/52096462/102014351-08f43200-3d88-11eb-9cce-8c23df0683da.png)
![image](https://user-images.githubusercontent.com/52096462/102014361-15788a80-3d88-11eb-8a8b-3954962bc05a.png)


**Buat topologi.sh dengan mengikuti topologi yang telah diberikan**

![topo](https://user-images.githubusercontent.com/52096462/102014418-6a1c0580-3d88-11eb-8da5-e4af0f60b02e.PNG)

**Jalankan topologi.sh, kemudian ubah semua /etc/network/interfaces
menjadi sebagai berikut**

![1](https://user-images.githubusercontent.com/52096462/102014298-dba78400-3d87-11eb-8b39-480557576211.PNG)
![2](https://user-images.githubusercontent.com/52096462/102014301-dcd8b100-3d87-11eb-9a21-ccd2cd6fd133.PNG)
![3](https://user-images.githubusercontent.com/52096462/102014303-dd714780-3d87-11eb-8739-9b5eb7ef2b05.PNG)
![4](https://user-images.githubusercontent.com/52096462/102014304-de09de00-3d87-11eb-8ed0-4a04518bb8ae.PNG)
![5](https://user-images.githubusercontent.com/52096462/102014305-dea27480-3d87-11eb-8b51-4e479abb4cd4.PNG)
![6](https://user-images.githubusercontent.com/52096462/102014306-df3b0b00-3d87-11eb-90f0-70ba6f42e23e.PNG)
![7](https://user-images.githubusercontent.com/52096462/102014307-df3b0b00-3d87-11eb-9f9c-2e44ff572445.PNG)
![8](https://user-images.githubusercontent.com/52096462/102014308-dfd3a180-3d87-11eb-999b-2e7fd6a7cef4.PNG)
![9](https://user-images.githubusercontent.com/52096462/102014310-e06c3800-3d87-11eb-80f8-9a47b7f732d0.PNG)
![10](https://user-images.githubusercontent.com/52096462/102014311-e104ce80-3d87-11eb-8a24-70f5d8a3a8ec.PNG)
![11](https://user-images.githubusercontent.com/52096462/102014313-e19d6500-3d87-11eb-9d61-f94bb4fb4db7.PNG)
![12](https://user-images.githubusercontent.com/52096462/102014314-e19d6500-3d87-11eb-95c9-5d8f917ad9c3.PNG)
![13](https://user-images.githubusercontent.com/52096462/102014315-e235fb80-3d87-11eb-948f-4552d0ea5a65.PNG)
![14](https://user-images.githubusercontent.com/52096462/102014316-e2ce9200-3d87-11eb-921a-c94e10a9a6e6.PNG)
![15](https://user-images.githubusercontent.com/52096462/102014317-e3672880-3d87-11eb-9e29-73f4faf4e2f7.PNG)
![16](https://user-images.githubusercontent.com/52096462/102014318-e3672880-3d87-11eb-8f35-0ffb7b9e90e5.PNG)
![17](https://user-images.githubusercontent.com/52096462/102014319-e3ffbf00-3d87-11eb-9fdd-c12ed84c2c2b.PNG)
![18](https://user-images.githubusercontent.com/52096462/102014320-e4985580-3d87-11eb-88cb-6781b845746f.PNG)
![19](https://user-images.githubusercontent.com/52096462/102014322-e530ec00-3d87-11eb-9117-36941a3b49b0.PNG)

**Lakukan routing di Surabaya, Pasuruan, Batu, dan Kediri**

![20](https://user-images.githubusercontent.com/52096462/102014276-bc105b80-3d87-11eb-9d15-2e60fc50a7bd.PNG)
![21](https://user-images.githubusercontent.com/52096462/102014277-bd418880-3d87-11eb-8b1f-03d39f0cc16f.PNG)
![22](https://user-images.githubusercontent.com/52096462/102014278-bdda1f00-3d87-11eb-929d-2367a453bb91.PNG)
![23](https://user-images.githubusercontent.com/52096462/102014279-be72b580-3d87-11eb-9f2c-1769d9cba8cd.PNG)

**Uncomment net.ipv4.ip_forward = 1 di /etc/sysctl.conf, kemudian
jalankan sysctl -p (lakukan di semua router)**

![24](https://user-images.githubusercontent.com/52096462/102014248-9e42f680-3d87-11eb-862e-e36f92ac8103.PNG)

**Lakukan iptables di Surabaya**

![25](https://user-images.githubusercontent.com/52096462/102014251-9f742380-3d87-11eb-8e6e-062f791a1c49.PNG)


**Testing dengan melakukan ping**

![26](https://user-images.githubusercontent.com/52096462/102014210-7d7aa100-3d87-11eb-89aa-667035196dcd.PNG)
![27](https://user-images.githubusercontent.com/52096462/102014211-7eabce00-3d87-11eb-9b5f-1452ed7eb61c.PNG)
![28](https://user-images.githubusercontent.com/52096462/102014212-7f446480-3d87-11eb-924b-97902b6c08ff.PNG)
![29](https://user-images.githubusercontent.com/52096462/102014213-7fdcfb00-3d87-11eb-879a-e4e372baa3a3.PNG)
![30](https://user-images.githubusercontent.com/52096462/102014214-80759180-3d87-11eb-93b9-09dd4308b92f.PNG)
![31](https://user-images.githubusercontent.com/52096462/102014215-810e2800-3d87-11eb-8cba-4d543e043ef9.PNG)
![32](https://user-images.githubusercontent.com/52096462/102014216-810e2800-3d87-11eb-9eeb-92b424d5a3df.PNG)
![33](https://user-images.githubusercontent.com/52096462/102014217-81a6be80-3d87-11eb-8139-6368beff0468.PNG)
![34](https://user-images.githubusercontent.com/52096462/102014218-823f5500-3d87-11eb-8c02-ab036973aeb5.PNG)
![35](https://user-images.githubusercontent.com/52096462/102014219-82d7eb80-3d87-11eb-9714-b95cd408ad9c.PNG)
![36](https://user-images.githubusercontent.com/52096462/102014220-83708200-3d87-11eb-8008-89bb0b143d1c.PNG)
![37](https://user-images.githubusercontent.com/52096462/102014221-84091880-3d87-11eb-8341-98b015ee294e.PNG)
![38](https://user-images.githubusercontent.com/52096462/102014222-84091880-3d87-11eb-8dea-622ee5a70b3b.PNG)
![39](https://user-images.githubusercontent.com/52096462/102014228-8d928080-3d87-11eb-9730-7c372ab08b79.PNG)
![40](https://user-images.githubusercontent.com/52096462/102014229-8f5c4400-3d87-11eb-9b9c-c3a658e3c4b2.PNG)
![41](https://user-images.githubusercontent.com/52096462/102014230-8ff4da80-3d87-11eb-8ee4-dd9702f17aa2.PNG)
![42](https://user-images.githubusercontent.com/52096462/102014231-908d7100-3d87-11eb-8199-2b09f5243a21.PNG)
![43](https://user-images.githubusercontent.com/52096462/102014234-91be9e00-3d87-11eb-9cf0-1a57e3e6e0c8.PNG)
![44](https://user-images.githubusercontent.com/52096462/102014235-91be9e00-3d87-11eb-9177-ebfc232dcd52.PNG)


## VSLM

**Topologi awal**

![1](https://user-images.githubusercontent.com/52096462/102014182-58862e00-3d87-11eb-9446-bc48ca8e5c56.png)
![image](https://user-images.githubusercontent.com/52096462/102014168-3db3b980-3d87-11eb-9e18-4055b007bfa4.png)

**VSLM Tree**

![image](https://user-images.githubusercontent.com/52096462/102014145-21b01800-3d87-11eb-8d76-f3398ac8a472.png)

**Pembagian NID**

![image](https://user-images.githubusercontent.com/52096462/102014130-06dda380-3d87-11eb-8b7a-7cc8970ac0e0.png)

**Routing**

![1](https://user-images.githubusercontent.com/52096462/102014069-bd8d5400-3d86-11eb-820b-d8a6d82af7dc.PNG)
![2](https://user-images.githubusercontent.com/52096462/102014070-bf571780-3d86-11eb-98c6-a574f6011557.PNG)
![3](https://user-images.githubusercontent.com/52096462/102014072-bfefae00-3d86-11eb-84b4-e39947dac47b.PNG)
![4](https://user-images.githubusercontent.com/52096462/102014074-c0884480-3d86-11eb-880f-ea5aa89e4037.PNG)
![5](https://user-images.githubusercontent.com/52096462/102014075-c120db00-3d86-11eb-82d2-d46fe694c266.PNG)
![6](https://user-images.githubusercontent.com/52096462/102014076-c1b97180-3d86-11eb-8878-a0a8b6d3834f.PNG)
![7](https://user-images.githubusercontent.com/52096462/102014077-c2520800-3d86-11eb-836f-7b87cd0f293b.PNG)
![8](https://user-images.githubusercontent.com/52096462/102014078-c2ea9e80-3d86-11eb-9757-ba58461a879d.PNG)
![9](https://user-images.githubusercontent.com/52096462/102014079-c3833500-3d86-11eb-9f0e-44548cea5118.PNG)
![10](https://user-images.githubusercontent.com/52096462/102014081-c41bcb80-3d86-11eb-8973-8aa8bcb14b89.PNG)

**Contoh Ping**

![ping1](https://user-images.githubusercontent.com/52096462/102014097-d7c73200-3d86-11eb-9aa9-531f09b57b79.PNG)
![ping2](https://user-images.githubusercontent.com/52096462/102014098-d8f85f00-3d86-11eb-805b-f5969c386d65.PNG)
![ping3](https://user-images.githubusercontent.com/52096462/102014099-d990f580-3d86-11eb-8de6-83db16943465.PNG)

### kendala yang di alami 
 - waktu pengerjaan nya sedikit
