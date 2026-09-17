# ⏰ Clock Application

A C++ application developed by [adarsh0707-kumar](https://github.com/adarsh0707-kumar) featuring time tracking, digital clock routines, stopwatch management, and timer functions.

---

## 📌 Features

- **Digital Clock Display**: Displays real-time system clock in 12-hour or 24-hour formats.
- **Stopwatch**: Real-time timer with start, stop, pause, and lap features.
- **Countdown Timer**: Customizable duration timer with terminal/GUI alerts upon completion.
- **Cross-Platform Compatibility**: Supports Linux, macOS, and Windows build environments using standard C++ features.

---

## 📁 Repository Structure

```text
Clock/
├── include/          # Header files (.h / .hpp)
├── src/              # Source code implementations (.cpp)
├── build/            # Compiled output binaries
├── Makefile          # Build automation configuration
├── README.md         # Project documentation
└── CONTRIBUTING.md   # Guidelines for contributors
```

---

## 🚀 Getting Started

### Prerequisites

Ensure you have a C++ compiler supporting **C++17** or higher and `make` installed:

- **GCC / G++** (`g++`) or **Clang**
- **Make** (`make`) or CMake

#### Installing prerequisites on Linux (Ubuntu/Debian):
```bash
sudo apt update
sudo apt install build-essential
```

---

## 💻 Building and Running

### 1. Clone the Repository
```bash
git clone https://github.com/adarsh0707-kumar/Clock.git
cd Clock
```

### 2. Compile the Project
Using the provided `Makefile`:
```bash
make
```

Alternatively, compile directly via `g++`:
```bash
g++ -std=c++17 -Iinclude src/*.cpp -o build/clock
```

### 3. Run the Program
```bash
./build/clock
```

---

## 📄 License

This project is open-source and available under the [MIT License](LICENSE).