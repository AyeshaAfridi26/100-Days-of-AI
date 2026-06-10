# 100 Days of AI Challenge

Challenge Details
- **Start Date:** May 24, 2026
- **Goal:** Complete 100 consecutive days of AI/ML learning
- **Focus Areas:** Python Programming, Machine Learning, Data Science
- **Repository:** Track progress, code, notes, and projects

---

##  Repository Structure

```
100 Days of AI/
├── Python/
│   ├── 01_Introduction_to_Programming.ipynb
│   ├── 02_Basic_Terminologies_of_Programming.ipynb
│   ├── 03_Introduction_to_Python_.ipynb
│   ├── 04_virtual_env.py
│   ├── 05_String_Manipulation.ipynb
│   ├── 06_Operators.ipynb
│   ├── 07_List.ipynb
│   ├── 08_Tuple.ipynb
│   ├── 09_Sets_and_Dictionaries.ipynb
│   ├── 10_Conditional_Statements.ipynb
│   ├── 11_Loops.ipynb
│   ├── 12_functions.ipynb
│   ├── 13_Arrays.ipynb
│   ├── 14_Json & RegEx.ipynb
│   ├── 15_Try & Except.ipynb
│   ├── 16_OOP_in_Python.ipynb
│   └── 17_File_Handling.ipynb
│
├── Libraries/
│   ├── Numpy/
│   │   ├── 01_Numpy.ipynb
│   │   ├── 02_Numpy.ipynb
│   │   ├── 03_Numpy.ipynb
│   │   ├── 04_Numpy.ipynb
│   │   └── 05_Numpy.ipynb
│   │
│   ├── Pandas/
│   │   ├── 01_Pandas.ipynb
│   │   ├── 02_Pandas.ipynb
│   │   ├── 03_Pandas.ipynb
│   │   ├── 04_Pandas.ipynb
│   │   └── 05_Pandas.ipynb
│   │
│   └── Matplotlib/
│       ├── 01_Matplotlib.ipynb
│       ├── 02_Matplotlib.ipynb
│       ├── 03_Matplotlib.ipynb
│       └── 04_Matplotlib.ipynb
│
├── Projects/
│   └── (Future project directories will be added)
│
├── Notes/
│   └── (Learning notes and summaries)
│
└── README.md
```

---

## Day 1 – Introduction to Programming & Python Basics
- **Introduction to Programming** — Programming concepts, why Python for AI/ML, environment setup.
- **Basic Terminologies** — Variables, data types, operators, control structures, functions and scope.
- **Introduction to Python** — Syntax, indentation, first program, interactive mode vs scripts.
- **Virtual Environments** — `venv`, installing packages with pip, managing dependencies.
- **String Manipulation** — Methods, formatting, slicing, indexing, regex basics.

---

## Day 2 – Operators and Lists
- **Operators** — Arithmetic, comparison, logical, bitwise, membership, identity; precedence and associativity.
- **Lists** — Creating and indexing, list methods, slicing, comprehensions, nested lists.

---

## Day 3 – Tuples, Sets, and Dictionaries
- **Tuples** — Immutable sequences, tuple methods, when to use them over lists.
- **Sets** — Union, intersection, difference, symmetric difference; adding and removing elements.
- **Dictionaries** — Key-value pairs, methods, iteration, nested dictionaries.

---

## Day 4 – Conditional Statements and Loops
- **Conditionals** — `if`/`elif`/`else`, nested conditions, ternary expressions.
- **Loops** — `for` and `while`, `break`/`continue`/`pass`, `range()`, nested loops.

---

## Day 5 – Functions and Arrays
- **Functions** — Defining and calling, parameters and arguments, return values, scope, lambdas, recursion.
- **Arrays** — `range()`, NumPy array introduction, lists vs NumPy arrays, element-wise math.

---

