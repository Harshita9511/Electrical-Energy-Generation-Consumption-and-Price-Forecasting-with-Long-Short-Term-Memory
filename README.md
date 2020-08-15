# Electrical Energy Generation, Consumption and Price Forecasting with Long Short Term Memory

<img src="/image.jpg" width="1000" height="300" />
<div align="justify">

## Long Short-Term Memory
Long Short Term Memory (LSTM) networks are a special kind of artificial recurrent neural network (RNN), capable of learning long-term dependencies. They were introduced by Hochreiter & Schmidhuber (1997) . LSTMs are explicitly designed to avoid the long-term dependency problem. Unlike standard feedforward neural networks, LSTM has feedback connections. It can not only process single data points (such as images), but also entire sequences of data (such as speech or video). LSTM is applicable to tasks such as unsegmented, connected handwriting recognition, speech recognition and anomaly detection in network traffic or IDS's (intrusion detection systems).<br />
A common LSTM unit is composed of a cell, an input gate, an output gate and a forget gate. The cell remembers values over arbitrary time intervals and the three gates regulate the flow of information into and out of the cell.<br />
LSTM networks are well-suited to classifying, processing and making predictions based on time series data, since there can be lags of unknown duration between important events in a time series. LSTMs were developed to deal with the vanishing gradient problem that can be encountered when training traditional RNNs.

## Dataset
This dataset contains 4 years of electrical consumption, generation, pricing for Spain. Consumption and generation data was retrieved from ENTSOE a public portal for Transmission Service Operator (TSO) data. Settlement prices were obtained from the Spanish TSO Red Electric España.<br />
Data Source: [Electrical Energy Dataset](https://www.kaggle.com/nicholasjhana/energy-consumption-generation-prices-and-weather/data#energy_dataset.csv)<br /><br />

*time:* Datetime index localized to CET<br />
*generation biomass:* biomass generation in MW<br />
*generation fossil brown coal/lignite:* coal/lignite generation in MW<br />
*generation fossil coal-derived gas:* coal gas generation in MW<br />
*generation fossil gas:* gas generation in MW<br />
*generation fossil hard coal:* coal generation in MW<br />
*generation fossil oil:* oil generation in MW<br />
*generation fossil oil shale:* shale oil generation in MW<br />
*generation fossil peat:* peat generation in MW<br />
*generation geothermal:* geothermal generation in MW<br />
*generation hydro pumped storage aggregated:* hydro1 generation in MW<br />
*generation hydro pumped storage consumption:* hydro2 generation in MW<br />
*generation hydro run-of-river and poundage:* hydro3 generation in MW<br />
*generation hydro water reservoir:* hydro4 generation in MW<br />
*generation marine:* sea generation in MW<br />
*generation nuclear:* nuclear generation in MW<br />
*generation other:* other generation in MW<br />
*generation other renewable:* other renewable generation in MW<br />
*generation solar:* solar generation in MW<br />
*generation waste:* waste generation in MW<br />
*generation wind offshore:* wind offshore generation in MW<br />
*generation wind onshore:* wind onshore generation in MW<br />
*forecast solar day ahead:* forecasted solar generation<br />
*forecast wind offshore day ahead:* forecasted offshore wind generation<br />
*forecast wind onshore day ahead:* forecasted onshore wind generation<br />
*total load forecast:* forecasted electrical demand<br />
*total load actual:* actual electrical demand<br />
*price day ahead:* forecasted price EUR/MWh<br />
*price actual:* price in EUR/MWh<br />

</div>
