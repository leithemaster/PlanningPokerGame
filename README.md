# Planning Poker App
## Overview
Planning Poker, also known as Scrum Poker, is a consensus-based technique for estimating, mostly used to estimate effort or relative size of development goals in software development. This Planning Poker App is designed to make sprint planning sessions more efficient and engaging for remote or in-person teams. The app is open-source, allowing teams to customize it to their workflow and improve it over time.

## Features
### Real-Time Collaboration
This feature enables teams to estimate tasks in real-time, ensuring everyone's participation regardless of their location. It's designed to make remote sprint planning sessions as interactive and efficient as in-person sessions.

### Anonymous Voting
To reduce bias in estimations, individual votes are kept hidden until the reveal. This encourages honest and independent input from each team member, leading to more accurate estimations.

### Session History
The app records past estimation sessions for future reference and analysis. This allows teams to review and learn from their estimation patterns over time.

### Integration Friendly
Designed to easily integrate with other project management tools, this feature ensures that the Planning Poker app can seamlessly fit into existing workflows, enhancing productivity without disrupting established processes.

### Different User Types
The app supports multiple user types with specific roles and permissions:
- **Host:** Manages the session, including posting lobby links for players to join.
- **Players:** Participate in the estimation process by voting on tasks.

## Nice to have features
### Customizable Decks
Offers various card decks to suit different estimation techniques (Fibonacci).
### Customizable card back. 
### Customizable player profile 
### Add emotes during planning (the feature is similar to discord emote when you are in VC, with the emote popping up and slowly dropping down)


### Card Features
- **Point Selections:** Players can select cards representing their estimate for the task's difficulty.
- **Submit/Edit Submission:** Players can submit their estimates or edit their submissions before the host moves to the result phase.

### Game Phases
- **Initial Phase:** The host starts the round by entering a story number. Leaving this blank keeps the session in a preparatory state.
- **Submission Phase:** Players select a card with points that they believe best match the difficulty of the story.
- **Result Phase:** The app displays the average estimate and calculates it based on the Fibonacci sequence, facilitating a discussion among team members.
- **Reset Phase:** After discussing the results, the host can reset the session to the initial phase, readying the team for the next round of estimation.

These features are designed to make the Planning Poker app a comprehensive tool for agile teams to facilitate their estimation process, improve accuracy, and save time during sprint planning.


## Getting Started
### Prerequisites
- Node.js (version X or higher)
- npm or Yarn
### Installation

1. Clone the repo:
```
git clone https://github.com/leithemaster/PlanningPokerGame.git
```

2. Install NPM packages:
```
cd planning-poker
npm install
```

4. Start the application:
```
npm start
The app will be running on http://localhost:3000.
```

## Usage
To start a new planning session, follow these steps:

1. Navigate to the main page and click on "Start New Session".
2. Share the session link with your team members.
3. Once everyone has joined, begin estimating tasks by selecting a card from your deck.
4. After all votes are in, reveal the results and discuss discrepancies.

For more detailed instructions, visit the Usage Guide.

## Contributing
We welcome contributions from the community! Whether it's a bug fix, a new feature, or an improvement to the documentation, your help is appreciated. Please check out our Contributing Guidelines for more information on making contributions.

## License
This project is licensed under the MIT License - see the LICENSE file for details.

## Acknowledgments
Thanks to all the contributors who have helped to make this app better.

Special thanks to [Captain Sparkles] for initial inspiration and guidance.

For any questions or suggestions, please open an issue or pull request on GitHub.

