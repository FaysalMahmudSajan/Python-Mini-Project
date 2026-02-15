# Python-Mini-Projects


## 1. API
`cd Python-Mini-Project/API`

A simple desktop application that displays random Kanye West quotes with every button click. Built with Python and Tkinter, powered by the kanye.rest API.

![Kanye West Quote Generator](API/API_1/kanye.png)

## 2. Auction-Bid
`cd auction_bid`
### Secret Auction Program 🤫

A simple command-line secret auction program where bidders can place anonymous bids, and the highest bidder wins!

### Features
- Anonymous bidding system
- Clear screen between bids for privacy
- Automatic winner determination
- Maximum bid tracking

### How It Works 
1. Enter your name when prompted
2. Place your bid amount (in $)
3. Indicate if there are more bidders
4. The screen clears between bids for privacy
5. Winner is announced when bidding ends

### Usage
```bash
python program_my.py
```
### Example
```
Welcome to the secret auction program
What is your name?: John
What's your bid?: $150
Are there any other bidders? Type 'yes' or 'no'. yes

What is your name?: Sarah
What's your bid?: $250
Are there any other bidders? Type 'yes' or 'no'. no
Sarah is winning the bid by $250
```

## 3. Bootstrap
A simple demonstration of Bootstrap's responsive grid system with colorful examples.

## 4. Calculator

A simple command-line calculator that supports continuous calculations with the result.

### Features 
- Basic operations: +, -, *, /
- Continue calculations with previous result
- Start fresh calculations anytime
- Clear screen between operations

### Calculation Flow
1. Enter first number
2. Choose operation (+, -, *, /)
3. Enter second number
4. View result
5. Choose to:
   - Continue with result (Type 'y')
   - Start new calculation (Type 'n')

### Example
```
What's the first number?: 10
'+' , '-' , '*' , '/'
Pick an operation: +
What's the next number?: 5
10 + 5 = 15

Type 'y' to continue with 15, or 'n' to start new: y
Pick an operation: *
What's the next number?: 3
15 * 3 = 45
```
## 5. Ceaser Chiper

Two versions of a classic Caesar cipher implementation for encoding and decoding secret messages.

### Features 
- **Encode**: Shift letters forward to encrypt messages
- **Decode**: Shift letters backward to decrypt messages
- **Loop Support**: Continue encoding/decoding multiple messages
- **Preserves Non-Letters**: Spaces and special characters remain unchanged (v2)
- **Wrap-around**: Letters wrap around the alphabet (z → a)

### v1: encode_decode.py
- Separate encode/decode functions
- Manual ASCII manipulation
- Basic alphabet wrapping

### v2: update_cease_chiper.py
- Unified caesar() function
- List-based alphabet handling
- Preserves spaces/special chars
- Cleaner modulo 26 wrapping

### Encoding
```
Original: hello
Shift: 5
Result: mjqqt
```

### Decoding  
```
Encoded: mjqqt
Shift: 5
Result: hello
```

## 6. Coffee Machine

A virtual coffee machine simulation that serves espresso, latte, and cappuccino with resource management and payment processing.

#### 1. **mycode.py** - Single File Version
A self-contained coffee machine with all functionality in one file.

#### 2. **Modular OOP Version** (Multiple Files)
- **main.py** - Main program loop
- **menu.py** - Menu and MenuItem classes
- **coffee_maker.py** - CoffeeMaker class for resource management
- **money_machine.py** - MoneyMachine class for payment processing

#### 3. **courseCode.py** - Course Reference Version
Original course implementation with global variables.

### Features

- **3 Drink Options**: Espresso ($1.5), Latte ($2.5), Cappuccino ($3.0)
- **Resource Management**: Tracks water, milk, coffee levels
- **Coin Processing**: Accepts quarters, dimes, nickles, pennies
- **Transaction Handling**: Calculates change, tracks profit
- **Admin Features**: 
  - "report" - View resource levels and profit
  - "off" - Shutdown the machine

### Order Flow
1. User selects a drink
2. System checks sufficient resources
3. User inserts coins
4. System verifies payment
5. Coffee is made (resources deducted)
6. Change returned if applicable

### Resource Requirements
| Drink | Water | Milk | Coffee | Cost |
|-------|-------|------|--------|------|
| Espresso | 50ml | 0ml | 18g | $1.50 |
| Latte | 200ml | 150ml | 24g | $2.50 |
| Cappuccino | 250ml | 100ml | 24g | $3.00 |


# 7. Desktop Calculator 

A fully-featured desktop calculator application with a modern GUI, built with Python Tkinter. Supports basic arithmetic, scientific functions, and calculation history.

### Basic Operations
- Addition (+), Subtraction (−), Multiplication (×), Division (÷)
- Percentage (%)
- Sign toggle (±)
- Decimal point (.)
- Clear (C) and Clear Entry (CE)
- Backspace (⌫)

