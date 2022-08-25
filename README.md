# cs-assignment-3

1. Challenge 1

Injek script javascript <script>alert('test')</script> di query string url
sehingga url menjadi seperti berikut
https://labs.tegalsec.org/xss-labs/chall/1.php?status=<script>alert('test')</script>

2. Challenge 2

Masukkan ke dalam input form <script>alert('test')</script>

![image](https://user-images.githubusercontent.com/6330046/186650234-4f0471e5-2b80-4bd8-9bcf-f7462d48f240.png)

3. Challenge 3

ubah request header dengan menggunakan Burp Suite pada User Agent dengan value javascript script <script>alert('Test XSS User Agent')</script>
kemudian di click forward pada burp suite

![image](https://user-images.githubusercontent.com/6330046/186656688-7da561ff-5653-4767-9f67-f1b7d7f0e563.png)

4. Challenge 4

Ubah request header menggunakan burp suite dan tambahkan header Referer dengan value javascript <script>alert('Test XSS Referer')</script>
kemudian di click forward pada burp suite

![image](https://user-images.githubusercontent.com/6330046/186659416-bc216ccf-3c85-441c-a94b-268bba0b518f.png)

5. Challenge 5

Ubah request header menggunakan burp suite pada request cookie ubah cookie value dengan key labs-tegal1137 dengan value javascript <script>alert('Test XSS Referer')</script>
kemudian di click forward pada burp suite

![image](https://user-images.githubusercontent.com/6330046/186661297-a1ac612e-76aa-4573-81ce-d6a707c525fa.png)

7. Challenge 8

buat sebuah file dengan nama <img src=x onerror=alert('test')> dan upload file tersebut

![image](https://user-images.githubusercontent.com/6330046/186710526-e27e058f-0304-4ae8-8a49-39c6744e2eab.png)


8. Challenge 9

Encode script javascript menggunakan burpsuite dan inject di query string url

![image](https://user-images.githubusercontent.com/6330046/186692248-b5c06623-cfa2-4e9d-9d2e-290bd25ca446.png)

9. Challenge 10

Karena kita tidak bisa menggunakan alert saya ganti menggunakan confirm dan inject di query string url

![image](https://user-images.githubusercontent.com/6330046/186692702-161408eb-26e3-4dad-acea-706bbfdb47f4.png)










