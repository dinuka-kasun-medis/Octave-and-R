# Octave-and-R
My laboratory lecture short note 
1. **3 Vs of Big Data**
  - Volume
    1. Massive and keeps increasing volumes of data
  - Verity
    1. All type of different data as part of the decision-making and insight process
  - Velocity
    1. How quick data is arriving, stored and retrieved by users
2. **Data analysis**
  - is a process of inspecting, cleansing, transforming, and modeling data with the goal of discovering useful information, informing conclusions, and supporting decision making.

1. **R language:**
  - Case sensitive
2. **Octave:**
  - GNU Octave is a high-level language
  - Octave is great for:
    1. Data Analytics
    2. Machine Learning
    3. Statistical Computations
    4. Numerical Computations
    5. Advanced Graphing for data visualization and manipulation
  - Octave is written in C++
  - Can run MATLAB file also
  - Octave commands:
    1. \&gt;\&gt;clc clear command window
    2. natural and base 10 logarithms log(), log10()
    3. square root sqrt()
    4. built in functions:
      1. sin(pi/2)
      2. cos()
      3. tan()
      4. acos() sin inverse
      5. asin()

1.
  -
    1.
      1. round(2.4)
      2. floor(x) return the largest integer not greater than x
      3. ceil(x) Return the lowest integer not less than x
  - variables can consist with letters and numbers, but should start with letter
  - complex numbers:
    1. a=0+1\*1i
    2. b=1+2\*1i



1.
  - Matrix
    1. A=[12 30;42 45;12 1]

 ![](data:image/*;base64,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)

1.
  -
    1. B= [1:4;5:8;9:12]

 ![](data:image/*;base64,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)

1.
  -
    1. eye(3) Identity matrix
    2. inv(A) Inverse of matrix
