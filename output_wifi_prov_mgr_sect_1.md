I (31) boot: ESP-IDF v5.3 2nd stage bootloader
I (31) boot: compile time Sep 26 2024 13:48:09
I (31) boot: Multicore bootloader
I (35) boot: chip revision: v3.0
I (39) boot.esp32: SPI Speed      : 40MHz
I (44) boot.esp32: SPI Mode       : DIO
I (48) boot.esp32: SPI Flash Size : 2MB
I (53) boot: Enabling RNG early entropy source...
I (58) boot: Partition Table:
I (62) boot: ## Label            Usage          Type ST Offset   Length
I (69) boot:  0 nvs              WiFi data        01 02 00009000 00006000
I (76) boot:  1 phy_init         RF data          01 01 0000f000 00001000
I (84) boot:  2 factory          factory app      00 00 00010000 00140000
I (91) boot: End of partition table
I (96) esp_image: segment 0: paddr=00010020 vaddr=3f400020 size=2b374h (177012) map
I (165) esp_image: segment 1: paddr=0003b39c vaddr=3ffbdb60 size=04c7ch ( 19580) load
I (172) esp_image: segment 2: paddr=00040020 vaddr=400d0020 size=bafach (765868) map
I (435) esp_image: segment 3: paddr=000fafd4 vaddr=3ffc27dc size=00ed0h (  3792) load
I (437) esp_image: segment 4: paddr=000fbeac vaddr=40080000 size=1bd2ch (113964) load
I (500) boot: Loaded app from partition at offset 0x10000
I (500) boot: Disabling RNG early entropy source...
I (511) cpu_start: Multicore app
I (520) cpu_start: Pro cpu start user code
I (520) cpu_start: cpu freq: 160000000 Hz
I (520) app_init: Application information:
I (523) app_init: Project name:     wifi_prov_mgr
I (528) app_init: App version:      1
I (533) app_init: Compile time:     Sep 26 2024 13:47:34
I (539) app_init: ELF file SHA256:  6c3bd706d...
I (544) app_init: ESP-IDF:          v5.3
I (549) efuse_init: Min chip rev:     v0.0
I (553) efuse_init: Max chip rev:     v3.99 
I (558) efuse_init: Chip rev:         v3.0
I (563) heap_init: Initializing. RAM available for dynamic allocation:
I (571) heap_init: At 3FFAFF10 len 000000F0 (0 KiB): DRAM
I (576) heap_init: At 3FFB6388 len 00001C78 (7 KiB): DRAM
I (583) heap_init: At 3FFB9A20 len 00004108 (16 KiB): DRAM
I (589) heap_init: At 3FFC9E90 len 00016170 (88 KiB): DRAM
I (595) heap_init: At 3FFE0440 len 00003AE0 (14 KiB): D/IRAM
I (601) heap_init: At 3FFE4350 len 0001BCB0 (111 KiB): D/IRAM
I (608) heap_init: At 4009BD2C len 000042D4 (16 KiB): IRAM
I (616) spi_flash: detected chip: generic
I (618) spi_flash: flash io: dio
W (622) spi_flash: Detected size(4096k) larger than the size in the binary image header(2048k). Using the size in the binary image header.
I (637) coexist: coex firmware version: dab85ae96
I (642) main_task: Started on CPU0
I (652) main_task: Calling app_main()
I (682) wifi:wifi driver task: 3ffcdcf4, prio:23, stack:6656, core=0
I (682) wifi:wifi firmware version: 0caa81945
I (682) wifi:wifi certification version: v7.0
I (682) wifi:config NVS flash: enabled
I (682) wifi:config nano formating: disabled
I (692) wifi:Init data frame dynamic rx buffer num: 32
I (692) wifi:Init static rx mgmt buffer num: 5
I (702) wifi:Init management short buffer num: 32
I (702) wifi:Init dynamic tx buffer num: 32
I (702) wifi:Init static rx buffer size: 1600
I (712) wifi:Init static rx buffer num: 10
I (712) wifi:Init dynamic rx buffer num: 32
I (722) wifi_init: rx ba win: 6
I (722) wifi_init: accept mbox: 6
I (722) wifi_init: tcpip mbox: 32
I (732) wifi_init: udp mbox: 6
I (732) wifi_init: tcp mbox: 6
I (732) wifi_init: tcp tx win: 5760
I (742) wifi_init: tcp rx win: 5760
I (742) wifi_init: tcp mss: 1440
I (752) wifi_init: WiFi IRAM OP enabled
I (752) wifi_init: WiFi RX IRAM OP enabled
I (762) wifi_prov_scheme_ble: BT memory released
I (762) app: Starting provisioning
I (772) app: Development mode: using hard coded salt
I (772) app: Development mode: using hard coded verifier
I (782) phy_init: phy_version 4830,54550f7,Jun 20 2024,14:22:08
W (862) phy_init: saving new calibration data because of checksum failure, mode(0)
I (882) wifi:mode : sta (94:b5:55:f6:f6:40)
I (882) wifi:enable tsf
I (892) BTDM_INIT: BT controller compile version [f021fb7]
I (892) BTDM_INIT: Bluetooth MAC: 94:b5:55:f6:f6:42
I (1132) protocomm_nimble: BLE Host Task Started
I (1142) wifi_prov_mgr: Provisioning started with service name : PROV_F6F640 
I (1152) app: Provisioning started
I (1152) app: Scan this QR code from the provisioning application for Provisioning.
I (1152) QRCODE: Encoding below text with ECC LVL 0 & QR Code Version 10
I (1162) QRCODE: {"ver":"v1","name":"PROV_F6F640","username":"wifiprov","pop":"abcd1234","transport":"ble"}
I (1192) NimBLE: GAP procedure initiated: advertise; 
I (1192) NimBLE: disc_mode=2
I (1192) NimBLE:  adv_channel_map=0 own_addr_type=0 adv_filter_policy=0 adv_itvl_min=256 adv_itvl_max=256
I (1202) NimBLE: 


  █▀▀▀▀▀█ ███ ▀▄▀▀▀▄▄▄█▄▀▀▄▄▀▀  █▀▀▀▀▀█   
  █ ███ █ █▄▀█ ▄▄▄█▀▀▀▄▀▀█▄▄ ▄█ █ ███ █   
  █ ▀▀▀ █ ▄  ▄▄█▀▀▀  ▄▀█▄▀ ▀█▀  █ ▀▀▀ █
  ▀▀▀▀▀▀▀ ▀▄▀ █ █ █▄▀ ▀▄▀▄▀ ▀▄█ ▀▀▀▀▀▀▀   
  ▀▀ ▄█▀▀ ▄ ▄▀▄▄█▄ ▀█▀▄▀██▀▄ ▄▀▄ █▄▀▀▀▀
  █▄▄ ▄▄▀ ▀█▄█▀▀ ▀█▄  ▄▄▄▀▄ ██▀██ ▀█▄█▄   
   ▄ █▄ ▀▀█   ▀  █▀██▀▀▀ ▄▀▄ ▄▀ ▀█▄▀█▄▀
  ▄█▀██▄▀ ▀   ▄ █▀██▀▄▀▄██▀▀▄▀▀█▄█ █▄     
  ▀  ███▀   █▀▄▀█▄ ▀█▀▀█ █▀▄▄▄▀██▀▄ ▀▀▀   
  ███▀▄▄▀▄▀█▄█▀█▀█▀▄ ▄ █▄▀█ █▀▀█ █▄▀▄▄▄
  █▄▀█▄▀▀▀▀██ ▀█▄▄█▀ ▀▀▀ ▄ ▄  ▄██▀▄█▀█▀   
  █▄▀  █▀▄▀▀█ ▄ ▄▀██▀ ▀▄█▀ ▀ ▀▀█▄▀ █▄▄▄
  ▄ ▄▀█▄▀▀█▄▀▀▄▀▀▄█▀ ▀▀▀█▄█ ▄▄▀▀█▀▄▀▀ ▀
    █▄▀▄▀██▄██▀█▀▀ ▄ ▄ ██▀ ▀▀▀▀ █▄█▄█▀▄
  ▀▀▀▀▀▀▀ ██▀ ▀█▄█▄▀▄▀██▀█▄▄▄ █▀▀▀█ ▀▄
  █▀▀▀▀▀█ ▄ ▄ ▄ ▄███▄▄ ▄ ▀  ▄▀█ ▀ ██▄▄▄
  █ ███ █ ▀▄▀▀▄▀▀▄██▄ ▄▀█▄█ ▄▄████▀▄█▄▄
  █ ▀▀▀ █ ▄▄▀█▀█▀▀▄▄▀▄ ████ █ ▄  ▀▄██▄
  ▀▀▀▀▀▀▀ ▀▀▀ ▀▀  ▀▀ ▀▀▀  ▀  ▀   ▀▀ ▀▀▀


