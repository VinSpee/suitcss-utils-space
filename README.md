# SUIT utilities: space

A SUIT collection of utility classes for low-level CSS spacing traits.

Read more about [SUIT's design principles](https://github.com/necolas/suit/).

## Installation

* npm: `npm install --save suitcss-utils-space`

## Available classes

* `u-margin<D><s>` - Margin of size `s` in the direction `D`.
* `u-padding<D><s>` - Padding of size `s` in direction `D`.

Where direction (`D`) can be:

* `A` - all
* `T` - top
* `R` - right
* `B` - bottom
* `L` - left
* `H` - horizontal
* `V` - vertical

And size (`s`) can be:

* `n` - none
* `b` - baby
* `s` - small
* `m` - medium
* `l` - large
* `g` - gigantic

## Usage

available vars:

```
	--space-n: 0;
	--space-b: .125rem;
	--space-s: .25rem;
	--space-m: .5rem;
	--space-l: 1rem;
	--space-g: 1.5rem;
```
Please refer to the README for [SUIT utils](https://github.com/necolas/suit-utils/)
