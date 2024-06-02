# ch5_homework
Home Work questions for class 05 conditional statements

1.

   - **Question**: Write a `for` loop that prints the numbers from 10 to 1 in descending order.
  for(var i=10;i>=1;i--){
  console.log(i);
  }

2. **While Loop**:

   - **Question**: Write a `while` loop that prints the first 5 even numbers starting from 0.
   var i=0;
   var con=0;
   while(con<5){
        if(i%2==0){
            console.log(i)
            con++;
        }
        i++;
   }

3. **Do-While Loop**:

   - **Question**: Write a `do-while` loop that prints the numbers from 1 to 5.
    var i=1;
      do{
          console.log(i);
          i++;
      }while(i<=5);
    

4. **Break Statement**:

   - **Question**: Write a `for` loop that prints numbers from 0 to 10, but stops the loop when the number 7 is reached.
    for(var i=0;i<=10;i++){
        if(i==7) 
            break;
          console.log(i);
      }

5. **Continue Statement**:

   - **Question**: Write a `for` loop that prints numbers from 0 to 10, but skips the number 5.
    for(var i=0;i<=10;i++){
          if(i==5) 
              continue;
          console.log(i);
      }

6. **If-Else Statement**:

   - **Question**: Write an `if-else` statement that checks if a given number `x` is positive, negative, or zero, and prints an appropriate message.
     // var i=3;
      // var i=0;
      var i=-5;
      if(i>0){
          console.log(i," Positive number");
      }else if(i==0){
          console.log(i," Number is zero");
      }else{
          console.log(i," Number is negative ");
      }

7. **Switch Statement**:

   - **Question**: Write a `switch` statement that takes a variable `day` (with values from 0 to 6) and prints the corresponding day of the week (e.g., 0 for Sunday, 1 for Monday, etc.).
   - var choice=1;
switch (choice) {
    case 0:
        console.log("Sunday");
        break;
    case 1:
        console.log("Monday");
        break;
    case 2:
        console.log("Tuesday");
        break;
    case 3:
        console.log("Wednesday");
        break;
    case 4:
        console.log("Thursday");
        break;
    case 5:
        console.log("Friday");
        break;
    case 6:
        console.log("Saturday");
        break;
    default:
        console.log("Select the choice between 0-6");
        break;
}


8. **Ternary Operator**:

   - **Question**: Use the ternary operator to check if a given number `y` is even or odd and print "Even" or "Odd" accordingly.
     var y = 3;
     console.log(y%2==0? "even": "odd");

9. **Combining Loops and Conditions**:

   - **Question**: Write a `for` loop that prints numbers from 1 to 20. For multiples of 3, print "Fizz" instead of the number, for multiples of 5, print "Buzz", and for multiples of both 3 and 5, print "FizzBuzz".
      for(var i=1;i<=20;i++){ 
    if(i%3==0 && i%5==0){
        console.log("FizzBuzz");
    }else if(i%3==0){
        console.log("Fizz");
    }else if(i%5==0){
        console.log("Buzz");
    }else{
        console.log(i);
    }
}
     
 

10. **Complex Condition**:
    - **Question**: Write an `if-else` statement that takes a variable `temperature` and prints "Cold" if the temperature is below 15, "Warm" if it’s between 15 and 25, and "Hot" if it’s above 25.
      var temp = 8;
if (temp < 15) {
    console.log("Cold");
} else if (temp >= 15 && temp <= 25) {
    console.log("Warm");
} else {
    console.log("Hot");
}
  

