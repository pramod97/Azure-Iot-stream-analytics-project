# Azure-Iot-stream-analytics-project
This project demonstrates the use of Azure IoT Hub and Stream Analytics for real-time data processing. I simulate IoT data using a Raspberry Pi Azure IoT simulator and stream this data to Azure IoT Hub. The data is then processed using Azure Stream Analytics and stored in Azure Blob Storage for further analysis.

### 1. Setting Up Raspberry Pi Azure IoT Simulator

- Use the Raspberry Pi Azure IoT Online Simulator.
- Connect it to your Azure IoT Hub by entering the connection string from the IoT Hub.
  ![pic](https://github.com/user-attachments/assets/209d2d42-2997-4aad-ae15-19a676cd2225)


### 2. Creating an Azure IoT Hub

- Create an IoT Hub in the Azure portal.
  ![image](https://github.com/user-attachments/assets/87d622ba-d5d9-46d0-8cd4-65b5b2add2ea)

- Retrieve the connection string from the IoT Hub to use in the IoT simulator.
  ![image](https://github.com/user-attachments/assets/ea53fc2d-1154-4c4d-98c4-38ef142579d0)


### 3. Setting Up Azure Stream Analytics Job

- Create an Azure Stream Analytics Job in the Azure portal.
  ![image](https://github.com/user-attachments/assets/82ece30a-36cc-40d6-90c6-4c047996237f)

- Define the IoT Hub as the input and Blob Storage as the output.
 ![image](https://github.com/user-attachments/assets/196b81ec-f80a-4d98-ac1a-ef4e05c5c0e2)
 ![image](https://github.com/user-attachments/assets/d3951d23-f869-4de1-9c90-0acd29820549)


- Use the following query in the Stream Analytics job:
 ![image](https://github.com/user-attachments/assets/8cfd1d05-aea3-4d73-b555-439d6c814433)


### 4. Setting Up Azure Blob Storage

- Create a Blob Storage account in the Azure portal.
- Create a container within the Blob Storage to store the output data.
  ![image](https://github.com/user-attachments/assets/b99954a7-be81-4b15-a8f4-b39303d4aafd)


## Running the Project

1. Start the IoT simulator to begin sending data to the IoT Hub.
2. Ensure the Stream Analytics job is started and running.
   ![image](https://github.com/user-attachments/assets/d1a00a95-bf8c-4efb-9d8b-6721691c54e3)

4. Monitor the Blob Storage container for the output data.
   ![image](https://github.com/user-attachments/assets/19e9f790-4b84-43f4-a424-6562104820e4)


## Conclusion

This project showcases a basic IoT pipeline using Azure services to simulate, process, and store IoT data. It serves as a example for real-time data processing and can be extended with visualization tools.

## Future Enhancements

- Add data visualization using Power BI.
