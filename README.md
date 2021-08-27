# Print-all-vowels-in-uppercase-of-a-string-in-PHP.
Here we are going to print the vowels of a given string in uppercase in PHP language...
use. the code given below




$str = "Some string values";

 function something($str)
       {
           $N = strlen($str);
    
           for ($i = 0; $i < $N; $i++) {
               if ($str[$i] === "a" || $str[$i] === "e" || $str[$i] === "i" || $str[$i] === "o" || $str[$i] === "u") {
                   print(strtoupper($str[$i]));
               } else {
                   print($str[$i]);
               }
           }
       }
       
 something($str);  
