# CS106AAssignment-THingy-Basic Karel
B
import stanford.karel.*;
public class VoteCountingKarel extends SuperKarel {
  public void run(); {
    while (frontIsClear()){
      move();
      placeBeeper();
      if (facingWest());{
        turnLeft();
        turnLeft();
        placeBeeper();
      else;{
        turnRight();
        turnRight();
        placeBeeper();
       }
      }
     }
    }
    