### Scientific Functions
- Square root (√)
- Square (x²)

### Advanced Features
- **Calculation History**: Stores last 50 calculations
- **Keyboard Support**: Full keyboard input support
- **Memory Display**: Shows pending operations
- **History Persistence**: Saves history between sessions
- **Responsive UI**: Button hover effects
- **Error Handling**: Division by zero protection

### Installation 

1. Ensure Python 3.x is installed
2. No additional packages required (uses standard library)
3. Download or clone the repository

# 8. Flask
practiced Flask

# 9. Guess the number

A fun command-line game where players guess a random number between 1 and 100 with different difficulty levels.

### Features 

- **Random Number Generation**: 1-100 range
- **Two Difficulty Levels**:
  - Easy Mode: 10 attempts
  - Hard Mode: 5 attempts
- **Hint System**: "Too high" or "Too low" feedback
- **Replay Protection**: Invalid input restarts selection
- **Attempt Counter**: Shows remaining guesses

### How to Play 

1. Game generates a random number between 1-100
2. Choose difficulty: 'easy' (10 tries) or 'hard' (5 tries)
3. Make guesses based on hints
4. Win by guessing correctly before attempts run out

# 10. Hangman
A classic word-guessing game where players try to save a stick figure from hanging by guessing letters correctly.

### Features 

- **ASCII Art Display**: Visual hangman progression
- **Random Word Selection**: From predefined word list
- **Letter Guessing System**: Track correct/incorrect guesses
- **Lives System**: 6 attempts before game over
- **Visual Feedback**: Shows hangman stage for wrong guesses
- **Win/Lose Detection**: Automatic game end conditions

### ascii_art.py
- Title ASCII art display
- 7 stages of hangman progression (6 lives + start)

### hangman.py
- Main game logic
- Word selection
- Guess processing
- Game state management

### How to Play 🎯

1. Game randomly selects a word
2. Guess one letter at a time
3. Correct letters reveal positions
4. Wrong letters add to hangman
5. Win by revealing all letters
6. Lose after 6 wrong guesses

### Title Art

