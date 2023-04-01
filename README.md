# Cisco WLAN Guest Users
Automatic create Cisco WLAN Guest Users and print Tickets by Epson POS Printer

# Setup
Enter IP Address or Hostname of the Epson POS Printer. I used a TM-m30
The Community String is the SNMP Access to the Cisco WLAN Controller. Need RW!
Enter the IP(s) of the WLC(s) and add the WLAN ID of each WLC.
The User Prefix is used by automatically creation.

![grafik](https://user-images.githubusercontent.com/51234422/229303254-0816f942-cff3-413d-b7ae-1e05a5c9284e.png)

# Use
## 1. Use Automatically (F11)
The username is generated by the prefix and a number. The password will be geneated randomly.
A ticket will be printed.

## 2. Enter the data manually
Fill in the fields. You can generate (Enter) or generate the user and print a ticket (CRTL + Enter).

![grafik](https://user-images.githubusercontent.com/51234422/229303396-3cd5d5da-648c-496d-8741-48ae9d8ce5e8.png)

## 3. Automatically by Shortcut
Generate a desktop shortcut (File > Generate Shortcut). The shortcut is CRTL + F12. You can change this in the Shortcut Settings.

![grafik](https://user-images.githubusercontent.com/51234422/229303563-74960f4a-b5ab-4189-ac1f-8f4e14072220.png)

## Easteregg
If you have a cash drawer installed on your Epson Printer, you can open it by pressing F12.