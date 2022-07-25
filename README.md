# Prediction-flow-around-a-cylinder
The problem of the fluid flow around a circular cylinder requests numerical solutions of significant computational cost.  
For this reason, the application of Machine Learning and Deep Learning algorithms to this problem is of great interest, since it can potentially be a good alternative to provide faster and better solutions.  
Using neural networks (in particular CNN and Long-short term memory models), we implemented two possible solutions.  
What can be found in this repository:  
- Data_Mining_Report.pdf, which contains the complete description of the dataset, code and work done.
- code, which contains the codes (from Jupyter Notebook) for LSTM and CNN models to predict both pressure and velocity. Moreover, Accuracy.ipynb can be used to compute the quality of the model and plot.ipynb to obtain significant graphs about data and results.  
In particular, at the beginning of the codes of LSTMPressure.ipynb and LSTMvelocity.ipynb the overall data are unified in tot_pressure.csv and tot_velocity_x.csv, tot_velocity_y.csv, tot_velocity_z.csv. Then, the predictions are saved in dataLSTM folder; similarly, CNNPressure.ipynb and CNNvelocity.ipynb saves their predictions in dataCNN folder. **These files should be used in this order: LSTMPressure.ipynb, LSTMvelocity.ipynb, CNNPressure.ipynb, CNNvelocity.ipynb.** The order can be changed, but appropriate modifications should be done.
- dataCNN and dataLSTM contain data with predicted values.
