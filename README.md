# Predicting-Google-Share-Price-using-RNN-LSTM-GRU

Introduction

Predicting stock prices is a challenging task due to the volatile and non-linear nature of financial markets. Deep learning models, especially Recurrent Neural Networks (RNNs) and their variants — Long Short-Term Memory (LSTM) and Gated Recurrent Unit (GRU) — are well-suited for time series forecasting tasks. This project aims to explore how these models can be applied to predict the share price of Google (Alphabet Inc.) using historical stock data.

Objectiv
To use different types of Recurrent Neural Networks — Simple RNN, LSTM, and GRU — to predict Google’s stock price.
To use historical stock data to train models that capture time-dependent patterns in share price movements.
To use advanced RNN architectures (LSTM and GRU) to improve prediction accuracy compared to simple RNN.
To use this project as a practical example of applying deep learning techniques to financial time series forecasting.

Tools & Technologies

Languages: Python
Libraries: NumPy, Pandas, Matplotlib, Seaborn, TensorFlow, Keras, scikit-learn
Models: Simple RNN, LSTM, GRU

Results

LSTM and GRU models showed better performance in learning long-term dependencies in time series data.
Simple RNN struggled with capturing complex price patterns due to vanishing gradient issues.
Among all, GRU provided the best trade-off between accuracy and computational efficiency.

Conclusion

This project demonstrates the effectiveness of deep learning models, especially LSTM and GRU, in financial time series forecasting. While these models cannot guarantee perfect accuracy in stock prediction, they significantly outperform traditional methods by learning from historical trends. The approach showcased here can serve as a foundation for building more robust forecasting systems by incorporating additional features like volume, sentiment data, or macroeconomic indicators.
