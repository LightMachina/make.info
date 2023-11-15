DKMS make.log for 8188gu-1.0.1 for kernel 6.5.11-x64v3-xanmod1 (x86_64)
Wed Nov 15 11:16:09 AM CST 2023
make ARCH=x86_64 CROSS_COMPILE= -C /lib/modules/6.5.11-x64v3-xanmod1/build M=/var/lib/dkms/8188gu/1.0.1/build  modules
make[1]: Entering directory '/usr/src/linux-headers-6.5.11-x64v3-xanmod1'
warning: the compiler differs from the one used to build the kernel
  The kernel was built by: gcc-13 (Debian 13.2.0-5) 13.2.0
  You are using:           gcc (Ubuntu 11.4.0-1ubuntu1~22.04) 11.4.0
  CC [M]  /var/lib/dkms/8188gu/1.0.1/build/core/rtw_cmd.o
  CC [M]  /var/lib/dkms/8188gu/1.0.1/build/core/rtw_security.o
  CC [M]  /var/lib/dkms/8188gu/1.0.1/build/core/rtw_debug.o
  CC [M]  /var/lib/dkms/8188gu/1.0.1/build/core/rtw_io.o
  CC [M]  /var/lib/dkms/8188gu/1.0.1/build/core/rtw_ioctl_query.o
  CC [M]  /var/lib/dkms/8188gu/1.0.1/build/core/rtw_ioctl_set.o
  CC [M]  /var/lib/dkms/8188gu/1.0.1/build/core/rtw_ieee80211.o
  CC [M]  /var/lib/dkms/8188gu/1.0.1/build/core/rtw_mlme.o
  CC [M]  /var/lib/dkms/8188gu/1.0.1/build/core/rtw_mlme_ext.o
  CC [M]  /var/lib/dkms/8188gu/1.0.1/build/core/rtw_mi.o
  CC [M]  /var/lib/dkms/8188gu/1.0.1/build/core/rtw_wlan_util.o
  CC [M]  /var/lib/dkms/8188gu/1.0.1/build/core/rtw_vht.o
  CC [M]  /var/lib/dkms/8188gu/1.0.1/build/core/rtw_pwrctrl.o
  CC [M]  /var/lib/dkms/8188gu/1.0.1/build/core/rtw_rf.o
  CC [M]  /var/lib/dkms/8188gu/1.0.1/build/core/rtw_recv.o
  CC [M]  /var/lib/dkms/8188gu/1.0.1/build/core/rtw_sta_mgt.o
  CC [M]  /var/lib/dkms/8188gu/1.0.1/build/core/rtw_ap.o
  CC [M]  /var/lib/dkms/8188gu/1.0.1/build/core/rtw_xmit.o
  CC [M]  /var/lib/dkms/8188gu/1.0.1/build/core/rtw_p2p.o
  CC [M]  /var/lib/dkms/8188gu/1.0.1/build/core/rtw_rson.o
  CC [M]  /var/lib/dkms/8188gu/1.0.1/build/core/rtw_tdls.o
  CC [M]  /var/lib/dkms/8188gu/1.0.1/build/core/rtw_br_ext.o
  CC [M]  /var/lib/dkms/8188gu/1.0.1/build/core/rtw_iol.o
  CC [M]  /var/lib/dkms/8188gu/1.0.1/build/core/rtw_sreset.o
  CC [M]  /var/lib/dkms/8188gu/1.0.1/build/core/rtw_btcoex_wifionly.o
  CC [M]  /var/lib/dkms/8188gu/1.0.1/build/core/rtw_btcoex.o
  CC [M]  /var/lib/dkms/8188gu/1.0.1/build/core/rtw_beamforming.o
  CC [M]  /var/lib/dkms/8188gu/1.0.1/build/core/rtw_odm.o
  CC [M]  /var/lib/dkms/8188gu/1.0.1/build/core/efuse/rtw_efuse.o
  CC [M]  /var/lib/dkms/8188gu/1.0.1/build/os_dep/osdep_service.o
  CC [M]  /var/lib/dkms/8188gu/1.0.1/build/os_dep/linux/os_intfs.o
  CC [M]  /var/lib/dkms/8188gu/1.0.1/build/os_dep/linux/usb_intf.o
