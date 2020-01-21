
# Community Detection - Lab

## Introduction

In this lab, you'll once again work to cluster a network dataset. This time, you'll be investigating a [Meetup](https://www.meetup.com/) dataset for events occurring in Nashville.

## Objectives

You will be able to: 

- Make visualizations of clusters and gain insights about how the clusters have formed 
- Cluster a real-life social network dataset to detect communities within the network  


## Load the Dataset

To get started, load the dataset `'nashville-meetup/group-edges.csv'` as a pandas Dataframe. 


```python
# Your code here

groups = None
```

To add some descriptive data, import the file `'nashville-meetup/meta-groups.csv'`.


```python
# Your code here
groups_meta = None
```

## Transform to a Network Representation

Take the Pandas DataFrame and transform it into a graph representation via NetworkX. Make nodes the names of the various groups within the Nashville area. The edges should be the weights between these groups.


```python
# Your code here
```

## Visualize the Network


```python
# Your code here
```

## Refine the Visual

As you should see, the initial visualization is a globular mess! Refine the visualization to better picture the center core of the  network.


```python
# Your code here
```

## Cluster the Network

Now, that the dataset is a little more manageable, try clustering the remaining group nodes.


```python
# Your code here
```

## Determine An Optimal Clustering Schema

Finally, determine a final clustering organization.


```python
# Your code here
```

## Visualize the Clusters

Analyze the output of your clustering schema. Do any clusters of groups stand out to you?


```python
# Your code here
```

## Summary

In this lab, you got another chance to practice your network clustering skills, investigating a meetup dataset of events and groups surrounding the Nashville area. If you're up for the challenge, feel free to continue investigating the dataset and trying to cluster users or events!                                                                                                                                                               
