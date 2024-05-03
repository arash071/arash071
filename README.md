{  
"مسیر": {
    "geoip": {
      "path": "geo-assets\\sagernet-sing-geoip-geoip.db"
    }،
    "ژئوسایت": {
      "path": "geo-assets\\sagernet-sing-geosite-geosite.db"
    }،
    "قوانین": [
      {
        "inbound": "dns-in"،
        "outbound": "dns-out"
      }،
      {
        "پورت": 53،
        "outbound": "dns-out"
      }،
      {
        "clash_mode": "مستقیم"،
        "خروجی": "مستقیم"
      }،
      {
        "clash_mode": "جهانی"،
        "خروجی": "انتخاب"
      }
    ]،
    "auto_detect_interface": درست است،
    "override_android_vpn": درست است
  }،
  "خروجی": [
    {
      "نوع": "انتخاب کننده"،
      "برچسب": "انتخاب"،
      "خروجی": [
        "خودکار"،
        "IP->ایران، یوتیوب:MisaHiro"،
        "IP->Main, Yotube:MisaHiro"
      ]،
      "پیش فرض": "خودکار"
    }،
    {
      "type": "urltest",
      "برچسب": "خودکار"،
      "خروجی": [
        "IP->ایران، یوتیوب:MisaHiro"،
        "IP->Main, Yotube:MisaHiro"
      ]،
      "url": "http://cp.cloudflare.com/"،
      "فاصله": "10m0s"
    }،
    {
      "نوع": "گارد سیم"،
      "tag": "IP->Iran, Yotube:MisaHiro",
      "آدرس محلی": [
        "172.16.0.2/32"،
        "2606:4700:110:8c91:4063:21d0:7dd5:f218/128"
      ]،
      "private_key": "CBVIIWvXdLr4PbSrnm11ZJJ300IiPudRD4R62/IxV1g="،
      "سرور": "188.114.96.233"،
      "server_port": 1018،
      "peer_public_key": "bmXOC+F1FxEMF9dyiK2H5/1SUtzH0JuVo51h2wPfgyo="،
      "رزرو شده": "AAAA"،
      "mtu": 1280،
      "fake_packets": "5-10"
    }،
    {
      "نوع": "گارد سیم"،
      "برچسب": "IP->Main، Yotube:MisaHiro"،
      "دور": "IP->ایران، یوتیوب:MisaHiro"،
      "آدرس محلی": [
        "172.16.0.2/32"،
        "2606:4700:110:8c15:3f90:ad2d:8810:77f3/128"
      ]،
      "private_key": "CCC/TQTc82ub9i8f37Rpix2v425Sv/mxTzvE/iKRMkw="،
      "سرور": "188.114.96.233"،
      "server_port": 1018،
      "peer_public_key": "bmXOC+F1FxEMF9dyiK2H5/1SUtzH0JuVo51h2wPfgyo="،
      "رزرو شده": "AAAA"،
      "mtu": 1280،
      "fake_packets": "5-10"
    }،
    {
      "نوع": "dns"،
      "برچسب": "dns-out"
    }،
    {
      "نوع": "مستقیم"،
      "برچسب": "مستقیم"
    }،
    {
      "نوع": "مستقیم"،
      "برچسب": "دور زدن"
    }،
    {
      "type": "block",
      "برچسب": "مسدود کردن"
    }
  ]  
}
