# Japanese Riichi Mahjong: WRC 2025 Beginner Guide

> **Scope:** Japan / international riichi
> **Version:** WRC Rules 2025 baseline
> **Summary:** Learn yaku, riichi, furiten, dora, calls, and the 2025 World Riichi Championship baseline.

## Version notice

This guide uses the World Riichi Championship 2025 rules as a published
baseline. Platforms, leagues, and local tables may differ on red fives, abortive
draws, multiple wins, nagashi mangan, and responsibility payments.

## Equipment and goal

Four players use 136 tiles, normally without Flowers. A standard win is four
sets and a pair; seven pairs and thirteen orphans are common special structures.
A legal win requires at least one yaku. Dora increase value but are not yaku by
themselves.

## Calls and riichi

A chi may be called only from the player on the left. Pon, kan, and ron can use
another player's discard. Calling usually opens the hand and removes access to
many concealed yaku.

A player with a closed tenpai hand may declare riichi by placing a 1,000-point
stick and turning the discard sideways. After riichi, choices are restricted.

## Furiten

Furiten prevents a player from winning by ron when their waits conflict with
their own discard history or when they pass a legal winning discard under the
applicable temporary or riichi rule. Self-draw may still be possible. Beginners
should check their full wait, not only the tile they hope to receive.

## Han, fu, and payment formula

For a non-limit hand, calculate base points and round each payment up to the
next 100 points:

```text
base_points = fu x 2^(han + 2)
```

| Win | Raw payment before rounding |
|---|---|
| Non-dealer ron | `base_points x 4` paid by discarder |
| Dealer ron | `base_points x 6` paid by discarder |
| Non-dealer tsumo | dealer pays `base x 2`; each non-dealer pays `base x 1` |
| Dealer tsumo | every non-dealer pays `base x 2` |

Limit tiers replace the raw formula when the WRC 2025 mangan-or-higher
conditions apply. Honba, riichi deposits, responsibility payments, and event
rounding then follow the same rulebook.

Example: a non-dealer wins by ron with 30 fu and 3 han.

```text
base = 30 x 2^(3+2) = 960
raw ron = 960 x 4 = 3840
round up to next 100 = 3900
```

Dora add han after the hand has a yaku; they never create the required yaku by
themselves.

## Beginner strategy

Prioritize a clear yaku such as riichi, tanyao, yakuhai, pinfu, or a suited
pattern. Keep the hand closed when the riichi and concealment value outweigh the
speed of a call. Track dealer position, dora, safe tiles, and opponents' riichi
discards before pushing an expensive risk.

## Sources and version control

- https://www.worldriichi.org/wrc-rules
- https://www.worldriichi.org/s/WRC-Rules-2025-42fx.pdf

Source links and version notes were last checked on 2026-07-11. Tournament, annual, platform, and local rules take precedence.

## About INEAN PLAY

INEAN PLAY provides automatic OKEY tables, automatic American Mahjong tables,
compatible magnetic OKEY tiles, player racks, manuals, and support resources.
Rule compatibility and table specifications should always be confirmed for the
exact product and game version.

- Website: [ineanplay.com](https://ineanplay.com/)
- WhatsApp: [+86 173 7839 0199](https://wa.me/8617378390199)
- Email: [service@ineanplay.com](mailto:service@ineanplay.com)
- Facebook: [INEAN PLAY](https://www.facebook.com/profile.php?id=61585370578775)
- Instagram: [@ineanplay](https://www.instagram.com/ineanplay/)
- TikTok: [@ineanplay](https://www.tiktok.com/@ineanplay)
- YouTube: [@ineanplay](https://www.youtube.com/@ineanplay)
