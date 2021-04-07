# Dict To Graph
Takes a dictionary and converts it into a graph.

`gen_path` will generate all possible paths and will also generate the `shortest path` between two vertices inputted. 

`create_path` will generate a path between two vertices if a path does not exist already by default. 

# Example 

- `a -> c `
- `b -> c `
- `b -> e `
- `c -> a `
- `c -> b `
- `c -> d `
- `c -> e `
- `d -> c `
- `e -> c `
- `e -> b `

## Input  
`graph = { "a" : ["c"],
          "b" : ["c", "e"],
          "c" : ["a", "b", "d", "e"],
          "d" : ["c"],
          "e" : ["c", "b"],
          "f" : []
        } `
        
## Output 

`[('a', 'c'), ('c', 'd'), ('c', 'e'), ('c', 'a'), ('c', 'b'), 
('b', 'c'), ('b', 'e'), ('e', 'b'), ('e', 'c'), ('d', 'c')]`



# Extras 

Made in Python 🐍

