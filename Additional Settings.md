# Additional Settings
  - This topic introduces my custom setting
  
##解析度/視窗大小
  1. 點選桌面右上方圖示
  2. System Settings
  3. Displays
  4. Set Resolution as 1920*1200
  5. Apply
  
##介面語言
  1. 點選桌面右上方圖示
  2. System Settings
  3. Language Support
  4. Drag the ideal language to the top of the list 
  5. Close

##GOOGLE Chrome
  1. Start Firefox
  2. Serch google.com
  3. 點選 更多=> 更多=> Google Chrome=> 下載Chrome
  4. Choose 64bit .deb (適用於 Debian/Ubuntu)
  5. 接受並安裝
  
##純文字介面
```
gedit /etc/default/grub &
  
#GRUB_CMDLINE_LINUX_DEFAULT="quiet splash"
GRUB_CMDLINE_LINUX_DEFAULT="text"
```
save & quit
  
```
sudo update-grub
```
  
```
reboot
```
  
ps. login acc is "fmirxx"
  
輸入 startx  即可切換至視窗介面，如需切換回文字介面，登出即可。
  
