---
title: End of an era! Micron DDR4 Rev.B 16GB Overclocking Showcase
date: 2022-09-25 09:43:36
categories:
- ['Overclocking']
tags:
- 'Micron'
- 'Crucial'
- 'AMD'
banner_img: https://cdn.mos.cms.futurecdn.net/jzLWFxMB5keGyQQuyFLgRD-970-80.jpg.webp
---
# Why? Who de hell needs 64 gigs?
After struggling with full CLANG LTO (Linker time optimization) using 32GB of RAM in early July, I decided to go all in for 64GB of RAM.
Since it has already been the end to DDR4 RAM, Crucial (mostly Micron) has decided to stop the production of the Ballistix line-up, therefore, it has already become nearly impossible to find any new kit under MSRP.
Luckily, after days of researching on eBay, I found someone who's willing to sell his for 260 bucks.
3200MHz, C16, 64GB, Micron ~~B-die~~ Rev.B ... Bet it has to be a good deal.

# OC result
It turns out it has been an awesome deal. Whereas, my CPU along with the ITX board is not good enough to keep it running at above-4000MHz.
To be more accurate, 3800MHz w/ 1900MHz FCLK is as far as it could reach.

|      | RAM OC | POST   | Stable |
| ---- | --------------- | -------- | -------- |
| 1    | 3200@C14             | :heavy_check_mark: | :heavy_multiplication_x: |
| 2    | 3600@C16             | :heavy_check_mark: | :heavy_check_mark:(stock) |
| 3    | **3800@C16**        | :heavy_check_mark: | :heavy_check_mark: |
| 4    | 4200@C20            | :heavy_check_mark: | :heavy_multiplication_x: (? Zen3 non-APU IMC sucks!) |


Anyway, I'll update with more details. Right now, I have been running this OC configuration for like a month now, everything is looking solid.
It was even functioning well at 70 degrees Celsius, but Samsung's legendary B-die suffers from anything higher than 50.

![image.png](micron-b-die-16GB-overclocking-showcase/oAhnvE9f1Npqzc3.png)

### Update
It is extremely sad to see the Ballistix go after being a reliable and affordable choise for years.
As of August, 2023, Micron's DDR5 still sucks ass. It really makes me not wanna upgrade to DDR5 any time soon.
Hynix A-die is in fact a way better choice, but affordability and the problem with the Zen 4 IMC are worse.

It's been a year since I started using the sticks for OCing. Luckily no corruption or anything happened to themselves. I actually got another pair of non-RGB version whereas the ICs on that one are absolutely trash - C9BLF clearly is incapable of being the successor of C9BLG but unfortunately it happened to be as my new pair is manufactured almost a year later than my previous.

# Results

![final oc - bench - 64gb.png](micron-b-die-16GB-overclocking-showcase/7KB9mCPfnMAX2J5.png)