## Day 6 – JSON, Regex, and Exception Handling
- **JSON & RegEx** — Parsing and serializing with the `json` module; pattern matching with `re` (`match`, `search`, `findall`, `sub`).
- **Try / Except** — Exception types, `try`/`except`/`else`/`finally`, `raise`, custom exception classes.

---

## Day 7 – Object-Oriented Programming and File Handling
- **OOP** — Classes and objects, `__init__` and `self`, instance vs class attributes, the four pillars (encapsulation, inheritance, polymorphism, abstraction), `super()`, MRO, `@property`, abstract base classes.
- **File Handling** — `open`/`close`, file modes, reading and writing, context managers (`with`), binary files, file exception handling.

---

## Day 8 – Introduction to NumPy
- **NumPy Foundations** (`01_Numpy.ipynb`) — Why NumPy beats Python lists, vectorization, array creation (`array`, `zeros`, `ones`, `arange`, `linspace`), `shape`/`dtype`, dtype gotchas.
- **Array Operations** (`02_Numpy.ipynb`) — Indexing, slicing, views vs copies, boolean masking, `np.where`, reshaping, broadcasting, stacking and splitting.

---

## Day 9 – NumPy Math, Statistics & Linear Algebra
- **Math & Statistics** (`03_Numpy.ipynb`) — ufuncs (`sqrt`, `exp`, `log`, trig, rounding), aggregations and the `axis` argument, `corrcoef`, `np.unique`.
- **Linear Algebra** — Dot product and the `@` operator, `np.linalg` (`det`, `inv`, `solve`, `eig`), linear regression from scratch via the Normal Equation.

---

## Day 10 – Real-World NumPy & The Bridge to ML
- **Real-World NumPy** (`04_Numpy.ipynb`) — Loading and saving (`loadtxt`, `save`, `savez`), missing values (`np.nan`, `nanmean`), `datetime64`, `np.random.default_rng()`, performance tips.
- **NumPy as the ML Bridge** (`05_Numpy.ipynb`) — How pandas, scikit-learn, PyTorch, and TensorFlow all speak NumPy underneath; images as arrays.

---

## Day 11 – Introduction to Pandas
- **Pandas Foundations** (`01_Pandas.ipynb`) — Series and DataFrame, `read_csv`, inspection (`head`, `info`, `describe`), the Index object.
- **Selecting and Filtering** (`02_Pandas.ipynb`) — `.loc` vs `.iloc`, boolean masks with `&`/`|`/`~`, `.query()`, `isin()`, `between()`, `SettingWithCopyWarning`.
- **Cleaning and Transforming** (`03_Pandas.ipynb`) — Missing data (`isna`, `dropna`, `fillna`), `astype`, `rename`, `.apply()` vs `.map()`, vectorized strings, categorical dtype.

---

## Day 12 – Pandas Grouping, Joining, and Reshaping
- **Grouping and Joining** (`04_Pandas.ipynb`) — `groupby()` split-apply-combine, `.agg()`, named aggregations, `transform()`, `filter()`, `pivot_table`, `crosstab`, `melt`, `pivot`, SQL-style merges, `concat`.

---

## Day 13 – Pandas Time Series, Plotting, and Method Chaining
- **Time Series and Plotting** (`05_Pandas.ipynb`) — `DatetimeIndex` and date-string slicing, `.resample()`, rolling and expanding windows, plotting with `.plot()`, method chaining with `.assign()` and `.query()`, performance pitfalls of `iterrows()`.

---

## Day 14 – Matplotlib Foundations
- **Foundations** (`01_Matplotlib.ipynb`) — pyplot vs object-oriented API, the Figure/Axes model, `plt.subplots()` for grids, line/scatter/bar/histogram, titles, labels, legends, saving to PNG/PDF/SVG.

---

## Day 15 – Matplotlib Customization and Styling
- **Customization** (`03_Matplotlib.ipynb`) — Color formats (named, hex, RGB, cycle), colormaps (sequential / diverging / qualitative), tick formatters (`FuncFormatter`, `PercentFormatter`), log-scale axes, annotations (`ax.annotate`, `axvspan`, `axhline`), style sheets, fonts, removing chart junk.

