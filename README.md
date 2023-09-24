# shelfy

## Decisions

Design

- I designed for 3 resolutions in Figma, based on how the current Mailersend website reacted to sizes. All 3 resolutions were from Figma’s suggested device sizes list.
- I took Mailersend’s ISO part of the logo resembling an S and used it for a new fictional logo of the book service brand “Shelfy”.
- In general I followed Mailersend’s style with a few design licenses due to Information architecture.

Tech

- For a matter of code reviewing and the smallest file sizes possible: I used several CSS sheets, also I’ve separated for static mobile-first code and responsive changes.
- A known issue React.js has with “sticky” elements (Mailersend’s tech stack includes an outdated version though, honestly I don’t know if that issue was solved): Decided to use it anyways and not the “traditional” fixed positioning for the header of the page.
- In conclusion, it would have been a lot better to use Tailwind+Sass or at least Sass to follow a set of variables, but it was fun to complete the assignment coding a bit like the old days.
