Design & Development of Compact Low Pass and Band Pass Filters for Microwave Receivers
This project report details the design, simulation, and implementation of compact low-pass and band-pass filters for microwave receiver applications. The work was conducted as a summer practical training program at the Space Applications Centre (SAC), a wing of the Indian Space Research Organisation (ISRO). The report focuses on the theoretical and practical development of microstrip and lumped-component filters to meet stringent performance criteria for satellite communication and radar systems.





Key Features and Methodologies

Band-Pass Filter (BPF): A lumped-component BPF centered at 312.5 MHz was designed to operate in the L&S-Band. The final design is a 3rd-order filter with a Butterworth response , achieving low insertion loss and high rejection in the stopband. The filter's layout was designed to be compact, fitting within a 





3/4×3/4 inch area.




Microstrip Low-Pass Filter (LPF): A compact microstrip LPF was developed for Wideband (WB) applications, with a cutoff frequency at 2.475 GHz. The design utilizes a high-dielectric Alumina substrate and employs a Chebyshev response for a high roll-off rate. The final design incorporates stepped-impedance lines and radial stubs to achieve wide stopband rejection and a compact layout. This design also fits within a 





3/4×3/4 inch area.



Advanced Design Techniques: The project utilized industry-standard tools like ADS (Advanced Design System) for simulation and layout design. Key concepts applied include:





Filter Theory: Fundamentals of Butterworth and Chebyshev responses, transfer functions, and pole-zero placement.






Filter Implementation: Use of Richards' Transformation and Kuroda's Identities to convert lumped elements to transmission line sections and for layout optimization.




Performance Validation: Extensive analysis of S-parameters to validate designs for insertion loss, return loss, and bandwidth.




Project Structure
This repository contains the detailed report, which is organized into the following chapters:


Chapter 1: Introduction: Provides an overview of the project, including its scope, relevance to ISRO's work, and the technologies explored.


Chapter 2: Basic Concepts of Filters: Discusses the fundamental theory behind filter design, including transfer functions, filter responses (Butterworth, Chebyshev, Elliptic, Gaussian), and transformations.


Chapter 3: Transmission Lines and Components: Covers the basics of microstrip lines, discontinuities, and quasi-lumped elements essential for physical filter realization.


Chapter 4: Filter 1 (Band-Pass Filter): Documents the design methodology, theoretical approach, and simulation results for the lumped-component BPF.




Chapter 5: Filter 2 (Low-Pass Filter): Outlines the design of the microstrip LPF, including various design strategies and iterative improvements.




Chapter 6: Final Proposed Designs: Presents the finalized layouts and simulation results for both filters, confirming they meet all specifications and constraints.


The designs are ready for the fabrication stage, with future work planned to test the fabricated filters using a Vector Network Analyzer (VNA) and compare the results with simulations.
