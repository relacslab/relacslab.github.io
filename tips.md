# Having a Nice Graduate Student Life?
- **Be honest**: Credibility is the most basic virtue for having a wonderful relationship with your colleagues and advisors. 
- **Be self-motivated**: Graduate student life has a very high degree of freedom. Try to plan out several short-term milestones (it can be publishing or completing tasks) similar to game quests. 
- **Be responsible**: Unlike in industry, you do research and write papers for yourself, not for your advisors.
- **Be productive**: After completing the project, please let your efforts bear fruit by publishing papers or patents -- These will leave solid records on your CV.
- **Don't be greedy**: Earning a degree is a marathon-like procedure. Hence, unless your paper's deadline is coming up, please take a day off per week at least to prevent yourself from burning out. 


# To Fresh: How to Read Papers?
Creativity originates from repeated learning and imitation -- This is indeed true for any field. Historically, people have augmented various methods by learning from papers and books. Since computer science has been quickly growing within decades, we cannot come up with novel ideas from the blank background. Thus, reading papers should be one of your usual habits that should not be commanded by your advisors/managers, even if you are pursuing a career in the industry in the future. However, reading papers **correctly** is also crucial to develop your skills. Before reading, you need to keep the following questions in your mind: 

- What is the problem definition of this paper? 
- Is there a previous approach? What are the limitations of the previous approach? 
- What is the proposed key idea for overcoming the aforementioned challenges? What are the challenges to realizing the idea in practice? 
- Why does the proposed approach perform better than the previous approach from the technical perspective?
- How do the authors address those challenges in detail in the methodology part? 
- In the evaluation part, how do the authors evaluate their idea? By simulation? Real machine-based emulation? 
- What are the evaluation configurations? What is the rationale behind those configurations?
- What are the general tendencies of results? How do the authors explain some outliers?
- Above all, what are the commonly used approaches to realize idea, considering papers in various fields?


# Classic Papers for Fresh Graduate Students
To get your feet wet at computer architecture (e.g., understand common architectural design, methods, and terminologies), I recommend you read the following classic, wonderful papers published within decades! 

## Microarchitectures
J. A. Fisher et al., “Very Long Instruction Word Architectures and the ELI-512,” ISCA, 1983. <br />
J. E. Smith et al., “The Microarchitecture of Superscalar Processors,” Proceedings of the IEEE, 1995. <br />
K. Olukotun et al., “The Case for a Single-Chip Multiprocessor,” ASPLOS, 1996. <br />
A. Moshovos et al., “JETTY: Filtering Snoops for Reduced Energy Consumption in SMP Servers,” HPCA, 2001. <br />
G. Hinton et al., "The Microarchitecture of the Pentium 4 Processor,” Intel Technology Journal Q1, 2001. <br />
S. J. Eggers et al., “Simultaneous Multithreading: A Platform for Next-Generation Processors,” IEEE Micro, 2002. <br />
O. Mutlu et al., “Runahead Execution: An Alternative to Very Large Instruction Windows for Out-of-Order Processors,” HPCA, 2003. <br />
P. Kongetira et al., “Niagara: A 32-Way Multithreaded SPARC Processor,” IEEE Micro, 2005. <br />
E. Lindholm et al., “NVIDIA Tesla: A Unified Graphics and Computing Architecture,” IEEE Micro, 2008. <br />
A. Jaleel et al., “Achieving Non-Inclusive Cache Performance with Inclusive Caches,” MICRO, 2010. <br />
E. Blem et al., “Power Struggles: Revisiting the RISC vs. CISC Debate on Contemporary ARM and x86 Architectures,” HPCA, 2013. <br />

# Data prefetch
S. Palacharla et al., "Evaluating Stream Buffers as a Secondary Cache Replacement", ISCA, 1994. <br />
K. J. Nesbit et al., “Data Cache Prefetching using a Global History Buffer”, HPCA, 2004. <br />
S. Srinath et al., "Feedback Directed Prefetching: Improving the Performance and Bandwidth-Efficiency of Hardware Prefetchers", HPCA, 2007. <br />
S. H. Pugsley et al., “Sandbox Prefetching: Safe run-time evaluation of aggressive prefetchers,” HPCA, 2014.  <br />
M. Shevgoor et al., "Efficiently Prefetching Complex Address Patterns", MICRO, 2015. <br />
J. Kim et al., "Path Confidence based Lookahead Prefetching,” MICRO, 2016. <br />

## Virtual memory
J. Huck et al., “Architectural Support for Translation Table Management in Large Address Space Machine,” ISCA, 1993. <br />
J. Navarro et al., “Practical, Transparent Operating System Support for Superpages,” OSDI, 2002. <br />
A. Seznec, “Concurrent Support of Multiple Page Sizes on a Skewed Associative TLB,” IEEE Transactions on Computers, 2003. <br />
R. Bhargava et al., “Accelerating Two-Dimensional Page Walks for Virtualized Systems,” ASPLOS, 2008. <br />
T. W. Barr et al., “Translation Caching: Skip, Don’t Walk (the Page Table),” ISCA, 2010. <br />
B. Pichai et al., “Architectural Support for Address Translation on GPUs,” ASPLOS, 2014. <br />
J. Power et al., “Supporting x86-64 Address Translation for 100s of GPU Lanes,” HPCA, 2014. <br />

