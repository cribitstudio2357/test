.. test documentation master file, created by
   sphinx-quickstart on Wed Mar 15 20:37:29 2023.
   You can adapt this file completely to your liking, but it should at least
   contain the root `toctree` directive.

Welcome to test's documentation!
================================

.. toctree::
   :maxdepth: 2
   :caption: Contents:



Indices and tables
==================

* :ref:`genindex`
* :ref:`modindex`
* :ref:`search`

#title Clicod

Speedy and Interactive Language made by Cribit Studio.

#value
NOTE: Clicod was developing now. It does not work yet.
NOTE: Clicod will be changed.

Hello, World!
Clicod has a distributing system we can use easy, a simple syntax and is a modern compiler language.
We can use Clicod for ML, a Server, and much more!
By Clicod, "Hello, World!" program is:

IMPORT cdfmt AS fmt

FN __main__()
  fmt.Print(val<<"Hello, World!")


Let's See More and Start a Travel of Clicod!

#next

Clicod's Syntax:

Variable:

foo <<< #1234  -- `#1234` into `foo`.
foo << #4321  -- `#4321` into `foo`
VAR bar: int  -- Define `bar` as `int`.
bar << #xc0d  -- c0ffee (hex) into `bar`
VAR hello: uflo  -- Define `hello` as ufloat.
VAR world: UFO  -- Define `world` as ufloat.


Function:

FN my_fn(my_arg: lis[int]) (Ret: int)
  foo(bar<<#1234)  -- Call function `foo` and give argument `bar` as `#1234`
  RET Ret << my_arg@[0]  -- Index 0 value of `my_arg` into `Ret` then return.


One Statement on Multi Line:

example_fn(
 | foo << #1234,
 | bar << helloworld,
 | )


Comment:

-- My comment.
--- Hello, World!
foo + -- This is a comment too. -- bar


Types:
There are int:integer (uint, int8, uint8...), flo:float (uflo, flo8, uflo8...), lis:list, boo:boolean, dic:dictionary, sto:set, sli:slice, and uniq:unique that we instant to be unique.

Slice:
We can make slice (type name is `sli`) and slice a list by that.
For example, this code slices `my_list` by `[#0 ~ #xc0d]`:

my_list@[#0 ~ #xc0d]

This (v) is an example code that deletes #0 to #xc0d with `my_list`

my_list.delete([#0 ~ #xc0d])
