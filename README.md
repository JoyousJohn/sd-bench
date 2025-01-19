# sd-card-tests
H2testw results for obscure or uncommon micro SD card brands. Cards are first assessed by FakeFlashTest. Observed average results sourced from final H2testw speeds when attempting to verify detected card capacity and compared to speeds from manual transfers afterward. Some cards are being tested for long-term endurance use and reliability in continuously recording security cameras.

| Brand | Claimed <br> Size | Designation | Expected | Observed (avg.) | Marketplace | Genuine? | Notes |
| - | - | - | - | - | - | - | - |
| Unbranded "MEMORY CARD" ("mask") | 256GB | UHS-I U1 <br> C10 | 238GiB <br> >10 MB/s write | 14.4GiB usable <br> 27.7 MB/s write <br> 50.4 MB/s read | Temu <br> $2.59 | No | Expected this one to be fake but gave it a chance due to the cents invested toward the artwork |
| EAGET | 128GB | V30 <br> UHS-III <br> C10 <br> A1 | 119.2GB raw <br> >30 MB/s write | 119.2GB usable <br> 52 MB/s write <br> 82.9 MB/s read | Temu <br> $4.94 | Yes |
| SHANNANZI | 128GB | C10 | 119.2GB raw <br> >10 MB/s write | 58.5GB usable <br> 16.8 MB/s write <br> 14.6 MB/s read | Temu <br> $3.19 | No | Disappointed to see a second fake card from Temu. To give it some credit, the packaging claimed a 7 MB/s max write, so there's that. The adapter it came with also had no branding whatsoever and limited genuine SD cards to <18 MB/s write. |
| TFIIOK| 128GB | UHS-I <br> C10 <br> A2 | 119.2GB raw <br> >10 MB/s write | 117.0GB usable <br> 43.2 MB/s write <br> 79.8 MB/s read | Temu <br> $3.64 | Yes | Came with adapter. |
| QVQ | 128GB | C10 <br> A1 | 119.2GB raw <br> >10 MB/s write | ~64GB usable <br> ~14 MB/s write | AliExpress <br> $1.99 | FakeFlashTest write sector errors at 50%. H2testw 433's before reaching this point. | First fake card from AliExpress, all previous cards from seller were genuine. Image on the product page also shows "U1" on the card which was missing on the one received. |
| OSMR | 128GB | V30 <br> UHS-I U3 <br> C10 <br> A2 | 119.2GiB <br> >30 MB/s write | 116.4GiB <br> 22.9 MB/s write <br> 33.1 MB/s read | AliExpress <br> $3.80 | Short of write speeds |
| LansTen | 128GB | V30 <br> UHS-I U3 <br> A2 | 119.2GiB <br> >30 MB/s write | 116.4GiB <br> 39 MB/s write <br> 77.5 MB/s read | AliExpress <br> $3.79 | Yes | Came with both a micro SD to SD and a micro SD to USB 2.0 adapter! First time ever seeing this and I'm surprised it wasn't mentioned/advertised in the listing. |
| amzwn (green) | 128GB | V30 <br> UHS-I U3 <br> C10 <br> A2 | 119.2GiB <br> >30 MB/s write | 116.4GiB <br> 47.4 MB/s write <br> 74.9 MB/s read | AliExpress <br> $1.98 | Yes | Appalled this was real. Maybe a quick death will be the tradeoff? |
| TOPESEL | 64GB | UHS-I <br> C10 | 59.6GB raw <br> >10 MB/s write | 58.6GB usable <br> 12 MB/s write <br> 78 MB/s read | Temu <br> $3.38 | Yes | Came with adapter. |
| KODAK | 64GB | V30 <br> UHS-III <br> C10 | 59.6GB raw <br> >30 MB/s write | 58.2GB usable <br> 45 MB/s write <br> 84 MB/s read | Temu <br> $4.58 | Yes | Came with KODAK.ico <br> and autorun.inf for icon. <br> Came with adapter. | 
| Eldingu | 64GB | UHS-III <br> C10 | 59.6GB raw <br> >30 MB/s write | 59.4GB usable <br> 25.9 MB/s write <br> 84 MB/s read | AliExpress <br> $1.99 | Short of advertised write speed. |
| MUOUM | 64GB | C10 | 59.6GB raw <br> >10MB/s write | 58.6GB usable <br> 33 MB/s write <br> 81 MB/s read | Temu <br> $3.89 | Yes | Write speed began at 80 MB/s and linearly decreased to 33 MB/s over the course of 15min. |
| Microdrive | 64GB | UHS-III <br> C10 | 59.6GB raw <br> >10MB/s write | 58.2GB usable <br> 42 MB/s write <br> 80 MB/s read | Temu <br> $3.48 | Yes | Came with adapter. |
| Hsthe sea | 64GB | UHS-III <br> C10 | 59.6GB raw <br> >30 MB/s write | 59.4GB usable <br> 25.4 MB/s write <br> 80 MB/s read | AliExpress <br> $1.99 | Short of advertised write speed. |
| AUGAOKE ("santa tomato") | 64GB | UHS-III <br> C10 | 59.6GB raw <br> >30 MB/s write | 59.4GB usable <br> 17 MB/s write <br> 66 MB/s read | AliExpress <br> $1.99 | Very short of advertised write speed. |
| AUGAOKE ("flowers") | 64GB | UHS-III <br> C10 | 59.6GB raw <br> >30 MB/s write | 58.5GB usable <br> 31 MB/s write <br> 84 MB/s read | AliExpress <br> $1.99 | Yes | Surprised the two AUGAOKE cards I tested are actually different and don't just have a different design printed. Maybe poor quality control? Will have to purchase multiple and test each. |
| BYKEJI | 64GB | C10 | 59.6GB raw <br> >10 MB/s write | 58.4GB usable <br> 41 MB/s write <br> 72 MB/s read | Temu <br> $3.39 | Yes |
| BESY | 64GB | V30 <br> UHS-III <br> C10 <br> A2 | 59.6GB raw <br> >30 MB/s write | 59.4GB usable <br> 26.2 MB/s write <br> 84 MB/s read | Temu <br> $2.59 | Short of write speed. | Only Temu card tested so far failing to reach expected speeds. Still impressive for $3 though. Odd grid of pins on back. | 
| Lenovo | 64GB | V30 <br> UHS-III | 59.6GB raw <br> >30 MB/s write | 58.2GB usable <br> 26.8 MB/s write <br> 73 MB/s read | Temu <br> $3.39 | Short of write speed. | Disappointed to see this from a reputable brand (card was bought direct). Also surprised to see no class rating. |
| MOVE SPEED | 64GB | V30 <br> UHS-III <br> C10 <br> A2 | 59.6GB raw <br> >30 MB/s write | 58.5GB usable <br> 28.4 MB/s write <br> 78 MB/s read | Temu <br> $2.98 | Slightly short of write speeds | 
| ESTRELLA | 64GB | V60 <br> UHS-III <br> C10 | 59.6GB raw <br> >60 MB/s write | 1.3GB usable <br> 19.1 MB/s write | Temu <br> $4.49 | No | First fake card from Temu |
| Lenovo thinkplus | 64GB | V30 <br> UHS-I U3 <br> C10 | 59.6GB raw <br> >30 MB/s write | 58.6GB usable <br> 34.8 MB/s write <br> 72.4 MB/s read | Temu <br> $2.69 | Yes | Happy to see a Lenovo comeback with advertised write speeds. |
| TECLAST | 64GB | UHS-I U1 <br> C10 | 59.6GB raw <br> >10 MB/s write | 58.6GB usable <br> 28.5 MB/s write <br> 83.3 MB/s read | Temu <br> $2.25 | Yes |
| ZDPDISK | 64GB | UHS-I UI <br> C10 | 59.6GB raw <br> >10 MB/s write | 58.2GB usable <br> 19.4 MB/s write <br> 30.1 MB/s read | Temu <br> $3.98 | Yes | Class 10 rating appears on the card twice, interesting... |
| Netac | 64GB | UHS-I U1 <br> C10 <br> A1 | 59.6GB raw <br> >10 MB/s write | 58.4GB usable <br> 19.9 MB/s write <br> 42.1 MB/s read | Temu <br> $2.69 | Yes |
| TECLAST | 64GB | V30 <br> UHS-I U3 | 59.6GB raw <br> >30 MB/s write | 58.2GB usable <br> 40.8 MB/s write <br> 77 MB/s write | Temu <br> $2.49 | Yes | 
| RELETECH | 64GB | UHS-I U3 <br> C10 <br> A1 | 59.6GB raw <br> >30 MB/s write | 58.6GB usable <br> 35.1 MB/s write <br> 79.7 MB/s write | AliExpress <br> $1.99 | Yes |
| MOVESPEED Ultra | 64GB | V30 <br> U3 <br> C10 <br> A2 | 59.6GB raw <br> >30 MB/s write | 58.2GB usable <br> 33 MB/s write <br> 84.5 MB/s read | Temu <br> $2.49 | Yes | No UHS rating |
| KRY | 64GB | V30 <br> UHS-I U3 <br> C10 <br> A1 | 59.6GB raw <br> >30 MB/s write | 58.5G usable <br> 32.9 MB/s write <br> 74.1 MB/s read | AliExpress <br> $1.99 | Yes |
| ALUNX | 64GB | V30 <br> U3 <br> A2 | 59.6GB raw <br> >30 MB/s write | 58.5GB usable <br> 44.9 MB/s write <br> 57.7 MB/s read | AliExpress <br> $1.99 | Yes | Write speeds remained >80 MB/s until last 2min of test |
| KOOTION | 64GB | V30 <br> UHS-I U3 <br> A1 | 59.6GB raw <br> >30 MB/s write | 58.2GB usable <br> 39.8 MB/s write <br> 72.9 MB/s read | AliExpress <br> $2.06 | Yes | Came with adapter. |
| Unbranded "Extreme PRO"| 64GB | UHS-I U3 <br> C10 | 59.6GB raw <br> >30 MB/s write | 58.6GB usable <br> 40.9 MB/s write <br> 71.7 MB/s read | Temu <br> $2.24 | Yes | Came with adapter. |
| Somnambulist | 64GB | V30 <br> UHS-I U3 <br> A2 | 59.6GB raw <br> >30 MB/s write | 58.2GB usable <br> 8.42 MB/s write <br> 13.3 MB/s read | AliExpress <br> $1.79 | Severely short of R/W speeds |
| Hsthe sea (dragon) | 64GB | UHS-I U3 <br> C10 | 59.6GB raw <br> >30 MB/s write | 50.7GB usable <br> 30.1 MB/s write <br> 77.2 MB/s read | AliExpress <br> $1.99 | Yes 
| Somnambulist (orange) | 64GB | UHS-I U3 <br> C10 | 59.6GB raw <br> >30 MB/s write | 58.2GB usable <br> 22 MB/s write <br> 78.4 MB/s read | AliExpress <br> $1.59 | Short of write speeds | Seems this brand has poor quality control if their lower-rated card performs better. |
| Bliksem | 64GB | UHS-I U3 <br> C10 <br> A1 | 59.6GB raw <br> <30MB/s write | 58.2GB usable <br> 30.5 MB/s write <br> 78.2 MB/s read | AliExpress <br> $1.59 | Yes |
| Bliksem (yellow) | 64GB | V30 <br> UHS-I U3 <br> C10 <br> A1 | 59.6GB raw <br> >30 B/s write | 54.5GB usable <br> 14.6 MB/s write <br> 78 MB/s read | AliExpress <br> $1.59 | Short of write speeds | Another case where the non-V30 card is the one that reaches V30 specs |
| Unbranded "Smart Card" (white/gray) | 64GB | UHS-I U3 <br> C10 | 59.6GiB <br> >30 MB/s write | 7.7GiB <br> 9.01 MB/s write <br> 19.7 MB/s read | AliExpresss <br> $1.28 | No | First beyond-generic card I purchased where half the card is still blank. Expected to be fake but came from a seller who previously sold genuine cards. |
| Unbranded (black) | 64GB | U3 <br> C10 <br> A1 | 59.6GiB <br> >30 MB/s write | 7.8GiB <br> 8.88 MB/s write <br> 19.8 MB/s read | AliExpresss <br> $1.23 | No | A tad surprised the results aren't identical to the above card. Although no UHS rating on card, the single row of pins indicates UHS-I. Came with adapter. |
| Unbranded "Smart Card" (white) | 64GB | UHS-I U3 <br> A1 | 59.6GiB <br> >30 MB/s write | 7.7GiB <br> 9.14 MB/s write <br> 18.2 MB/s read | AliExpresss <br> $1.23 | No | Surprised manufacturer of this card and the two above bothered to change card specification branding on these cards instead of just changing the background color. Came with adapter. |
| Fireurus | 64GB | V30 <br> U3 <br> C10 <br> A2 <br> | 59.6GiB <br> >30 MB/s write | 59.6GiB <br> 25.3 MB/s write <br> 33.4 MB/s read | AliExpress <br> $1.92 | Short of write speeds | No UHS rating | 
| KEXIN | 32GB | UHS-I <br> C10 | 29.8GB raw <br> >10 MB/s write | 29.1GB usable <br> 10.6 MB/s write <br> 39 MB/s read | Temu <br> $2.38 | Yes | Barely surpassed minimum write speeds. Avoid. |
| Lexar | 32GB | UHS-I <br> C10 | 29.8GB raw <br> >10 MB/s write | 29.5GB usable <br> 33 MB/s write <br> 43 MB/s read | AliExpress <br> $1.99 | Yes | Difficult to believe a genuine(?) Lexar card is available for $2. |
| OLEVO | 32GB | UHS-I <br> C10 | 29.8GB raw <br> >10 MB/s write | 29.4GB usable <br> 11.8 MB/s write <br> 17.6 MB/s read | AliExpress <br> $1.74 | Short of advertised read speeds | Short of claimed "15-30 MB/s read" in listing description. Came formatted as FAT32 but could only be reformatted as NTFS, otherwise crashes FakeFlashTest and File Explorer. Very sketchy card in terms of reliability. |
| Unbranded "Extreme PRO"| 16GB | UHS-I <br> C10 | 14.9GB raw <br> >10 MB/s write | 14.7GB usage <br> 69 MB/s write <br> 79 MB/s read | AliExpress <br> $1.18 | Yes | Surprised a SanDisk knockoff is real and has these write speeds when claimed to be Class 10. Poor card printing. |
| OLEVO | 16GB | V10 <br> UHS-I <br> C10 | 14.9GB raw <br> >10MB/s write | 14.6GB usable <br> 9.3 MB/s write <br> 11.4 MB/s read | AliExpress <br> $1.39 | Short of advertised read and write speeds | Can only be formatted as exFAT. Crashes Win. File Explorer and FakeFlashTest with other file systems. Also short of claimed "15-30 MB/s read" in listing. Embarrassing it took H2testw 48min to verify <16GB. Do not purchase or use this card. |
Z-suit | 16GB | UHS-I U1 <br> C10 | 14.9GB raw <br> >10MB/s write | 14.4GB usable <br> 18.7 MB/s write <br> 84.7 MB/s read | AliExpress <br> $1.84 | Yes |
