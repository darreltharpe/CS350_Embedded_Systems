# CS350_Embedded_Systems




    Summarize the project and what problem it was solving.

This project was the early design for a cloud connected thermostat. It was meant to track AC usage via regularly sending usage data to a cloud server.
    
    What did you do particularly well?

I feel my best work was done in problem solving. Working wiith new libraries on hardware of dubious functionality required implementing unfamiliar functions while discerning what issues were code related and which were due to hardware mishaps.
    
    Where could you improve?

The project needs optimization. Everything works, but the operation of the LEDs and LCD were less than perfectly smooth, and there is still a rare error that I cannot reproduce reliably that appears to be a disagreement between some part of my code and some piece of library code.
    
    What tools and/or resources are you adding to your support network?

I had been avoiding it for as long as possible, but I'm adding AI to my toolbox. It's been wrong or unhelpful on some things, but it's also helped me to understand the syntax of new functions that were not properly or thoroughly documented.
    
    What skills from this project will be particularly transferable to other projects and/or course work?

Discerning software and hardware issues. You can focus so much on your code that you can forget that sometimes the reason a light isn't blinking or a screen isn't printing is that the hardware has failed, or vice versa. I had that issue with the LCD screen. It wouldn't put out any text, though it clearly had power. It was just a loose wire, but I must have scoured the code a few dozen times over before noticing.
    
    How did you make this project maintainable, readable, and adaptable?

Lots of notation and white space. I make myself put notes on code that I think should be perfectly obvious, because it may not be to a new observer. I've also taken to labeling subsections of code. For instance, a long block of if-elses that control the LEDs are notated for which part of the cycle they operate in. You could glean that information from the code, but it's easier and faster to read colorful notations.
