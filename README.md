# Paulie's GRT Subgraph

This repository contains the subgraph developed during the course on becoming a subgraph developer in The Graph Network. If you're looking to understand the technical intricacies of The Graph and get hands-on experience with subgraphs, this repository and the corresponding course are the right starting points!

## About the Course

The course, titled **["Learn everything you need to know about becoming a subgraph developer in The Graph Network"](https://thegraph.academy/course/subgraph-developer-course/)**, is tailored to introduce participants to:

- The core technical aspects of The Graph.
- The concept, architecture, and nuances of subgraphs.
- Practical skills needed for developing and deploying subgraphs.

## Repository Structure

- `schema.graphql`: Defines the entities and their relationships for this subgraph.
- `src/`: Contains the mapping logic.

## Queries

To test the subgraph, you can use the following basic query:

```graphql
{
  transferEvents(first: 5) {
    id
    amount
  }
}

