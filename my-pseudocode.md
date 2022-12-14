# How to Brew a Cup of Tea

## About

- Tea is an aromatic beverage prepared by pouring hot or boiling water over cured or fresh tea leaves 
- There are many types of tea
- Some teas have caffeine, others do not

## Initialize- Create Variables

1. Water
    - Material for making tea
    - Freezes at -32 degrees, boils at 212 degrees.

    Properties: <br>
        waterTemp <br>
        waterAmount <br>

2. Tea bag
    - Material for making tea.
    - Cured or fresh tea leaves in a small, porous, sealed bag or packet.
    - Many varieties exist for example black tea, green tea, mint tea, and caffenated and decaf.

    Properties: <br>
        teabagUnused <br>
        teabagUsed <br>

3. Coffee mug
    - Receptical used for brewing tea and for drinking tea

    Properties: <br>
        mugSize 

4. Tools:
    1. Tea Kettle- pot with a lid used for heating water
    2. Stove- cooktop with burners used for heating things
    3. Timer- a specialized type of clock used for measuring specific time intervals

## Functionality

### Preparation Stage:

> FUNCTION gatherMaterials: <br>
    >* water (1 cup) <br>
    >* tea bag (1) <br>
    >* coffee mug (1) <br>
    >* tea kettle (1) <br>
    >* stove (1) <br>
    >* timer (1) <br>


FUNCTION checkTemperature: <br>
     *IF waterTemperature > 212 degrees Fahrenheit <br>
         THEN  <br>
             Say "This water is hot enough." <br>
                 END <br>
                               
### Building Stage:

FUNCTION heatWater: <br>
   a. Pour water into tea kettle <br>
   b. Put tea kettle on stove <br>
   c. Set burner on HIGH. <br>

FUNCTION checkBoiling: <br>
     * IF water is boiling then remove tea kettle from the stove <br>
            Else <br>
                wait a minute and loop back to beginning <br>
                
FUNCTION addWater: <br>
    * Pour water into coffee mug. <br>
    
FUNCTION addTeaBag <br>
    * Place tea bag into coffee mug with hot water. <br>
    
FUNTION setTimer <br>
    a. Set timer for 3 minutes <br>
    b. If timer dings <br>
        THEN <br>
            remove tea bag from coffee mug and END <br>
        ELSE <br>
            do nothing. <br>
            
### START: Start the Program

> gatherMaterials <br>
> checkTemperature <br>
> heatWater <br>
> waterBoiling <br>
> addWater <br>
> addTeaBag <br>
> setTimer <br>

### END: End the Program



1. While water is cold put water in a tea kettle
    Else
    skip to step 5.

2. Then put the tea kettle on the stove.

3. Then turn burner on high.

4. If water is boiling then remove tea kettle from the stove
    Else 
    wait a minute and loop back to beginning of step 4.

5. Add hot water into a coffee mug.

6. Add a teabag into the coffee mug.

7. Begin timer for 3 minutes.

8. If timer dings then remove tea bag from the coffee mug
    Else 
    do nothing.

9. Tea is done, enjoy!
