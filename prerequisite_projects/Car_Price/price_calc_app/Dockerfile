# Use an official Python image as a base
FROM python:3.9

# Set the working directory in the container
WORKDIR /app

# Copy the necessary files
COPY requirements.txt .
COPY car_price_model.pkl .
COPY price_calc_app.py .

## Install dependencies
RUN pip install --no-cache-dir -r requirements.txt

# Expose the port that Streamlit runs on
EXPOSE 8501

# Run the Streamlit app
CMD ["streamlit", "run", "price_calc_app.py", "--server.port=8501", "--server.address=0.0.0.0"]