I (1472) app: If QR code is not visible, copy paste the below URL in a browser.
https://espressif.github.io/esp-jumpstart/qrcode.html?data={"ver":"v1","name":"PROV_F6F640","username":"wifiprov","pop":"abcd1234","transport":"ble"}
I (126932) app: BLE transport: Connected!
I (127122) protocomm_nimble: mtu update event; conn_handle=0 cid=4 mtu=256
I (128742) security2: Using salt and verifier to generate public key...
I (129642) app: Secured session established!
I (170902) app: Received Wi-Fi credentials
        SSID     : AIS 4G Hi-Speed Home WiFi_76947550769475
        Password : 50769475
I (176992) wifi:new:<11,0>, old:<1,0>, ap:<255,255>, sta:<11,0>, prof:1, snd_ch_cfg:0x0
I (177002) wifi:state: init -> auth (0xb0)
I (177002) wifi:state: auth -> assoc (0x0)
I (177012) wifi:state: assoc -> run (0x10)
I (177042) wifi:connected with AIS 4G Hi-Speed Home WiFi_769475, aid = 2, channel 11, BW20, bssid = 30:0a:c5:9e:94:9f
I (177042) wifi:security: WPA2-PSK, phy: bgn, rssi: -59
I (177072) wifi:pm start, type: 1

