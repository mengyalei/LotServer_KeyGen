# LotServer_KeyGen


Usage: 

  - cli: 
  ```
  php keygen.php mac [ver]
  For example, php keygen.php 00:00:00:00:00:00 1
  ```
  - web:
  ```
  http://example.com/keygen.php?ver=1&mac=00:00:00:00:00:00
  ```
  api申请调用:<br>
将 .template_3.11.20.10.lic 和 keygen.php 放入网站空间内即可使用，api调用方法"https://lotserverkey.*****.tk/keygen.php?ver=${acce_ver}&mac=${Mac}"
