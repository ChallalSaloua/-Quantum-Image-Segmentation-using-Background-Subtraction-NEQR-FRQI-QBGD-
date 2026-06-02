### ⚛️ Quantum Image Segmentation using Background Subtraction (NEQR, FRQI & QBGD)

This research project explores the application of Quantum Image Processing techniques to image segmentation through background subtraction methods. The study investigates the effectiveness of quantum image representations and quantum segmentation algorithms compared to traditional computer vision approaches.

The project focuses on two major quantum image representation models, **NEQR (Novel Enhanced Quantum Representation)** and **FRQI (Flexible Representation of Quantum Images)**, and evaluates their performance for motion detection and foreground-background segmentation tasks. A quantum segmentation approach based on the **Quantum Background Difference (QBGD)** algorithm was implemented and analyzed using multiple image datasets.

The research aims to assess whether quantum image processing can provide practical advantages in image segmentation while identifying the current limitations of quantum representations and quantum computing hardware.

#### Research Objectives

* Study quantum image representation techniques.
* Implement and analyze NEQR and FRQI image encoding models.
* Develop a quantum background subtraction framework.
* Compare quantum and classical segmentation approaches.
* Evaluate segmentation quality using IoU and Accuracy metrics.
* Analyze computational complexity, circuit depth, and simulation cost.

#### Key Contributions

* Implementation of NEQR image representation circuits.
* Implementation of FRQI image representation circuits.
* Development of a Quantum Background Difference (QBGD) segmentation pipeline.
* Comparative performance evaluation across multiple datasets.
* Critical analysis of current quantum image processing limitations.

#### Experimental Analysis

The project evaluates:

* Classical Background Subtraction
* NEQR Representation
* FRQI Representation
* NEQR + QBGD Segmentation
* FRQI + QBGD Segmentation

Performance was measured using:

* Intersection over Union (IoU)
* Segmentation Accuracy
* Quantum Circuit Depth
* Number of Qubits
* Simulation Execution Time

#### Main Findings

The experimental results demonstrated that classical background subtraction remains significantly more effective for practical image segmentation tasks, achieving substantially higher segmentation accuracy and lower execution times.

Among the quantum approaches, NEQR outperformed FRQI by providing:

* Exact intensity recovery
* Significantly lower circuit depth
* Faster simulation performance
* Better suitability for image processing applications

The study also revealed important limitations of current quantum segmentation algorithms, particularly the loss of spatial information during measurement, which prevents accurate pixel-level segmentation.

#### Technologies & Tools

* Python
* Qiskit
* Quantum Computing
* Quantum Image Processing
* NumPy
* OpenCV
* Matplotlib
* Scientific Research Methodology

#### Research Areas

* Quantum Computing
* Quantum Image Processing
* Computer Vision
* Image Segmentation
* Background Subtraction
* Quantum Algorithms
* Artificial Intelligence

#### Project Outcome

This work demonstrates that while quantum image representations such as NEQR and FRQI provide promising theoretical foundations for future image processing systems, current implementations remain largely proof-of-concept solutions. The project highlights both the potential and the present limitations of quantum approaches for real-world computer vision applications.
