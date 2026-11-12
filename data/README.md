# Jeju trail open data

Trail lines used by the Jeju trekking app (https://jeju-oreum-trip.github.io/oreum/). For map and video visuals only. Not hiking guidance: lines can be off or incomplete, and trails can be closed. Check conditions on site.

## Files
- `trails-sanrimcheong-jeju-city.geojson` / `.gpx`: oreum trail lines in 제주시 (WGS84).
- `trails-sanrimcheong-seogwipo.geojson` / `.gpx`: oreum trail lines in 서귀포시 (WGS84).
- `trails-osm-hallasan.geojson`: Hallasan 성판악 and 관음사 climbing routes, from OpenStreetMap.

## Sources and licences
- 산림청 등산로정보 (공공데이터포털 15029184), 제한 없음 (no use restriction). Survey data dated 2016-12-31. Converted from ITRF2000 TM to WGS84; side trails dropped so each oreum has one connected line (GPX points thinned to about 30 m). Credit: 산림청.
- OpenStreetMap routes: (c) OpenStreetMap contributors, ODbL 1.0. https://www.openstreetmap.org/copyright. Share-alike: keep this credit and licence if you reuse them.

Not included: official 제주올레 route files, blog GPX, Google/Naver map coordinates, and any hand-traced or auto-connected lines.
