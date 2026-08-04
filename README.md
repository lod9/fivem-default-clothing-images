# fivem-default-clothing-images

GTA V freemode ped'lerinin (`mp_m_freemode_01` / `mp_f_freemode_01`) varsayılan
kıyafet ve aksesuarlarının greenscreen render'ları.

- 700×700 PNG, arka plan saydam
- Dosya adı: `<cinsiyet>_<component>_<drawable>.png`
  - `male_11_422.png` → erkek, component 11 (Top), drawable 422
  - prop'larda: `<cinsiyet>_prop_<component>_<drawable>.png`

## Component numaraları

| id | parça | id | parça |
|---|---|---|---|
| 1 | Mask | 8 | Undershirt |
| 3 | Hands / Arms | 9 | Body Armor |
| 4 | Legs | 11 | Top |
| 5 | Bag | | |
| 6 | Shoes | | **Props** |
| 7 | Accessory | 0 | Hat |
| | | 1 | Glasses |
| | | 2 | Ears |
| | | 6 | Watch |
| | | 7 | Bracelet |

## Nasıl üretildi

[fivem-greenscreener](https://github.com/Bentix-cs/fivem-greenscreener) (GPL-3.0)
tabanlı bir araçla, yeşil zemin önünde tek tek çekilip ortadan 700×700 kırpılarak.

## Lisans / kullanım

Görseller Rockstar Games'e ait GTA V oyun varlıklarının render'larıdır. Kod
lisansı görsellerin telif durumunu değiştirmez. Kendi sunucunda envanter /
kıyafet mağazası arayüzünde kullanabilirsin; ticari dağıtımdan önce hakları
kontrol et.
