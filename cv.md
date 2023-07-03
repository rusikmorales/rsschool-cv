# *Anastasiia Shishova*

## *Contacts:*
* knightofthesword123@gmail.com
* +995511211268 (main)
* @aamorales (telegram), @rusik_morales (instagram)

## *About me:*
My name is Anastasia. I'm 22 years old. I live in Batumi, Georgia. 
My hobbies is music, gaming, sport, watching tv shows.
I want to learn Frontend, cause it's new and ineresting for me and I want to change my profession.

## _Skills:_
* Figma
* Adobe AI, Photoshop, Lightroom
* Sony Vegas Pro 13

## _Code example_
A Narcissistic Number (or Armstrong Number) is a positive number which is the sum of its own digits, each raised to the power of the number of digits in a given base. In this Kata, we will restrict ourselves to decimal (base 10).
```
function narcissistic(value) {
  let length = value.toString().length;
  let result = 0;
  for( i = 1; i <= length; i++ ){
    let number = parseInt((value % 10**i) / 10**(i-1)) ;
    result += number**length;
  }
  if(result == value){
    return true;
  } else {
    return false;
  }
}
```
## _Courses:_
* RS school (in progress)

## _Languages:_
* Russian (native)
* English (Intermediate)