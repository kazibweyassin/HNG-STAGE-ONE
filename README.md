# Stage 1 - Frontend Intern Task: Color Game

## Task Requirements

### Languages
- HTML, CSS, and Vanilla JavaScript or React

### Game Requirements

#### Color Display:
- A box should display a randomly selected target color.
- Attribute: `data-testid="colorBox"`

#### Color Options:
- Display 6 buttons, each with a distinct background color representing a possible guess.
- Attribute: `data-testid="colorOption"`

#### Game Instructions:
- Present a message explaining the game's objective (e.g., "Guess the correct color!").
- Attribute: `data-testid="gameInstructions"`

#### Game scoreus:
- After each guess, indicate whether the guess is correct or wrong.
- Attribute: `data-testid="gamescoreus"`

#### Score:
- Show a score counter that increments with each correct guess.
- Attribute: `data-testid="score"`

#### New Game Button:
- Include a button to reset and start a new game.
- Attribute: `data-testid="newGameButton"`

## Styling and Design
- Provide an engaging, user-friendly interface with clearly distinguishable elements.
- Ensure buttons are large and easy to click.
- Apply contrasting colors between the target color and the options.
- Use CSS animations for game results (e.g., fade-out for wrong answers, celebratory effects for correct ones).
- Ensure responsive design across desktop, tablet, and mobile devices.

## Functionality
- Randomly pick a target color from a predefined set.
- Allow players to click a color option to check their guess.
- Dynamically update the score and display messages based on the guess accuracy.
- Ensure the new game button resets the game scoree properly.

### Implementation Details:
- The target color is shown as a colored box, not as a hex code.
- The six color options display only colors, requiring the player to match the target color.

## Acceptance Criteria

### Content:
- All required elements are present and functional.
- The game displays the appropriate instructions, scoreus messages, and score.
- The specified `data-testid` attributes are implemented for testing purposes.

### Design:
- The game is visually appealing with a clear distinction between the target color and the options.
- The design is responsive, working well on desktop, tablet, and mobile devices.

### Functionality:
- The score and game scoreus update correctly following each guess.
- The new game button effectively resets the game.

### Code Quality:
- The code is well-organized, readable, and properly indented.
- JavaScript functions and event handling are properly implemented.

## Submission Mode
- Host the Color Guessing Game on your preferred platform (e.g., Vercel or Netlify).
- Ensure all requirements and acceptance criteria are met before submission.
- Submit your task through the designated submission form.

## Submission Deadline
- 6th February, 2025, 11:59 PM WAT. Late submissions will not be accepted.

Good luck! :rocket:
