---
title: Aviation NOTAMs
tags:
  - airports
  - aviation
  - flight
  - NOTAMs
  - dashboard
category: Aviation
topic:
  - NOTAMs
type: Dashboard
status: Active
dateCreated: 2024-12-30
cssclasses: 
banner: https://fixingnotams.org/wp-content/uploads/2019/11/Field-Guide.png
---

# 📝 Notices to Airmen (NOTAMs) 📢
___

NOTAMs (Notices to Airmen) are critical pieces of information that every pilot must review before a flight. They provide real-time updates on conditions and restrictions that could affect your flight. This guide covers the types of NOTAMs and offers resources to ensure you're always up to date.

## 🛬 Key NOTAM Concepts for Pilots:

# Types of NOTAMs
- **D (Distance) NOTAMs**
	- Contain information about airports, navigation aids, services, and facilities.
	- Example: Runway closures or unserviceable taxiways.

- **FDC (Flight Data Center) NOTAMs**
	- Regulatory notices such as airspace restrictions or amendments to instrument approach procedures.
	- Example: Temporary Flight Restrictions (TFRs).

- **Military NOTAMs**
	- Information specific to military operations and facilities.

- **International NOTAMs**
	- Pertinent to flights outside the United States, detailing airspace restrictions, weather-related issues, or other international concerns.

# Common NOTAM Subjects
- Runway and taxiway closures.
- Changes in lighting systems (e.g., beacon or PAPI outages).
- Temporary obstacles like cranes near airports.
- Airspace restrictions, including TFRs for VIP movements or special events.
- NAVAID outages or irregularities.
- GPS testing or outages affecting navigation.

# How to Read NOTAMs
- **Example NOTAM:**
	`!JFK 12/045 JFK RWY 4L/22R CLSD 1901121200-1901121800`
	- `!JFK`: The affected location.
	- `12/045`: The NOTAM number.
	- `JFK RWY 4L/22R`: The runway in question.
	- `CLSD`: The closure status.
	- `1901121200-1901121800`: The effective date and time (Zulu).

# Accessing NOTAMs
- Always review NOTAMs during preflight planning.
- Use online tools, aviation apps, or consult ATC for the latest information.

---

# 🌍 Useful NOTAM Resources:
- [FAA NOTAM Search](https://notams.aim.faa.gov/notamSearch/)
- [SkyVector NOTAM Overlay](https://skyvector.com/)
- [ForeFlight App](https://foreflight.com/)
- [AOPA NOTAM Guide](https://www.aopa.org/)

## NOTAM Notes:
```dataview  
TABLE WITHOUT ID
link(file.path, title) AS "Note", type AS "Type", dateCreated AS "Date Created", file.mtime AS "Last Modified", status AS "Status", chapter AS "Chapter"
FROM "Notes"
WHERE contains(topic, "NOTAMs") AND type != "Dashboard"
SORT title ASC
````

---

```plaintext
     ~ ~ ~ ~ ~ ~ ~ ~ ~ ~
  ~ ~   Fly safe!   ~ ~
     ~ ~ ~ ~ ~ ~ ~ ~ ~ ~
```

Always review NOTAMs before flight and be prepared to adjust your plans if necessary. Remember: An informed pilot is a safe pilot!