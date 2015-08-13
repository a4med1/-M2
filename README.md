# -M2
## Notes 
  * Modules are routines and calling a function from a module requires Module.function.
  * Modules have to start with Uppercase letter.
  * Functions have to start with lowercase letters.
  * Function names can be separtated by _
  * Begining ( Monad ? ) $
  * End ( Apply ? ) ^
  * factories are middle tier functions that has only one input --> input array 
  * calling a factory works the same as calling external functions. you just need to Call.Factory(Module.factory)
  * when calling factories externally you cannot specify an input --> because we only have one input remember ?
  * each factory gets a validation input and a test case for every possibity with types. 
  * you can copy factories from one module to another and then modify it
  * use ~[lower-alpha] to shorten array (for example let ~a be data("input","initial","blah","blah") 
  * so ~a("seriouslytho")="aaa"  is the same as data("input","initial","blah","blah","seriouslytho")="aaa"
  * arrays are tubles. arrays are to globals the same as data("subscript1","subscript2") as ^data^("aaa")
  * follow the convention of import Module exposing (functiona, functionb, functionc) 
  * follw the convention of as Something

## M shorthand
* R ok:30 E  do something  (dont have to explicitly check $t) </pre>
* R *var === w $a("var")  
* w *13,*10,*80 === w $c(13)_$c(10)_$c(80)
* ZK --helpful
* $A("ABCEDE",LOCATION)
* S REF=$NA(^A(P,4))
* W REF --> ^A("A",4)
* $QL (number of subscripts)
* 
