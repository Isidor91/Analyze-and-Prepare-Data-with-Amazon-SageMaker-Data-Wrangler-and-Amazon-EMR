# Analyze-and-Prepare-Data-with-Amazon-SageMaker-Data-Wrangler-and-Amazon-EMR

Lab overview

A local not-for-profit citizen advocacy group promotes government assistance services to qualified citizens in their region. The advocacy group is preparing to promote a newly established assistance service. One of the key eligibility criteria is that an individual cannot have an annual income that exceeds 50,000 USD. The citizen advocacy group has demographic data that includes citizens’ education and employment, but only a subset of the data includes income data. The citizen advocacy group has asked AnyCompany Consulting to deliver a machine learning (ML) solution that can predict if an individual is likely to make less than 50,000 USD, based on the other demographic data. This solution will help them to make the best use of their limited budget by targeting promotions to citizens who are most likely to be eligible for the service. AnyCompany Consulting wants you to visualize and prepare the data. After the data is cleaned, they want you to export the data to their Amazon Simple Storage Service (Amazon S3) bucket.

In addition to that, you have some datasets that AnyCompany Consulting wants you to bring into Amazon SageMaker later that require data preparation at scale. You want to test how Apache Spark on Amazon EMR can be integrated with Amazon SageMaker Studio to process data and prepare it.

In this lab, you learn how to visualize and prepare data, and complete several transformations on the dataset in SageMaker Data Wrangler. After the data is transformed, you learn to export the data back to Amazon S3. You also learn how to discover and securely connect to an EMR cluster directly from SageMaker Studio. You use a SageMaker Studio notebook to visually discover, authenticate with, and connect to an EMR cluster. You then query an Apache Hive table on Amazon EMR using Apache Spark.

Objectives

After completing this lab, you should be able to do the following:

Choose effective methods for visualizing data
Explain the value of data cleaning and transformation
Describe how to process missing values, outliers, duplicated data, etc.
Define Key Encoding techniques
Describe how to ingest and transform data into Amazon Sagemaker Data Wrangler
Describe how to transform data using Spark on Amazon EMR
Technical knowledge prerequisites
To successfully complete this lab, you should have knowledge of:

Basic navigation of the AWS Management Console.
An understanding of database concepts, MySQL, and database availability.
