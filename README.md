# Bomb the Hornets Nests

A small project on how to implement a evolutionary algorithm and utilize it to eliminate a couple of hornets nests inside a house's attic. 

## Problem's Description

You just bought a house and you discover that the attic is full of hornets. You decide to eliminate these hornets before moving in.
In order to do so, you equip yourself with three insecticide bombs which have a specific range and must be placed really close to the 
nests. 

Unfortunately, only three of these bombs are not enough to kill all the hornets, but there is a way to maximize the amount of hornets 
that will be killed. 

You are given the following hints:

* A map that describes the placement of the nests and also the amount of hornets that live in each one of them (using an array of 100x100).

<p align='center'>![alt text](https://raw.githubusercontent.com/Xronis/Bomb_the_hornets/master/images/Selection_035.png)</p>	

* A formula that describes the relationship between the distance of the bomb from the nest and the killing rate: <br>
	<p align='center'>K = n * dmax / (20 * d + 0.00001)</p>

  where:
    * K: Dead hornets inside the nest
    * n: Amount of hornets inhabiting the nest
    * d: Distance between the bomb and the nest
    * dmax: Maximum distance between 2 nests

The aim of this exercise is to find out the best placement of the bombs in order to kill most of the hornets.

## Authors

**Chronis Panagiotidis** - [Xronis](https://github.com/Xronis)
