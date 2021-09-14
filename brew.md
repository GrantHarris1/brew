"Start Program" "brew"

1. user.InsertsKcup
2. user.insertsWater
3. user.pressStart
<br>
IF KcupInserted()
    
    IF water >= waterMin 
        
        brewCoffee 
           
            Else: Beep 
               
                Dispense Coffee 
                   
                    End Program
    
___


    Functions : 
    
    KcupInserted() 

    waterMin()

    Var: Kcup, water, pressStart

    Properties: has.Kcup, has.enoughWater, brewCoffee

    minWater =< 6 oz.
    Kcupmin =  <0
