# Reputation Decision-Making Game (Python & Data Handling)

An interactive, data-driven simulation game built in Python that models professional scenario-based decision making and quantifies the impact on a player's reputation score.

## 🚀 Key Technical Features
- **Data-Driven Architecture**: Dynamically loads complex game scenarios, options, and impact metrics directly from structured CSV files (`csv.DictReader`).
- **Robust Exception Handling**: Implements strict data validation for empty fields and out-of-bounds player inputs.
- **Dynamic Score Scaling**: Computes and normalizes absolute scores into relative percentages (-100% to +100%) based on mathematical bounds (min/max analysis).
- **Persistent Storage**: Automatically logs and appends player profiles and final analytical results onto a local tracking database (`results.csv`).
- **Modular Programming**: Formatted with clean, production-grade modular design (`if __name__ == '__main__': main()`).

## 🛠️ Tech Stack
- **Language**: Python 3.x
- **Core Modules**: `csv` (Data manipulation), Standard I/O

## 📦 How to Run
1. Ensure you have `scenarios_batch.csv` in the same directory.
2. Run the program via terminal:
   ```bash
   python reputation_game.py
