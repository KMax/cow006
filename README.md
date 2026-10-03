# Cow 006 Score Keeper (Корова 006 / 6 nimmt!)
> 🐮 **Live App:** [**https://kolchinmax.ru/cow006/**](https://kolchinmax.ru/cow006/)

[Cow 006](https://ru.wikipedia.org/wiki/%D0%9A%D0%BE%D1%80%D0%BE%D0%B2%D0%B0_006) (Russian: «Корова 006») is a popular card game designed by Wolfgang Kramer — the Russian edition of the famous game **[6 nimmt!](https://en.wikipedia.org/wiki/6_nimmt!)** (also known as *Take 5!* / *Take 6!* / *Category 5*).

This project is a lightweight, mobile-first web application designed for scoring rounds in real life without pen and paper.

---

## 🎯 Purpose & Why This App?

When playing **Cow 006 / 6 nimmt!**, remembering and recalculating penalty points (*bull heads / cows*) between consecutive rounds can be tedious:
- Each round, players collect penalty cards containing 1, 2, 3, 5, or 7 bull heads.
- Under official rules, the game ends as soon as any player accumulates **66 penalty points**, with the player having the **fewest points winning**.
- Keeping track on paper is slow, prone to math errors, and easy to lose.

This app solves the problem by providing a fast, fun, and zero-setup score keeper that anyone at the table can open directly in their mobile or desktop browser.

---

## ✨ Features

- **🐮 Themed UI**: Styled after the secret-agent cow aesthetics of the game.
- **📱 Mobile-First**: Responsive layout optimized for phones and tablets on the game table.
- **👥 Custom Player Names**: Add players with any fictional nicknames; fun avatar icons are assigned automatically.
- **⚡ Fast Score Input**: Enter round penalty totals per player in seconds.
- **📊 Live Leaderboard & 66-Point Warning**:
  - Highlights the current leader (lowest penalty points).
  - Visual progress bar towards the 66-point threshold.
  - Warning indicators for scores approaching 50+ and 66+ points.
- **📜 Round History Table**: View score breakdown per round with running cumulative totals and an *Undo Round* feature.
- **🏆 End Game Summary**: Instant podium, rankings, and one-click rematch options.
- **🔒 Zero-Backend & Privacy Friendly**: All data is stored purely in the browser (`localStorage`). No external databases, accounts, or tracking.

---

## 📜 Game Rules Reference

- **Deck**: 104 numbered cards (1–104).
- **Goal**: Collect as few penalty points (bull heads) as possible.
- **Placement**: Cards played simultaneously are placed in ascending order into one of 4 rows, choosing the row with the lowest positive difference.
- **6th Cow Rule**: The 6th card in any row takes the preceding 5 cards as penalty points.
- **Game Over**: Game finishes at the end of the round in which any player reaches or exceeds **66 points**.

---

## 📄 License

MIT License. See [LICENSE](LICENSE) for details.
