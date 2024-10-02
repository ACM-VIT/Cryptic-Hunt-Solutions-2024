<table border = '3'>
    <tr>
        <td>Part:</td>
        <td>2</td>
    </tr>
    <tr>
        <td>Mode:</td>
        <td>Online</td>
    </tr>
    <tr>
        <td>Entry Point:</td>
        <td>Riddle</td>
    </tr>
    <tr>
        <td>Endpoint:</td>
        <td>String</td>
    </tr>
</table>

## To solve the question 

Solution:

        0410 0410 0412 0423 0410 0412 0410 0412 0423 0410 0412 0424 0412 0410 0423 0410 0424 0410 0412 0412 0410 0424 0423

## Description of the Question

Having unlocked the first part, you’ve proven your worth. Now, to continue your journey, venture into the world of Tennis. Solve the mystery that combines his victories with a twist. Decode the secret message hidden within the sequence of his Grand Slam wins in the order they were won, translate the victories into the alphabet from his country of origin using the provided mapping. Convert the transliterated string to its hexadecimal representation and use this code to uncover the hidden message and advance to the next stage of your quest.

dist_2/mapping.png

## Hints

**Hint 1:**
       
        Points: 50
        Convert the string to Unicode code point and then form a string with the numbers

## Links 


https://firebasestorage.googleapis.com/v0/b/cryptic-hunt-24.appspot.com/o/question_resources%2Fmapping.png?alt=media&token=c62a3eda-09d6-4746-9342-576bb5e2618c

## Solution 

1. The second part of the question, another riddle, talks about the GOAT of Tennis, Novak Djokovic. The player has to arrange his 24 Grand Slam victories in chronological order and form a string.

        AAWUAWAWUAWFWAUAFAWWAFU

2. Based on the riddle, the string has to be encoded in an alphabet from Serbia, the Cyrillic alphabet. The mapping for the same is given as part of the question. Upon transliterating the string:

        ААВУАВАВУАВФВАУАФАВВАФУ

3. Each Cyrillic alphabet has to then be converted to its Unicode code point:

        А = 0410
        В = 0412
        У = 0423
        Ф = 0424  
        
4. Upon converting the entire string, the solution for Sequence 2 is obtained:

        0410 0410 0412 0423 0410 0412 0410 0412 0423 0410 0412 0424 0412 0410 0423 0410 0424 0410 0412 0412 0410 0424 0423

## Link to next part

N/A
