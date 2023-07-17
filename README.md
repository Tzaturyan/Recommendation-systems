# Recommendation-systems
# 1. Metrics
# 2. Baselines and deterministic item-item algorithms
# 3. Collaborative filtering
# 4. Content-based recommendation systems
# 5. Search for similar products and users. Hybrid recommendation systems
# 6. Two-level recommendation models
# Task
# Build a recommendation recommendation system.
# Target metric - precision@5. Threshold for successful completion of the precision project@5 > 25%
# There will be a public test dataset where you can measure the metric
# There will also be a private test dataset to measure the final quality
# It is NOT necessary, but it is highly desirable to use 2-level recommendation systems in the project
# You submit the project code in the form of a github repository and a csv file with recommendations
# rec_sys_course_project - model c CatBoostClassifier
# rec_sys_course_project_class - lightautoml model - approached prediction as a classification problem
# rec_sys_course_project_reg - lightautoml model - approached prediction as a regression problem

# Model	              precision@5 - train	   precision@5 -test
# CatBoostClassifier	        0.398	                 0.29
# lightautoml (классификация)	0.314	                 0.273
# lightautoml (регрессия)	    0.314	                 0.268
