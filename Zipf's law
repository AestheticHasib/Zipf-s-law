

import matplotlib.pyplot as plt
import numpy as np

# Number of ranks (like top 50 words)
N = 50

# Zipf's Law: f(r) ~ 1/r
ranks = np.arange(1, N+1)
frequencies = 1 / ranks

# Normalize frequencies to sum to 1 (like probabilities)
frequencies = frequencies / frequencies.sum()

# Plotting
plt.figure(figsize=(10, 6))
plt.plot(ranks, frequencies, marker='o')
plt.title("Zipf's Law (f ∝ 1/r)")
plt.xlabel("Rank")
plt.ylabel("Frequency (normalized)")
plt.grid(True)
plt.show()