```  

| |                                            
| |__   __ _ _ __   __ _ _ __ ___   __ _ _ __  
| '_ \ / _` | '_ \ / _` | '_ ` _ \ / _` | '_ \ 
| | | | (_| | | | | (_| | | | | | | (_| | | | |
|_| |_|\__,_|_| |_|\__, |_| |_| |_|\__,_|_| |_|
                    __/ |                      
                   |___/     

```

### Hangman Stages

```
Stage 0 (Game Over):
  +---+
  |   |
  O   |
 /|\  |
 / \  |
      |
=========

Stage 6 (Start):
  +---+
  |   |
      |
      |
      |
      |
=========
```

# 11. Guess the number
```
    __  ___       __             
   / / / (_)___ _/ /_  ___  _____
  / /_/ / / __ `/ __ \/ _ \/ ___/
 / __  / / /_/ / / / /  __/ /    
/_/ ///_/\__, /_/ /_/\___/_/     
   / /  /____/_      _____  _____
  / /   / __ \ | /| / / _ \/ ___/
 / /___/ /_/ / |/ |/ /  __/ /    
/_____/\____/|__/|__/\___/_/     

You're right! Current score: 3

Compare A: Instagram, a Social media platform, from United States.
 _    __    
| |  / /____
| | / / ___/
| |/ (__  ) 
|___/____(_)

Against B: Cristiano Ronaldo, a Footballer, from Portugal.
Who has more followers? Type 'A' or 'B': 
```

A fun guessing game where players compare follower counts of celebrities, brands, and social media accounts!

### Game Overview 🎮

Test your knowledge of social media popularity! Players see two accounts and must guess which one has more followers. The game continues until a wrong guess is made.

### Features 

- **Real Data**: 50+ celebrity and brand follower counts
- **Continuous Gameplay**: Score increases with correct guesses
- **Visual ASCII Art**: Eye-catching logo and VS display
- **Random Selection**: Different accounts each round
- **Score Tracking**: Running total of correct guesses
- **Clean Interface**: Screen clears between rounds


### How to Play

1. Game shows two accounts (A and B)
2. Each account shows: name, description, country
3. Guess which has MORE followers
4. Type 'A' or 'B' to answer
5. Correct answer = +1 point and continue
6. Wrong answer = Game Over with final score

```python
{
    'name': 'Cristiano Ronaldo',
    'follower_count': 215,  # in millions
    'description': 'Footballer',
    'country': 'Portugal'
}
```

# 12. High_low


A simple web-based number guessing game built with Flask. Guess a number between 0 and 9 and get instant feedback!

### Features 

- **Web Interface**: Clean, browser-based gameplay
- **Random Numbers**: Server generates random target each session
- **Visual Feedback**: Different GIFs for each outcome
- **URL-Based Guessing**: Guess by visiting `/your-number`
- **Instant Response**: Immediate feedback on guesses

### How It Works 

1. Visit the homepage (`/`) to start
2. Server generates a random number (0-9)
3. Make guesses by visiting `/[your-guess]`
4. Get visual feedback:
   - **Correct**: Celebration GIF
   - **Too High**: "Too high" GIF
   - **Too Low**: "Too low" GIF

### Routes 

| Route | Description |
|-------|-------------|
| `/` | Homepage with game instructions |
| `/<int:num>` | Make a guess (0-9) |


# 13. Higher-lower-Start
A fun guessing game where players compare follower counts of celebrities, brands, and social media accounts!

##  Files

- `Game.py` - Your personal implementation
- `game.py` - Course/reference implementation
- `Game_Data.py` - Follower count database (50+ entries)
- `art.py` - ASCII art assets (logo and VS display)

##  How to Play

1. Run either `Game.py` or `game.py`
2. Compare two accounts (A vs B)
3. Guess which has MORE followers
4. Type 'A' or 'B' to answer
5. Correct = +1 point and continue
6. Wrong = Game Over with final score

### Sample Data
```
{
    'name': 'Cristiano Ronaldo',
    'follower_count': 215,  # millions
    'description': 'Footballer',
    'country': 'Portugal'
}
```
# 14. Love Calcular 💕

A fun Python program that calculates love compatibility between two names!

### Files

- `LoveCalcular.py` - Basic version
- `LoveCalculator(fast).py` - Function-based version

### How It Works

The calculator counts specific letters in both names:

- **TRUE Letters** (T,R,U,E) → First digit
- **LOVE Letters** (L,O,V,E) → Second digit
### Example:
```
Welcome to the Love Calculator!
What is your name? 
John
What is their name? 
Jane

Result: 34%
```
# 15. Mail Merge Project
A Python script that generates personalized letters for multiple recipients by replacing placeholders with actual names.
# 16. Password-Generantor

A simple Python script that generates random, secure passwords based on user preferences!

### File

- `PyPassword_Generator.py` - Main password generator script

### How It Works

The generator creates a random password using:
- **Letters** (a-z, A-Z)
- **Numbers** (0-9)
- **Symbols** (! # $ % & ( ) * +)


### Example
```
Welcome to the PyPassword Generator!
How many letters would you like?: 4
How many numbers would you like?: 2
How many symbols would you like?: 2

password is: aB3$kL9@m
```
# 17. Rock-Paper-Scissors
Rock:
```
   _______
---'   ____)
      (_____)
      (_____)
      (____)
---.__(___)
```
Paper:
```
    _______
---'   ____)____
          ______)
          _______)
         _______)
---.__________)

```
Scissors
```
    _______
---'   ____)____
          ______)
       __________)
      (____)
---.__(___)

```
✂️📄🪨

A classic Rock Paper Scissors game with ASCII art visuals!

###  Files

- `RockPaperScissors.py` - Original version
- `rockpaperscisser(new).py` - Improved version with loop

### 🎮 How to Play

- **0** = Rock 🪨
- **1** = Paper 📄
- **2** = Scissors ✂️

## 🚀 Quick Start

```bash
# Run either version
python RockPaperScissors.py
# or
python rockpaperscisser(new).py

```

# 18 WhatsApp Birthday Bot 🤖

An automated Python script that sends birthday wishes via WhatsApp using pyautogui!

### 📁 File

- `main.py` - Main automation script

### 🎯 What It Does

1. Opens Windows Search
2. Types "whatsapp" and launches it
3. Searches for a contact named "Homies"
4. Finds and clicks on the contact
5. Types a birthday message
6. Sends the message

### 🚀 Quick Start

```bash
python main.py
```
# 19. Tracker
 Phone Number Tracker 📱

A Python script that tracks the location and service provider of a phone number and displays it on an interactive map!

## 📁 File

- `project1.py` - Main tracking script
- `new.py` - Contains the phone number (external file)

## 🎯 What It Does

1. Parses a phone number using phonenumbers library
2. Identifies the geographic location
3. Determines the mobile carrier/service provider
4. Fetches coordinates using OpenCage Geocoder
5. Creates an interactive HTML map with Folium

## 🚀 Quick Start

```bash
python project1.py
```

# 20. Treasure-Map

# Treasure Island Game 🏝️

A text-based adventure game where players make choices to find the hidden treasure!

## 📁 Files

- `Treasure_Map.py` - 3x3 grid treasure marking game
- `Treasure.py` - Text adventure with ASCII art

## 🎮 Treasure_Map.py

### How to Play
1. View the 3x3 grid
2. Enter coordinates (e.g., "23" for row 2, column 3)
3. Mark the spot with "X"


# 21. Turtle
Practiced Built in turtle library
# 23. Who's Paying

A simple random selector to decide who buys the meal!

## 🎯 How It Works

1. Enter names separated by commas
2. Program randomly selects one person
3. Announces who pays for the meal
