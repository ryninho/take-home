## My thoughts on what distinguishes a great submission on a take-home data science challenge

In no particular order:

1. Concise and clear code- easy to follow and potentially modify. Bonus points for good use of functions for DRY-ness (not needed if repetition is kept to a minimum in other ways)
2. Reasonably performant code- doesn’t require excess computation or memory given what it achieves
3. Resourceful use of libraries and tools (e.g caret for grid search or seaborne for graphs)- uses the right tools for job and minimizes reinvention of existing functions
4. Notes or comments in code when needed or helpful
5. Runs basic profiles and sanity-checks on the data (e.g. counts, duplicates, min and max)
6. Explores relationships in the data
7. Gets the most out of the data available- uses what’s “free” and engineers more and better features; uses features intelligently (e.g. store_id should be a factor, not an integer)
8. Demonstrates understanding of the particulars of the approach they are taking- e.g. knows what to do in order to improve the kind of model they are using (e.g. handling the bias/variance tradeoff via tweaking interaction depth limits in a tree-based model, or handling outliers carefully and doing some form of variable selection in a linear model)
9. Shows some tendency toward simplicity where complexity is not clearly a potential help
10. Efficiency and/or comprehensiveness of search in the modeling path- either good insight-driven search or thoughtfully-tuned grid-based search of hyperparameters could demonstrate this
11. Uses training, cross-validation and test sets appropriately (bonus points for time-based split, bonus points for having a “test” group that is not part of cross-validation for evaluating the final model)
12. Tries more than one thing- pursues the best possible outcome in some way (with different models or feature selection or feature engineering, etc)
13. Uses a reasonable quality measure and seems to know what it means
14. Doesn’t make any amateur-ish or seriously damaging errors
15. Reflects on what they’ve learned at the end- is this model any good? What do we now know about the problem? Was it the right model for the problem?
16. Has good idea for what next steps would be given more time
17. Articulates thinking and takeaways clearly for the reader- e.g. translating MSE into average error in minutes… bonus points for relevant graphs or tables


Short version- skills and tendencies demonstrated:

* Analytical curiosity (reasonable amount of exploration and insight)
* Careful execution (avoids errors or sloppiness)
* Modeling skill (uses selected modeling approach effectively)
* Coding proficiency (concise and clear and uses best tools)
* Communication (articulates approach and findings effectively enough for collaboration)

