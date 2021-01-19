
## Sample

|   code           |   local   |   en_us          |   zh_tw   |   zh_cn   |   ko       |   mm           |   latitude  |   longitude  |   default_zoom  |
|------------------|-----------|------------------|-----------|-----------|------------|----------------|-------------|--------------|-----------------|
|   tai2wan1       |   台灣    |   Táiwān         |   台灣    |   台湾    |   대만     |   ထိုင်ဝမ်       |   120.9605  |   23.6978    |   6             |
|   xin1zhu2xian4  |   新竹縣  |   Xīnzhú County  |   新竹縣  |   新竹县  |   신주현   |   ဆင်ချူကောင်တီ  |   121.0177  |   24.8387    |   9             |
|   zhu2bei3shi4   |   竹北市  |   Zhúběi City    |   竹北市  |   竹北市  |   주 베이  |   ကြုဗေမြို့       |   120.9934  |   24.8347    |   12            |
| chiangmai        | เชียงใหม่   | Chiang Mai       | 清邁      | 清迈      | 치앙마이   | ချင်းမိုင်       | 98.9853     | 18.7883      | 12              |

`code` must be unique. For Mandarin palcenames, pinyin with tone numbers is used, however this will not work for two places with homophonous names.
`local` is used for showing native names along with whatever the user's locale is. This can be in any script, even if not supported by the localisation sets.
`default_zoom` is used for setting the map zoom level for varieties that do not have sufficient recordings to set bounds automatically.
