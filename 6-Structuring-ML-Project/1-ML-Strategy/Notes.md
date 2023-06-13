# Introduction to ML Strategy

- Course focus: Structuring machine learning projects and machine learning strategy.
- Goal: Learn to quickly and efficiently improve machine learning systems.
- Motivating example: Working on a cat classification project with 90% accuracy, aiming for higher performance.
- Ideas for improvement:
    - Collecting more diverse training data, including images of cats in different poses and varied negative examples.
    - Experimenting with longer training duration using gradient descent or alternative optimization algorithms like Adam.
    - Trying different network sizes, dropout, L2 regularization, and modifying network architecture.
- Importance of choosing effective strategies: Poor choices can lead to wasted time and effort.
- Course objectives: Teach strategies to analyze machine learning problems and identify promising approaches.
- Unique course materials: Sharing lessons from building and deploying numerous deep learning products.
- Evolution of machine learning strategy in the era of deep learning.
- Hope to enhance effectiveness in developing deep learning systems.

# Orthogonalization

- Orthogonalization is a process in machine learning where you identify specific knobs to tune in order to achieve a desired effect.
- The concept of orthogonalization is illustrated using examples of TV knobs and car controls.
- In machine learning, there are four criteria to consider: performance on the training set, performance on the dev set, performance on the test set, and real-world performance.
- Each criterion may require tuning specific knobs or sets of knobs.
- Examples of knobs to tune include network size, optimization algorithms, regularization techniques, and adjusting the size of the dev set.
- Orthogonal controls are preferable as they affect a single aspect without impacting other variables.
- Early stopping is less orthogonalized because it affects both training set fit and dev set performance simultaneously.
- The goal is to diagnose the bottleneck in system performance and identify the specific knobs to improve it.
- Detailed exploration of this process will be covered in the upcoming weeks.