---

## Day 16 – Matplotlib Core Plot Types
- **Core Plot Types** (`02_Matplotlib.ipynb`) — Line plots with full styling (color, linestyle, linewidth, markers), scatter plots with 4D encoding via size and color, bar charts (vertical, horizontal, grouped, stacked), histograms for single distributions, box and violin plots for comparing distributions across groups, pie charts (and the sorted-bar alternative), plus a reference table for picking the right plot type.

---

## Day 17 – Matplotlib Advanced and Real-World
- **Advanced and Real-World** (`04_Matplotlib.ipynb`) — Non-uniform layouts with `GridSpec`, twin y-axes (`ax.twinx()`) for two scales on one chart, heatmaps via `imshow` (activity, correlation, confusion matrices), publication-quality saves (`dpi=300`, `bbox_inches='tight'`, vector formats), seaborn as the higher-level layer for statistical plots, and a complete multi-panel revenue dashboard pulling everything together.

---

## Day 18 – Matplotlib Foundations Revisit
- Small tweaks to `01_Matplotlib.ipynb` and a closer look at `figsize`, `dpi`, `plt.tight_layout()`, and the matplotlib backend.

---

## References

**Day 1**
- [Python Programming Language](https://www.geeksforgeeks.org/python-programming-language/)
- [Python Data Types](https://www.geeksforgeeks.org/python-data-types/)
- [Python String](https://www.geeksforgeeks.org/python-string/)

**Day 2**
- [Python Operators](https://www.geeksforgeeks.org/python-operators/)
- [Python Lists](https://www.geeksforgeeks.org/python-lists/)

**Day 3**
- [Python Tuples](https://www.geeksforgeeks.org/python-tuples/)
- [Sets in Python](https://www.geeksforgeeks.org/sets-in-python/)
- [Python Dictionary](https://www.geeksforgeeks.org/python-dictionary/)

**Day 4**
- [Python If Else](https://www.geeksforgeeks.org/python-if-else/)
- [Loops in Python](https://www.geeksforgeeks.org/loops-in-python/)

**Day 5**
- [Python Functions](https://www.geeksforgeeks.org/python-functions/)
- [NumPy Array in Python](https://www.geeksforgeeks.org/numpy-array-in-python/)

**Day 6**
- [Read, Write and Parse JSON using Python](https://www.geeksforgeeks.org/read-write-and-parse-json-using-python/)
- [Python RegEx](https://www.geeksforgeeks.org/python-regex/)
- [Python Try Except](https://www.geeksforgeeks.org/python-try-except/)

**Day 7**
- [Python OOPs Concepts](https://www.geeksforgeeks.org/python-oops-concepts/)
- [Python Classes and Objects](https://www.geeksforgeeks.org/python-classes-and-objects/)
- [Inheritance in Python](https://www.geeksforgeeks.org/inheritance-in-python/)
- [Polymorphism in Python](https://www.geeksforgeeks.org/polymorphism-in-python/)
- [Encapsulation in Python](https://www.geeksforgeeks.org/encapsulation-in-python/)
- [File Handling in Python](https://www.geeksforgeeks.org/file-handling-python/)

**Day 8**
- [Introduction to NumPy](https://www.geeksforgeeks.org/introduction-to-numpy/)
- [Indexing in NumPy](https://www.geeksforgeeks.org/indexing-in-numpy/)
- [NumPy Array Slicing](https://www.geeksforgeeks.org/numpy-array-slicing/)
- [Broadcasting in NumPy](https://www.geeksforgeeks.org/python-broadcasting-with-numpy-arrays/)
- [Reshape NumPy Array](https://www.geeksforgeeks.org/reshape-numpy-array/)

**Day 9**
- [Universal Functions (ufuncs) in NumPy](https://www.geeksforgeeks.org/universal-functions-in-numpy/)
- [Statistical Functions in NumPy](https://www.geeksforgeeks.org/numpy-statistical-functions/)
- [NumPy Linear Algebra](https://www.geeksforgeeks.org/numpy-linear-algebra/)
- [Matrix Multiplication in NumPy](https://www.geeksforgeeks.org/numpy-matrix-multiplication-np-matmul/)
- [Eigenvalues and Eigenvectors in NumPy](https://www.geeksforgeeks.org/python-numpy-linalg-eig-method/)

**Day 10**
- [Read CSV files into NumPy arrays](https://www.geeksforgeeks.org/read-csv-files-using-numpy-genfromtxt/)
- [Save and Load NumPy Arrays](https://www.geeksforgeeks.org/save-and-load-numpy-array-using-the-npy-extension/)
- [Handling Missing Values in NumPy](https://www.geeksforgeeks.org/how-to-remove-nan-values-from-a-given-numpy-array/)
- [datetime64 in NumPy](https://www.geeksforgeeks.org/numpy-datetime64-method/)
- [Random Numbers in NumPy](https://www.geeksforgeeks.org/random-sampling-in-numpy-random-method/)

**Day 11**
- [Introduction to Pandas](https://www.geeksforgeeks.org/introduction-to-pandas-in-python/)
- [Pandas Series](https://www.geeksforgeeks.org/python-pandas-series/)
- [Pandas DataFrame](https://www.geeksforgeeks.org/python-pandas-dataframe/)
- [.loc and .iloc in Pandas](https://www.geeksforgeeks.org/python-pandas-dataframe-loc/)
- [Boolean Indexing in Pandas](https://www.geeksforgeeks.org/boolean-indexing-in-pandas/)
- [Handling Missing Data in Pandas](https://www.geeksforgeeks.org/working-with-missing-data-in-pandas/)

**Day 12**
- [Pandas groupby](https://www.geeksforgeeks.org/python-pandas-dataframe-groupby/)
- [Aggregation in Pandas](https://www.geeksforgeeks.org/aggregation-in-pandas/)
- [Pandas pivot_table](https://www.geeksforgeeks.org/python-pandas-pivot_table/)
- [Pandas melt](https://www.geeksforgeeks.org/python-pandas-melt/)
- [Pandas merge](https://www.geeksforgeeks.org/python-pandas-merging-joining-and-concatenating/)
- [Pandas concat](https://www.geeksforgeeks.org/python-pandas-concat/)

**Day 13**
- [Pandas Time Series / Date Functionality](https://www.geeksforgeeks.org/python-pandas-time-series/)
- [Pandas resample](https://www.geeksforgeeks.org/python-pandas-dataframe-resample/)
- [Pandas rolling window](https://www.geeksforgeeks.org/python-pandas-dataframe-rolling/)
- [Pandas plotting](https://www.geeksforgeeks.org/data-visualization-with-pandas/)
- [Method chaining in pandas](https://www.geeksforgeeks.org/method-chaining-in-pandas/)

**Day 14**
- [Introduction to Matplotlib](https://www.geeksforgeeks.org/python-introduction-matplotlib/)
- [Pyplot in Matplotlib](https://www.geeksforgeeks.org/pyplot-in-matplotlib/)
- [Multiple plots with `plt.subplots()`](https://www.geeksforgeeks.org/matplotlib-pyplot-subplots-in-python/)
- [Matplotlib Bar Chart](https://www.geeksforgeeks.org/bar-plot-in-matplotlib/)
- [Saving a Matplotlib Figure](https://www.geeksforgeeks.org/matplotlib-pyplot-savefig-in-python/)

**Day 15**
- [Matplotlib Colors](https://www.geeksforgeeks.org/matplotlib-pyplot-colors-in-python/)
- [Choosing Colormaps in Matplotlib](https://www.geeksforgeeks.org/choosing-colormaps-in-matplotlib/)
- [Matplotlib Tick Labels](https://www.geeksforgeeks.org/matplotlib-pyplot-xticks-in-python/)
- [Matplotlib Annotations](https://www.geeksforgeeks.org/matplotlib-pyplot-annotate-in-python/)
- [Matplotlib Style Sheets](https://www.geeksforgeeks.org/style-plots-using-matplotlib/)

**Day 16**
- [Line Chart in Matplotlib](https://www.geeksforgeeks.org/line-chart-in-matplotlib-python/)
- [Matplotlib Scatter Plot](https://www.geeksforgeeks.org/matplotlib-pyplot-scatter-in-python/)
- [Grouped Bar Chart in Matplotlib](https://www.geeksforgeeks.org/create-a-grouped-bar-plot-in-matplotlib/)
- [Stacked Bar Chart in Matplotlib](https://www.geeksforgeeks.org/stacked-bar-chart-with-matplotlib/)
- [Matplotlib Histogram](https://www.geeksforgeeks.org/plotting-histogram-in-python-using-matplotlib/)
- [Box Plot in Matplotlib](https://www.geeksforgeeks.org/box-plot-in-python-using-matplotlib/)
- [Violin Plot in Matplotlib](https://www.geeksforgeeks.org/violin-plot-using-matplotlib/)

**Day 17**
- [GridSpec in Matplotlib](https://www.geeksforgeeks.org/how-to-create-different-subplot-sizes-in-matplotlib/)
- [Twin Axes in Matplotlib](https://www.geeksforgeeks.org/plot-multiple-plots-in-matplotlib/)
- [Heatmap in Matplotlib](https://www.geeksforgeeks.org/how-to-plot-a-heatmap-in-python/)
- [Confusion Matrix Visualization](https://www.geeksforgeeks.org/confusion-matrix-machine-learning/)
- [seaborn Tutorial](https://www.geeksforgeeks.org/python-seaborn-tutorial/)
- [Saving Publication-Quality Figures](https://www.geeksforgeeks.org/matplotlib-pyplot-savefig-in-python/)

---

##  How to Use This Repository

1. **Clone the repository:**
   ```bash
   git clone https://github.com/AyeshaAfridi26/100-Days-of-AI.git
   cd 100-Days-of-AI
   ```

2. **Set up virtual environment (recommended):**
   ```bash
   python -m venv env
   source env/bin/activate  # On Windows: env\Scripts\activate
   ```

3. **Explore the notebooks:**
   ```bash
   jupyter notebook
   ```

4. **Follow along with the daily lessons and exercises**

---

## Goals for the 100 Days

- **Week 1-2:** Python fundamentals and core concepts
- **Week 3-4:**  Introduction to Data Science (NumPy, Pandas)
- **Week 5-8:**  Data structures and algorithms
- **Week 9-12:** Machine Learning basics (Scikit-learn)
- **Week 13-16:** Deep Learning fundamentals
- **Week 17+:** Advanced projects and specializations


---

##  Connect

- **GitHub:** [@AyeshaAfridi26](https://github.com/AyeshaAfridi26)
- **linkedin:** www.linkedin.com/in/ayesha-k-a8b827307

---

## License

This repository is open for educational purposes. Feel free to learn and share!

---

**Remember:** Consistency is key. Every day of learning brings you closer to mastering AI! 

May 24, 2026 | Day 1 DONE
May 25, 2026 | Day 2 DONE
May 26 2026  | Day 3 DONE
May 27, 2026 | Day 4 DONE
May 28, 2026 | Day 5 DONE
May 29, 2026 | Day 6 DONE
May 30, 2026 | Day 7 DONE
May 31, 2026 | Day 8 DONE
June 1, 2026  | Day 9 DONE
June 2, 2026  | Day 10 DONE
June 3, 2026  | Day 11 DONE
June 4, 2026  | Day 12 DONE
June 5, 2026  | Day 13 DONE
June 6, 2026  | Day 14 DONE
June 7, 2026  | Day 15 DONE
June 8, 2026  | Day 16 DONE
June 9, 2026  | Day 17 DONE
June 10, 2026 | Day 18 DONE
