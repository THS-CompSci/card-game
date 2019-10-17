# Card Game Starter

Your project is to build a card game in Java. It can be any multiplayer card game you'd like, but it needs to either be one where it doesn't matter if the players can see each others hands or you'll need to create a computer player. 



## Requirements

* You'll either need to make a game where it doesn't matter if the players can see the other hands or create a computer player to play against. A single player game also works. 
* The game has to get to either a win or loss state and let the player, or players, know when they've won or lost.
* The computer must determine wins or losses. It cannot be left up to the player. 
* After a win or loss you need to be able to restart the game. 

## Images

A full set of playing card face images along with the back are included in the `/images/` folder. They are numbered, so you'll probably want to work out some type of data structure that will make it easier to work with. 

Maybe something like this...

```java
public class CardFaces {
    public static final String ACE_CLUBS = "1.png";
    public static final String ACE_SPADES = "2.png";
    
    // And so on through the reset of the deck.
}
```

That way, instead of using `"1.png"` in your code where you have no real idea what card it is you can use `CardFaces.ACE_CLUBS` which tells you exactly what face it is. 

The Images game from [Open Game Art](https://opengameart.org/content/playing-cards)

