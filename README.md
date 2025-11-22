✅ Features Implemented

Android (Kotlin + JNI + OpenCV)
- ✅ **Real-time camera preview** using Camera2 API and TextureView
- ✅ **Runtime camera permissions** handling (Android 6.0+)
- ✅ **Edge-to-edge layout** with modern Android UI
- ✅ **JNI integration** for native C++ processing
- ✅ **OpenCV Canny edge detection** applied to each frame
- ✅ **Frame capture and processing** at real-time frame rates
<img width="378" height="771" alt="Screenshot 2025-11-22 223230" src="https://github.com/user-attachments/assets/bcf93fdf-c930-490a-bc26-be32a4b617b5" />


Architecture Overview
High-Level Flow

Camera2 API → TextureView → Frame Capture (Bitmap)
                                    ↓
                            JNI Bridge (Kotlin ↔ C++)
                                    ↓
                    OpenCV Processing (Canny Edge Detection)
                                    ↓
                            Return Processed Bitmap
                                    ↓
                            Display on UI (TextureView)
