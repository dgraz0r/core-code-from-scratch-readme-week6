# THURSDAY CHALLENGES

## STRINGS

function greet(test) {
return "Hello " + test + "!";
}

## STRING LENGTH

function length(test) {
return test.length
}

let res = length("Gato")


## STRING: ToUpperCase()

function toCase(test) {
return test.toLowerCase() + "-" + test.toUpperCase()
}

let res = toCase("Gato")


## STRING: charAt()

function shortcut(first, last) {
return first.charAt(0) + last.charAt(0);
}

let res = shortcut("Amnesty", "International")


## STRING: IndexOf()

function indexOfIgnoreCase(s1, s2) {
let s1L = s1.toLowerCase();
let s2L = s2.toLowerCase();
return s1L.indexOf(s2L)
}

let n1 = indexOfIgnoreCase("bit", "it")



