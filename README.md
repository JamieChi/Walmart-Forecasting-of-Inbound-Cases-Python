🎯 Goal: better truck planning, optimized staff allocation, and overall efficient operations.

✅ Approaches:
We went beyond several models, integrated external data, and let AI do its thing through In-Context Learning to identify patterns.
Of course, it wasn't all smooth. 
We ran into some challenges, but our team figured them out:

☑️ Challenge 1: Missing External Data
- Solution: We forecasted the missing data (e.g., using Linear Regression)
  
☑️ Challenge 2: Data Leakage
- Solution: We trained both Recursive Model (feeding predictions back into subsequent forecasts) and Direct Multi-Horizon Model (training separate models for each day T+1, T+2, etc.)

🎉 Impact:
We achieved a MAPE of 6.41%, which is great for the retail industry. 
As we learned, even a 1% reduction in forecast error across Walmart's scale (4,600 stores × 40 departments) 
can save them 20k–45k weekly labor hours of overstaffing/understaffing.

That's a real-world business impact!
