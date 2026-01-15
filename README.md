# Mathematical Foundations Learning Portfolio

**Repository**: `melaniagr/math_porfolio_`  
**Status**: In progress (January 15, 2026)  
**Total courses**: 3 parallel mathematics courses  
**Total hours invested**: ~80 hours (with ~170 hours more planned)  

---

## Overview

Computational psychiatry requires rigorous mathematical foundations. Rather than treating mathematics as a prerequisite to tackle during a PhD, I'm systematically building these skills now through three parallel university-level courses.

### Current Progress

| Course | Institution | Status | Timeline | Relevance |
|--------|-----------|--------|----------|-----------|
| **Calculus 1A: Differentiation** | MIT (MITx 18.01.1x) | 58% complete | Finish Jan 30, 2026 | Rates of change in neural dynamics, optimization, drug kinetics |
| **Pre-University Calculus** | Delft University (Calc001x) | Exam Jan 22 | Complete May 27, 2026 | Foundations: functions, polynomials, exponentials, trigonometry |
| **Mathematics for Machine Learning** | Imperial College (Coursera) | 32% complete | Finish June 2026 | Linear algebra, multivariate calculus, dimensionality reduction (PCA) |

**Total planned**: 250+ hours of rigorous mathematical training

---

## Why This Matters

### For Computational Psychiatry / Neuroscience

- **Calculus**: Understanding rates of change in neural adaptation, drug metabolism, synaptic plasticity
- **Linear algebra**: Neural connectivity matrices, dimensionality reduction of neuroimaging data, ML model construction
- **Optimization**: Fitting computational models to behavioral data, algorithm training, parameter estimation
- **Dynamical systems**: Understanding how neural circuits evolve over time

## Repository Structure

```
├── README.md (THIS FILE)
│
├── 01_MIT_Calculus_1A_Differentiation/
│   ├── course_overview.md
│   ├── progress_tracker.md (current: 58% complete)
│   ├── 01_limits_and_continuity.md
│   ├── 02_derivatives_introduction.md
│   ├── 03_power_rule.md
│   ├── 04_chain_rule.md
│   ├── 05_trigonometric_derivatives.md
│   ├── 06_exponential_logarithmic_derivatives.md
│   ├── 07_applications_derivatives.md
│   ├── problem_sets/
│   │   ├── ps1_limits_solutions.md
│   │   ├── ps2_derivatives_intro_solutions.md
│   │   ├── ps3_derivative_rules_solutions.md
│   │   ├── ps4_chain_rule_solutions.md
│   │   ├── ps5_special_functions_solutions.md
│   │   └── practice_exam_questions.md
│   ├── progress_screenshots/
│   │   └── 58_percent_completion.png
│   ├── psychiatric_connections.md
│   ├── reflection.md
│   └── certificate_pending.pdf
│
├── 02_DeltfX_PreCalculus/
│   ├── course_overview.md
│   ├── exam_information.md (Exam: Jan 22, 2026)
│   ├── 01_functions_basics.md
│   ├── 02_polynomial_functions.md
│   ├── 03_rational_functions.md
│   ├── 04_exponential_logarithmic.md
│   ├── 05_trigonometric_functions.md
│   ├── exam_prep/
│   │   ├── study_guide.md
│   │   ├── practice_problems.md
│   │   └── common_mistakes.md
│   ├── psychiatric_connections.md
│   ├── preparation_status.md (85% ready)
│   └── certificate_pending.pdf
│
├── 03_Imperial_ML_Mathematics/
│   ├── course_overview.md
│   ├── progress_tracker.md (32% complete)
│   ├── 01_Linear_Algebra/
│   │   ├── 01_vectors_and_matrices.md
│   │   ├── 02_matrix_operations.md
│   │   ├── 03_eigenvalues_eigenvectors.md
│   │   ├── 04_matrix_decomposition.md
│   │   ├── 05_applications_linear_algebra.md
│   │   ├── problem_sets_solutions.md
│   │   └── psychiatric_connections.md
│   ├── 02_Multivariate_Calculus/ (TBD)
│   │   ├── gradients_and_optimization.md
│   │   └── [more coming]
│   ├── 03_PCA/ (TBD)
│   │   ├── dimensionality_reduction.md
│   │   └── [more coming]
│   └── certificate_pending.pdf
│
├── cross_course_connections/
│   ├── math_for_computational_psychiatry.md
│   │   "How calculus, linear algebra, and optimization connect to modeling"
│   ├── neural_dynamics_mathematics.md
│   │   "How differential equations describe neural evolution"
│   ├── ml_mathematics_foundations.md
│   │   "Mathematical foundations of machine learning"
│   └── computational_model_building.md
│       "From theory to implementation: using math to build models"
│
└── resources/
    ├── formula_reference.md (one-page summary)
    ├── glossary.md (mathematical terms)
    ├── recommended_textbooks.md
    ├── supplementary_videos.md
    └── problem_solving_strategies.md
```

---

## Key Concepts by Course

### MIT Calculus 1A: Differentiation
**What it covers**: Limits, derivatives, differentiation rules, applications

