# Test Time compute

Test-time methods use dynamic inference strategies that allow models to “think longer” on harder problems. These methods can make smaller models outperforms their larger conuterparts.

# Mini-Project

In this mini-project, we explore a new test time compute approach that leverages dynamic beam search based on 2 confidence metrics:
* entropy: used to limit or increase the sampling space at each iteration
* Attention score with the last prompt: used to measure how aligned the models response with the instruction in the last prompt. We use this metric to select best beam candidates during beam search.

 
