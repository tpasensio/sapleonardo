# SAP Leonardo + Tensorlow

What is SAP Leonardo?
SAP Leonardo Machine Learning is the new branding for SAP's entire portfolio of intelligent applications and services
![SAP Leonardo Architecture](https://blogs.sap.com/wp-content/uploads/2018/01/Hierarchy-1.1.png)

# Dataset and demo

This demo is built on a subset of the information from the New York City Taxi & Limousine Commission. The full dataset is about 1,000 Millions Records. For the sake of simplicity this demo runs only on a month data. You can run the analytics on the full dataset using SAP HANA. [For more information on the dataset](http://www.nyc.gov/html/tlc/html/about/trip_record_data.shtml)

In this demo we will use Tensorflow machine learning library to train a model on Taxi usage and later use this model to predict the demand on different parts of the New York City

# For the impatient
Download and install [Docker](https://www.docker.com/community-edition)

Clone/download this github [repository](https://github.com/tpasensio/sapleonardo/archive/master.zip)

On a console run this command, change PATH with the path used to uncompress the code

```bash
docker run -v PATH:/notebooks -it -p 8888:8888 tensorflow/tensorflow:1.4.0
```

Copy the url from the output console and open your browser

```bash
    Copy/paste this URL into your browser when you connect for the first time,
    to login with a token:
        http://localhost:8888/?token=e310f1aa8f772f5aaadb9c14d9eac157e7f7dbcc94811d12
```

From here you can open and run the notebook called nyc-passengers-predict

Or browse the [notebook](nyc-passengers-predict.ipynb)
# Detail

# Next steps


