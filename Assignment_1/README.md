# MFCS-SYSTEM_LAB

# **📊 Probability Distributions **  

Welcome to the **Probability Distributions of Random Variables Assignment**! 🎓✨ This project is all about exploring the magical world of probability distributions 🧙‍♂️ — Poisson, Binomial, Geometric, and Uniform. It’s a blend of computer science, mathematics.

---

## **📖 About the Assignment**

This project implements a Python function `get_probability_distribution` that computes probabilities for different probability distributions based on user-defined parameters and input values. The function also handles edge cases like negative numbers (we remove them faster than spam emails 🧹). A graphical plot is generated to visualize the probability distribution for the given inputs.

---



## **⚙️ Features**

1. **Negative Values Cleanup**: Negative values? Nope. Removed and logged because they’re just not allowed here.  
2. **Smart Filtering for Uniform Distribution**: Ensures input values stay within the required range (`[a, b]`) for valid computations.  
3. **Handles Multiple Distributions**:  
   - **Poisson** 🐟 (because it sounds like a fish, but it’s math).  
   - **Binomial** 🎲 (n trials, p probability — it's the classic coin flip game).  
   - **Geometric** ⛓️ (success probability with failures in tow).  
   - **Uniform** 📏 (everything is equally likely, like guessing which Netflix show you’ll watch).  
4. **Interactive Visualization**: Plots a clean bar chart for better data representation 📈.  

---


## **🔬 Workflow Explained**  

Here's how it works:

1. **🎯 Input Validation**:  
   - Removes any negative numbers and logs them.  
   - For uniform distribution, ensures values are in the range `[a, b]`.  

2. **📐 Probability Calculation**:  
   - Based on the distribution selected, computes the probabilities for filtered values.  

3. **🖼️ Plot the Distribution**:  
   - Generates a bar chart for visualizing the probabilities. 