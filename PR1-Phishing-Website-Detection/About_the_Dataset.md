# About the Dataset
Comprehensive phishing detection datasets collection featuring diverse URL analysis approaches for cybersecurity machine learning research

## Dataset Overview
This collection contains 6 phishing detection datasets with different feature extraction approaches and varying complexity levels, suitable for comparative machine learning research in cybersecurity.

## Dataset Descriptions

### Dataset 1: Traditional Phishing Indicators
- Focus: Classic web security features
- Features: IP addresses, URL length, SSL state, redirects
- Target: Binary classification (-1: legitimate, 1: phishing)
- Balance: Slightly imbalanced (0.796 ratio)

### Dataset 2: Detailed URL Parsing
- Focus: Comprehensive URL component analysis
- Features: Character counts, domain analysis, redirects, certificates
- Target: Binary classification (0: legitimate, 1: phishing)
- Notable: Largest feature set (112 features)

### Dataset 3: Web Analysis Features

- Focus: Website content and structure analysis
- Features: HTML elements, JavaScript, external resources
- Target: Multi-class (legitimate/phishing status)
- Notable: Includes web traffic and domain age features

### Dataset 4: Large-Scale Engineering
- Focus: Scalable feature extraction for production
- Features: Optimized set for large-scale deployment
- Target: Binary classification (0: legitimate, 1: phishing)
- Notable: Largest sample size (235K+ samples)

### Dataset 5: [Requires Preprocessing]
- Status: Contains formatting issues (line 18259+)
- Action Required: Use clean_csv_file() function to fix
- Expected: Similar phishing detection structure

### Dataset 6: Balanced Research Set
- Focus: Perfectly balanced dataset for fair evaluation
- Features: URL structure, form analysis, redirect patterns
- Target: Binary classification (0: legitimate, 1: phishing)
- Notable: Perfect class balance (50/50 split)