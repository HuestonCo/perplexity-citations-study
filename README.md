# Perplexity Domain Authority Mapping 
## For Fun and Profit

![Status](https://img.shields.io/badge/Research-August%202025-blue)
![Citations](https://img.shields.io/badge/Citations%20Analyzed-23%2C936-green)
![Domains](https://img.shields.io/badge/Domains%20Studied-6%2C606-orange)
![License](https://img.shields.io/badge/License-MIT-yellow)

## Overview

This repository contains the complete dataset and analysis from our comprehensive study of AI search citation patterns in Perplexity. We analyzed 23,936 citations across 6,606 domains to understand how AI search engines determine authority and select sources.

## 📊 Key Findings

- **YouTube dominates** with 3.3x more citations than any other domain
- **Citation positions are evenly distributed** (20% each) unlike traditional SEO
- **25 domains** achieved perfect cross-vertical presence
- **$0.0054** average cost per query with 100% success rate

## 📖 Read the Full Analysis

**[The Day We Discovered AI Search Doesn't Care About Your #1 Rankings →](https://github.com/HuestonCo/perplexity-citations-study/blob/main/authority-mapping.md)**

## 📁 Repository Structure

```

├── /data/             # Raw and processed datasets

```

## 🚀 Quick Start

### Access the Data

1. **Download the complete dataset**: [data/processed/](data/)
2. **Read the full analysis**: [authority-mapping.md)

### Key Datasets

- `top_domains_authority.csv` - Top 50 domains by authority score
- `citation_patterns.csv` - Citation patterns by vertical and query type
- `cross_vertical_analysis.csv` - Cross-vertical authority analysis
- `cost_efficiency_metrics.csv` - Query cost and efficiency data

## 📈 Key Statistics

| Metric | Value |
|--------|-------|
| Total Domains Analyzed | 6,606 |
| Total Citations | 23,936 |
| Total Queries | 4,835 |
| Verticals Covered | 23 |
| Query Success Rate | 100% |
| Total Cost | $26.09 |

## 🔍 Main Insights

1. **Cross-vertical presence = Higher authority** (correlation: 0.381)
2. **First position citations** strongest predictor of authority
3. **Query complexity** has minimal impact on cost ($0.0054 avg)
4. **Direct quotes** represent only 5% of citations

## 💻 Usage

```python
import pandas as pd

# Load the authority scores
authority_df = pd.read_csv('data/processed/top_domains_authority.csv')

# View top 10 domains
print(authority_df.head(10))
```



## 📄 License

This project is licensed under the MIT License - see [LICENSE.md](LICENSE.md) for details.

## 📧 Contact

- **Email**: hello@hueston.co
- **LinkedIn**: [Jeremy Meindl](https://www.linkedin.com/in/jeremymeindl)

## 🙏 Acknowledgments

Lahina Strong! 

---

**Keywords**: `AI search` `Perplexity` `SEO research` `citation analysis` `authority scoring`
