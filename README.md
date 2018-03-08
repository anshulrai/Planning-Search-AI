
# Planning Search AI

## Synopsis

This project includes the classes and functions needed to solve deterministic logistics planning problems for an Air Cargo transport system using a planning search agent.
With progression search algorithms optimal plans for each problem will be computed.  Unlike simple navigation problems, there is no simple distance heuristic to aid the agent.
Instead, domain-independent heuristics are used.

![Progression air cargo search](images/Progression.PNG)

## Environment requirements
- Python 3.4 or higher
- Includes a copy of [companion code](https://github.com/aimacode) from the Stuart Russel/Norvig AIMA text.  


- The `tests` directory includes `unittest` test cases to evaluate the implementation.
    - `python -m unittest tests.test_my_air_cargo_problems`
    - `python -m unittest tests.test_my_planning_graph`
    - You can run all the test cases with additional context by running `python -m unittest -v`
- The `run_search` script is provided for gathering metrics for various search methods on any or all of the problems and should be used for this purpose.

Few results saved in folder `Result Images`.
