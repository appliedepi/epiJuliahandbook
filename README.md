# The Epidemiologist Julia Handbook

Starting off with a quarto book proj for a julia handbook. 

## How it works 

- Using VScode because you can run Julia in terminal (RStudio doesn't currently support) 
- Quarto projects is the new replacement for R's {bookdown}, and is much more flexible and clean 

## Getting setup 
- install the following: 
    - [Julia](https://julialang.org/)
        - necessary additions for working with [quarto](https://quarto.org/docs/computations/julia.html#installation)
        - note just like R, Julia is the backend hideous to work with, and Rstudio or VScode are the front end - unfortunately Rstudio doesn't currently allow you to run Julia in the console, but this might come ? which would simplify things 
    - [Visual Studio Code](https://visualstudio.microsoft.com/) note **CODE** in blue not purple
        - within VSCODE you add extensions for: 
            - [julia](https://code.visualstudio.com/docs/languages/julia)
            - [quarto](https://quarto.org/docs/get-started/hello/vscode.html) 
    - Once installed you can [clone the repo](https://vscode.github.com/) directly from VScode

# Packages 
- Julia has built in package management (called {pkg}) for a project (the equivalent of R's {renv})
- see the [documentation](https://docs.julialang.org/en/v1/stdlib/Pkg/) for how this works



    