# Machine-15 "FUNBOX: LUNCHBREAKER"

**netdiscover**

![image](https://github.com/Bultuush/Machine-15/assets/129934501/17a05880-2cbe-4f00-b555-95cb30fb1cab)

**nmap**

![image](https://github.com/Bultuush/Machine-15/assets/129934501/82b91c1b-c725-4375-99e2-ca5b7c24dbe2)

Би 80-р порт дээр юу ажиллаж байгааг мэдэхийн тулд 80-р портыг үзэж байна

![image](https://github.com/Bultuush/Machine-15/assets/129934501/d8663427-53ca-4e85-92b4-c0305d1ffde3)

80-р порт дээрх далд өгөгдлийг уншихын тулд CTRL+U товчийг дарна

![image](https://github.com/Bultuush/Machine-15/assets/129934501/7a2e8088-b42c-46b4-904c-ae4b9202a79d)

Цаашид би Жэйн хэрэглэгч дээр доор өгөгдсөн командын дагуу wordlist ашиглан FTP руу нэвтрэхийн тулд нууц үг илрүүлэгчийг ажиллуулдаг

# hydra -l jane -P /usr/share/wordlists/rockyou.txt ftp://192.168.1.32

![image](https://github.com/Bultuush/Machine-15/assets/129934501/ebcc6111-7468-4d00-9903-641424f702cc)

Дараа нь би энэ Jane хэрэглэгч & нууц үгийг ашиглан FTP руу нэвтэрсэн

Дараа нь би машин дээр хэдэн хэрэглэгч байгааг мэдэхийн тулд Home лавлах руу очно

![image](https://github.com/Bultuush/Machine-15/assets/129934501/d08e7d7f-2316-46b8-9e33-60e0278abadc)

Цаашид би доор өгөгдсөн командын дагуу wordlist ашиглан FTP-д нэвтрэхийн тулд Жим хэрэглэгч дээр нууц үг илрүүлэхийг ажиллуулдаг

# hydra -l jim -P /usr/share/wordlists/rockyou.txt ftp://192.168.1.32

![image](https://github.com/Bultuush/Machine-15/assets/129934501/10dde092-91af-4c47-ba7d-51804761423f)

Дараа нь би Jim хэрэглэгчийн болон нууц үг 12345 ашиглан FTP руу нэвтэрсэн

Дараа нь би фолдерыг шалгасны дараа .ssh хавтас олсон 2 түлхүүр олсон боловч тэдгээр нь хоосон байна

![image](https://github.com/Bultuush/Machine-15/assets/129934501/35f2655d-d13d-4b5f-aad4-ddb13e8237d1)

Дараа нь би доор өгөгдсөн командын дагуу wordlist ашиглан FTP-д нэвтрэхийн тулд Jules хэрэглэгч дээр нууц үг илрүүлэхийг ажиллуулдаг

# hydra -l jules -P /usr/share/wordlists/rockyou.txt ftp://192.168.1.32

![image](https://github.com/Bultuush/Machine-15/assets/129934501/db591912-3bad-4684-b596-8446f9c50758)

Дараа нь би Jules хэрэглэгчийн нууц үг, sexylady ашиглан FTP руу нэвтэрсэн

Эндээс би .backups файлыг олсон

![image](https://github.com/Bultuush/Machine-15/assets/129934501/ad50f371-6576-4331-97d5-51a52bb5ff69)

.backups файлд зарим нууц үгийн файлууд байгаа боловч тэдгээрийн 2 нь 0 байт байгаа нь ямар ч агуулга байхгүй гэсэн үг.

![image](https://github.com/Bultuush/Machine-15/assets/129934501/fa99067b-350e-40d5-a411-86a7b8c1e49a)

Би энэ хоёр файлыг дотоод компьютер дээрээ авдаг

![image](https://github.com/Bultuush/Machine-15/assets/129934501/14155c0f-8705-42e1-b9ec-c3faa4941d9b)

файлын нэрийг өөрчлөх

Дараа нь би доор өгөгдсөн командын дагуу wordlist ашиглан SSH-д нэвтрэхийн тулд Жон хэрэглэгч дээр нууц үг илрүүлэгч ажиллуулдаг

# hydra -l john -P /root/bad_passwd ssh://192.168.1.32

![image](https://github.com/Bultuush/Machine-15/assets/129934501/cdc67ae8-5581-4b36-a13f-365b76de00af)

Дараа нь би дээр дурдсан дэлгэцийн агшинд дурдсан John хэрэглэгчийн нууц үгийг ашиглан FTP руу нэвтэрч , амжилттай нэвтэрсэн

![image](https://github.com/Bultuush/Machine-15/assets/129934501/0a266ffe-5655-4f7f-8637-69d2c7d126f1)

Дараа нь би доор дурдсан john by cammand хэрэглэгчийн sudo зөвшөөрлийг мэдэхийг оролдсон

![image](https://github.com/Bultuush/Machine-15/assets/129934501/1b1a583c-2010-4162-b1f3-a2a613ca841e)

Цаашид би доор дурдсан cammand-н Жон хэрэглэгчийн одоогийн лавлах файлуудыг шалгаж байна

![image](https://github.com/Bultuush/Machine-15/assets/129934501/ec746ccd-52fa-4bbf-a854-7e3e64973277)

Үүнээс цааш би todo.list файлыг олсон

![image](https://github.com/Bultuush/Machine-15/assets/129934501/74a62332-2d84-42ad-85e1-719204359b12)

Дараа нь би энэ todo.list-ийг уншаад зурвас оллоо

![image](https://github.com/Bultuush/Machine-15/assets/129934501/2f93f7b3-29b3-4277-86ac-5c2277b84451)

Цаашид би johnın нууц үгийг ашиглан root хэрэглэгчээ сольдог

![image](https://github.com/Bultuush/Machine-15/assets/129934501/9087aeeb-0d34-4c9a-b865-1c7716a21dab)

/ root директор руу очно уу
үндсэн тугийг цуглуул
МАНАЙ язгуур туг ЭНЭ БАЙНА :)

![image](https://github.com/Bultuush/Machine-15/assets/129934501/809ad73c-c6a6-47ba-bed4-04c50880693f)
