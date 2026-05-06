# 🐍 Self-Playing Snake Game - 1 Hour Challenge

A self-playing Snake game that runs automatically for exactly 1 hour!

## Features

- **Fully Autonomous**: The game plays itself using an AI algorithm
- **1 Hour Duration**: Game runs for exactly 60 minutes
- **Smart AI**: Uses pathfinding and flood-fill algorithms to avoid getting trapped
- **Visual Progress Bar**: Shows remaining time
- **Score Tracking**: Current score and high score display
- **Responsive Design**: Works on desktop and mobile devices
- **Beautiful UI**: Modern gradient design with glowing effects

## How to Deploy on GitHub Pages

### Option 1: GitHub Pages (Simple)

1. Push this repository to GitHub
2. Go to your repository settings
3. Navigate to "Pages" section
4. Select the main/master branch as source
5. Click Save
6. Your game will be live at `https://yourusername.github.io/repository-name/`

### Option 2: Using gh-pages branch

```bash
# Create and switch to gh-pages branch
git checkout --orphan gh-pages
git reset --hard

# Add all files
git add .
git commit -m "Deploy self-playing snake game"

# Push to GitHub
git push origin gh-pages

# In GitHub Settings > Pages, select gh-pages branch as source
```

## How It Works

1. **Start**: Simply open the `index.html` file in a browser or visit your GitHub Pages URL
2. **Watch**: The AI-controlled snake plays automatically
3. **AI Logic**: 
   - Finds safe moves that don't result in collision
   - Prioritizes moves toward food
   - Uses flood-fill to ensure it doesn't trap itself
4. **Game Over**: If the snake crashes, it automatically restarts after 2 seconds
5. **End**: After 1 hour, the game ends and displays the final score

## Game Controls

No controls needed! The game is fully autonomous and plays itself.

## Technologies Used

- HTML5 Canvas
- Vanilla JavaScript
- CSS3 with animations and gradients

## License

Free to use and modify!
