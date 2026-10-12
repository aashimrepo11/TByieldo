TByieldo is a web front end for a machine learning project in the energy sector. The project builds regression models that estimate gas turbine energy output (in MW) and evaluates them with sound methodology. The site lets anyone try the predictor without any technical background.
https://tbyieldo.vercel.app/

Features
Friendly first-time tour: a short welcome that explains the site in very simple words.
3D wind turbine hero: a three.js scene that reacts to your mouse and spins faster when predicted output is higher.
Interactive predictor: sliders for each input with an instant result, gauge and trend chart.
Live mode: simulated sensor readings stream in so you can watch predictions change.
Need help section: plain-English glossary (RMSE, MAE, R², ensemble learning, overfitting and more).
Responsive and accessible: works on phones, supports light/dark theme, keyboard focus and reduced motion.
Inputs and output
Input	Meaning	Range in demo
Air temperature	Outside air temperature	2 to 37 °C
Exhaust vacuum	Suction pulling steam out of the turbine	25 to 82 cm Hg
Air pressure	Atmospheric pressure	993 to 1033 mbar
Humidity	Relative humidity	26 to 100 %

Output: estimated net electrical power in MW.

Machine learning approach
Regression modelling: predicting continuous turbine output.
Feature engineering: selecting and preparing relevant inputs with a disciplined data-prep process.
Model evaluation: established regression metrics (RMSE, MAE, R²).
Model optimisation: ensemble learning to improve predictive capability.
Reliability: validation, error analysis and ongoing performance monitoring.
