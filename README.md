# How to Win CCDC

[![Deploy to GitHub Pages](https://github.com/mubix/howtowinccdc/actions/workflows/deploy.yml/badge.svg)](https://github.com/mubix/howtowinccdc/actions/workflows/deploy.yml)

Notes, Slides, Comments, and Commands on How to Win CCDC

Live Link: [https://howtowinccdc.com/](https://howtowinccdc.com/)

Original Doc: [https://docs.google.com/presentation/d/1pPXLg3KqwSMLRCNRfows5QnVI2mLjSmll5vN2WHMFJg](https://docs.google.com/presentation/d/1pPXLg3KqwSMLRCNRfows5QnVI2mLjSmll5vN2WHMFJg)

## Contributing

This repository is open to all contributions from CCDC Blue Team competitors to Red Teamers or even just people interested in correcting my grammar. Please feel free to just make an issue if you aren't familiar with GitHub, or make a pull request if you are.

### Slides

The presentation at [howtowinccdc.com](https://howtowinccdc.com/) is a single `index.html` file using [reveal.js](https://revealjs.com/). To add or edit slides, edit `index.html` directly. Each `<section>` is a slide. Nested `<section>` tags create vertical slide groups. Speaker notes go in `<aside class="notes">` tags.

### Historical Documents

One of the best ways to learn and prepare for an event is to read up on all of its history. Even if you don't compete in a specific region, learning how they prepare or recommendations they make could add that extra edge.

Team packets, rules, and other competition documents are archived in the [`documents/`](https://github.com/mubix/howtowinccdc/tree/main/documents) folder, organized by region. If you happen to have any of these documents or know where to get them, please contribute them to the repository.

Please use the standard naming convention:

```
YEAR-REGIONCODE[-Stage]-DocumentType.pdf
```

Examples: `2026-NECCDC-Qualifiers-TeamPacket.pdf`, `2019-WRCCDC-Finals-TeamPacket.pdf`

White papers go in `documents/_WhitePapers/` using the format `Author-ShortTitle.pdf`.

### Team Packet Coverage

Q = Qualifiers | F = Finals/Regional — click ✅ to download. ❌ = missing (PRs welcome!)

| Year | Nationals | AL | MA | MW | NE | PR | RM | SE | SW | WR |
|------|------|------|------|------|------|------|------|------|------|------|
| 2007 | [F✅](documents/Nationals/2007-NCCDC-TeamPacket.pdf) | ❌ | ❌ | ❌ | ❌ | ❌ | ❌ | ❌ | ❌ | ❌ |
| 2008 | ❌ | ❌ | [Q✅](documents/MidAtlantic-MACCDC/2008-MACCDC-Qualifiers-TeamPacket.pdf) [F✅](documents/MidAtlantic-MACCDC/2008-MACCDC-TeamPacket.pdf) | ❌ | ❌ | ❌ | ❌ | ❌ | ❌ | ❌ |
| 2010 | ❌ | ❌ | Q❌ [F✅](documents/MidAtlantic-MACCDC/2010-MACCDC-TeamPacket.pdf) | ❌ | ❌ | ❌ | ❌ | ❌ | ❌ | Q❌ [F✅](documents/Western-WRCCDC/2010-WRCCDC-TeamPacket.pdf) |
| 2011 | [F✅](documents/Nationals/2011-NCCDC-TeamPacket.pdf) | ❌ | ❌ | Q❌ [F✅](documents/MidWest-MWCCDC/2011-MWCCDC-TeamPacket.pdf) | Q❌ [F✅](documents/NorthEast-NECCDC/2011-NECCDC-TeamPacket.pdf) | ❌ | ❌ | ❌ | ❌ | ❌ |
| 2012 | ❌ | ❌ | ❌ | Q❌ [F✅](documents/MidWest-MWCCDC/2012-MWCCDC-TeamPacket.pdf) | ❌ | ❌ | ❌ | ❌ | ❌ | Q❌ [F✅](documents/Western-WRCCDC/2012-WRCCDC-TeamPacket.pdf) |
| 2013 | [F✅](documents/Nationals/2013-NCCDC-TeamPacket.pdf) | ❌ | Q❌ [F✅](documents/MidAtlantic-MACCDC/2013-MACCDC-TeamPacket.pdf) | ❌ | Q❌ [F✅](documents/NorthEast-NECCDC/2013-NECCDC-TeamPacket.pdf) | ❌ | ❌ | Q❌ [F✅](documents/SouthEast-SECCDC/2013-SECCDC-TeamPacket.pdf) | ❌ | Q❌ [F✅](documents/Western-WRCCDC/2013-WRCCDC-TeamPacket.docx) |
| 2014 | [F✅](documents/Nationals/2014-NCCDC-TeamPacket.pdf) | ❌ | Q❌ [F✅](documents/MidAtlantic-MACCDC/2014-MACCDC-TeamPacket.pdf) | ❌ | [Q✅](documents/NorthEast-NECCDC/2014-NECCDC-Qualifiers-TeamPacket.pdf) F❌ | ❌ | ❌ | [Q✅](documents/SouthEast-SECCDC/2014-SECCDC-Qualifiers-TeamPacket.pdf) F❌ | [Q✅](documents/SouthWest-SWCCDC/2014-SWCCDC-Qualifiers-TeamPacket.pdf) F❌ | [Q✅](documents/Western-WRCCDC/2014-WRCCDC-Qualifiers-TeamPacket.pdf) F❌ |
| 2015 | [F✅](documents/Nationals/2015-NCCDC-TeamPacket.pdf) | Q❌ [F✅](documents/AtLarge-ALCCDC/2015-ALCCDC-TeamPacket.pdf) | Q❌ [F✅](documents/MidAtlantic-MACCDC/2015-MACCDC-TeamPacket.pdf) | ❌ | [Q✅](documents/NorthEast-NECCDC/2015-NECCDC-Qualifiers-TeamPacket.pdf) [F✅](documents/NorthEast-NECCDC/2015-NECCDC-TeamPacket.pdf) | ❌ | ❌ | [Q✅](documents/SouthEast-SECCDC/2015-SECCDC-Qualifiers-TeamPacket.pdf) F❌ | [Q✅](documents/SouthWest-SWCCDC/2015-SWCCDC-Qualifiers-TeamPacket.pdf) F❌ | [Q✅](documents/Western-WRCCDC/2015-WRCCDC-Qualifiers-TeamPacket.pdf) F❌ |
| 2016 | [F✅](documents/Nationals/2016-NCCDC-TeamPacket.pdf) | ❌ | Q❌ [F✅](documents/MidAtlantic-MACCDC/2016-MACCDC-TeamPacket.pdf) | Q❌ [F✅](documents/MidWest-MWCCDC/2016-MWCCDC-TeamPacket.pdf) | Q❌ [F✅](documents/NorthEast-NECCDC/2016-NECCDC-TeamPacket.pdf) | ❌ | ❌ | ❌ | [Q✅](documents/SouthWest-SWCCDC/2016-SWCCDC-Qualifiers-TeamPacket.pdf) F❌ | Q❌ [F✅](documents/Western-WRCCDC/2016-WRCCDC-Invitational-TeamPacket.pdf) |
| 2017 | [F✅](documents/Nationals/2017-NCCDC-TeamPacket.pdf) | Q❌ [F✅](documents/AtLarge-ALCCDC/2017-ALCCDC-TeamPacket.pdf) | Q❌ [F✅](documents/MidAtlantic-MACCDC/2017-MACCDC-TeamPacket.pdf) | [Q✅](documents/MidWest-MWCCDC/2017-MWCCDC-Qualifiers-TeamPacket.pdf) [F✅](documents/MidWest-MWCCDC/2017-MWCCDC-State-TeamPacket.pdf) | [Q✅](documents/NorthEast-NECCDC/2017-NECCDC-Qualifiers-TeamPacket.pdf) [F✅](documents/NorthEast-NECCDC/2017-NECCDC-TeamPacket.pdf) | ❌ | ❌ | Q❌ [F✅](documents/SouthEast-SECCDC/2017-SECCDC-TeamPacket.pdf) | [Q✅](documents/SouthWest-SWCCDC/2017-SWCCDC-Qualifiers-TeamPacket.pdf) F❌ | ❌ |
| 2018 | [F✅](documents/Nationals/2018-NCCDC-TeamPacket.pdf) | ❌ | [Q✅](documents/MidAtlantic-MACCDC/2018-MACCDC-Qualifiers-TeamPacket.pdf) [F✅](documents/MidAtlantic-MACCDC/2018-MACCDC-TeamPacket.pdf) | Q❌ [F✅](documents/MidWest-MWCCDC/2018-MWCCDC-TeamPacket.pdf) | [Q✅](documents/NorthEast-NECCDC/2018-NECCDC-Qualifiers-TeamPacket.pdf) [F✅](documents/NorthEast-NECCDC/2018-NECCDC-TeamPacket.pdf) | ❌ | ❌ | ❌ | ❌ | ❌ |
| 2019 | [F✅](documents/Nationals/2019-NCCDC-TeamPacket.pdf) | Q❌ [F✅](documents/AtLarge-ALCCDC/2019-ALCCDC-TeamPacket.pdf) | [Q✅](documents/MidAtlantic-MACCDC/2019-MACCDC-Qualifiers-TeamPacket.pdf) [F✅](documents/MidAtlantic-MACCDC/2019-MACCDC-TeamPacket.pdf) | Q❌ [F✅](documents/MidWest-MWCCDC/2019-MWCCDC-TeamPacket.pdf) | [Q✅](documents/NorthEast-NECCDC/2019-NECCDC-Qualifiers-TeamPacket.pdf) [F✅](documents/NorthEast-NECCDC/2019-NECCDC-TeamPacket.pdf) | ❌ | ❌ | ❌ | [Q✅](documents/SouthWest-SWCCDC/2019-SWCCDC-Qualifiers-TeamPacket.pdf) [F✅](documents/SouthWest-SWCCDC/2019-SWCCDC-Finals-TeamPacket.pdf) | Q❌ [F✅](documents/Western-WRCCDC/2019-WRCCDC-Finals-TeamPacket.pdf) |
| 2020 | [F✅](documents/Nationals/2020-NCCDC-TeamPacket.pdf) | ❌ | [Q✅](documents/MidAtlantic-MACCDC/2020-MACCDC-Qualifiers-TeamPacket.pdf) [F✅](documents/MidAtlantic-MACCDC/2020-MACCDC-TeamPacket.pdf) | ❌ | ❌ | ❌ | ❌ | ❌ | ❌ | ❌ |
| 2021 | [F✅](documents/Nationals/2021-NCCDC-TeamPacket.pdf) | ❌ | ❌ | ❌ | Q❌ [F✅](documents/NorthEast-NECCDC/2021-NECCDC-Regional-TeamPacket.pdf) | ❌ | ❌ | ❌ | ❌ | ❌ |
| 2022 | ❌ | ❌ | [Q✅](documents/MidAtlantic-MACCDC/2022-MACCDC-Qualifiers-TeamPacket.pdf) [F✅](documents/MidAtlantic-MACCDC/2022-MACCDC-TeamPacket.pdf) | ❌ | ❌ | ❌ | ❌ | ❌ | ❌ | ❌ |
| 2023 | ❌ | ❌ | [Q✅](documents/MidAtlantic-MACCDC/2023-MACCDC-Qualifiers-TeamPacket.pdf) F❌ | Q❌ [F✅](documents/MidWest-MWCCDC/2023-MWCCDC-Regional-TeamPacket.pdf) | [Q✅](documents/NorthEast-NECCDC/2023-NECCDC-Qualifiers-TeamPacket.pdf) [F✅](documents/NorthEast-NECCDC/2023-NECCDC-Regional-TeamPacket.pdf) | ❌ | ❌ | ❌ | ❌ | ❌ |
| 2024 | ❌ | ❌ | ❌ | Q❌ [F✅](documents/MidWest-MWCCDC/2024-MWCCDC-Regional-TeamPacket.pdf) | [Q✅](documents/NorthEast-NECCDC/2024-NECCDC-Qualifiers-TeamPacket.pdf) [F✅](documents/NorthEast-NECCDC/2024-NECCDC-Regional-TeamPacket.pdf) | ❌ | ❌ | ❌ | ❌ | ❌ |
| 2025 | [F✅](documents/Nationals/2025-NCCDC-TeamPacket.pdf) | ❌ | ❌ | Q❌ [F✅](documents/MidWest-MWCCDC/2025-MWCCDC-Regional-TeamPacket.pdf) | [Q✅](documents/NorthEast-NECCDC/2025-NECCDC-Qualifiers-TeamPacket.pdf) [F✅](documents/NorthEast-NECCDC/2025-NECCDC-Regional-TeamPacket.pdf) | ❌ | ❌ | [Q✅](documents/SouthEast-SECCDC/2025-SECCDC-Qualifiers-TeamPacket.pdf) [F✅](documents/SouthEast-SECCDC/2025-SECCDC-Regionals-TeamPacket.pdf) | ❌ | ❌ |
| 2026 | ❌ | Q❌ [F✅](documents/AtLarge-ALCCDC/2026-ALCCDC-TeamPacket.pdf) | ❌ | Q❌ [F✅](documents/MidWest-MWCCDC/2026-MWCCDC-Regional-TeamPacket.pdf) | [Q✅](documents/NorthEast-NECCDC/2026-NECCDC-Qualifiers-TeamPacket.pdf) [F✅](documents/NorthEast-NECCDC/2026-NECCDC-Regional-TeamPacket.pdf) | [Q✅](documents/RockyMountain-RMCCDC/2026-RMCCDC-Qualifiers-TeamPacket.pdf) | ❌ | [Q✅](documents/SouthEast-SECCDC/2026-SECCDC-Qualifiers-TeamPacket.pdf) [F✅](documents/SouthEast-SECCDC/2026-SECCDC-Regionals-TeamPacket.pdf) | ❌ | ❌ |

## Code of Conduct

This project follows the [Citizen Code of Conduct](code_of_conduct.md). Please read it before contributing.

## License

This project is licensed under the [MIT License](LICENSE).

---

Please report incorrect information or broken links via [GitHub Issues](https://github.com/mubix/howtowinccdc/issues).