**Core skills**:
- ✅ Understanding limits formally and intuitively
- ✅ Computing derivatives using multiple methods
- ✅ Chain rule (most important!)
- ✅ Optimization and applications
- ✅ Implicit differentiation
- ✅ Trigonometric, exponential, logarithmic functions

**Psychiatric / neuroscience relevance**:
- How quickly does drug concentration change? (derivatives)
- Where is maximum neuronal firing rate? (optimization)
- How fast does a neural adaptation process? (rates of change)

### DeltfX Pre-University Calculus
**What it covers**: Functions, polynomials, rational functions, exponentials, trigonometry

**Core skills**:
- ✅ Function basics (domain, range, transformations)
- ✅ Solving polynomial and rational equations
- ✅ Understanding exponential/logarithmic growth and decay
- ✅ Trigonometric identities and applications

**Psychiatric / neuroscience relevance**:
- Exponential decay models drug elimination
- Polynomial functions model dose-response curves
- Trigonometric functions model circadian rhythms, neural oscillations

### Imperial College Mathematics for ML
**What it covers**: Linear algebra, multivariate calculus, PCA

**Core skills**:
- ✅ Vector and matrix operations
- ✅ Eigenvalues and eigenvectors
- ✅ Matrix decomposition (SVD, QR)
- ✅ Gradients and optimization
- ✅ Dimensionality reduction (PCA)

**Psychiatric / neuroscience relevance**:
- Neural activity represented as vectors in high-dimensional space
- Eigenvectors reveal principal modes of brain activity
- PCA reduces neuroimaging data to interpretable dimensions
- Optimization trains ML models on behavioral data

---

## Psychiatric / neuroscience Connections

### 1. Neural Adaptation
Many neural systems show exponential adaptation:
```
Response(t) = R_max × (1 - e^(-t/τ))

Where τ = time constant of adaptation

As t → ∞, Response → R_max (complete adaptation)
τ determines adaptation speed

Psychiatric relevance: Different disorders show different adaptation rates
- Depression: Slow adaptation to positive stimuli (anhedonia)
- ADHD: Fast adaptation (novelty-seeking)
```

### 2. Dose-Response Curves
Often modeled as Hill equation (polynomial/rational function):
```
Response = E_max × [Dose]^n / (EC50^n + [Dose]^n)

Optimization: Finding optimal dose that maximizes benefit, minimizes side effects
```

### 3. Neural Oscillations
```
Neural activity = A × sin(2πft + φ)

Where:
- A = amplitude (strength)
- f = frequency (cycles/second)
- φ = phase (timing)

Different frequencies reflect different brain states:
- δ (0.5-4 Hz): Deep sleep
- θ (4-8 Hz): Memory/attention
- α (8-12 Hz): Relaxed wakefulness
- β (12-30 Hz): Active cognition
- γ (30-100 Hz): Attention, binding

Psychiatric disorders show abnormal oscillations
Mathematics lets us characterize and quantify these
```

---

## Timeline & Milestones

### January 2026
- **Jan 22**: full portfolio update
- **Jan 22**: DeltfX exam (target: pass)
- **Jan 30**: MIT calculus 1A completion and portfolio update
- **Feb**: finish "Math for ML"
- **Action**: Finish courses, upload files, update porfolio

### February-March 2026
- 

### April-May 2026
- 

### June 2026
- 

---

## How This Integrates with Other Portfolios

### With Neuroscience Portfolio
- **Hodgkin-Huxley model**: Uses differential equations (calculus) to model action potentials
- **Neural dynamics**: Differential equations describe how neural circuits evolve
- **Synaptic plasticity**: Exponential functions model short-term/long-term changes

### With Innovation/Digital Health Portfolio
- **ML implementation**: Linear algebra and optimization train neural networks
- **Data analysis**: Multivariate calculus enables gradient descent
- **Statistical modeling**: Calculus underpins probability and statistics

### With Research Training Portfolio
- **Study design**: Understanding rates (incidence, prevalence) requires calculus concepts
- **Data analysis**: Statistical tests often rest on mathematical foundations

### With QI Portfolio
- **Trend analysis**: Derivatives describe rate of change in audit metrics
- **Forecasting**: Exponential models predict future performance

### With Programming Portfolio
- 
---

## Learning Outcomes

By completing this portfolio, I will be able to:

✅ Understand and apply calculus to model changing systems  
✅ Use linear algebra to analyze high-dimensional data  
✅ Implement dimensionality reduction (PCA)  
✅ Construct mathematical models of biological systems  
✅ Solve optimization problems (fitting models, training algorithms)  
✅ Interpret computational results with mathematical confidence  
✅ Explain mathematics to non-mathematician colleagues (clinicians)  


## Resources

- **MIT OpenCourseWare**: Free calculus lectures
- **3Blue1Brown**: Excellent visual explanations of calculus and linear algebra
- **Khan Academy**: Supplementary problems and explanations
- **Stewart's Calculus**: Comprehensive textbook (reference)
- **Linear Algebra and Its Applications (Strang)**: Linear algebra deep dive
- **Linear Algebra and Its Applications (Strang)** 

---

**Status**: Portfolio ongoing, updated with course progress  
**Last updated**: January 15, 2026  
**Next update**: January 30, 2026 
