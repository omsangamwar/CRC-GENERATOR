# CRC-GENERATOR


## Problem statement

The problem is to implement a CRC (Cyclic Redundancy Check) generator and receiver in a web application using HTML, CSS, and JavaScript. The generator should take a message and a divisor as input, compute the CRC code, and display the remainder and the encoded data. The receiver should verify the received data for errors using the same divisor.

## Methodology

### Designing the User Interface (HTML/CSS):

Created an interface using HTML and CSS, providing input fields for the message, divisor, and received data.
Styled the interface elements to enhance usability and aesthetics.

### Implementing CRC Logic (JavaScript):

Defined functions for XOR operation (xor) and performing modulo-2 division (mod2div).
The encodeData function encodes the input data by appending zeros, computing the CRC, and displaying the remainder and the encoded data.
The receiver function verifies the received data by performing CRC computation and checking for errors.

### Handling User Interaction (JavaScript):

Linked the HTML elements with JavaScript functions using event listeners.
Triggered CRC computation and result display upon user interaction, such as button clicks.

### Testing and Debugging:

Conducted testing with various inputs to ensure correct CRC computation and error detection.
Debugged the code to address any issues encountered during testing.

### Styling and Refinement (CSS/HTML):

Made refinements to the user interface based on feedback and testing results.
Ensured the interface is intuitive and responsive across different devices.


## Working:

### CRC Generation:

The user inputs the message and divisor.
The encodeData function appends zeros to the message, computes the CRC using mod2div, and displays the remainder and encoded data.

### CRC Verification:

The user inputs the received data and divisor.
The receiver function performs CRC computation on the received data using mod2div.
If the remainder contains any non-zero bits, an error is detected, indicating incorrect transmission. Otherwise, the message is considered correct.


## Conclusion:

Through the collaborative effort of designing, implementing, and testing the CRC generator and receiver, we have successfully developed a functional tool for error detection in data transmission. The CRC algorithm provides a reliable method for detecting errors, ensuring data integrity in communication systems.
