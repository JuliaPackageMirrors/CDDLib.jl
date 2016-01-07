# CDD

CDD.jl is a wrapper for [cdd](https://www.inf.ethz.ch/personal/fukudak/cdd_home/).

As written in the [README of cddlib](ftp://ftp.ifor.math.ethz.ch/pub/fukuda/cdd/README.libcdd):
> The C-library  cddlib is a C implementation of the Double Description
> Method of Motzkin et al. for generating all vertices (i.e. extreme points)
> and extreme rays of a general convex polyhedron in R^d given by a system
> of linear inequalities:
>
>    P = { x=(x1, ..., xd)^T :  b - A  x  >= 0 }
>
> where  A  is a given m x d real matrix, b is a given m-vector
> and 0 is the m-vector of all zeros.
>
> The program can be used for the reverse operation (i.e. convex hull
> computation).  This means that  one can move back and forth between
> an inequality representation  and a generator (i.e. vertex and ray)
> representation of a polyhedron with cdd.  Also, cdd can solve a linear
> programming problem, i.e. a problem of maximizing and minimizing
> a linear function over P.

[![Build Status](https://travis-ci.org/blegat/CDD.jl.svg?branch=master)](https://travis-ci.org/blegat/cdd.jl)
[![Coverage Status](https://coveralls.io/repos/blegat/CDD.jl/badge.svg?branch=master&service=github)](https://coveralls.io/github/blegat/cdd.jl?branch=master)
