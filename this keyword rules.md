5 this keyword binging rules

Default binging
this points to a global object. Keep in mind: in the strict mode global object is undefined

Implicit binding
A "­context object­" reference gets bound to this

Explicit binding
this gets bound to an object of our choice by calling explicitly Functi­on.p­ro­tot­ype.call() or Functi­on.p­ro­tot­ype.ap­ply(). Unfort­una­tely, this biding is lost in = assign­ments.

Explicit "­har­d" binding
"­Har­d" is just an implem­ent­ation of the bind() patter­n/m­ethod that addresses problem of this context lost in assign­ments

new f() binding
An object, newly constr­ucted by new call, is set as this reference in function f

this binding rules apply to how this keyword gets evaluated in functions. The rules above are sorted from the most generic to the most specia­lised. Explicit "­sof­t" binding does not prevent us from losing this context
