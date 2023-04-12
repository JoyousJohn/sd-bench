# sd-card-tests
H2testw results for obscure or uncommon micro SD card brands. Cards are first assessed by FakeFlashTest. Observed average results sourced from final H2testw speeds when attempting to verify detected card capacity and compared to speeds from manual transfers afterward. Some cards are being tested for long-term endurance use and reliability in continuously recording security cameras.

| Brand | Claimed <br> Size | Designation | Expected | Observed (avg.) | Marketplace | Genuine? | Notes |
| - | - | - | - | - | - | - | - |
| TOPESEL | 64GB | UHS-I <br> C10 | 59.6GB raw <br> >10 MB/s write | 58.6GB usable <br> 12 MB/s write <br> 78 MB/s read | Temu | Yes | Came with adapter. |
| KODAK | 64GB | V30 <br> UHS-III <br> C10 | 59.6GB raw <br> >30 MB/s write | 58.2GB usable <br> 45 MB/s write <br> 84 MB/s read | Temu | Yes | Came with KODAK.ico <br> and autorun.inf for icon. <br> Came with adapter. | 
| Eldingu | 64GB | UHS-III <br> C10 | 59.6GB raw <br> >30 MB/s write | 59.4GB usable <br> 25.9 MB/s write <br> 84 MB/s read | AliExpress | Short of advertised write speed |
| KEXIN | 32GB | UHS-I <br> C10 | 29.8GB raw <br> >10 MB/s write | 29.1GB usable <br> 10.6 MB/s write <br> 39 MB/s read | Temu | Yes |
| Lexar | 32GB | UHS-I <br> C10 | 29.8 raw <br> >10 MB/s write | 29.5GB usable <br> 33 MB/s write <br> 43 MB/s read | AliExpress | Yes |
| Unbranded "Extreme PRO"| 16GB | UHS-I <br> C10 | 14.9GB raw <br> >10 MB/s write | 14.7GB usage <br> 69 MB/s write <br> 79 MB/s read | AliExpress | Yes | Surprised a SanDisk knockoff is real and has these write speeds when claimed to be Class 10. Poor card printing. |
| OLEVO | 16GB | V10 <br> UHS-I <br> C10 | 14.9GB raw <br> >10MB/s write | 14.6GB usable <br> 9.3 MB/s write <br> 11.4 MB/s read | AliExpress | Short of advertised write and read speed | Can only be formatted as exFAT. Crashes Windows Explorer and FakeFlashTest with other file systems. Short of claimed "15-30 MB/s read" in listing. Embarrassing it took H2testw 48min to verify <16GB. Do not purchase or use this card. |
