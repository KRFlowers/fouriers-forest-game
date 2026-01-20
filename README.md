# Fourier's Forest
**Find the Signal in the Noise**

Fourier's Forest is a statistics quiz game with a forest theme background built in JavaScript. It was originally created as a class project and later extended to add data science quiz elements. Give it a try and test your knowledge!

Questions have been created in alignment with AP Statistics course.

**JavaScript concepts practiced:**
- DOM manipulation and event handling
- CSS Grid layout for responsive card positioning
- jQuery for dynamic content generation
- localStorage API for persistent game history
- Timer functions and game state management
- Click tracking and performance analytics
- Modal dialogs and UI interactions

## How to Play

1. Open `index.html` in your browser
2. Select a difficulty level (Easy, Medium, or Hard)
3. Click "Start" - a grid of statistical concepts appears
4. Click only on valid concepts to score points
5. Avoid invalid concepts (they subtract points)
6. Win by finding more signal than noise before time runs out

## Difficulty Levels

**Level 1 (Easy): Foundational Concepts**
- Basic terminology, simple calculations, and fundamental principles
- Mean, median, mode, standard deviation, z-scores, correlation

**Level 2 (Medium): Inference & Probability**
- Probability rules, sampling distributions, confidence intervals, hypothesis testing
- Binomial/normal distributions, Central Limit Theorem, p-values, Type I/II errors

**Level 3 (Hard): Advanced Inference & Modeling**
- Complex inference, regression, chi-square, ANOVA, experimental design
- Residual analysis, r², confounding variables, randomization, Simpson's Paradox

## Features

- Three difficulty levels with varying grid sizes and time limits
- Scoring system: +1 for correct, -1 for incorrect
- End-game statistics (accuracy, identification rate, reaction time)
- Game history saved in browser (last 10 games)
- Forest-themed visual design with animated background
- Info modal about Joseph Fourier

## Tech Used

- HTML5/CSS3 with CSS Grid
- JavaScript and jQuery
- localStorage for game history
- Bug animation library by Auz

## Notes

Desktop only - mobile support not implemented.

Questions can be edited in `data/questions.js`.

## Credits

- Bug animation library by [Auz](https://github.com/Auz/Bug)
- Forest background from Pixabay
- Cicada sound effect from Notification Sounds

## License

MIT License

---

**Author:** K Flowers  
**Contact:** kristirflowers@gmail.com
