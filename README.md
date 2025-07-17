# 📊 Multivariate Visualization and Network Analysis – Glass & Board Games

This project showcases two interactive data visualization modules applied to real-world datasets (Glass composition & BoardGame metadata). It explores different visualization paradigms for multivariate and network data using Python, R, D3.js, and Gephi.

---

## 🧪 A2: Glass Composition Analysis

### 🔧 Tools & Libraries
- D3.js (parallel coordinates plot)
- R + Plotly (MDS dimensionality reduction)

### 📈 Visualizations
1. **Parallel Coordinates**  
   - Displays 9-element oxide composition across 6 glass types  
   - Interactive filtering with rectangular brushing  
   - Z-score normalization & path simplification  

2. **MDS Scatter Plot**  
   - 2D mapping of material similarity via multidimensional scaling  
   - Color-coded clusters show glass type proximity and anomalies  

### 🔍 Key Findings
- Si is dominant in all types, validating Shakhgildyan et al.'s oxide glass claims.  
- Ca, Al, Na, and Ba show strong type-specific variation.  
- MDS helps identify overlapping categories and potential misclassifications.

---

## 🎲 B1: Board Game Network Analysis

### 🔧 Tools & Libraries
- Python (NetworkX, Matplotlib)
- Gephi (Yifan Hu layout, Louvain community detection)

### 📈 Visualizations
1. **Top-150 BoardGames (NetworkX)**  
   - Colored by dominant category combinations  
   - Node size = game popularity or centrality  
   - Reveals interconnected and isolated niche games

2. **Subgraph: Fantasy vs. Fighting**  
   - Graph filter on thematic categories  
   - Explores how community structures shift based on genre constraints  

3. **Gephi Layout**  
   - Uses force-directed layout with modularity clustering  
   - Highlights organic community formation and structural outliers  

---

## 📚 References
- Shakhgildyan et al. (2020), *Glass: Home of the Periodic Table*, [Frontiers in Chemistry](https://doi.org/10.3389/fchem.2020.00384)

---

## 🧠 Author
**Zhenyu Wang**  
Assignment for COMP5048 – Data Visualization  
University of Adelaide  
