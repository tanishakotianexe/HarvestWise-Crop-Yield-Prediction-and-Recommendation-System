# HarvestWise-Crop-Yield-Prediction-and-Recommendation-System
HarvestWise is an AI-powered web app that helps Maharashtra farmers with crop yield prediction, crop recommendations, rainfall forecasting, and fertilizer guidance. It combines 20+ years of historical data with real-time weather inputs to support efficient and sustainable farming decisions.

HarvestWise is a smart, AI-powered web application developed to assist farmers in Maharashtra by providing accurate predictions and recommendations for efficient and sustainable farming. The platform addresses common agricultural challenges such as unpredictable weather, inconsistent yields, and inefficient resource usage by combining historical data with real-time weather inputs.

Built using FastAPI for backend logic, and leveraging machine learning frameworks like scikit-learn and PyTorch, HarvestWise processes over 20 years of crop, weather, and soil data from Maharashtra’s 30 districts. This allows the system to deliver highly accurate insights across four main features:

--> Crop Yield Prediction: Using models like Random Forest and Linear Regression, the system predicts total expected crop yield based on parameters like crop type, soil condition, district, area, and season.

--> AI-based Crop Recommendation: A deep neural network (PyTorch-based) suggests the most suitable crops to grow based on real-time inputs like NPK values, temperature, humidity, pH, and rainfall.

--> Rainfall Forecasting: HarvestWise estimates monthly rainfall patterns at the district level using historical meteorological data, helping farmers plan sowing and irrigation schedules better.

--> Fertilizer Guidance: The platform recommends optimal NPK levels and pH-balancing strategies tailored to the selected crop and current soil conditions.

Planned features include a Crop Calendar, which will provide month-wise crop recommendations, and premium tools such as pest alerts, market insights, and multilingual (Marathi, Hindi, English) support. The frontend (in development using Next.js and Tailwind CSS) is being designed with a mobile-first, user-friendly approach for accessibility by non-technical users, especially small-scale farmers.

By combining AI with real-time and historical data, HarvestWise shifts traditional farming practices toward precision agriculture. It enables better planning, reduces risks from climate variability, and promotes efficient resource usage—helping farmers improve productivity, income, and sustainability.
