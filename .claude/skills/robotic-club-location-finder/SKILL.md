---
name: robotic-club-location-finder
description: Find and evaluate real-world physical locations for hosting or starting a robotics club (FIRST/FLL/FTC/VEX team, hobbyist maker group, school extracurricular, etc.) in a given city or region. Use this whenever someone asks where to hold robotics club meetings, is scouting a venue for a robotics/STEM/maker team, needs a meeting space with workbenches and storage for robots and parts, or wants to compare libraries, schools, universities, makerspaces, hackerspaces, community centers, or coworking spaces as candidate club sites — even if they just say "robotics club space" or "where can my team meet" without naming a specific venue type.
---

# Robotic Club Location Finder

Help someone find a physical place to run a robotics club: regular meetings, hands-on build sessions, and storage of robots, tools, and parts between sessions. The output is a short, comparable list of real candidate venues in their city, not a generic essay about venue types.

## Before searching

Get the essentials if they weren't given:
- **City/region** — required. Searches and organization directories are local; don't guess a location.
- **Group profile** — age range (kids/teens/adults), team size, and affiliation if any (FIRST Robotics/FTC/FLL, VEX, university club, independent hobbyist group). This changes which directories and venue types are relevant.
- **Meeting cadence and budget** — weekly vs. seasonal, and whether the space needs to be free/low-cost (most school and hobbyist teams need free or near-free space).

If any of these is missing and matters for the search, ask before spending searches on it — a location search run against the wrong city wastes effort and produces confident-sounding but useless results.

## Where to search

Work through these sources; not every one will apply to every group profile, but check the ones that do:

1. **Competitive robotics registries** — if the group is or wants to be part of an organized program, these list existing local teams whose venues and sponsor organizations are worth learning from:
   - FIRST team/event locator (FRC, FTC, FLL) — search "FIRST [FRC/FTC/FLL] teams near [city]" or check the FIRST website's team search.
   - VEX Robotics team and event locator, similarly.
   - A nearby existing team's host venue (a school, library, or makerspace) is strong evidence that venue already knows how to host a robotics club.
2. **Public library systems** — many library systems have maker labs, meeting rooms, or STEM programming and will host or co-sponsor a youth robotics club for free. Search "[city] public library makerspace" or "[city] library meeting room robotics."
3. **Makerspaces and hackerspaces** — search "[city] makerspace" and "[city] hackerspace." These typically already have workbenches, power, tools, and sometimes 3D printers/electronics benches, but usually charge membership dues.
4. **Schools and universities** — local schools (for a school-affiliated or after-school club) and university engineering/robotics departments (which often support community outreach or let student robotics clubs sponsor a youth team). Search "[school/university name] robotics club" or "[university] engineering outreach STEM."
5. **STEM and youth nonprofits** — Boys & Girls Clubs, 4-H, YMCA, science museums, and STEM-focused nonprofits sometimes have dedicated program space and grant funding for robotics programming.
6. **Community and recreation centers** — city-run community centers and rec centers often rent or donate meeting rooms to youth and hobbyist groups.
7. **Coworking spaces** — a fallback for adult hobbyist groups; usually the most expensive option per session.

Use web search for each of these against the requested city, and follow through to a venue's own site or contact page rather than stopping at the search results page — you need an address and a way to make contact, not just a name.

## What to evaluate each candidate on

For every real candidate you find, check what's actually knowable from its website, listing, or contact info (don't fabricate specifics you couldn't find — say "not listed, would need to ask" instead):

- **Space**: room size/capacity, tables or workbenches, floor type (carpet vs. hard floor matters for rolling robots).
- **Power and connectivity**: enough outlets for chargers/laptops/soldering irons; wifi if the team uses programming software or streams competition info.
- **Storage**: a lockable closet, cabinet, or shelf to leave robots, tools, and parts between meetings — this is often the deciding factor, since hauling gear every session kills attendance.
- **Safety and liability**: whether the venue requires insurance, a waiver, or adult supervision ratios (relevant for soldering, power tools, or battery charging).
- **Cost**: free, membership-based, or per-session rental; whether a school or nonprofit affiliation waives fees.
- **Access**: hours of availability matching the group's schedule, accessibility (elevator/ramp if needed), and parking or public transit for members getting there.
- **Fit signal**: any evidence the venue already supports STEM/robotics (an existing team, a maker lab, science programming) — this predicts a smoother approval process.

## Output format

Present findings as a short comparison, most-promising first. For each candidate:

```
### [Venue name]
- **Type**: library / makerspace / school / university / community center / nonprofit / coworking
- **Address**: [address, or "not listed" if unavailable]
- **Contact**: [phone/email/contact page URL]
- **Why it fits**: [1-2 sentences tying it to the group's profile and the criteria above]
- **Open questions**: [what you couldn't confirm from public info — e.g. "storage availability not listed, ask directly"]
```

Close with a one-line recommendation on which 1-2 candidates to contact first and why, plus any gaps in the search (e.g. "no low-cost option found for adult hobbyist groups in this city — worth asking the local library directly even though their site doesn't mention a makerspace").

Don't invent addresses, phone numbers, or amenities you didn't actually find — an unconfirmed detail is worse than an honest "not listed."
