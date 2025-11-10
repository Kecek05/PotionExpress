# 🧙‍♀️ PotionExpress

**PotionExpress** is a whimsical 3D management simulation game where you play as a witch running a potion delivery business. Gather ingredients, brew magical potions, and deliver them to customers while managing your daily expenses to keep your business thriving!

## 🎮 Gameplay Overview

In PotionExpress, you'll experience the life of a potion-brewing witch entrepreneur. Your goal is to craft potions according to customer orders, deliver them successfully, earn money, and keep your business afloat by paying daily expenses.

### Core Gameplay Loop

1. **Start Your Day**: Wake up in your cozy witch's house
2. **Gather Ingredients**: Explore your greenhouse to collect magical ingredients
3. **Brew Potions**: Use various kitchen counters and a magical cauldron to prepare potions
4. **Deliver Orders**: Complete rhythm-based delivery minigames to successfully deliver potions
5. **Manage Finances**: Pay your daily expenses and balance your budget
6. **Repeat**: Continue through multiple days, growing your potion business

## 🎯 Key Features

### Potion Brewing System
- **Multiple Ingredients**: Collect and process various magical ingredients
- **Recipe Matching**: Each potion requires specific ingredients and a matching potion shape
- **Kitchen Stations**: 
  - **Cutting Counter**: Prepare ingredients by slicing them
  - **Cauldron**: Cook ingredients together to create potions
  - **Container Counter**: Store and organize ingredients
  - **Plate Counter**: Assemble your final potion products
  - **Clear Counter**: Use as workspace for ingredient preparation
  - **Trash Counter**: Dispose of unwanted items

### Ingredient Processing
- Cut, cook, and combine ingredients in the correct order
- Progress bars show cooking/cutting completion
- Visual and audio feedback for each action

### Delivery Minigame
- **Rhythm-Based Challenge**: Hit timing marks to successfully deliver potions
- **Dynamic Difficulty**: Minigame difficulty scales based on potion complexity
- **Multiple Hit Types**: React to different input prompts (A, S, D, F keys)
- **Scoring System**: Earn bonus money for perfect deliveries
- **Obstacles**: Avoid sharks and water hazards during delivery

### Economy & Management
- **Daily Expenses**: Pay fixed and random expenses each day
- **Money System**: Earn money from successful potion deliveries
- **Budget Management**: Balance income and expenses to avoid game over
- **Day Counter**: Track your business's longevity

### Multiple Scenes
- **Main Menu**: Start your adventure
- **Greenhouse**: Explore and gather ingredients in a 3D environment
- **House/Kitchen**: Your potion-brewing workspace
- **Delivery Scene**: Mini-game for potion delivery
- **Payment Scene**: Review finances and pay expenses

## 🎨 Art Style

PotionExpress features a charming low-poly 3D art style with a fantasy aesthetic:

- **Character Design**: Cute witch character with custom animations
- **Environment**: 
  - Cozy witch's house with detailed interior
  - Lush greenhouse with collectible plants
  - Stylized terrain with custom textures
  - Fantasy-themed props and decorations
- **Visual Effects**: 
  - Particle effects for magical actions
  - Progress indicators and visual feedback
  - Custom shaders for special materials (roof tiles, transparent elements)
  - Lightmapped environments for atmospheric lighting
- **UI**: Clean, intuitive interface with custom icons and sprites
- **Color Palette**: Warm, inviting colors that create a magical atmosphere

## 🎮 Controls

### Greenhouse/Exploration
- **W**: Move forward
- **A/D**: Rotate left/right
- **Mouse**: Look around (in some modes)
- **E**: Interact with objects
- **Tab**: Open/Close inventory

### Kitchen/House
- **Mouse**: Look around
- **Click**: Interact with counters and objects
- **E**: Pick up/place items
- **F**: Perform special actions (cut, cook, etc.)

### Delivery Minigame
- **A, S, D, F**: Hit timing marks as they appear

### Menus
- **Mouse**: Navigate menu options
- **ESC**: Pause/Options menu

## 🧪 How to Brew Potions

1. **Check the Order**: Look at the displayed recipe showing required ingredients and potion shape
2. **Gather Ingredients**: Collect needed ingredients from containers
3. **Prepare Ingredients**: 
   - Use the cutting counter to slice ingredients that need cutting
   - Some ingredients can go directly to the cauldron
4. **Cook in Cauldron**: Add all required ingredients to the cauldron
5. **Choose Potion Shape**: Select the correct potion bottle/shape that matches the order
6. **Plate the Potion**: Place the completed potion on a plate
7. **Deliver**: Take the plated potion to the delivery counter to start the delivery minigame

## 📦 Technical Details

### Built With
- **Engine**: Unity (Universal Render Pipeline)
- **Language**: C# 
- **Additional Packages**:
  - Cinemachine (for camera control)
  - TextMesh Pro (for UI text)
  - Input System (for player controls)

### Key Systems
- **ScriptableObject-based Design**: Recipes, ingredients, and game data stored as ScriptableObjects
- **Event-driven Architecture**: Clean separation of concerns using C# events
- **Save System**: Player progress, money, and day count persistence
- **Audio System**: Dynamic SFX and background music management
- **Scene Management**: Smooth transitions between game scenes with loading screens

## 🚀 Getting Started

### Prerequisites
- Unity 2021.3 or later
- Basic understanding of Unity interface

### Installation
1. Clone this repository
   ```bash
   git clone https://github.com/Kecek05/PotionExpress.git
   ```
2. Open the project in Unity Hub
3. Open the `MainMenuScene` scene in `Assets/Scenes/`
4. Press Play to start the game

### Building
1. Go to File > Build Settings
2. Select your target platform
3. Click "Build" and choose output location

## 🎯 Game Progression

- Start with a basic set of ingredients and recipes
- Each day presents random potion orders to fulfill
- Successfully delivered potions earn money
- Pay daily expenses to continue operating
- **Game Over Condition**: Unable to pay all expenses
- **Victory**: Successfully managing your business day after day

## 🔊 Audio

The game features:
- Background music for different scenes
- SFX for cutting, cooking, and other actions
- UI interaction sounds
- Delivery minigame audio feedback
- Adjustable volume settings in the options menu

## 💾 Save System

Your progress is automatically saved:
- Total money earned
- Current day count
- Completed payments
- The game saves at the end of each day during the payment phase

## 🎓 Tips for Success

1. **Plan Ahead**: Check all orders before starting to brew
2. **Time Management**: Work on multiple potions simultaneously when possible
3. **Practice Delivery**: The minigame difficulty increases, so practice makes perfect
4. **Budget Wisely**: Keep track of your expenses vs. income
5. **Don't Rush**: Accuracy is more important than speed
6. **Match Exactly**: Ensure both ingredients AND potion shape match the order

## 🤝 Contributing

This is an educational/portfolio project. Feel free to fork and experiment with your own variations!

## 📝 License

This project is developed as a game development portfolio piece.

## 🙏 Credits

- **Developer**: Kecek05
- **Engine**: Unity Technologies
- **Assets**: Custom 3D models and Unity Asset Store resources

---

*Brew potions, deliver happiness, and keep your magical business thriving! 🧪✨*
