##  NASDAQ-100 Index Fund Construction

**Description:**

Our project's primary objective is to create a strategy for stock selection and weight determination to replicate the NASDAQ-100 index. This involves identifying a subset of stocks with strong return correlations that can effectively represent the entire index. Our aim is to pinpoint specific stocks and their respective weights for our fund's portfolio while determining the optimal number of stocks to minimize the absolute deviation of returns from the underlying index.

**Project Heading:**

**1. Project Objective:**

   - Develop a strategy to construct a fund that closely replicates the NASDAQ-100 index.
   - Identify specific stocks and their respective weights for the portfolio.
   - Determine the optimal number of stocks to minimize deviations from the index returns.

**2. Approach:**

   - Analyze NASDAQ-100 returns in 2019 to lay the foundation for a passive investment strategy.
   - Utilize the index returns in 2020 as a benchmark for evaluating the performance of the passive strategy.
   - Employ a multi-step process involving integer programming, linear programming, and mixed-integer programming techniques.

**3. Methodology:**

   - Integer programming for stock selection based on correlations.
   - Linear programming to calculate optimal weights for selected stocks.
   - Explore mixed-integer programming for fine-tuning the solution.

**4. Recommendations:**

   - Utilize Mixed-Integer Programming (MIP) for stock selection for maximum cumulative returns.
   - Optimal stock selection range in the MIP model: 40 to 60 stocks.
   - Strongly endorse Method 2 for constructing the Index fund to replicate the NASDAQ-100.
   - Set 'm' at approximately 30, considering the trade-offs between portfolio expansion costs and tracking error.

**5. Considerations:**

   - Method 2 requires more computational resources and time.
   - Method 1 may be considered when resource constraints are insurmountable.
   - Visualizations provided for comparative performance analysis across different 'm' values.

This data-driven analysis empowers you to make informed decisions aligned with our fund's objectives and resource constraints.
