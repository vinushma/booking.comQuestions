# booking.com Questions Haker Rank
# LogicalJavascript
# Question 1
<pre class="highlight plaintext"><code>Logs 'Fizz' for multiples of three, 'Buzz', for multiples of 5, and 'Fizz Buzz' for multiples of 3 & 5
</code></pre>
<div>
 # Output <pre>10
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
