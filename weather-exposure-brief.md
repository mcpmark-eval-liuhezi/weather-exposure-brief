# Weather-Exposure Brief — Field Network On-Call Handoff

**Prepared:** Wed, Nov 11, 2026 (pre Handoff Meeting)
**Runbook sites:** us-east (Ashburn, VA), us-central (Dallas, TX), us-south (Miami, FL), us-west (Redmond, WA)
**Upstream national weather source:** weather.gov (NOAA National Weather Service)
**Dashboard network operator:** AS13335 (Cloudflare, Inc.)

---

## 1. Site us-east — Ashburn, Virginia (39.0437,-77.4875) — STATUS: CLEAR

- **Alert status:** No active weather alerts, watches, or warnings for Virginia (state-wide check: clean).
- **Current conditions** (obs station KJYO, 5.0 mi away, observed 2:55 AM local 11/11/2026):
  - Temperature: 44.6°F (7.0°C)
  - Conditions: Clear
  - Humidity: 93%
  - Wind: 0 mph from 0°
  - Pressure: 30.02 inHg
  - Visibility: 10.0 miles
- **Precipitation risk (next 24 hrs):** Minimal. Sky turns mostly cloudy after 6 PM; rain chance peaks at 10% around 1–2 AM. Dry overnight into tomorrow morning.
- **Nearest observation station:** **KJYO** — Leesburg / Godfrey, elevation 390 ft, 5.0 miles from site coordinates.
- **Multi-day outlook:** Sunny/high near 67°F on Veterans Day with light west wind (1–7 mph). Wednesday night: 20% chance of rain after 4 AM. Thursday: chance of rain, high 64°F, 50% precip chance, W 2–18 mph gusting to 24. Friday: 25–30% chance of showers early morning then mostly sunny, high 51°F. Sunny and dry through the weekend (1–2% precip). Cold stable pattern.

---

## 2. Site us-central — Dallas, Texas (32.7767,-96.7970) — STATUS: WATCH

- **Alert status:** WATCH — Texas has 5 active alerts (Dense Fog Advisory for Southern Lea/Scurry counties through 11 AM; Flood Warnings for Val Verde County Devils River x2 and Llano County Llano River; Flood Advisory for Brooks County Los Olmos Creek). None are in the Dallas metro area, but state-level flag = WATCH.
- **Current conditions** (obs station KDAL, 6.0 mi away, observed 2:05 AM local 11/11/2026):
  - Temperature: 64.4°F (18.0°C)
  - Conditions: Clear
  - Humidity: 83%
  - Wind: 17 mph from 230° (SW)
  - Pressure: 30.09 inHg
  - Visibility: 10.0 miles
- **Precipitation risk (next 24 hrs):** Very low. Patchy fog before 9 AM (1–2%), then sunny all day, high near 80°F. Clear overnight into tomorrow (61–62°F).
- **Nearest observation station:** **KDAL** — Dallas Love Field, elevation 476 ft, 6.0 miles from site coordinates.
- **Multi-day outlook:** Patchy fog then sunny — high 80°F, 1–2% precip through Saturday (Sat evening: 20–24% slight chance showers after midnight). Sunny, high 76°F Thursday. Sunny 71°F Friday. Weekend mostly sunny (70°F, 2%). Heads-up: **Showers and thunderstorms likely Sunday (70% precip, high 62°F) — plan staffing around Sunday for this region.**

---

## 3. Site us-south — Miami, Florida (25.7617,-80.1918) — STATUS: WATCH

- **Alert status:** WATCH — Florida has 7 active alerts (Flood Warnings on the St. Johns River in Seminole/Brevard/Lake/Volusia counties, Peace River in DeSoto County, Monroe Upper Keys Coastal Flood Statement). None local to Miami-Dade, but state-level flag = WATCH.
- **Current conditions** (obs station KMIA, 8.3 mi away, observed 3:00 AM local 11/11/2026):
  - Temperature: 75.2°F (24.0°C), feels like 76.6°F
  - Conditions: Mostly Clear
  - Humidity: 89%
  - Wind: 0 mph from 0°
  - Pressure: 30.03 inHg
  - Visibility: 10.0 miles
