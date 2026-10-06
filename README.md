# Data-Driven Decisions | Applied Data Science Projects

A portfolio of three comprehensive, team-based data science projects developed as part of the **Data-Driven Decisions in Practice** course.

The projects use **real-world datasets and business cases** to translate data into actionable decisions through predictive modeling, machine learning, optimization, geospatial analytics, and simulation.

## Projects

### 1. CashLog — Predictive Analytics & Robust Network Optimization

A strategic cash-logistics network design project combining transportation cost modeling with facility-location optimization and scenario-based robustness analysis.

**Key components:**
- Developed and compared multiple transportation cost models using regional demand, productivity, and travel-time data
- Built a shift-based predictive cost model achieving approximately **R² = 0.81**
- Integrated estimated transportation costs into a facility-location optimization model
- Evaluated network performance against benchmark costs and achieved **98.6% assignment agreement**
- Conducted sensitivity analyses for declining cash demand and wage/fuel cost inflation
- Evaluated alternative delivery technologies and their impact on network design
- Performed multi-scenario robustness analysis to identify strategically resilient cash-center locations

**Methods:** Predictive Modeling · Regression · Facility Location · Optimization · Sensitivity Analysis · Scenario Analysis · Robust Decision-Making

---

### 2. Revenue Management — Dynamic Demand & Adaptive Capacity Optimization

A hotel revenue-management project using historical booking data to design data-driven pricing, capacity, and overbooking policies under uncertain and seasonal demand.

**Key components:**
- Analyzed booking behavior, lead times, pricing patterns, and customer segments
- Developed property-specific advance-sale and capacity-protection policies
- Derived probabilistic overbooking buffers based on cancellation behavior and walk-away risk
- Modeled seasonal demand patterns and dynamically adjusted decision rules across demand periods
- Built a booking-level cancellation-risk model to estimate expected occupancy
- Implemented an adaptive booking-control strategy that dynamically updates capacity decisions as bookings arrive
- Compared the adaptive strategy against a static baseline using simulated booking streams
- Achieved approximately **9.7% higher realized revenue** in the evaluated simulation while improving inventory utilization

**Methods:** Revenue Management · Dynamic Demand Analysis · Probabilistic Modeling · Customer Segmentation · Overbooking Optimization · Adaptive Control · Simulation

---

### 3. Urban Analytics — Geospatial Machine Learning for Airbnb Pricing

A spatial data science project analyzing **6,110 Airbnb listings in San Diego** to understand and predict accommodation prices using property characteristics and location-based information.

**Key components:**
- Conducted exploratory and spatial analysis of Airbnb listings
- Engineered geospatial features using KDE-based density measures for nearby amenities and infrastructure
- Combined traditional property attributes with spatial information for price prediction
- Developed and compared Linear Regression, Decision Tree, and Random Forest models
- Performed hyperparameter tuning and feature-importance analysis
- Evaluated the predictive contribution of geospatial features
- Identified Random Forest as the strongest model, demonstrating the value of nonlinear and spatial relationships in urban pricing

**Methods:** Geospatial Analytics · Machine Learning · Feature Engineering · KDE · Random Forest · Decision Trees · Regression · Model Evaluation

---

## Technical Stack

**Languages & Libraries:** Python · Pandas · NumPy · scikit-learn · GeoPandas · Matplotlib

**Data Science:** Machine Learning · Predictive Modeling · Feature Engineering · Regression · Model Evaluation

**Decision Analytics:** Optimization · Revenue Management · Simulation · Sensitivity Analysis · Scenario & Robustness Analysis

**Spatial Analytics:** Geospatial Data Processing · Spatial Feature Engineering · Kernel Density Estimation (KDE)

## Project Context

These projects were completed collaboratively as university group projects. Each case required translating a real-world business problem into a quantitative decision framework, developing and evaluating analytical models, and communicating the resulting managerial recommendations.

The notebooks retain the original group-member attribution.
