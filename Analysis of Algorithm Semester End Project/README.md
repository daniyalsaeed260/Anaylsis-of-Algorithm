# Closest Pair Quest 

##  Quick Start (No Installation Required!)

Since you don't have a Python installed, here's the **fastest way** to run the game:

### Option 1: Use Online Python (3 minutes, NO installation!)

1. **Copy the code** from `closest_pair_quest.cpp`
2. Go to one of these online compilers:
   - **https://www.onlinegdb.com/online_c++_compiler** (Recommended)
   - **https://replit.com/languages/cpp**
   - **https://www.programiz.com/cpp-programming/online-compiler/**

3. **Paste the code** and click "Run"
4. **Download the generated HTML file** from the output
5. **Open the HTML file** in your browser

### Option 2: Install MinGW (if you want to run locally)

1. Download MinGW from: https://sourceforge.net/projects/mingw/
2. Or install via Chocolatey: `choco install mingw`
3. After installation, compile:
   ```bash
   g++ -o closest_pair_quest.exe closest_pair_quest.cpp -std=c++17
   ./closest_pair_quest.exe
   ```
4. Open the generated `closest_pair_game.html` in your browser

##  Files Included

- `closest_pair_quest.cpp` - Complete C++ implementation
- This program will:
  - Generate 50 random points
  - Run Brute Force algorithm
  - Run Divide & Conquer algorithm
  - Compare execution times
  - Generate a beautiful HTML visualization

##  What You'll See

The program outputs:
- Console results showing algorithm times
- An HTML file with:
  - Interactive canvas showing all points
  - Highlighted closest pair (red dots)
  - Line connecting the closest pair
  - Performance statistics
  - Beautiful dark theme UI

##  How It Works

1. **Brute Force**: Compares every pair of points - O(n²)
2. **Divide & Conquer**: Recursively splits the problem - O(n log n)
3. **Result**: See how much faster D&C is!

---

**Need Help?** Just paste the C++ code into an online compiler - it works immediately with zero setup!

