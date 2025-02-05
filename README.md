# Deep-Learning
AI BASED ELECTRICITY DEMAND FORECASTING FOR DELHI

# Introduction
Electricity forms the mainstay of modern urban living and the operation of industries, businesses, and houses. For metropolitans like Delhi, population growth, extreme climatic conditions, and changes in consumer behavior continue to influence electricity demand fluctuations. Demand balancing at each point and assuring it is efficient is a critical role for maintaining the stability of the grid, reducing energy wastage, and integrating renewable sources of energy. The need for sustainable energy management has never been greater. Accurate electricity demand forecasting can: prevention of blackout and grid failure during high-energy demand periods, decreased cost of overproduction or underutilization of energy resources, and smooth integration of renewable energy sources into the grid, furthering environmentally friendly practices. With AI and powerful statistical models, energy planners can predict and avoid demand-supply mismatches, opening the gates to more reliable and efficient power systems. India's capital city, Delhi, experiences extreme weather conditions, high growth rates of urbanization, and a considerable base of household and commercial customers. Traditional forecasting tools fail to capture intricate connections among numerous factors influencing electricity demand. Therefore, such forecasting tools make energy consumption inefficient and costly, along with an increased risk of blackout. Thus, AI-based predictive models can help overcome these issues by presenting accurate data-driven insights into electricity consumption patterns.

# Result and Discussion
1.  Results: 
The LSTM model performed the best with the below metrics: 
• Mean Absolute Error (MAE): 145 MW   
• Root Mean Square Error (RMSE): 210 MW   
Random Forest showed good performance but slightly lagged behind LSTM:   
• MAE: 160 MW   
• RMSE: 235 MW 
ARIMA performed satisfactorily but could not encapsulate much of the non-linear 
patterns:  
• MAE: 175 MW  
• RMSE: 250 MW

3. Discussion: The improved results obtained for LSTM could be attributed to the fact that 
the network can capture dependences in the sequence data over long time horizons. 
• Random Forest proved stability to nonlinear relationships but did not gain 
awareness of the temporal of LSTM. 
• ARIMA was bound by the assumption of being a linear approach, and it easily 
gets confused by complex and dynamic patterns in the electricity demand.

3.Visualization: The forecast by the LSTM model also followed the trends of the actual 
demand with less deviation at peak and off-peak times.

![image](https://github.com/user-attachments/assets/d3a1efaa-ba7c-422b-a7cb-6148fb0885f0)
