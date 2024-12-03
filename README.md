# Goclasses

Test Series of ML-1
### Ques(1):
### Given:
- Query point \( x_q = (0, 0) \)
- Points:
  - \( x_1 = (1, 1) \)
  - \( x_2 = (1.5, 0) \)
- Distance metrics:
  - **Euclidean Distance**: \( d_E = \sqrt{(x_2 - x_1)^2 + (y_2 - y_1)^2} \)
  - **Manhattan Distance**: \( d_M = |x_2 - x_1| + |y_2 - y_1| \)

### Step 1: Calculate distances

#### Euclidean Distance:
1. From \( x_q \) to \( x_1 \):
   \[
   d_E(x_q, x_1) = \sqrt{(1 - 0)^2 + (1 - 0)^2} = \sqrt{1 + 1} = \sqrt{2} \approx 1.41
   \]

2. From \( x_q \) to \( x_2 \):
   \[
   d_E(x_q, x_2) = \sqrt{(1.5 - 0)^2 + (0 - 0)^2} = \sqrt{(1.5)^2} = 1.5
   \]

#### Manhattan Distance:
1. From \( x_q \) to \( x_1 \):
   \[
   d_M(x_q, x_1) = |1 - 0| + |1 - 0| = 1 + 1 = 2
   \]

2. From \( x_q \) to \( x_2 \):
   \[
   d_M(x_q, x_2) = |1.5 - 0| + |0 - 0| = 1.5 + 0 = 1.5
   \]

### Step 2: Compare distances
- **Euclidean Distance**:
  - \( d_E(x_q, x_1) = \sqrt{2} \approx 1.41 \)
  - \( d_E(x_q, x_2) = 1.5 \)
  - Nearest neighbor: \( x_1 \) (smaller distance)

- **Manhattan Distance**:
  - \( d_M(x_q, x_1) = 2 \)
  - \( d_M(x_q, x_2) = 1.5 \)
  - Nearest neighbor: \( x_2 \) (smaller distance)

### Step 3: Correct Option
The correct statement is:
> **C. \( x_1 \) is the nearest neighbor according to Euclidean distance, and \( x_2 \) is the nearest neighbor according to Manhattan distance.**
