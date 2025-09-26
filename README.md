# 🎰 Lucky Spin (Go Console Game)

A simple slot machine–style game built with **Go**.
Play by placing bets, spinning the reels, and winning based on symbol multipliers.

---

## 🚀 How to Play
1. Download the latest release from [Releases](https://github.com/Mo7amed3nan/Lucky-Spin/releases/download/v1.0.0/lucky-spin.exe).
2. Run `lucky-spin.exe` (it opens in your terminal).
3. Enter your name, place your bet, and spin!


---

## 🛠️ Build from Source

If you want to build it yourself:

```bash
git clone https://github.com/<your-username>/<repo-name>.git
cd <repo-name>
go mod tidy
go build -o bin/lucky-spin.exe
```

---

## 📂 Project Structure

* `main.go` → game loop and logic
* `spin.go` → slot machine spin logic
* `utils.go` → user input helpers
* `bin/lucky-spin.exe` → prebuilt executable

---

## ✨ Features

* Console-based interactive slot game
* 4 symbols (A, B, C, D) with custom multipliers
* Betting system with balance tracking
* Spin until you run out of balance or quit

---

Enjoy spinning 🎉
