FizzBuzzPHP
===========

Fizz Buzz PHP

Simple Fizz Buzz done in PHP



#INIT PHP

for ($count=1; $count<=100; $count++)
{
    if ($count%3 == 0 && $count%5 ==0){
        print "FizzBuzz<br>";
    }
    elseif ($count%3 == 0){
        print "Fizz<br>";
    }
    elseif ($count%5 == 0){
        print "Buzz<br>";
    }
    else {
        print $count."<br>";
    }
}

#END PHP
