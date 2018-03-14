# rain

# Raindrop Optimization

TYPE 1:

1. Points are scattered stochatically and evaluated. An initial contour map of what's known and unknown is defined.
2. Each successive iteration refines the map, until n rounds are completed.
3. PSO or something like it is applied, but weighted by what was learned in the mapping phase.

TYPE 2:

1. Identify probable locations of optima based on relative weights of stochastic points.
2. Use information gained to constrain the next selections (like a Gaussian Process - only simpler, since those are expensive)
3. Repeat until converge