- **Precipitation risk (next 24 hrs):** Slight and building. Mostly cloudy 4–10% through late morning, then **slight chance of showers/thunderstorms 3–5 PM peaking at 28% around 5 PM**, easing to 5–12% overnight. Tropical-adjacent moisture there.
- **Nearest observation station:** **KMIA** — Miami International Airport, elevation 10 ft, 8.3 miles from site coordinates.
- **Multi-day outlook:** Mostly sunny, high near 84°F with 28–30% chance of a slight shower/T-storm chance (3–5 PM). Wed night 20–23% chance of showers. Thu night 10%. **Tropical pattern continues: Mon 80°F with 27–40% chance of showers/storms, rising to 48% Tue.**

---

## 4. Site us-west — Redmond, Washington (47.6742,-122.1215) — STATUS: WATCH

- **Alert status:** WATCH — Washington has 10 active alerts (Special Weather Statements for dense fog in the Columbia Gorge/Blue Mountains, Flood Warning for Mason County Skokomish River, High Surf Advisory for the coast, Coastal Flood Advisory for Whatcom/San Juan counties, Wind Advisory for Island/Skagit/Snohomish/Whatcom/Jefferson with gusts to 50 mph). **None are Redmond-local; however state-level flag = WATCH.**
- **Current conditions** (obs station SEAW1 — Seattle WFO, 6.2 mi away, observed 11:30 PM local 11/10/2026):
  - Temperature: 54.0°F (12.2°C)
  - Humidity: 97%
  - Wind: 7 mph from 209°
  - Sky: Mostly Cloudy (current obs returns temp/humidity/wind)
- **Precipitation risk (next 24 hrs):** Very dry. Mostly cloudy 2–6% all day. High 68°F, 6% precip chance.
- **Nearest observation station:** **SEAW1** — Seattle Weather Forecast Office, elevation 29 ft, 6.2 miles from site coordinates.
- **Multi-day outlook:** High 68°F (mostly cloudy) today, 6% precip. Thursday 30% chance of light rain morning, cloudy, high 64°F. **Rain returns hard: Friday 78–80% light rain, Saturday 51–92% chance of rain through Sunday (92% Sat night/Sun), then tapering to 19% by Tuesday.** This is the highest-impact site for the next few days — budget for wet-weather gear and possible outages in the Redmond/Snohomish area.

---

## 5. Data Provenance (Audit Binder)

### weather.gov — WHOIS (registry lookup via whois.nic.gov)
- **Domain Name:** weather.gov
- **Registrar:** get.gov (Registrar IANA ID 8888888; Registrar URL https://get.gov)
- **Registrar WHOIS Server:** whois.nic.gov
- **Domain Status:** serverTransferProhibited (https://icann.org/epp#serverTransferProhibited)
- **Name Servers:** a1-97.akam.net, a11-66.akam.net, a18-67.akam.net, a26-64.akam.net, a6-65.akam.net, a7-66.akam.net (Akamai DNS)
- **DNSSEC:** signedDelegation
- **Created:** 1999-04-30T21:06:20Z | **Updated:** 2026-10-01T11:30:29Z | **Expires:** 2027-08-27T15:55:27Z
- **Registrant:** Department of Commerce, Silver Spring, MD, US (NOAA operator of the national weather service)
- **Registry Security contact:** security@noaa.gov

### AS13335 — WHOIS (ARIN lookup)
- **ASNumber:** 13335 | **ASName:** CLOUDFLARENET | **ASHandle:** AS13335
- **Registered:** 2010-07-14 (record updated 2017-02-17)
- **Operator (OrgName):** **Cloudflare, Inc.** (OrgId: CLOUD14, 101 Townsend Street, San Francisco, CA 94107, US)
- **NOC:** Cloudflare-NOC, +1-650-319-8930, noc@cloudflare.com
- **Abuse:** abuse@cloudflare.com (reporting via https://www.cloudflare.com/abuse)
- **Tech/Admin:** rir@cloudflare.com, +1-650-319-8930
- **Ref:** https://rdap.arin.net/registry/autnum/13335

---

## 6. Handoff Notes
- ** us-east (VA):** CLEAR. Dry, sunny, cold trend. Nothing from weather side.
- ** us-central (TX):** WATCH (state alerts, not local). Moody wind 17 mph SW; fog dies by 9 AM; sunny day ahead; pack thunderstorms Sunday in TX.
- ** us-south (FL):** WATCH (state alerts, not local). Tropical moisture; showers/storms possible late afternoon; storm chances Mon/Tue.
- ** us-west (WA):** WATCH (state alerts incl. coastal flood + wind). Driest right now but wet pattern moving in Thu–Sat (80%+ rain Fri/Sun); plan accordingly.
