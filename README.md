# Dimensionality_Reduction_in_Action
Tutorial on Dimensionality Reduction for a presentation at 2026 Applied Machine Learning Conference in Charlottesville.

### Plan of the tutorial


1. Curse of dimensionality - and how it affects clustering of high-dimensional data

  *   distribution of distances in high-dimension looses its importance
  *   the nearest neighbor is almost as far as the farthest

2. Random projections

*   low computational way to preserve distances
*   project to an extremely low dimension, disrupt distance structure, reveal hidden groupings as clusters in low dimensions


3. Linear reduction - easy to interpret

  *   eigenvectors identify the direction where the data is spread out the most

4. Complex non-linear reductions

  *  neural network that encodes and subsequently decodes high-dimensional data.
  *  use the encoder to reduce dimensionality

5. Non-linear mappings useful for visualization

  * preserve local and global structure combining several low-dimensional manifolds

