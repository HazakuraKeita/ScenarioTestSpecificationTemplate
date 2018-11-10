# Scenario Test Specification Template
This is a scenario test specification template.  
## How to write scenario test specification  
### Title  
We should write the following information in the title page.  

- Title
- Description of the test
- Test date
- Tester
- Required time
- Test result summary

I write test environtment in each scenario page bacause I change it in each scenario sometimes.  

### Result status  
We hope there are 3 result statuses at least.  

- OK
- Attention
- NG

It is difficult for us to prevent to make specification bugs.  
If we get a feeling of strangeness, we will set Attention at the result.  

### Test specification basis  
- Anybody can get same software behaviors
- Anybody can decide same results (OK or NG)

## Anti-pattern  
### Procedure  
#### NG:  
Go to 4th floor.  

#### OK:  
1. Click on Upside button.  
2. Go on the elevator when the door is opened.  
3. Click on 4th button.  
4. Go out from the elevator when the door is opened.  

In NG case, we cannot get same elevator behaviors because somebody who does not know an elevotor may use an escalator.  
If a tester use an escalator, he cannot find bugs of the elevator.  
### Predict  
#### NG  
Elevator moves to 4th floor correctly.  

#### OK
1. Upside button lights up whitely.  
2. The elevator opens the door with the open sound.  
3. 4th button lights up whitely. Then, the elevator moves to 4th floor.  
4. The elevator opens the door with the open sound.  
