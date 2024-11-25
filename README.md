
# AI-Fruit Recognition

**AI-Fruit Recognition** is a JavaFX-based application that utilizes neural networks to accurately recognize various fruits. The system was trained and tested on extensive datasets, achieving high accuracy. The project includes the implementation of advanced activation functions such as tanh, sigmoid, and ReLU to optimize neural network performance.

---

## Key Features

- **Neural Network Implementation**:
  - Custom-built neural network for fruit recognition.
  - Supports multiple activation functions: tanh, sigmoid, and ReLU.
- **Dataset Integration**:
  - Trained and tested on extensive fruit datasets to ensure high accuracy.
- **Graphical User Interface**:
  - Interactive GUI built with JavaFX for ease of use.
- **Real-Time Recognition**:
  - Processes and recognizes fruit images in real time.

---

## Technologies Used

- **Frontend**: JavaFX (GUI)
- **Backend**: Neural Networks (custom implementation)
- **Machine Learning Libraries**: Integrated with Java libraries for matrix computations and model optimization.

---

## Getting Started

### Prerequisites

- **Java** (JDK 8 or higher)
- **JavaFX SDK**
- A pre-trained fruit dataset (included in the project)

---

### Installation

1. **Clone the repository**:
   ```bash
   git clone https://github.com/YazanM23/FruitRecognition-AI-
   cd FruitRecognition-AI-
   ```

2. **Set up JavaFX**:
   - Ensure JavaFX SDK is installed and properly configured in your development environment.

3. **Run the application**:
   Compile and run the `Main.java` file using your IDE or the command line:
   ```bash
   javac -cp javafx-sdk/lib/*:. Main.java
   java -cp javafx-sdk/lib/*:. Main
   ```

---

## How It Works

1. **Dataset Loading**:
   - The application loads the pre-trained dataset included in the project files.

2. **Neural Network Architecture**:
   - Multi-layer perceptron with user-selectable activation functions (tanh, sigmoid, ReLU).

3. **Fruit Recognition**:
   - Users can upload an image of a fruit, and the application predicts the fruit type with high accuracy.

---

## File Structure

- **`Main.java`**: Entry point of the application.
- **`NeuralNetwork.java`**: Contains the neural network implementation.
- **`ui/`**: Includes FXML files and JavaFX controllers for the GUI.
- **`resources/`**: Contains datasets, stylesheets, and icons.

---

## Customization

- Modify the `NeuralNetwork.java` file to experiment with different architectures or activation functions.
- Add additional datasets to improve the model's recognition capabilities.
- Update FXML files in the `ui/` directory to change the interface layout.

---

## License

This project is open-source and available under the [MIT License](LICENSE).

---

## Contact

For queries or feedback, reach out:

- **Name**: Yazan Mansour
- **Email**: Yazan.mansour2003@gmail.com
