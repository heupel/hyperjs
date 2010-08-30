HyperJS - JavaScript in C#
Project initiated by Tony Heupel (pronounced "High-pull")
===========================
Copyright 2010 (C) Tony Heupel

Contents:
  HyperJS - a.k.a. JS.cs:    JavaScript-like programming in C# using closures and dynamics.  
    This is a lame attempt at creating JavaScript in C# just to see how the
    HyperHypo class holds up to being similar to JavaScript style in C#; not
    necessarily because it's a good idea to write C# in JavaScript--because 	it's not...

    That being said, it's just a fun weekend project for me right now and is
    stretching my brain and expanding my knowlege of JavaScript and C# 4.0.
    
    Boolean is the only thing that actually resembles JavaScript (and has unit tests), 
    but it uses C# constructs to do it.  I suspect that once I get Object.valueOf and
    the other core JavaScript conversions in place, it will look nothing like it does 
    now; but at least I have tests to prove it!
  
    This is based on my HyperCore libraries with HyperDictionary (dictionary
	implementation with prototype-style "inhertance") and HyperHypo (dynamic
	C# class that support JavaScript-style prototype inheritance using
	a HyperDictionary as the Member Provider.
    Hyper - "More than" C#
    Hypo  - "Less than" JavaScript.

  HyperJS.UnitTest: Unit test that cover HyperJS implementations.