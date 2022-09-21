SEND 'Please enter your height in meters' TO DISPLAY
RECIEVE heightNumber FROM KEYBOARD
SEND 'Please enter your weight in kilograms' TO DISPLAY
RECIEVE weightNumber FROM KEYBOARD
SET BMI TO(heightNumber / weightNumber^2) 
SEND total TO DISPLAY
If BMI <18.5 THEM
SEND 'underweight' TO DISPLAY
If BMI <=24.9 THEN
SEND 'normal weight' TO DISPLAY
IF BMI <=25 THEN 
SEND'overweight' TO DISPLAY
END IF
END IF
END IF
