<h1 align="center">Cassandra Parameters for Dummies - Cassandra Calculator</h1>
<div align="center">
<a href="https://github.com/badges/shields/graphs/contributors" alt="Contributors">
    <img alt="Hex.pm" src="https://img.shields.io/hexpm/l/cassandra"> 
    <img src="https://img.shields.io/github/contributors/jalkanen/cassandracalculator?color=green" />
    <img alt="GitHub issues" src="https://img.shields.io/github/issues/jalkanen/cassandracalculator?color=green"></a>
</div><br>
This is a straightforward tool for understanding and experimenting with Cassandra's replication factor and consistency levels. Cassandra is a popular NoSQL database that replicates data across multiple nodes to provide high availability and fault tolerance. This, however, introduces difficulties in maintaining data consistency and avoiding conflicts.<br><br>

## Features
* Inputs of this calculator are ```Cluster Size```, ```Replication Factor```, ```Right Level```, ```Read Level```.
* Outputs of the calculator constitutes of: 
  * Whether your nodes are consistent
  * You can survive the loss of how many without impacting the application
  * You can survive the loss of how many nodes without data loss
  * You are really reading from how many nodes every time
  * You are really writing to how many nodes every time
  * Each node holds what percentage of your data
* This is a live calculator i.e., it calculates values immediately as they are entered.

There is a live version of this app available at:
http://www.ecyrd.com/cassandracalculator/

## Getting started
No extra guidelines needed, just change the values and get output.
![Tutorial GIF](https://user-images.githubusercontent.com/66861659/219908299-cc781528-8810-4405-9772-cb17946020be.gif)



