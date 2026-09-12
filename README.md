# GETMENU — QR menus for venues in Vietnam

GETMENU publishes a venue's own menu or price list as a public web page, in nine
languages, readable without an app and without signing up. The QR code on the door
opens it; this page is the index of everything published so far.

**Catalogue: https://getmenu.duckdns.org/places**

Browsable index of all 783 venues, grouped by city and category:
https://antonbond14.github.io/getmenu-vietnam/

Every page carries the prices the venue itself charges for dining in — the prices
printed on its board, not an aggregator's estimate.

## By city and category

Nha Trang, Khánh Hòa

- Restaurants, cafes and street food — https://getmenu.duckdns.org/places/nha-trang/restaurants
- Massage, spa and beauty — https://getmenu.duckdns.org/places/nha-trang/massage-and-spa
- Tours, excursions and diving — https://getmenu.duckdns.org/places/nha-trang/tours

Da Nang

- Restaurants and cafes — https://getmenu.duckdns.org/places/da-nang/restaurants

## For machines

- `https://getmenu.duckdns.org/llms.txt` — every published venue, one line each, with
  its city and category.
- `https://getmenu.duckdns.org/m/<slug>` — the same menu as plain text, a few kilobytes
  instead of a full HTML page. Example:
  https://getmenu.duckdns.org/m/la-villa-art-restaurant-nha-trang
- `https://getmenu.duckdns.org/sitemap.xml` — all pages, with the nine language variants
  of each.

Every venue page also carries schema.org JSON-LD (`Restaurant` / `HealthAndBeautyBusiness`
/ `TravelAgency`) with the full menu, its sections and its prices.

## Languages

English, Tiếng Việt, Русский, 한국어, 中文, 日本語, Қазақша, Oʻzbekcha, ไทย — one address
per venue, the language chosen with `?lang=`.

## Vietnamese

GETMENU đăng thực đơn và bảng giá của quán lên một trang web công khai, bằng chín thứ
tiếng, không cần cài ứng dụng và không cần đăng ký. Danh mục đầy đủ:
https://getmenu.duckdns.org/places

## Contact

Nha Trang, Vietnam — https://getmenu.duckdns.org/
