Exoplanet Detection using Light Curve Analysis

An end-to-end Machine Learning pipeline utilizing LightGBM and PyTorch to classify astrophysical signals and detect exoplanet transits from TESS light curve data.

 Features-
- Data Processing: Automated pipeline for loading and cleaning TESS light curve data.
- Feature Engineering: Extraction of statistical properties, autocorrelation periods, and transit dip metrics.
- Signal Classification: Machine learning models trained to differentiate between False Positives, Eclipsing Binaries, and true Exoplanet Transits.
- Parameter Estimation: Trapezoidal transit model curve fitting to estimate orbital periods, transit depths, and durations.

Tech Stack-
- Languages & Frameworks: Python, PyTorch, LightGBM
- Libraries: Lightkurve, SciPy, Scikit-Learn, Pandas, Matplotlib
