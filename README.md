# Car-Price-Prediction
This Python script, app.py, is a Streamlit application designed to predict car prices. It uses a pre-trained machine learning model, loaded from model.pkl, and a car details dataset from Car details.csv to create an interactive web interface.

The application allows users to input various car features through sliders and select boxes, such as:

Car Brand: Select from a list of car manufacturers.

Manufacturing Year: Choose the year the car was made.

#Kilometers Driven: Specify the total distance the car has traveled.

Fuel Type: Select the type of fuel the car uses.

Seller Type: Indicate whether the seller is an individual, dealer, etc.

Transmission Type: Choose between manual or automatic transmission.

Owner: Select the number of previous owners.

Mileage: Input the car's fuel efficiency.

Engine CC: Specify the engine displacement.

Max Power: Enter the maximum power output of the engine.

Number of Seats: Choose the seating capacity.

When the "Predict" button is clicked, the script takes the user's input, processes it by converting categorical features into numerical representations, and feeds it into the machine learning model. The model then predicts the car's price, which is displayed to the user.
