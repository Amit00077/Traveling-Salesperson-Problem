# Traveling-Salesperson-Problem

# The approach

### Let’s start with a few definitions, rephrased in the context of the TSP:

### Gene: a city (represented as (x, y) coordinates)

### Individual (aka “chromosome”): a single route satisfying the conditions above

### Population: a collection of possible routes (i.e., collection of individuals)

### Parents: two routes that are combined to create a new route

### Mating pool: a collection of parents that are used to create our next population (thus creating the next generation of routes)

### Fitness: a function that tells us how good each route is (in our case, how short the distance is)

### Mutation: a way to introduce variation in our population by randomly swapping two cities in a route

### Elitism: a way to carry the best individuals into the next generation