## Non-volatile memory
B. Yang et al., “A Low Power Phase-Change Random Access Memory using a DCW Scheme,” ISCAS, 2007. <br />
M. K. Qureshi et al., Scalable High Performance Main Memory System Using PCM Technologies,” ISCA, 2009. <br />
B. C. Lee et al., “Architecting Phase Change Memory as a Scalable DRAM Alternative,” ISCA, 2009. <br />
S. Cho et al., “Flip-N-write: A Simple Deterministic Technique to Improve PRAM Write Performance, Energy and Endurance,” MICRO, 2009. <br />
M. K. Qureshi et al., “Enhancing Lifetime and Security of PCM-Based Main Memory with Start-Gap Wear Leveling,” MICRO, 2009. <br />
S. Schechter et al., “Use ECP, not ECC, for Hard Failures in Resistive Memories,” ISCA, 2010. <br />
M. K. Qureshi et al., “Security Refresh,” ISCA, 2011. <br />
R. Wang et al., “SD-PCM: Constructing Reliable Super Dense Phase Change Memory under Write Disturbance,” ASPLOS, 2016. <br />
X. Liu et al., “Binary Star: Coordinated Reliability in Heterogeneous Memory Systems for High Performance and Scalability,” MICRO, 2019. <br />

## DRAM and RowHammers
Y. Kim et al., “A Case for Exploiting Subarray-Level Parallelism (SALP) in DRAM,” ISCA, 2012. <br />
Y. Kim et al., “Flipping Bits in Memory Without Accessing Them: An Experimental Study of DRAM Disturbance Errors,” ISCA, 2014. <br />
E. Lee et al., “TWiCe: Preventing Row-hammering by Exploiting Time Window Counters,” ISCA, 2019. <br />
J. S. Kim et al., “Revisiting RowHammer: An Experimental Analysis of Modern DRAM Devices and Mitigation Techniques,” ISCA, 2020. <br />

## Memor compression
D. A. Wood et al., “Frequent Pattern Compression: A Significance-Based Compression Scheme for L2 Caches,” Technical Report 1500 UW-Madison, 2004. <br />
G. Pekhimenko et al., “Base-Delta-Immediate Compression: Practical Data Compression for On-Chip Caches,” PACT, 2012. <br />
G. Pekhimenko et al., “Linearly Compressed Pages: A Low-Complexity, Low-Latency Main Memory Compression Framework,” MICRO, 2013. <br />
Y. Kim et al., “Flipping Bits in Memory Without Accessing Them: An Experimental Study of DRAM Disturbance Errors,” ISCA, 2014. <br />
E. Choukse et al., “Compresso: Pragmatic Main Memory Compression,” MICRO, 2018. <br />

## Memory security
B. Gassend et al., “Caches and Merkle Trees for Efficient Memory Authentication,” HPCA, 2003. <br />
C. Yan et al., “Improving Cost, Performance, and Security of Memory Encryption and Authentication,” ISCA, 2006. <br />
B. Rogers et al., “Using Address Independent Seed Encryption and Bonsai Merkle Trees to Make Secure Processors OS- and Performance-Friendly,” MICRO, 2007. <br />
L. Ren et al., “Design Space Exploration and Optimization of Path Oblivious RAM in Secure Processors,” ISCA, 2013. <br />
S. Gueron, “A Memory Encryption Engine Suitable for General Purpose Processors,” eprint iacr, 2016. <br />
A. Awad et al., “Silent Shredder: Zero-Cost Shredding for Secure Non-Volatile Main Memory Controllers,” ASPLOS, 2016. <br />
A. Awad et al, “Triad-NVM: Persistency for Integrity-Protected and Encrypted Non-Volatile Memories,” ISCA, 2019. <br />
K. A. Zubair et al., “Anubis: Ultra-Low Overhead and Recovery Time for Secure Non-Volatile Memories,“ ISCA, 2019. <br />
J. Zhou et al., “Lelantus: Fine-Granularity Copy-on-Write Operations for Secure Non-Volatile Memories,” ISCA, 2020. <br />

## Chiplets
D. Stow et al., “Cost Analysis and Cost-Driven IP Reuse Methodology for SoC design Based on 2.5D/3D Integration,” ICCAD, 2016. <br />
A. Arunkumar et al., “MCM-GPU: Multi-Chip-Module GPUs for Continued Performance Scalability,” ISCA, 2017.  <br />
S. Naffziger et al., “Pioneering Chiplet Technology and Design for the AMD EPYC and Ryzen Processor Families,” ISCA, 2021. <br /> 

## Disaggregation
K. Lim et al., “Disaggregated Memory for Expansion and Sharing in Blade Servers,” ISCA, 2009. <br />
J. Gu et al., “Efficient Memory Disaggregation with INFINISWAP,” USENIX NSDI, 2017. <br />
Y. Shan et al., “LegoOS: A Disseminated, Distributed OS for Hardware Resource Disaggregation,” USENIX OSDI, 2018. <br />
I. Calciu et al., “Rethinking Software Runtimes for Disaggregated Memory,” ASPLOS, 2021. <br />
S.-S. Lee et al., “MIND: In-Network Memory Management for Disaggregated Data Centers,” SOSP, 2021. <br />

## Near data processing
J. Ahn et al., A Scalable Processing-in-Memory Accelerator for Parallel Graph Processing,” ISCA, 2016. <br />
Hadi et al., “Chameleon: Versatile and Practical Near-DRAM Acceleration Architecture for Large Memory Systems,” ISCA, 2016. <br />
M. Alian et al., “Application-Transparent Near-Memory Processing Architecture with Memory Channel Network,” MICRO, 2018. <br />
M. He et al., “Newton: A DRAM-maker’s Accelerator-in-Memory (AiM) Architecture for Machine Learning,” MICRO, 2018. <br />
S. Lee et al., “Hardware Architecture and Software Stack for PIM Based on Commercial DRAM Technology : Industrial Product,” ISCA, 2021. <br />
L. Ke et al., “Near-Memory Processing in Action: Accelerating Personalized Recommendation with AxDIMM,” IEEE Micro, 2022. <br />

