# **IIT Kanpur Traffic Analysis - Vehicle Detection and Counting**
**Project Description :-** In this project I have analysed the  different types of vehicles running in IITK campus. In this analysis I basically performed the vehical detection and tracking along with counted the number of incoming and outgoing vehicle in campus.

**Datset Description :-** I collected the data of IIT kanpur traffic from diffrent areas. In dataset I used the traffic videos, further converted into frames which are around 8000 images in number. Dataset basically contain five types of vehicle i.e.

➡ Bicycle

➡ MotorBike

➡ E-Rickshaw

➡ Car

➡ Auto-Rickshaw

**Model used:-** I have Used YOLOv8 object detection model for detection and tracking. Here I have used transfer learning to train the model over custom dataset which I have collected.

**Result and Anlysis:-** All are generated result are stored in ///that folder. Due to lack of GPU computation,  model is only trained upto 60 epochs. Due to this I have achieved only ~72% validation accuracy. But prediction is still good to recognise the object and track it properly.

**Future Scope of project:-** We can extend this project to track person coming in any particular orgnization and also analyze the customer traffic in that orgnization.
