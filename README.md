# electriccity_price_prediction
THis data is from OpenML (https://www.openml.org/) . In this data the price of electricity is not fixed but based on certani conditions such as demands , transfer etc. base on the given data, i have shown how to predict using these conditions as to wheteher  electricity price goes Up or Down.


==========================================================================================================================================
*******************************************************************************************************************************************
Description
Author: M. Harries, J. Gama, A. Bifet
Source: Joao Gama - 2009
Please cite: None

Electricity is a widely used dataset described by M. Harries and analyzed by J. Gama (see papers below). This data was collected from the Australian New South Wales Electricity Market. In this market, prices are not fixed and are affected by demand and supply of the market. They are set every five minutes. Electricity transfers to/from the neighboring state of Victoria were done to alleviate fluctuations.

The dataset (originally named ELEC2) contains 45,312 instances dated from 7 May 1996 to 5 December 1998. Each example of the dataset refers to a period of 30 minutes, i.e. there are 48 instances for each time period of one day. Each example on the dataset has 5 fields, the day of week, the time stamp, the New South Wales electricity demand, the Victoria electricity demand, the scheduled electricity transfer between states and the class label. The class label identifies the change of the price (UP or DOWN) in New South Wales relative to a moving average of the last 24 hours (and removes the impact of longer term price trends).

The data was normalized by A. Bifet.

Attribute information
Date: date between 7 May 1996 to 5 December 1998. Here normalized between 0 and 1
Day: day of the week (1-7)
Period: time of the measurement (1-48) in half hour intervals over 24 hours. Here normalized between 0 and 1
NSWprice: New South Wales electricity price, normalized between 0 and 1
NSWdemand: New South Wales electricity demand, normalized between 0 and 1
VICprice: Victoria electricity price, normalized between 0 and 1
VICdemand: Victoria electricity demand, normalized between 0 and 1
transfer: scheduled electricity transfer between both states, normalized between 0 and 1
