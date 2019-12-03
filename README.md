# Case Study of Chrome Sandbox Escape
A Collection of Chrome Sandbox Escape POCs/Exploits for learning.

## Permission Allowed Issues  

Issue | Type | Summary | Label | Reporter | Links
-- | -- | -- | -- | -- | --
[crbug-997190](https://crbug.com/997190) | Patch POC | UAF in MediaSession (Android) | CVE-2019-5876, M-76, reward-20000 | [Man Yue Mo](https://crbug.com/?can=1&q=man%20yue%20mo) | -
[crbug-993223](https://crbug.com/993223) | HTML POC | UAF in Payment | M-77, reward-5000 | [chromium.khalil](https://crbug.com/?q=reporter%3Achromium.khalil%40gmail.com&can=1) | [crbug-992285](https://crbug.com/992285)
[crbug-987261](https://crbug.com/987261) | HTML POC | Logic Bug in WebUI | - | [Vladimir Metnew](https://crbug.com/?q=reporter%3Avladimirmetnew%40gmail.com%20OR%20Vladimir%20Metnew&can=1) | -
[crbug-984521](https://crbug.com/984521) | MojoJS POC | UAF in IndexedDB IndexedDBConnection::Close | M-76 | [Mark Brand](https://crbug.com/?q=reporter%3Amarkbrand%40google.com&can=1) | [p0-1912](https://crbug.com/project-zero/1912) 
[crbug-981873](https://crbug.com/981873) | MojoJS POC | UAF in IndexedDB ~LevelDBIteratorImpl | M-76 | [Mark Brand](https://crbug.com/?q=reporter%3Amarkbrand%40google.com&can=1) | [p0-1904](https://crbug.com/project-zero/1904) 
[crbug-977462](https://crbug.com/977462) | MojoJS POC | UAF in OfflinePage | CVE-2019-5850, M-75, reward-10000 | [Brendon Tiszka](https://crbug.com/?q=reporter%3Abtiszka%40gmail.com&can=1) | - 
[crbug-972239](https://crbug.com/972239#c26) | MojoJS POC | UAF in IndexedDB IndexedDBTransaction::Abort | M-76 | [Mark Brand](https://crbug.com/?q=reporter%3Amarkbrand%40google.com&can=1) | - 
[crbug-971702](https://crbug.com/971702) | HTML POC | UAF in chrome!content::Portal::Activate | M-76, reward-8000 | [Pawel Wylecial](https://crbug.com/?q=reporter%3Apawel%40blackowlsec.com&can=1) | -
[crbug-966784](https://crbug.com/966784) | MojoJS POC | UAF in IndexedDB AbortAllTransactions | M-76, reward-5000 | [cdsrc2016](https://crbug.com/?q=reporter%3Acdsrc2016%40gmail.com&can=1) | -
[crbug-966762](https://crbug.com/966762) | MojoJS POC | UAF in IndexedDB RequestComplete 2 | M-76, reward-10500 | [cdsrc2016](https://crbug.com/?q=reporter%3Acdsrc2016%40gmail.com&can=1) | -
[crbug-962500](https://crbug.com/962500) | HTML POC | Logic Bug in WebUI | reward-10000 | [Michal Bentkowski](https://crbug.com/?q=Michal%20Bentkowski&can=1) | -
[crbug-960484](https://crbug.com/960484) | MojoJS POC | UAF in SerialChooserController | M-75 | [jonorman](https://crbug.com/?q=reporter%3Ajonorman%40microsoft.com&can=1) | -
[crbug-956597](https://crbug.com/956597) | HTML POC | UAF in ServiceWorkerPaymentInstrument | M-75, M-76, reward-5000 | [leecraso](https://crbug.com/?q=reporter%3Aleecraso%40gmail.com&can=1), [Guang Gong](https://crbug.com/?q=Guang%20Gong%20OR%20reporter%3Ahigongguang%40gmail.com&can=1) | - 
[crbug-948172](https://crbug.com/948172) | Full Chain Exploit | Logic Bug in PDF plugin using Pepper Socket API | M-75 | [Sergey Glazunov](https://crbug.com/?q=reporter%3Aserg.glazunov%40gmail.com%2Cglazunov%40google.com&can=1) | [Full Chain Exploit](https://bugs.chromium.org/p/project-zero/issues/attachment?aid=402215&signed_aid=uJieSMQe19F_G21FV0OaCg==), [crbug-950005](https://crbug.com/950005), [p0-1813](https://crbug.com/project-zero/1813), [p0-1817](https://crbug.com/project-zero/1817)
[crbug-945370](https://crbug.com/945370) | HTML POC | UAF in IndexedDB DeleteRequest | M-75, reward-8000 | [cdsrc2016](https://crbug.com/?q=reporter%3Acdsrc2016%40gmail.com&can=1) | -
[crbug-942898](https://crbug.com/942898) | HTML POC | UAF in  IndexedDB RequestComplete | M-74, reward-10000 | [cdsrc2016](https://crbug.com/?q=reporter%3Acdsrc2016%40gmail.com&can=1) | -
[crbug-941746](https://crbug.com/941746) | Full Chain WriteUp | UAF in IndexedDBDatabase (Pwnium 2019) | CVE-2019-5826, M-73 | [Gengming Liu](https://crbug.com/?q=l.dmxcsnsbh%40gmail.com&can=1) | [BlackhatUSA2019](https://i.blackhat.com/USA-19/Wednesday/us-19-Feng-The-Most-Secure-Browser-Pwning-Chrome-From-2016-To-2019.pdf), [POC2019](http://www.powerofcommunity.net/poc2019/Gengming.pdf)
[crbug-941008](https://crbug.com/941008) | MojoJS POC | UAF in FileChooserImpl | CVE-2019-5809, M-73, M-74, M-75 | [Mark Brand](https://crbug.com/?q=reporter%3Amarkbrand%40google.com&can=1) | [p0-1803](https://crbug.com/project-zero/1803)
[crbug-925864](https://crbug.com/925864) | MojoJS POC | UAF in FileSystemOperationRunner | CVE-2019-5788, M-73 | [Mark Brand](https://crbug.com/?q=reporter%3Amarkbrand%40google.com&can=1) | [p0-1767](https://crbug.com/project-zero/1767) 
[crbug-922677](https://crbug.com/922677) | Full Chain Exploit | UAF in FileWriterImpl | M-71 | [Mark Brand](https://crbug.com/?q=reporter%3Amarkbrand%40google.com&can=1) | [Full Chain Exploit](https://bugs.chromium.org/p/project-zero/issues/attachment?aid=388589&signed_aid=l6i6pjLBlXcNkkKWiDvd9A==), [p0-1755](https://crbug.com/project-zero/1755), [P0 Blog](https://googleprojectzero.blogspot.com/2019/04/virtually-unlimited-memory-escaping.html)
[crbug-921581](https://crbug.com/921581) | MojoJS POC | UAF in WebMIDI | CVE-2019-5789, M-73 | [Mark Brand](https://crbug.com/?q=reporter%3Amarkbrand%40google.com&can=1) | [p0-1754](https://crbug.com/project-zero/1754)
[crbug-916523](https://crbug.com/916523) | MojoJS POC | Double Free in StoragePartitionService | CVE-2019-5797, M-73 | [Mark Brand](https://crbug.com/?q=reporter%3Amarkbrand%40google.com&can=1) | [p0-1744](https://crbug.com/project-zero/1744)
[crbug-916080](https://crbug.com/916080) | MojoJS POC | UAF in P2PSocketDispatcherHost | M-71 | [Mark Brand](https://crbug.com/?q=reporter%3Amarkbrand%40google.com&can=1) | [p0-1743](https://crbug.com/project-zero/1743)
[crbug-912947](https://crbug.com/912947) | MojoJS POC | UAF in PaymentRequest | M-72 | [Mark Brand](https://crbug.com/?q=reporter%3Amarkbrand%40google.com&can=1) | [p0-1735](https://crbug.com/project-zero/1735)
[crbug-912520](https://crbug.com/912520) | MojoJS POC | UAF in MediaStream | M-72 | [Mark Brand](https://crbug.com/?q=reporter%3Amarkbrand%40google.com&can=1) | [p0-1730](https://crbug.com/project-zero/1730)
[crbug-888926](https://crbug.com/888926) | Full Chain Exploit | UaF in Appcache (Hack2Win 2018) | CVE-2018-17462, M-69, M-70 | [Ned Williamson](https://crbug.com/?q=reporter%3Anedwilliamson%40gmail.com&can=1), [Niklas Baumstark](https://twitter.com/_niklasb) | [POC2018](http://www.powerofcommunity.net/poc2018/ned.pdf), [35C3](https://www.youtube.com/watch?v=39yPeiY808w), [Github](https://github.com/niklasb/hack2win-chrome), [OffensiveCon2019](http://paper.vulsee.com/OffensiveCon2019/IPC%20You%20Outside%20the%20Sandbox%20-%20One%20bug%20to%20Rule%20the%20Chrome%20Broker/chrome_ipc_exploitation_offensivecon19.pdf)
[crbug-888366](https://crbug.com/888366) | HTML POC |  UAF in WebAudio | M-70, M-71, reward-5500 | [cdsrc2016](https://crbug.com/?q=reporter%3Acdsrc2016%40gmail.com&can=1) | -
[crbug-877182](https://crbug.com/877182) | Patch POC | OOB Read/Write in Mojo DataPipe deserialization | CVE-2018-16068, M-68 | [Mark Brand](https://crbug.com/?q=reporter%3Amarkbrand%40google.com&can=1) | -
[crbug-842990](https://crbug.com/842990) | Patch POC | UAF in IndexedDB Connection | CVE-2018-6127, M-66, reward-10000 | [Looben Yang](https://crbug.com/?q=reporter%3Aloobenyang%40gmail.com&can=1) | -
[crbug-835887](https://crbug.com/835887) | Full Chain Exploit | Logic Bug in "filesystem:" Scheme URL, PDF Plugin, Extension, WebUI  | M-67, M-68, reward-40633.7 | [Sergey Glazunov](https://crbug.com/?q=reporter%3Aserg.glazunov%40gmail.com%2Cglazunov%40google.com&can=1) | [crbug-836362](https://crbug.com/836362), [crbug-836859](https://crbug.com/836859), [crbug-836858](https://crbug.com/836858), [crbug-840857](https://crbug.com/840857)
[crbug-831963](https://crbug.com/831963) | Patch POC | UAF in In-memory Cache 2 | CVE-2018-6118, M-66, M-67, M-68, reward-10500 | [Ned Williamson](https://crbug.com/?q=reporter%3Anedwilliamson%40gmail.com&can=1) | - 
[crbug-827492](https://crbug.com/827492) | Patch POC | UAF in In-memory Cache | CVE-2018-6086, M-66, reward-10500 | [Ned Williamson](https://crbug.com/?q=reporter%3Anedwilliamson%40gmail.com&can=1) | -
[crbug-826626](https://crbug.com/826626) | Patch POC | UAF in Blockfile Media Cache | CVE-2018-6085, M-66, reward-10000 | [Ned Williamson](https://crbug.com/?q=reporter%3Anedwilliamson%40gmail.com&can=1) | -
[crbug-794969](https://crbug.com/794969) | Patch POC | OOB Read in deserializing Mojo "Event" messages | M-65 | [Gal Beniamini](https://crbug.com/?q=reporter%3Alaginimaineb%40google.com&can=1) | -
[crbug-791003](https://crbug.com/791003) | Patch POC | Logic Bug in "catalog" service | CVE-2018-6055, M-65 | [Gal Beniamini](https://crbug.com/?q=reporter%3Alaginimaineb%40google.com&can=1) | -
[crbug-780708](https://crbug.com/780708) | WriteUp | Logic Bug in Android “googlechrome:” Scheme URL (Mobile Pwn2Own 2017) | M-65 | ? | -
[crbug-779314](https://crbug.com/779314) | Patch POC |  OOB Read in Blob | CVE-2017-15416, M-65, reward-2500 | [Ned Williamson](https://crbug.com/?q=reporter%3Anedwilliamson%40gmail.com&can=1) | -
[crbug-778505](https://crbug.com/778505) | Patch POC | OOB Write in QUIC | CVE-2017-15407, M-65, reward-10500 | [Ned Williamson](https://crbug.com/?q=reporter%3Anedwilliamson%40gmail.com&can=1) | -
[crbug-777728](https://crbug.com/777728) | Patch POC | Stack Overflow in QUIC | CVE-2017-15398, M-76, reward-10500 | [Ned Williamson](https://crbug.com/?q=reporter%3Anedwilliamson%40gmail.com&can=1) | -
[crbug-728887](https://crbug.com/728887) | Patch POC | UAF in IndexedDB OpenCursor | CVE-2017-5091, M-60, reward-10000 | [Ned Williamson](https://crbug.com/?q=reporter%3Anedwilliamson%40gmail.com&can=1) | -
[crbug-725032](https://crbug.com/725032) | Patch POC | UAF in IndexedDB Transactions | CVE-2017-5087, M-58, M-60, M-61, reward-10500 | [Ned Williamson](https://crbug.com/?q=reporter%3Anedwilliamson%40gmail.com&can=1) | - 
[crbug-698622](https://crbug.com/698622) | HTML POC | UAF in Printing | CVE-2017-5055, M-57, M-58, reward-9337 | [Wadih Matar](https://crbug.com/?q=reporter%3Awadih.matar%40gmail.com&can=1) | - 
[crbug-664551](https://crbug.com/664551) | Full Chain Exploit | Logic Bug in Android Play Store (PWNFest 2016) | M-55 | [Guang Gong](https://crbug.com/?q=Guang%20Gong%20OR%20reporter%3Ahigongguang%40gmail.com&can=1) | [Github](https://github.com/secmob/pwnfest2016)
[crbug-659489](https://crbug.com/659489) | Full Chain WriteUp | Logic Bug in Android "content:" Scheme URL, File Download (Mobile Pwn2Own 2016) | M-54 | Robert Miller, Georgi Geshev | [crbug-659492](https://crbug.com/659492), [WriteUp](https://bugs.chromium.org/p/chromium/issues/attachment?aid=256529&signed_aid=SVqnSnUXkCxCd2kvi4taPQ==)
[crbug-659474](https://crbug.com/659474) | Full Chain WriteUp | Logic Bug in Android "intent:" Scheme URL, IPC (Mobile Pwn2Own 2016) | M-54 | Qidan He, [Gengming Liu](https://crbug.com/?q=l.dmxcsnsbh%40gmail.com&can=1) | [crbug-659477](https://crbug.com/659477), [WriteUp](https://bugs.chromium.org/p/chromium/issues/attachment?aid=256510&signed_aid=aCap7zbHUwwvY27EqLSDQw==), [CSW2017](https://cansecwest.com/slides/2017/CSW2017_QidanHe-GengmingLiu_Pwning_Nexus_of_Every_Pixel.pdf) 
[crbug-610600](https://crbug.com/610600) | Frida Exploit | Logic Bug in PPAPI/Flash Broker | CVE-2016-1706, M-52, reward-15000 | [Pinkie Pie](https://crbug.com/?q=Pinkie%20Pie%20OR%20reporter%3A70696e6b6965706965%40gmail.com&can=1) | -
[crbug-595834](https://crbug.com/595834) | Full Chain Exploit | Logic Bug in GPU, WebUI, SmartScreen (Pwn2Own 2016) | - | [JungHoon Lee](https://crbug.com/?q=reporter%3Alkhz49%40gmail.com,lokihardt%40google.com&can=1) | [crbug-595844](https://crbug.com/595844), [crbug-596862](https://crbug.com/596862), [WriteUp](https://bugs.chromium.org/p/chromium/issues/attachment?aid=227798&signed_aid=BJUc8JNFcIyk7erbvIE1EQ==)
[crbug-590284](https://crbug.com/590284) | Patch POC | UAF in RenderWidgetHostImpl | CVE-2016-1647, M-49, M-50, reward-10500 | [gzobqq](https://crbug.com/?q=reporter%3Agzobqq%40gmail.com&can=1) | - 
[crbug-564501](https://crbug.com/564501) | Patch POC | UAF in MidiHost | M-48 | [Oliver Chang](https://crbug.com/?q=reporter%3Aochang%40chromium.org%2Cochang%40google.com&can=1) | -  
[crbug-558589](https://crbug.com/558589) | Webserver POC | UAF in AppCacheUpdateJob | CVE-2015-6765, M-47, M-48, reward-10000 | [gzobqq](https://crbug.com/?q=reporter%3Agzobqq%40gmail.com&can=1) | -
[crbug-554946](https://crbug.com/554946) | Full Chain WriteUp | Logic Bug in Android Play Store (Mobile Pwn2Own 2015) | CVE-2015-6764, M-47, reward-7500 | [Guang Gong](https://crbug.com/?q=Guang%20Gong%20OR%20reporter%3Ahigongguang%40gmail.com&can=1) | [crbug-554518](https://crbug.com/554518), [Github](https://github.com/secmob/cansecwest2016)
[crbug-554908](https://crbug.com/554908) | Patch, Webserver POC | UAF in AppCacheDispatcherHost | CVE-2015-6767, M-47, M-48, reward-10000 | [gzobqq](https://crbug.com/?q=reporter%3Agzobqq%40gmail.com&can=1) | -
[crbug-551044](https://crbug.com/551044) | Patch, Webserver POC | Memory Corruption in AppCacheUpdateJob | CVE-2015-6766, M-47, M-48, reward-11337 | [gzobqq](https://crbug.com/?q=reporter%3Agzobqq%40gmail.com&can=1) | -
[crbug-484270](https://crbug.com/484270) | Webserver POC | Heap Overflow in CertificateResourceHandler | M-43 | [Mark Brand](https://crbug.com/?q=reporter%3Amarkbrand%40google.com&can=1) | -
[crbug-416449](https://crbug.com/416449) | Full Chain Exploit | OOB Write in P2PHostMsg_Send IPC | CVE-2014-3188, M-38, reward-27634 | [Jüri Aedla](https://crbug.com/?q=reporter%3Aaedla%40chromium.org&can=1) | [crbug-416528](https://crbug.com/416528), [WriteUp](https://bugs.chromium.org/p/chromium/issues/attachment?aid=63680&signed_aid=Mz6eypMLGiZqfxRiO-8Agw==)
[crbug-386988](https://crbug.com/386988) | Full Chain Exploit | Logic Bugs in Extension and WebUI | reward-30000 | [JungHoon Lee](https://crbug.com/?q=reporter%3Alkhz49%40gmail.com,lokihardt%40google.com&can=1) | [crbug-367567](https://crbug.com/367567), [crbug-387033](https://crbug.com/387033), [crbug-387037](https://crbug.com/387037), [crbug-50275](https://crbug.com/50275)
[crbug-352369](https://crbug.com/352369) | Full Chain Exploit | Memory Corruption in Clipboard IPC (Pwn2Own 2014) | M-33 | [VUPEN](https://crbug.com/?q=VUPEN&can=1) | [crbug-352395](https://crbug.com/352395), [Google Presentation](https://docs.google.com/presentation/d/1c90yZXNHs7w8oi7uXveEOCx5-8O_NZIxolEKalscuAQ)
[crbug-319117](https://crbug.com/319117) | Full Chain Exploit | Memory Corruption in Clipboard IPC (Mobile Pwn2Own 2013) | CVE-2013-6632, M-31, M-32 | [Pinkie Pie](https://crbug.com/?q=Pinkie%20Pie%20OR%20reporter%3A70696e6b6965706965%40gmail.com&can=1) | [crbug-319125](https://crbug.com/319125), [WriteUp](https://docs.google.com/document/d/1tHElG04AJR5OR2Ex-m_Jsmc8S5fAbRB3s4RmTG_PFnw/edit)

* It only includes Chrome Browser own Bugs like IPC(Mojo), WebAPI, WebUI, Extension.. (Not included using Kernel Bugs like [MWRLab's Pwn2own 2013 Exploit](https://labs.mwrinfosecurity.com/assets/BlogFiles/MWR-PolishingChrome-NSC-slides.pdf), [lokihardt's Pwn2Own 2015 Exploit](https://crbug.com/468933))  
* It only includes Security Bugs that published POC/Exploit from [crbug.com](https://crbug.com).  
* It was searched by hands, so there may be something missing.  


## Permission Denied Issues  

Issue Number | Patch Version | Summary | Reporter 
-- | -- | -- | -- 
[crbug-1024121](https://crbug.com/1024121) | [78.0.3904.108](https://chromereleases.googleblog.com/2019/11/stable-channel-update-for-desktop_18.html) | [$TBD] High CVE-2019-13723: Use-after-free in Bluetooth (Not Sure SBX) | Yuxiang Li
[crbug-1024116](https://crbug.com/1024116) | [78.0.3904.108](https://chromereleases.googleblog.com/2019/11/stable-channel-update-for-desktop_18.html) | [$TBD] High CVE-2019-13724: Out-of-bounds access in Bluetooth (Not Sure SBX) | Yuxiang Li
[crbug-1019226](https://crbug.com/1019226) | [78.0.3904.87](https://chromereleases.googleblog.com/2019/10/stable-channel-update-for-desktop_31.html) | [$TBD] High CVE-2019-13720: Use-after-free in audio (Not Sure SBX) | Anton Ivanov, Alexey Kulaev
[crbug-1001503](https://crbug.com/1001503) | [78.0.3904.70](http://chromereleases.googleblog.com/2019/10/stable-channel-update-for-desktop_22.html) | [$20000] High CVE-2019-13699: Use-after-free in media | Man Yue Mo
[crbug-1005753](https://crbug.com/1005753) | [77.0.3865.120](http://chromereleases.googleblog.com/2019/10/stable-channel-update-for-desktop.html) | [$20500] High CVE-2019-13693: Use-after-free in IndexedDB |  Guang Gong
[crbug-1004730](https://crbug.com/1004730) | [77.0.3865.120](http://chromereleases.googleblog.com/2019/10/stable-channel-update-for-desktop.html) | [$15000] High CVE-2019-13695: Use-after-free in audio | Man Yue Mo
[crbug-1000934](https://crbug.com/1000934) | [77.0.3865.90](http://chromereleases.googleblog.com/2019/09/stable-channel-update-for-desktop_18.html) | [$TBD] Critical CVE-2019-13685: Use-after-free in UI | Khalil Zhani
[crbug-995964](https://crbug.com/995964) | [77.0.3865.90](http://chromereleases.googleblog.com/2019/09/stable-channel-update-for-desktop_18.html) | [$20000] High CVE-2019-13688: Use-after-free in media | Man Yue Mo
[crbug-998548](https://crbug.com/998548) | [77.0.3865.90](http://chromereleases.googleblog.com/2019/09/stable-channel-update-for-desktop_18.html) | [$20000] High CVE-2019-13688: Use-after-free in media | Man Yue Mo
[crbug-1000002](https://crbug.com/1000002) | [77.0.3865.90](http://chromereleases.googleblog.com/2019/09/stable-channel-update-for-desktop_18.html) | [$TBD] High CVE-2019-13686: Use-after-free in offline pages | Brendon Tiszka
[crbug-999311](https://crbug.com/999311) | [77.0.3865.75](http://chromereleases.googleblog.com/2019/09/stable-channel-update-for-desktop.html) | [$30000] Critical CVE-2019-5870: Use-after-free in media | Guang Gong
[crbug-989797](https://crbug.com/989797) | [77.0.3865.75](http://chromereleases.googleblog.com/2019/09/stable-channel-update-for-desktop.html) | [$3000] High CVE-2019-5874: External URIs may trigger other browsers | James Lee
[crbug-959438](https://crbug.com/959438) | [76.0.3809.87](http://chromereleases.googleblog.com/2019/07/stable-channel-update-for-desktop_30.html) | [$TBD] High CVE-2019-5859: Some URIs can load alternative browsers | James Lee

* It only includes Permission Denied Issues posted on [Chrome Releases Blog](https://chromereleases.googleblog.com/) (Latest 3 years).
* It was searched by hands, so there may be something missing, too.  

## Chrome Sandbox Internals
* [Stanford seclab - The Security Architecture of the Chromium Browser (2008)](https://seclab.stanford.edu/websec/chromium/chromium-security-architecture.pdf), [PPT](https://pdfs.semanticscholar.org/8a02/1c9c69effbdd159838ac5204d9da4e996f86.pdf)
* [Chromium Docs - Sandbox](https://chromium.googlesource.com/chromium/src/+/master/docs/design/sandbox.md)
* [Chromium Docs - Sandbox FAQ](https://chromium.googlesource.com/chromium/src/+/master/docs/design/sandbox_faq.md)
* [Chromium Docs - WebUI Explainer](https://chromium.googlesource.com/chromium/src/+/master/docs/webui_explainer.md)
* [Chromium Docs - Mojo](https://chromium.googlesource.com/chromium/src/+/master/mojo/README.md)
* [Chromium Docs - Intro to Mojo & Services](https://chromium.googlesource.com/chromium/src/+/master/docs/mojo_and_services.md)
* [Chromium Docs - Mojo Basics](https://chromium.googlesource.com/chromium/src/+/master/mojo/docs/basics.md)
* [Chromium Docs - Mojo IDL](https://chromium.googlesource.com/chromium/src/+/master/mojo/public/tools/bindings/README.md)
* [Chromium Docs - Mojo C System API](https://chromium.googlesource.com/chromium/src/+/master/mojo/public/c/system/README.md)
* [Chromium Docs - Mojo C++ Bindings API](https://chromium.googlesource.com/chromium/src/+/master/mojo/public/cpp/bindings/README.md)
* [Chromium Docs - Mojo JavaScript Bindings API](https://chromium.googlesource.com/chromium/src/+/master/mojo/public/js/README.md)
* [Chromium Docs - Mojo “Style” Guide](https://chromium.googlesource.com/chromium/src/+/master/docs/security/mojo.md)
* [Chromium Docs - Converting Legacy IPC to Mojo](https://chromium.googlesource.com/chromium/src/+/master/docs/mojo_ipc_conversion.md)
* [Chromium Docs - The Service Manager & Services](https://chromium.googlesource.com/chromium/src/+/master/services/service_manager/README.md)
* [Chromium Docs - Service Development Guidelines](https://chromium.googlesource.com/chromium/src/+/master/services/README.md)
* [Chromium Docs - Servicifying Chromium Features](https://chromium.googlesource.com/chromium/src/+/master/docs/servicification.md)
* [Google Docs - Chrome Service Model](https://docs.google.com/document/d/15I7sQyQo6zsqXVNAlVd520tdGaS8FCicZHrN0yRu-oU)
* [Google Docs - Mojo Tutorial](https://docs.google.com/document/d/1mufrtxTk8w9qa3jcnlgqsYkWlyhwEpc7aWNaSOks7ug)
* [Google Docs - Blob Servicification](https://docs.google.com/document/d/1_ROmusFvd8ATwIZa29-P6Ls5yyLjfld0KvKchVfA84Y)
* [Google Docs - Device Service in Chromium](https://docs.google.com/document/d/1k0caAXgSchvXzkzwZYxudZRNpwtFWUkgvQInlw-fKuY)
* [Google Docs - Device Service: Technical Approach](https://docs.google.com/document/d/1_1Vt4ShJCiM3fin-leaZx00-FoIPisOr8kwAKsg-Des)
* [Google Docs - Device Service: Extraction from the Content Layer](https://docs.google.com/document/d/1UVFBfz8XajKwFYUtcjvPTOp4gEFRgCZ_hqz_gDO8LBo/edit#heading=h.z3q403opm2na)
* [Google Docs - Identity Service in Chromium](https://docs.google.com/document/d/1hVZDURLaL6ZwzEw8kYwzCqA8EpJmCIf0ItU7voMfTWg/)
* [Google Docs - Identity Service: Technical Approach](https://docs.google.com/document/d/1EPLEJTZewjiShBemNP5Zyk3b_9sgdbrZlXn7j1fubW0)
* [Google Docs - Serving the Identity Extension API via the Identity Service](https://docs.google.com/document/d/1XUNE30A-aEyg1_Sbe6kFiDCWKXnz5s5vQDsd6ymIb-0)
* [Google Docs - Network Service in Chrome](https://docs.google.com/document/d/1wAHLw9h7gGuqJNCgG1mP1BmLtCGfZ2pys-PdZQ1vg7M)
* [Google Docs - Network Service Conversion Cheat Sheet](https://docs.google.com/document/d/1OyBYvN0dwvpqfSZBdsfZ29iTFqGnVS2sdiPV14Z-Fto)
* [Google Docs - Error Handling in Network Service](https://docs.google.com/document/d/1CZMPzQrmGvjz3O7RC-MR56fStLJj1RjdKNkFItzJs0Y)
* [Google Docs - Restartable Network Service](https://docs.google.com/document/d/14dQpOaPgnpX0TZffSGeYyE-dUS93HY06VKGWUGZHtrY/)
* [Google Docs - Notes on Mojo-ifying Safe Browsing's URL Check](https://docs.google.com/document/d/1H5_0CUVvX_R34RwuTt_iUun-px7QMnLQh8toEWcwCQk)
* [Google Docs - Per-Profile Mojo Services](https://docs.google.com/document/d/1Fj013SXClTzk4Yfq2eoL9OkKfN0h-GLXPAokCXFkcTY)
* [Google Docs - Pref Service](https://docs.google.com/document/d/1JU8QUWxMEXWMqgkvFUumKSxr7Z-nfq0YvreSJTkMVmU)
* [Google Drawing - Chrome Security Architecture](https://docs.google.com/drawings/d/1TuECFL9K7J5q5UePJLC-YH3satvb1RrjLRH-tW_VKeE)
* [Google PDF - bpf_dsl: A domain-specific language for seccomp-bpf policies](https://drive.google.com/file/d/0B9LSc_-kpOQPVHhvcVBza3NWR0k)
* [The Chromium Projects - OSX Sandboxing Design](http://dev.chromium.org/developers/design-documents/sandbox/osx-sandboxing-design)
* [The Chromium Projects - Security Tips for IPC](https://www.chromium.org/Home/chromium-security/education/security-tips-for-ipc)
* [hidd3ncod3s blog - Chrome IPC Internals](https://hiddencodes.wordpress.com/2012/08/07/chrome-ipc-internals-part-i/)

## Other Materials 
* [Blue Forest Security (2019) - Escaping the Chrome Sandbox via an IndexedDB Race Condition](https://labs.bluefrostsecurity.de/blog/2019/08/08/escaping-the-chrome-sandbox-via-an-indexeddb-race-condition/) 
* [Tencent Xuanwu Lab (Blackhat Asia 2019) - Attacking Browser Sandbox: Live Persistently and Prosperously](https://i.blackhat.com/asia-19/Fri-March-29/bh-asia-Ma-Attacking-Browser-Sandbox.pdf)
* [WCTF 2019 - Mojojojo](https://drive.google.com/drive/u/0/folders/1xijouA9fj1YUrY97wyoEQCZ5Q3tRWNOq)  
* [Google CTF 2019 - monochromatic](https://github.com/google/google-ctf/tree/master/2019/quals/sandbox-monochromatic)  
* [Google CTF 2018 - pwn-mojo](https://github.com/google/google-ctf/tree/master/2018/finals/pwn-mojo)  
* [360 Alpha Team (CanSecWest 2018) - Attacks and analysis of the Samsung S8 from Mobile PWN2OWN](https://cansecwest.com/slides/2018/Attacks%20and%20Analysis%20of%20the%20Samsung%20S8%20from%20Mobile%20PWN2OWN%20-%20Guang%20Gong%20and%20Jianjun%20Dai,%20Qihoo%20360.pdf)
* [Microsoft Blog - Browser security beyond sandboxing (2017)](https://www.microsoft.com/security/blog/2017/10/18/browser-security-beyond-sandboxing/?source=mmpc)
* [X41 - Browser Security White Paper (2017)](https://paper.seebug.org/papers/Archive/X41-Browser-Security-White-Paper.pdf)
* [KEEN Team (DEFCON24 2016) - Escaping The Sandbox By Not Breaking It](https://papers.put.as/papers/macosx/2016/sandbox_defcon.pdf)
* [James Forshaw (Troopers 2016) - The Joy of Sandbox Mitigations](https://www.troopers.de/media/filer_public/f6/07/f6076037-85e0-42b7-9a51-507986edafce/the_joy_of_sandbox_mitigations_export.pdf)
* [James Forshaw (Nullcon 2015) - The Windows Sandbox Paradox](https://nullcon.net/website/archives/ppt/goa-15/the-windows-sandbox-paradox.pdf)
* [Guang Gong (BlackHat USA 2015) - Fuzzing Android System Services by Binder Call to Escalate Privilege](https://www.blackhat.com/docs/us-15/materials/us-15-Gong-Fuzzing-Android-System-Services-By-Binder-Call-To-Escalate-Privilege.pdf)
* [A Tale of Two Pwnies (Part 1)](https://blog.chromium.org/2012/05/tale-of-two-pwnies-part-1.html)  
* [A Tale Of Two Pwnies (Part 2)](https://blog.chromium.org/2012/06/tale-of-two-pwnies-part-2.html)  

