# Licensing Guide — GodAlone Open Source

This file is the single source of truth for which license applies to which
kind of content across the GodAlone organization. Every repo's own
`LICENSE` file should be one of the licenses below; this page explains why.

| Content Type | Recommended License | Why |
|---|---|---|
| Software / source code | **MIT** | Permissive, extremely well understood, minimal friction for reuse. (Apache-2.0 is a fine alternative if explicit patent-grant language is ever needed.) |
| Quran Arabic text (Uthmani/Hafs) | **CC0** or **CC-BY** on the compiled dataset | The Arabic text itself carries no proprietary claim; the *compiled, versioned dataset* in `quran-data` is released openly, with clear sourcing documented in `ATTRIBUTIONS.md`. |
| Quran translations (e.g. a named translator's work) | **Only what the translator/rights-holder has authorized** | A translation is the translator's copyrighted work. Never included in a public repo without confirmed permission — see `ATTRIBUTIONS.md` process. If unconfirmed, link to the authorized source instead of hosting the full text. |
| Original written content (articles, docs, calculator explanations) | **CC-BY-4.0** | Freely shareable and adaptable with attribution. |
| Books, videos, audio created by the project | **CC-BY-4.0** or **CC-BY-SA-4.0** | Use CC-BY-SA-4.0 if you want derivative works to remain open too (share-alike). |
| Third-party media, fonts, recitation audio | **Original license only — never relicensed** | Credited in that repo's `ATTRIBUTIONS.md`; included only when the original license permits redistribution. |
| Databases / structured data | **CC0** or **ODbL-1.0** | CC0 for maximum reuse; ODbL if share-alike protection on the data specifically is wanted. |

## Rule of thumb

If you didn't create it and don't have clear, confirmed permission to
redistribute it, it doesn't go in a public repo as full content — link to
the authorized source and credit it in `ATTRIBUTIONS.md` instead.

Full license texts are in the `LICENSES/` folder of this starter kit, or
can be fetched from [choosealicense.com](https://choosealicense.com) /
[SPDX](https://spdx.org/licenses/).
