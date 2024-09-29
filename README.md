# Vehicle Detection and Counting from Video Streams

## Project Overview
This project aims to detect and count different types of vehicles from video streams. Using computer vision techniques, the system identifies **buses, cars, rickshaws, and bikes** and provides separate counts for each category. The project is designed to operate efficiently on video inputs, offering a real-time solution for vehicle detection and analysis.

## Features
- **Vehicle Detection**: Identifies buses, cars, rickshaws, and bikes from video streams.
- **Vehicle Counting**: Separately counts each detected vehicle type.
- **Real-time Processing**: Processes video input in real time.
- **Scalable Model**: Can be adapted to detect additional vehicle types.

## Use Cases
- **Traffic Monitoring**: Analyze traffic flows and vehicle density in urban environments.
- **Traffic Management**: Supports traffic management systems for congestion control.
- **Data Collection**: Useful for research related to traffic and vehicle patterns.

## Requirements
- Python 3.x
- OpenCV
- Pre-trained YOLO (You Only Look Once) model
- NumPy
- Other dependencies as listed in `requirements.txt`

## Installation

1. Clone this repository:
    ```bash
    git clone https://github.com/your-umermustafa00/vehicle-detection-counting.git
    ```
2. Navigate to the project directory:
    ```bash
    cd vehicle-detection-counting
    ```
3. Install the required dependencies:
    ```bash
    pip install -r requirements.txt
    ```

## How to Use

1. Ensure you have your video file or stream ready for processing.
2. Run the script using the following command:
    ```bash
    python main.py --video <path_to_video_file>
    ```
3. The script will output the total number of vehicles detected and count them by type (buses, cars, rickshaws, bikes).

## Future Enhancements
- Support for additional vehicle types (e.g., trucks, motorcycles).
- Improved accuracy for occluded or partially visible vehicles.
- Performance optimization for processing larger datasets faster.

## Contributing
Contributions are welcome! Please fork this repository and submit a pull request if you want to contribute to this project.

## License
This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

---

