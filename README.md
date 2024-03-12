# Gray-Scale-Image


# Electromania FPGA 2024

## Abstract

**Team Name:** Savi

### Team Details:

| Name             | Registration Number | Phone Number  | Email ID                  |
|------------------|----------------------|---------------|---------------------------|
| Bhargavi A. Shukla | 20215117 | 9818450526 | bhargavi.shukla3@gmail.com |
| Sachin Kumar      | 20215001 | 6202924663 | sachinkr24663@gmail.com    |
| Dhiraj Kr. Singh  | 20215137 | 7903909480 | dhirajkumar55588@gail.com  |

## Grey Scale Image

### Technology Stack (Proposed)

- Verilog
- FPGA
- Xilinx Vivado

### Approach to Solve the Problem

1. **Decompressing the Image:**
   - Decompress the image, e.g., using the inverse cosine transform for JPEG format.

2. **Conversion to Hardware-Compatible Format:**
   - Convert the JPEG image to a format compatible with hardware design by representing pixel data in hexadecimal values.

3. **GaussianBlur Module:**
   - Implement a module named `GaussianBlur` to blur the image using a Gaussian Kernel.

4. **Booth Multiplier Enhancement:**
   - Enhance the multiplier using the Booth multiplication algorithm.

5. **Image Storage in RAM:**
   - Store the initial and processed images in the RAM using a module named `ImgRAM`.

6. **Data Path and Control Path Modeling:**
   - Model the Data Path and Control Path using knowledge of state machines in Digital Electronics.

7. **Interconnection and Testbench:**
   - Interconnect all modules and apply testbenches to validate the design.

### Progress

- Implemented Booth Multiplication separately to clarify concepts of Data and Path Controller.

## Booth Multiplier
![Screenshot 2024-03-11 163636](https://github.com/bhargavishukla3/Gray-Scale-Image/assets/97394773/6cc6f685-d2f3-4246-948a-6abb4501aefe)
![Screenshot 2024-03-11 163541](https://github.com/bhargavishukla3/Gray-Scale-Image/assets/97394773/ef39c406-8b7c-4921-a1f0-c467a9897bd1)






