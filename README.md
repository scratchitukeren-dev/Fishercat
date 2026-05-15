# 🎣 Fishercat Esolang 🐱

Welcome to **Fishercat**, a creative and fun Esoteric Programming Language (Esolang) created by **scratchitukeren-dev**! 🚀

## 📖 The Story Behind Fishercat
Imagine a poor, patient cat sitting by the ocean with a fishing rod 🌊. The cat hopes to catch some delicious fish, but the ocean is full of digital pollution! Every time the cat pulls the line, instead of a fish, it catches "digital trash" like random numbers, timestamps, hooks, or empty bubbles. 

Despite only catching garbage, the cat never gives up and just says: **"still fishing lol!!"** 😹

---

## 🛠️ How It Works (The Fishing Rules)
Fishercat compiles your text file character by character. Depending on what letter the cat "fishes" out, it appends a specific piece of digital trash to the `Data Table`:


| Character | What it do |  
| :---: | :--- | 
| `[Space/Enter]` | `Add 00 to Data Table` | 
| `r` | `Add RANDOM Number to Data Table` | 
| `d` | `Add Current Timestamp to Data Table` | 
| `s` | `` | 
| `c` | `Duplicates current data` | 
| `i` | `\|` | 
| `y` | `~` | 
| `m` | `{{` | 

---

## 🚀 Installation & Usage

Fishercat acts like a real compiler with no file extension! Follow these steps to run it on your Linux terminal:

### 1. Give Execution Permission
Before running Fishercat for the first time, make it executable:
```bash
chmod +x fishercat
```

### 2. Create a Bait File
Create a simple text file (e.g., `test.txt`) with some characters for the cat to fish:
```bash
echo "r d s c m" > test.txt
```

### 3. Start Fishing!
Run the compiler by passing your bait file as an argument:
```bash
sh fishercat [file name].txt
```

---


## Feel free to fork this repository, add more digital trash to the ocean, and help the cat keep fishing! 🐱🐟

