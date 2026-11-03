# GlareX-Smart-LED-Matrix-Headlight-
Algorithm used
1. Initialize the YOLO11n model and webcam.
2. Capture a frame from the webcam.
3. Detect vehicles using the pretrained YOLO model.
4. Extract the bounding box and confidence score.
5. Determine which LED zone contains the vehicle.
6. Reduce the brightness of the corresponding LED zone.
7. Send the brightness values to the ESP32 through serial communication.
8. Repeat continuously for real-time adaptive illumination.
