# Translation Policy

The key words "MUST", "MUST NOT", "REQUIRED", "SHALL", "SHALL NOT", "SHOULD",
"SHOULD NOT", "RECOMMENDED", "MAY", and "OPTIONAL" in this document are to be
interpreted as described in [RFC 2119](https://tools.ietf.org/html/rfc2119).

## Newly Requested Languages

Accepted when:

- Submitted in .po form to the project maintainers
- 85 % of the main game strings and the main level and worldmap strings MUST be
  translated
- 25 % of the add-on strings MUST be translated

## Existing Languages

Removed from the game's source code as soon as:

- Less than 75 % of the main game strings and the main level and worldmap
  strings are translated
- Less than 20 % of the add-on strings are translated
- The translation has not been updated in the last three (3) months

Even when removed from the source code, translations SHOULD be kept on the
translation platform (currently: Transifex).

In case they meet the requirements again, they MAY be added to the source code
again.

## Decisions

The following decisions in regards to translation policies were made and
documented:

1. Initional decision on newly requested and existing languages
   - Translation policy RFC (#351)
     - For newly requested languages: Submitted in .po form to the projects
       maintainers, 85 % of main game and mainlevels translated, 25 % of the
       add-ons
     - :+1: @Hume2, @kneekoo, @tobbi, @giby, @maxteufel
     - **Result:** PASS
     - Remove them from the game when less than 75 % of the main game and
       main levels and 20 % of the addons are translated, and the translation
       has not been updated for 3 months. Keep them on Transifex. (Add them
       back once they reach the requirements)
     - :+1: @Hume2, @kneekoo, @tobbi, @giby, @maxteufel
     - **Result:** PASS
   - [SuperTux/supertux#351](https://github.com/SuperTux/supertux/issues/351)
   - [SuperTux/supertux#435
     (comment)](https://github.com/SuperTux/supertux/issues/435#issuecomment-225631252)
