# Crossing-the-river-game
# Problem statement
# Create famous 3 missionaries 3 cannibals crossing the river game. Rules are as follows.
# Demonstration.

# Rules
# 1.Number of missionaries on either side should never be less than number of cannibals
# 2.Only one or 2 people can travel through boat at a time.
# 3.You win the game when all missionaries and cannibals on the right go to the left side

# Steps to solve the problem
# Step 1
# Display number of cannibals(C) and missionaries(M) on the left and right.
# Display boat(B) on the appropriate side starting from the right.
# Initial Display :-
# M = 0 C = 0 |-----B| M = 3 C = 3
# (You can change display according to your imagination or convinience)

# Step 2
# Accept number of missionaries and then number of cannibals. Example: Initially if 1 missionaries and 1 cannibals goes from right to left the game display will look like this

# M = 1 C = 1 |B-----| M = 2 C = 2

# (Keep the side of the boat in mind)

# Don't forget to add and subtract number of missonary on both sides accordingly

# Step 3
# Define Invalid moves and add conditional 'if' statements accordingly

# Rules

# Number of people in a Boat should be 1 or 2
# Number of chosen missionaries or cannibals should not be greater than number of available missionaries or cannibals on the given side. In above step one should not be able subtract 2 missionaries from left as only 1 is available.
