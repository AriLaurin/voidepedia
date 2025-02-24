---
Community-Size: Outpost
Alignment: Chaotic Evil
Government: Autocracy
type: Settlement
politics: Lordship
leader: 
guildsgroups:
  - Thieves Guild 1
  - Cult 1
  - Guiled 1
region:
  - This area
  - Of this area
size: Small city
population: 0
commonraces:
  - Humans
  - Elves
  - Dwarves
religion:
  - Lathander
exports:
  - Something
imports:
  - Something Else
---

> [!infobox]
> # `=this.file.name` 
> ![[MapPlaceholder.png|cover hsmall]]
> ###### Geography
> Type |  Stat |
> ---|---|
> Type | `=this.type` |
> Size | `=this.size` |
> Region | `=this.region` |
> ###### Politics
> Type |  Stat |
> ---|---|
> Govt Type | `=this.politics` |
> Ruler | `=this.leader`|
> ###### Society
> Type |  Stat |
> ---|---|
> Population | `=this.population` |
> Races | `=this.commonraces`|
> Temples | `=this.religion` |
> ###### Organizations
> Type |  Stat |
> ---|---|
> ```dataview
table WITHOUT ID link(file.name) AS "Group", link(Leader) AS "Leader"
where contains( PrimaryHome, this.file.name)


# `=this.file.name`
## Overview
Placeholder

### Placeholder Map
![[MapPlaceholder.png|Placeholder Map]]

### Placeholder Picture
![[ImagePlaceholder.png|Placeholder Picture]]


## Notable NPCs
Placeholder

## Points of Interest
Placeholder

## Valuables
Placeholder

## Background
Placeholder

## Additional Details
Placeholder
