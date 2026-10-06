# Borozdov Apothecary

A theme from the Borozdov collection. Two faces — light **Tincture**, a warm apothecary
journal on parchment, and dark **Mortar**, the same journal read by lamplight after the
shop closes. Warm ink carries every word on both; the only colour is a single
terracotta-clay seal that marks a link, a tag or a button, like wax pressed onto a
label. Style source: Refero #59 Function, "Warm apothecary journal".

![Borozdov Apothecary in light mode](https://raw.githubusercontent.com/borozdov-obsidian-themes/apothecary/main/screenshots/light.png)

![Borozdov Apothecary in dark mode](https://raw.githubusercontent.com/borozdov-obsidian-themes/apothecary/main/screenshots/dark.png)

## Principles

- **Parchment, never white.** Every surface sits in a warm cream range — Parchment for
  the canvas, Aged Paper one step deeper for cards — the way the source card insists a
  clinical white would break the mood.
- **One terracotta seal.** A single clay accent marks a link, a tag and the filled
  button — Terracotta Seal by day, brightened so it still reads as a seal against
  Mortar's dark page by night. Nothing else on the page carries a tint besides the
  pastel callout washes.
- **A ladder of warm greys.** Ink for headings, a softer Charcoal for running text,
  Graphite for muted labels — three steps that never turn cold, plus the one
  cool-leaning grey the source card reserves strictly for form borders.
- **A hairline builds every card.** Callouts, code panes, tables and popovers round to
  a generous 20px corner with a 1px rim, never a shadow — the source card's own
  card language, just without the drop shadows it uses on a marketing page.
- **Journal paper underfoot.** A faint dot grid rides under every note, in the same
  hairline the rest of the page is built from — barely there, never a distraction.
- **Developer-native type.** The platform's own sans stands in for the source card's
  serif-and-sans pairing; no embedded font, no load, no flash of unstyled text.

## Features

- Light and dark modes, following Settings → Appearance → Base color scheme
- Callouts, code blocks, embeds, tables and popovers drawn as the same hairline-rimmed
  card at a 20px radius
- A table draws its own rounded frame; cells only carry the inner grid, so no edge is
  ever doubled
- Tags and the primary button round to a full pill, filled with the same terracotta
  seal the source card uses for its own key badges
- The highlighter stays an opaque cream or amber with ink on top, so a note never grows
  an olive smear by night
- Quiet editing: no focus ring around the note, its title or form fields while you
  type; property names read as labels, not boxed fields
- A toggle thumb tuned per face so it never disappears against its own track
- Text colours meet WCAG contrast on both faces
- The phone layout keeps the same colours and shapes
- No embedded fonts, so the theme stays well under the directory's size limit
- No `!important`: every rule can be overridden with a CSS snippet

## Installation

**From the community directory, as a variant:** this theme ships inside **Borozdov
Trellis**. Install Borozdov Trellis under Settings → Appearance → Themes → Manage, then
the [Style Settings](https://github.com/mgmeyers/obsidian-style-settings) plugin, and
choose **Apothecary** under Style Settings → Borozdov Trellis → Variant. The variant
brings this theme's palette, type and corners; its own layout, and its embedded font if it
has one, come with the full theme below.

**The full theme, by hand:** download `manifest.json` and `theme.css` from the
[latest release](https://github.com/borozdov-obsidian-themes/apothecary/releases/latest)
into `<vault>/.obsidian/themes/Borozdov Apothecary/`, then choose Borozdov Apothecary
under Settings → Appearance → Themes.

## License

MIT — see [LICENSE](LICENSE).

---

**По-русски.** Тема из коллекции Borozdov. Два лика: светлый «Tincture» — тёплый
дневник аптекаря на пергаменте, и тёмный «Mortar» — тот же дневник при свете лампы
после закрытия лавки. Тёплые чернила несут любой текст на обоих ликах; единственный
цвет — терракотовая печать, которой помечены ссылка, тег и кнопка. Шрифты не встроены.
В каталоге тема живёт вариантом Borozdov Trellis: установите Borozdov Trellis и плагин Style Settings, затем выберите Apothecary в Style Settings → Borozdov Trellis → Variant. Целиком, со своей вёрсткой, тема ставится вручную из последнего релиза репозитория.
