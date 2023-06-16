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

- The script discusses the challenge of building machine learning systems and the numerous options available for experimentation and modification.
- Orthogonalization is introduced as a process of identifying specific parameters to tune in order to achieve a desired effect.
- The analogy of an old school television with multiple knobs is used to illustrate the concept of orthogonalization.
- The importance of designing knobs with interpretable functions is emphasized, where each knob has a distinct impact on a specific aspect.
- The script extends the analogy to driving a car, highlighting the need for separate controls for steering and speed to make driving more interpretable.
- Orthogonal controls that align with the desired dimensions of control make it easier to tune the system.
- The script relates orthogonalization to machine learning and identifies four main aspects that need to be addressed: performance on the training set, performance on the development set, performance on the test set, and real-world performance.
- Each aspect requires specific knobs or sets of knobs to be adjusted, such as using a bigger network or a better optimization algorithm for training set performance.
- Different sets of knobs are introduced for each aspect, such as regularization for improving performance on the development set or increasing the size of the development set to address overfitting.
- The importance of aligning the knobs with the specific aspects to be controlled is stressed.
- The script mentions the possibility of changing the dev set or the cost function if the system's performance on the test set does not align with real-world requirements.
- The concept of early stopping is discussed as a knob that affects both training set fit and development set performance, making it less orthogonalized.
- The script highlights the benefits of orthogonalized controls in making the tuning process easier.
- The importance of diagnosing the bottleneck in system performance and identifying the specific knobs to address the issue is emphasized.
- The script mentions that further details and examples of specific knobs will be discussed in subsequent sections.