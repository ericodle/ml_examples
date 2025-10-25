# ML Examples - Machine Learning Educational Notebooks

A collection of interactive Jupyter notebooks designed to teach machine learning concepts through hands-on examples and visualizations.

## 📚 Available Notebooks

### 1. Support Vector Machines (SVM) - Complete Guide
**File:** `01_support_vector_machines.ipynb`

A comprehensive tutorial covering:
- SVM theory and mathematical foundations
- Visual demonstrations of support vectors and margins
- All major kernel types (Linear, Polynomial, RBF, Sigmoid)
- Practical examples with real datasets
- Performance comparisons and best practices

### 2. K-Nearest Neighbors (KNN) - Complete Guide
**File:** `02_k_nearest_neighbors.ipynb`

An in-depth exploration covering:
- KNN theory and lazy learning concepts
- Distance metrics (Euclidean, Manhattan, Chebyshev)
- Visual demonstrations of decision boundaries
- Hyperparameter tuning and performance analysis
- Practical examples with real datasets

### 3. Random Forest - Complete Guide
**File:** `03_random_forest.ipynb`

A comprehensive guide covering:
- Decision Trees as building blocks
- Ensemble learning and Bootstrap Aggregating
- Feature importance and selection
- Hyperparameter tuning
- Performance comparisons with single Decision Trees

### 4. Decision Trees - Complete Guide
**File:** `04_decision_trees.ipynb`

A detailed tutorial covering:
- Decision Tree theory and algorithms
- Splitting criteria (Gini, Entropy, MSE)
- Visual demonstrations and tree structure
- Hyperparameter tuning and overfitting
- Feature importance analysis
- Comparison with Random Forest

### 5. Dimensionality Reduction - PCA and t-SNE
**File:** `05_dimensionality_reduction.ipynb`

A comprehensive guide covering:
- PCA theory and mathematical foundations
- t-SNE for non-linear dimensionality reduction
- Visual demonstrations with real datasets
- Parameter tuning and best practices
- Feature engineering applications
- Performance comparisons and use cases

## 🚀 Getting Started

### Prerequisites
- Python 3.8+ (Python 3.13 recommended)
- Virtual environment support

### Installation

1. **Clone or download this repository**
   ```bash
   git clone <your-repo-url>
   cd ml_examples
   ```

2. **Create and activate a virtual environment**
   ```bash
   python -m venv env
   source env/bin/activate  # On Windows: env\Scripts\activate
   ```

3. **Install dependencies**
   ```bash
   pip install -r requirements.txt
   ```

### Running Jupyter Notebooks

#### Method 1: Jupyter Notebook (Classic Interface)
```bash
# Activate your virtual environment
source env/bin/activate

# Start Jupyter Notebook
jupyter notebook --ip=0.0.0.0 --port=8888 --no-browser --allow-root
```

#### Method 2: JupyterLab (Modern Interface)
```bash
# Activate your virtual environment
source env/bin/activate

# Start JupyterLab
jupyter lab --ip=0.0.0.0 --port=8888 --no-browser --allow-root
```

### Accessing the Notebooks

1. **Open your web browser**
2. **Navigate to one of these URLs:**
   - `http://localhost:8888` (if running locally)
   - `http://127.0.0.1:8888` (alternative local address)
   - The URL with token shown in your terminal output

3. **Find your notebook** in the file browser and click to open it

## 📖 How to Use the Notebooks

### Running Cells
- **Single cell:** Press `Shift + Enter`
- **All cells:** Go to `Cell` → `Run All`
- **Cell by cell:** Use `Shift + Enter` to run and move to next cell

### Navigation
- **Table of Contents:** Use the navigation links in each notebook
- **Sections:** Each notebook is organized into clear sections
- **Code and Theory:** Mix of explanatory text and executable code

### Interactive Learning
- **Experiment:** Try changing parameters and see what happens
- **Visualizations:** Each concept includes interactive plots
- **Real Data:** Work with actual datasets (Iris, synthetic data)

## 🛠️ Troubleshooting

### Common Issues

**Port already in use:**
```bash
# Try a different port
jupyter notebook --port=8889
```

**Permission denied:**
```bash
# Add --allow-root flag
jupyter notebook --allow-root
```

**Missing dependencies:**
```bash
# Reinstall requirements
pip install -r requirements.txt --force-reinstall
```

**Browser doesn't open automatically:**
- Copy the URL from the terminal output
- Paste it into your browser manually

### Stopping Jupyter
- Press `Ctrl + C` twice in the terminal
- Or close the terminal window

## 📦 Dependencies

The project includes these key libraries:
- **Core ML:** scikit-learn, numpy, pandas
- **Visualization:** matplotlib, seaborn
- **Jupyter:** jupyter, jupyterlab
- **Deep Learning:** torch, torchvision (for future notebooks)
- **Data Processing:** scipy, scikit-learn

See `requirements.txt` for the complete list with versions.

## 🎯 Learning Path

### For Beginners
1. Start with the SVM notebook
2. Run cells step by step
3. Read the theory sections carefully
4. Experiment with different parameters

### For Intermediate Users
1. Focus on the practical examples
2. Try implementing your own variations
3. Compare different algorithms
4. Apply to your own datasets

### For Advanced Users
1. Use as reference material
2. Modify code for your specific needs
3. Contribute additional examples
4. Create your own educational notebooks

## 🔧 Customization

### Adding New Notebooks
1. Create a new `.ipynb` file
2. Follow the naming convention: `XX_topic_name.ipynb`
3. Include a table of contents
4. Add clear explanations and visualizations

### Modifying Existing Notebooks
- All notebooks are designed to be educational
- Feel free to experiment and modify
- Save your changes if you want to keep them

## 📝 Contributing

This is an educational repository! Contributions are welcome:
- New machine learning concepts
- Better visualizations
- Additional datasets
- Improved explanations
- Bug fixes

## 🆘 Support

If you encounter issues:
1. Check the troubleshooting section above
2. Ensure all dependencies are installed
3. Try restarting Jupyter
4. Check that your virtual environment is activated

## 📄 License

This project is for educational purposes. Feel free to use, modify, and share!

---

**Happy Learning! 🎓📊**

Start with the SVM notebook to understand one of the most powerful machine learning algorithms through interactive examples and beautiful visualizations.
