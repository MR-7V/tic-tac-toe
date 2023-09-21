## Game Interaction Flow

1. The user clicks on a square.
2. The Square component calls the `handleClick()` method of the Board component.
3. The Board component checks if the square is already occupied. If it is, the Board component returns.
4. The Board component updates the game state to mark the square as occupied.
5. The Board component calls the `calculateWinner()` method to check if there is a winner.
6. If there is a winner, the Board component updates the game state to indicate the winner.
7. The Board component calls the `render()` method to update the game board.
8. The Board component calls the `onPlay()` method of the Game component.
9. The Game component checks if there is a winner. If there is, the Game component updates the game state to indicate the winner and renders the game board.
10. If there is no winner, the Game component updates the game state to indicate the next player and renders the game board.
