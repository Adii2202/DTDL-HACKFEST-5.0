
**Fingerprint Verification System**
This project implements a fingerprint verification system capable of processing fingerprint images for feature extraction and verification. The current implementation accepts input as an image file, but it can be modified to directly interface with a fingerprint scanner for real-time input.

**Adapting to Fingerprint Scanner Input**
To adapt the system to accept input directly from a fingerprint scanner:

Replace the input image with a method that captures frames or data from the fingerprint scanner.
Modify the extract_minutiae_features function to process the scanner input in real-time.
For example usage and integration with a fingerprint scanner, refer to the source code and modify the input handling accordingly.

****