/var/lib/dkms/8188gu/1.0.1/build/core/efuse/rtw_efuse.c: In function ‘rtw_efuse_analyze’:
/var/lib/dkms/8188gu/1.0.1/build/core/efuse/rtw_efuse.c:713:17: warning: this ‘if’ clause does not guard... [-Wmisleading-indentation]
  713 |                 if (i % 16 == 0)
      |                 ^~
In file included from /var/lib/dkms/8188gu/1.0.1/build/include/drv_types.h:60,
                 from /var/lib/dkms/8188gu/1.0.1/build/core/efuse/rtw_efuse.c:17:
/var/lib/dkms/8188gu/1.0.1/build/include/rtw_debug.h:292:9: note: ...this statement, but the latter is misleadingly indented as if it were guarded by the ‘if’
  292 |         do {\
      |         ^~
/var/lib/dkms/8188gu/1.0.1/build/core/efuse/rtw_efuse.c:715:25: note: in expansion of macro ‘_RTW_PRINT_SEL’
  715 |                         _RTW_PRINT_SEL(RTW_DBGDUMP, "%02X%s"
      |                         ^~~~~~~~~~~~~~
/var/lib/dkms/8188gu/1.0.1/build/os_dep/osdep_service.c: In function ‘thread_exit’:
/var/lib/dkms/8188gu/1.0.1/build/os_dep/osdep_service.c:1210:9: error: implicit declaration of function ‘complete_and_exit’ [-Werror=implicit-function-declaration]
 1210 |         complete_and_exit(comp, 0);
      |         ^~~~~~~~~~~~~~~~~
/var/lib/dkms/8188gu/1.0.1/build/os_dep/osdep_service.c: In function ‘isFileReadable’:
/var/lib/dkms/8188gu/1.0.1/build/os_dep/osdep_service.c:2085:9: error: unknown type name ‘mm_segment_t’
 2085 |         mm_segment_t oldfs;
      |         ^~~~~~~~~~~~
/var/lib/dkms/8188gu/1.0.1/build/os_dep/osdep_service.c: In function ‘retriveFromFile’:
/var/lib/dkms/8188gu/1.0.1/build/os_dep/osdep_service.c:2125:9: error: unknown type name ‘mm_segment_t’
 2125 |         mm_segment_t oldfs;
      |         ^~~~~~~~~~~~
/var/lib/dkms/8188gu/1.0.1/build/os_dep/osdep_service.c: In function ‘storeToFile’:
/var/lib/dkms/8188gu/1.0.1/build/os_dep/osdep_service.c:2164:9: error: unknown type name ‘mm_segment_t’
 2164 |         mm_segment_t oldfs;
      |         ^~~~~~~~~~~~
/var/lib/dkms/8188gu/1.0.1/build/os_dep/osdep_service.c: In function ‘rtw_change_ifname’:
/var/lib/dkms/8188gu/1.0.1/build/os_dep/osdep_service.c:2375:28: warning: passing argument 1 of ‘_rtw_memcpy’ discards ‘const’ qualifier from pointer target type [-Wdiscarded-qualifiers]
 2375 |         _rtw_memcpy(pnetdev->dev_addr, adapter_mac_addr(padapter), ETH_ALEN);
      |                     ~~~~~~~^~~~~~~~~~
/var/lib/dkms/8188gu/1.0.1/build/os_dep/osdep_service.c:915:24: note: expected ‘void *’ but argument is of type ‘const unsigned char *’
  915 | void _rtw_memcpy(void *dst, const void *src, u32 sz)
      |                  ~~~~~~^~~
/var/lib/dkms/8188gu/1.0.1/build/os_dep/linux/os_intfs.c: In function ‘rtw_net_set_mac_address’:
/var/lib/dkms/8188gu/1.0.1/build/os_dep/linux/os_intfs.c:1196:28: warning: passing argument 1 of ‘_rtw_memcpy’ discards ‘const’ qualifier from pointer target type [-Wdiscarded-qualifiers]
 1196 |         _rtw_memcpy(pnetdev->dev_addr, sa->sa_data, ETH_ALEN); /* set mac addr to net_device */
      |                     ~~~~~~~^~~~~~~~~~
In file included from /var/lib/dkms/8188gu/1.0.1/build/include/drv_types.h:27,
                 from /var/lib/dkms/8188gu/1.0.1/build/os_dep/linux/os_intfs.c:17:
/var/lib/dkms/8188gu/1.0.1/build/include/osdep_service.h:290:35: note: expected ‘void *’ but argument is of type ‘const unsigned char *’
  290 | extern void     _rtw_memcpy(void *dec, const void *sour, u32 sz);
      |                             ~~~~~~^~~
/var/lib/dkms/8188gu/1.0.1/build/os_dep/linux/os_intfs.c: In function ‘rtw_os_ndev_register’:
/var/lib/dkms/8188gu/1.0.1/build/os_dep/linux/os_intfs.c:1597:9: error: too many arguments to function ‘netif_napi_add’
 1597 |         netif_napi_add(ndev, &adapter->napi, rtw_recv_napi_poll, RTL_NAPI_WEIGHT);
      |         ^~~~~~~~~~~~~~
In file included from /var/lib/dkms/8188gu/1.0.1/build/include/osdep_service_linux.h:30,
                 from /var/lib/dkms/8188gu/1.0.1/build/include/osdep_service.h:47,
                 from /var/lib/dkms/8188gu/1.0.1/build/include/drv_types.h:27,
                 from /var/lib/dkms/8188gu/1.0.1/build/os_dep/linux/os_intfs.c:17:
./include/linux/netdevice.h:2639:1: note: declared here
 2639 | netif_napi_add(struct net_device *dev, struct napi_struct *napi,
      | ^~~~~~~~~~~~~~
/var/lib/dkms/8188gu/1.0.1/build/os_dep/linux/os_intfs.c:1611:25: warning: passing argument 1 of ‘_rtw_memcpy’ discards ‘const’ qualifier from pointer target type [-Wdiscarded-qualifiers]
 1611 |         _rtw_memcpy(ndev->dev_addr, adapter_mac_addr(adapter), ETH_ALEN);
      |                     ~~~~^~~~~~~~~~
In file included from /var/lib/dkms/8188gu/1.0.1/build/include/drv_types.h:27,
                 from /var/lib/dkms/8188gu/1.0.1/build/os_dep/linux/os_intfs.c:17:
/var/lib/dkms/8188gu/1.0.1/build/include/osdep_service.h:290:35: note: expected ‘void *’ but argument is of type ‘const unsigned char *’
  290 | extern void     _rtw_memcpy(void *dec, const void *sour, u32 sz);
      |                             ~~~~~~^~~
/var/lib/dkms/8188gu/1.0.1/build/os_dep/osdep_service.c: In function ‘rtw_random32’:
/var/lib/dkms/8188gu/1.0.1/build/os_dep/osdep_service.c:2499:16: error: implicit declaration of function ‘prandom_u32’; did you mean ‘get_random_u32’? [-Werror=implicit-function-declaration]
 2499 |         return prandom_u32();
      |                ^~~~~~~~~~~
      |                get_random_u32
make[3]: *** [scripts/Makefile.build:243: /var/lib/dkms/8188gu/1.0.1/build/os_dep/linux/os_intfs.o] Error 1
make[3]: *** Waiting for unfinished jobs....
cc1: some warnings being treated as errors
make[3]: *** [scripts/Makefile.build:243: /var/lib/dkms/8188gu/1.0.1/build/os_dep/osdep_service.o] Error 1
make[2]: *** [/usr/src/linux-headers-6.5.11-x64v3-xanmod1/Makefile:2189: /var/lib/dkms/8188gu/1.0.1/build] Error 2
make[1]: *** [Makefile:234: __sub-make] Error 2
make[1]: Leaving directory '/usr/src/linux-headers-6.5.11-x64v3-xanmod1'
make: *** [Makefile:1894: modules] Error 2

