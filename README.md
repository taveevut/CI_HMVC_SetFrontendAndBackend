# Codeigniter HMVC Set `Frontend` , `Backend` , `Api`
> ดาวโหลดไฟล์ต้นฉบับได้ที่ [CodeIgniter-HMVC](https://github.com/Pholenk/CodeIgniter-HMVC)

## แก้ไขไฟล์ .htaccess
```sh
RewriteEngine On
RewriteBase /`{ชื่อโปรเจค}`

RewriteCond %{REQUEST_URI} ^/system.*
RewriteRule ^(.*)$ index.php?/$1 [L]
RewriteCond %{REQUEST_FILENAME} !-f
RewriteCond %{REQUEST_FILENAME} !-d
RewriteRule ^(.+)$ index.php?/$1 [L]
```
<br>
<br>

---
<p align="center"> จัดทำโปรแกรมคอมพิวเตอร์พัฒนาระบบงานธุรกิจส่วนตัวและหน่วยงาน ใส่ใจคุณภาพ คุ้มราคา ส่งงานตรงเวลา<br>ติดต่อ 086-288-7987 (ท็อป) หรืออีเมล์    nakomah.web@gmail.com<br>ติดตามผลงานได้ที่ <a href="https://nakomah.com" target="_blank">www.nakomah.com</a></p>