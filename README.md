# awningcontrol
ESPHome configuration and hardware to automate a retractable awning

Based on [ESPHome](https://esphome.io/), designed to integrate with [Home Assistant](https://www.home-assistant.io/).

The current hardware is a functional prototype, but the packaging is ugly and not durable.

[Video](https://youtu.be/Huf7AvCcUww)

**Hardware Used:**
- [Beauty-Mark 12' Manual Retractable Awning](https://www.homedepot.com/p/Beauty-Mark-12-ft-California-DX-Model-Manual-Retractable-Awning-120-in-Projection-in-Tan-White-CAM12-DX-TW/205888522)
- [Milwaukee 12V cordless angle drill](https://www.amazon.com/Bare-Tool-Milwaukee-2415-20-12-Volt-Cordless/dp/B002SQK996)
- [Robot Power Simple-H](http://www.robotpower.com/products/simple-h_info.html)
- [Wemos D1 Mini](https://www.aliexpress.com/item/4000447444004.html?spm=2114.12010612.8148356.7.207b717duyb5pR)
- [12V 30A Power Supply](https://www.aliexpress.com/item/4001041355095.html?spm=a2g0o.cart.0.0.73be3c00i4qFup&mp=1)
- [Single relay module](https://www.aliexpress.com/item/33058192089.html?spm=a2g0o.productlist.0.0.567b77528wt3ly&algo_pvid=5405e8eb-005f-4661-aa5f-649459a72042&algo_expid=5405e8eb-005f-4661-aa5f-649459a72042-48&btsid=0bb0623c16030491096784621e6fe7&ws_ab_test=searchweb0_0,searchweb201602_,searchweb201603_)
- [Adjustable DC power converter](https://www.aliexpress.com/item/32727955770.html?spm=a2g0o.productlist.0.0.21281b4dInFxpQ&algo_pvid=427e732f-c5a9-49b0-8cd6-e2b67c2cedb6&algo_expid=427e732f-c5a9-49b0-8cd6-e2b67c2cedb6-18&btsid=0bb0623a16030491639468880ef306&ws_ab_test=searchweb0_0,searchweb201602_,searchweb201603_)
- [Gikfun PCB](https://smile.amazon.com/Gikfun-Solder-able-Breadboard-Plated-Arduino/dp/B071R3BFNL/ref=sr_1_2?dchild=1&keywords=gikfun+pcb&qid=1603049250&sr=8-2)
- [MCP 23008](https://www.adafruit.com/product/593)
- [Door contact sensors](https://smile.amazon.com/BNYZWOT-Surface-Contact-Sensor-Magnetic/dp/B07VNY4TCS/ref=sr_1_12_sspa?dchild=1&keywords=magnetic+reed+switch&qid=1603049447&sr=8-12-spons&psc=1&spLa=ZW5jcnlwdGVkUXVhbGlmaWVyPUExOE5FRlRBSEZNV0dCJmVuY3J5cHRlZElkPUEwNDk4OTkzOFJQWUcwVUlYVjEmZW5jcnlwdGVkQWRJZD1BMDcxOTc1OTNNQzRaMlhJUjE0VVEmd2lkZ2V0TmFtZT1zcF9tdGYmYWN0aW9uPWNsaWNrUmVkaXJlY3QmZG9Ob3RMb2dDbGljaz10cnVl)
- Generic doorbell switches, with the bulb cut off
- Misc hardware
- Misc breadboard components
