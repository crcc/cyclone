[<img src="images/cyclone-logo-04-header.png" alt="cyclone-scheme">](http://github.com/justinethier/cyclone)

# Benchmarks

The following [benchmarks from Larceny](http://www.larcenists.org/benchmarksGenuineR7Linux.html) give an indication of how well Cyclone performs compared with other R<sup>7</sup>RS Schemes. These benchmarks were recorded on a system with an Intel Core i5 CPU @ 2.20 GHz and indicate elapsed time in seconds. Longer bars indicate worse performance, although a bar is not displayed if the benchmark could not be completed in a reasonable amount of time.

## Gabriel Benchmarks

<img src="images/benchmarks/gabriel.png">

Benchmark | Cyclone | Chibi | Chicken
--------- | ------- | ----- | -------
browse    | 77      | 439   | 30
deriv     | 39      | 212   | 13
destruc   | 136     | 197   | 20
diviter   | 51      | 122.9 | 8
divrec    | 70      | 108   | 29
puzzle    | 184     | -     | 32
triangl   | 95      | 201   | 26.6
tak       | 70      | 105   | 28.9
takl      | 132     | -     | 78.7
ntakl     | 152     | 193   | 77.9
cpstak    | 92      | -     | 35
ctak      | 7.9     | -     | 8.6

## Kernighan and Van Wyk Benchmarks

<img src="images/benchmarks/kvw.png">

Benchmark | Cyclone | Chibi | Chicken
--------- | ------- | ----- | -------
ack       | 288     | 161   | 116
array1    | 167     | 130   | 29.4
string    | 1       | 8.478 | 1.584
sum1      | 27      | 74    | 7.737
cat       | 43.669  | 132   | 55
tail      | 367     | 674   | -
wc        | 202     | 1072  | 36.4

## Garbage Collection Benchmarks

<img src="images/benchmarks/gc.png">

Benchmark | Cyclone | Chibi | Chicken
--------- | ------- | ----- | -------
nboyer    | 67.783  | 73.516  | 39.377
sboyer    | 48.044  | 69.243  | 23.628
gcbench   | 143.478 | -       | 16.75
mperm     | 328.741 | 260.358 | 57.5