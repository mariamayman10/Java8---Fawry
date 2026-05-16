# Java Functional Interfaces & Streams

An exercise on Java functional interfaces, lambdas, and the Stream API.

## Overview

Each task is solved twice:
- **Declared** — functional interfaces defined explicitly as anonymous classes
- **Direct (lambda)** — functional interfaces used inline via lambdas or method references

## Tasks

### LambdaExample — User Repository
Filtering and sorting a list of users using `Predicate` and `Comparator`.

| Task | FI Used |
|------|---------|
| List all users | — |
| List active users | `Predicate` |
| List users with age > 5 sorted by name | `Predicate`, `Comparator` |
| List users with age < 10 sorted by age | `Predicate`, `Comparator` |
| List active users sorted by name | `Predicate`, `Comparator` |
| List active users with age > 8 sorted by name | `Predicate`, `Comparator` |

### StreamsExample — Library
Processing authors and books using the Stream API.

| Task | FI Used |
|------|---------|
| Print all authors | `Consumer` |
| Print active authors | `Predicate`, `Consumer` |
| List published books for all authors | `Function`, `Predicate`, `Consumer` |
| Average price of all books | `Function`, `ToDoubleFunction` |
| Active authors with at least one published book | `Predicate` |