I (177072) wifi:dp: 1, bi: 102400, li: 3, scale listen interval from 307200 us to 307200 us
I (177142) wifi:AP's beacon interval = 102400 us, DTIM period = 1
I (178072) app: Connected with IP Address:192.168.1.190
I (178072) esp_netif_handlers: sta ip: 192.168.1.190, mask: 255.255.255.0, gw: 192.168.1.1
I (178072) wifi_prov_mgr: STA Got IP
I (178082) app: Provisioning successful
I (178082) app: Hello World!
I (179092) app: Hello World!
I (180092) app: Hello World!
I (180532) wifi:<ba-add>idx:0 (ifx:0, 30:0a:c5:9e:94:9f), tid:0, ssn:4, winSize:64
I (181092) app: Hello World!
I (182092) app: Hello World!
I (182272) NimBLE: GAP procedure initiated: stop advertising.

I (182282) NimBLE: GAP procedure initiated: stop advertising.

I (182282) NimBLE: GAP procedure initiated: terminate connection; conn_handle=0 hci_reason=19

E (182382) protocomm_nimble: Error setting advertisement data; rc = 30
I (182392) wifi_prov_mgr: Provisioning stopped
I (182392) app: BLE transport: Disconnected!
I (182392) wifi_prov_scheme_ble: BTDM memory released
I (183092) app: Hello World!
I (184092) app: Hello World!
I (185092) app: Hello World!
I (186092) app: Hello World!
I (187092) app: Hello World!
I (188092) app: Hello World!
I (189092) app: Hello World!
I (190092) app: Hello World!
I (191092) app: Hello World!
I (192092) app: Hello World!
I (193092) app: Hello World!
I (194092) app: Hello World!
I (195092) app: Hello World!
I (196092) app: Hello World!
I (197092) app: Hello World!
I (198092) app: Hello World!
I (199092) app: Hello World!
I (200092) app: Hello World!
I (201092) app: Hello World!
I (202092) app: Hello World!
I (203092) app: Hello World!
I (204092) app: Hello World!
I (205092) app: Hello World!
I (206092) app: Hello World!
I (207092) app: Hello World!
I (208092) app: Hello World!
I (209092) app: Hello World!
I (210092) app: Hello World!
I (211092) app: Hello World!
I (212092) app: Hello World!
I (213092) app: Hello World!
I (214092) app: Hello World!
I (215092) app: Hello World!
I (216092) app: Hello World!
I (217092) app: Hello World!
I (217602) wifi:<ba-add>idx:1 (ifx:0, 30:0a:c5:9e:94:9f), tid:6, ssn:0, winSize:64
I (218092) app: Hello World!
I (219092) app: Hello World!
I (220092) app: Hello World!
I (221092) app: Hello World!
I (222092) app: Hello World!
I (223092) app: Hello World!
I (224092) app: Hello World!
I (225092) app: Hello World!
I (226092) app: Hello World!
I (227092) app: Hello World!
I (228092) app: Hello World!
I (229092) app: Hello World!
I (230092) app: Hello World!
I (231092) app: Hello World!
I (232092) app: Hello World!
I (233092) app: Hello World!
I (234092) app: Hello World!
I (235092) app: Hello World!
I (236092) app: Hello World!
I (237092) app: Hello World!
I (238092) app: Hello World!
I (239092) app: Hello World!
I (240092) app: Hello World!
I (241092) app: Hello World!
I (242092) app: Hello World!
I (243092) app: Hello World!
I (244092) app: Hello World!
I (245092) app: Hello World!
I (246092) app: Hello World!
I (247092) app: Hello World!
I (248092) app: Hello World!
I (249092) app: Hello World!
I (250092) app: Hello World!
I (251092) app: Hello World!
I (252092) app: Hello World!
I (253092) app: Hello World!
I (254092) app: Hello World!
I (255092) app: Hello World!
I (256092) app: Hello World!
I (257092) app: Hello World!
I (258092) app: Hello World!
I (259092) app: Hello World!
I (260092) app: Hello World!
I (261092) app: Hello World!
I (262092) app: Hello World!
I (263092) app: Hello World!
I (264092) app: Hello World!
I (265092) app: Hello World!
I (266092) app: Hello World!
I (267092) app: Hello World!
I (268092) app: Hello World!
I (269092) app: Hello World!
I (270092) app: Hello World!
I (271092) app: Hello World!
I (272092) app: Hello World!
I (273092) app: Hello World!
I (274092) app: Hello World!
I (275092) app: Hello World!
I (276092) app: Hello World!
I (277092) app: Hello World!
I (278092) app: Hello World!
I (279092) app: Hello World!
I (280092) app: Hello World!
I (281092) app: Hello World!
I (282092) app: Hello World!
I (283092) app: Hello World!
I (284092) app: Hello World!
I (285092) app: Hello World!
I (286092) app: Hello World!
I (287092) app: Hello World!
I (288092) app: Hello World!
I (289092) app: Hello World!
I (290092) app: Hello World!
I (291092) app: Hello World!
I (292092) app: Hello World!
I (293092) app: Hello World!
I (294092) app: Hello World!
I (295092) app: Hello World!
I (296092) app: Hello World!
I (297092) app: Hello World!
I (298092) app: Hello World!
I (299092) app: Hello World!
I (300092) app: Hello World!
I (301092) app: Hello World!
I (302092) app: Hello World!
I (303092) app: Hello World!
I (304092) app: Hello World!
I (305092) app: Hello World!
I (306092) app: Hello World!
I (307092) app: Hello World!
I (308092) app: Hello World!
I (309092) app: Hello World!
I (310092) app: Hello World!
