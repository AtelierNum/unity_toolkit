# Classic modules

## How to use events

It is advised to create an empty GameObject, to call it "Event Manager" and to put all your emitter scripts in there.

![](readme_resources/emitter/1.PNG)
![](readme_resources/emitter/2.PNG)


To match an emitter with a receiver

1. Add the "do X onEvent" script to the GameObject you want to affect. And the emitter you want to use in the EventManager if it's not already there.
![](readme_resources/emitter/3.PNG)
![](readme_resources/emitter/4.PNG)

2. click the "+" in the Event list of the emitter
![](readme_resources/emitter/5.PNG)

3. drag the affected GameObject in the emitter where you can read `None (Object)`
![](readme_resources/emitter/6.PNG)

4. in the drop down, select "do X onEvent" > "X"
![](readme_resources/emitter/7.PNG)

Profit  
![](readme_resources/emitter/final.gif)