# 7. Practical Coding Basics: Your First ML Model 🐍

Now that you understand the concepts, let's see what a Machine Learning "recipe" looks like in actual code! We use a library called **Scikit-Learn** because it's very beginner-friendly.

## The "Fruit Picker" Code Example 🍎🍊

In this example, we want to teach the computer to tell the difference between an **Apple** and an **Orange** based on their **Weight** and **Texture**.

### 1. The Ingredients (Data)
First, we give the computer some examples.
*   **Weight:** In grams.
*   **Texture:** 0 for Smooth (Apple), 1 for Bumpy (Orange).

```python
# Features: [Weight, Texture]
features = [[140, 0], [130, 0], [150, 1], [170, 1]]

# Labels: 0 for Apple, 1 for Orange
labels = [0, 0, 1, 1]
```

### 2. Choosing the Chef (The Model)
We'll use a **Decision Tree** (the "Yes/No" question model).

```python
from sklearn import tree

# Initialize the model
clf = tree.DecisionTreeClassifier()
```

### 3. Training (Learning from Examples)
This is where the magic happens! The model looks at the features and labels and learns the patterns.

```python
clf = clf.fit(features, labels)
```

### 4. Predicting (The Test)
Now we give it a new fruit it has never seen before!
*   A fruit that weighs **160g** and is **Bumpy** (1).

```python
print(clf.predict([[160, 1]]))
# Output will be [1] -> Orange!
```

---

## Layman Code Logic: What just happened? 🤔

Instead of writing:
`if weight > 150 and texture == \"Bumpy\": return \"Orange\"`

We just said:
`Hey computer, look at these 4 examples. Now you figure out the rule for this 5th one!`

## Why Python? 🐍

Python is the most popular language for ML because:
1.  **Readability:** It looks like English.
2.  **Libraries:** People have already written the hard math parts for you (like Scikit-Learn).
3.  **Community:** If you get stuck, thousands of people have already asked the same question online!

**Next Up:** [Glossary & Learning Resources](08_glossary_and_resources.md) (Coming Soon!)
