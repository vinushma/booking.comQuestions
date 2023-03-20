# booking.com Questions Haker Rank
# LogicalJavascript
# Question 1
<pre class="highlight plaintext"><code>Logs 'Fizz' for multiples of three, 'Buzz', for multiples of 5, and 'Fizz Buzz' for multiples of 3 & 5
</code></pre>
<div>
 # Output <pre>
function fizzBuzz(n: number): void {
   for(let i = 1 ; i < n ; i++){
      if(i % 3 == 0 && i % 5 == 0){
            console.log("FizzBuzz");
      }
       else if(i % 3 == 0 && i % 5 != 0){
          console.log("Fizz");
      }else if(i % 5 == 0 && i % 3 != 0){
          console.log("Buzz");
      }
      else {
          console.log(i);
      }
   } 
}
fizzBuzz(15);

</pre></div>
# Question 2
<pre class="highlight plaintext"><code>Backspace string compare

Two strings are said to be the same if they are of the same length and have the same character at each index. Backspacing in a string removes the previous character in the string.
Given two strings containing lowercase English letters and the character # which represents a backspace key, determine if the two final strings are equal. Return 1 if they are equal or 0 if they are not. Note that backspacing an empty string results in an empty string.

In the first string, one 'x' and one 'b' are backspaced over. The first string becomes "axbc", the second string also becomes "axbc", the answer is 1

compareStrings has the following parameter(s):

s1 = 'axx#bb#c' 
s2 = 'axbd#c#c'

</code></pre>
<div>
 # Output <pre>
function compareStrings(s1, s2) {
        let sArr = [];
        let yArr = [];
       if(s1.length == s2.length)
       {
          for(let i= 0; i< s1.length ; i++){
              if(s1[i] == '#'){
                  console.log("im here");
                sArr.pop();
              }else{
                sArr.push(s1[i]);
              }
          }
          for(let i=0;i< s2.length ;i++){
                   if(s2[i] == '#'){
                      yArr.pop();
                  }else{
                      yArr.push(s2[i]);
                  } 
          }
        }
}
const s1 = "axx#bb#c";
const s2 = "axbd#c#c";
compareStrings(s1, s2);

</pre></div>
