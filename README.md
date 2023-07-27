# wiki

Example: https://en.wikipedia.org/wiki/Walrus

## Dependencies

- jq
- xmllint

## Simple

```bash
$ wiki walrus
The walrus (Odobenus rosmarus) is a large pinniped marine mammal with discontinuous distribution about the North Pole in the Arctic Ocean and subarctic seas of the Northern Hemisphere.

sections:
- Etymology
- Taxonomy and evolution
- Anatomy
- Toggle Anatomy subsection
- Life history
- Toggle Life history subsection
- Ecology
- Toggle Ecology subsection
- Relationship with humans
- Toggle Relationship with humans subsection
- See also
- References
- Further reading
- External links
```

## With section

```bash
$ wiki walrus anatomy
While some outsized Pacific males can weigh as much as 2,000 kg (4,400 lb), most weigh between 800 and 1,700 kg (1,800 and 3,700 lb).

subsections:
- Tusks and dentition
- Vibrissae (whiskers)
- Skin
```

## Stretch goal

```bash
$ wiki walr[tab] # completes to walrus

$ wiki walrus anat[tab] # completes to walrus
```
