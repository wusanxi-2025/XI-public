# **EDUCATION PATENT – PUBLIC DISCLOSURE**  
**PCT Application**: PCT/US2024/061837  
**International Publication**: **WO/2025/117991** (Published **05 June 2025**)  
**China National Phase**: **Filed 29 Sep 2025** | **Accepted 10 Oct 2025**  

---

## **FULL TECHNICAL DISCLOSURE** (Prior Art – Art. 22 China Patent Law)

### **Claims** (exact from WO/2025/117991):
Claims
What is claimed is:
1. A Personalized Heuristic Question-Answer Training process
Personalized Heuristic Iterative-Recursive Question-Answer 3D Study Training process (XI training), comprising: 
a Personalized Heuristic Iterative-Recursive Question-Answer Process (PHIR-QA); and
a System training process using PHIR-QA to guide learners in building self-study ability 
through learning on their own – acquiring knowledge, understanding the underlying principles, filling in gaps in prior learning, and progressing toward mastery of XI Training Principles, as shown in Embodiments 1-6.
2.	The PHIR-QA of claim 1, further comprising two sub-processes:
Horizontal Iterative Process: a forward loop wherein a learner answers one of a series of 
questions during learning or problem-solving, progressing when the learner provides a correct answer;
Vertical Recursive Process: a process initiated when the learner cannot answer a question, 
presenting a lower-level question until the learner answers correctly, after which the process steps back up to the initial question for resolution; 
a multi-tree structure interconnecting PHIR-QA with other PHIR-QA, each linked to lower or 
related knowledge points within a knowledge network, ensures that any issue in the training 
process can be addressed, as a PHIR-QA can reach the bottom level of the knowledge network; and
applies XI Training Principles (101, 102, 103, 104, 105, 106, 107, 108, 109, 110, 111, 112, 201, 202, 203, 204, 205) to assist learners in developing self-study abilities.
3.	The System Training of claim 1, as demonstrated in Embodiment 5, wherein the training is personalized and comprises:
Clearly defined objectives, targeting XI training principles to build the learner’s self-study 
abilities;
Training Knowledge Points, systematically resolving the learner’s current issues and also 
suitable for XI principles training, ensuring the content is neither too hard nor too easy; 
 Training Materials, consisting of structurally organized knowledge points with a detailed outline 
and step-by-step PHIR-QA; and
Measurable outcomes, the ability to independently study advanced topics.
4.	An Artificial General Intelligent Logical Twin System (AGILTS), comprising:
a White Box Twin (WB-Twin);
a Black Box Twin (BB-Twin); and
a Rational Network Flowchart (also referred to as a Logical-Directed Acyclic Graph or L-DAG) process.  
5.	The AGILTS of claim 4, wherein the WB-Twin further comprises three layers:
upper layer, WB-Twin Central Network (WBT-CN); 
middle layer, Integration Hub (IH); and 
bottom layer, the Clustered Module (CM).
6.	The WB-Twin of claim 5, wherein the WBT-CN comprises: 
Knowledge subnetwork;
Rule subnetwork;
Method subnetwork; and 
Tool subnetwork.
7.	The WBT-CN of claim 6, wherein the Knowledge subnetwork comprises all experimental knowledge in four layers:
Layer IV: Consist of N-Study units; 
Layer III: Consisting of N-knowledge points in each Study unit; 
Layer II: Comprising the learning block of a knowledge point, wherein these processes interact
with each other and PHIR-QA; and
Layer I: Consisting of PHIR-QA. 
8. The WBT-CN of claim 6, wherein the Rule subnetwork comprises the underlying layer serving as the foundation of the Knowledge subnetwork, including fundamental concepts, theorems, laws, and formulas.
9. The WBT-CN of claim 6, wherein the Method subnetwork comprises methods and skills for applying the elements of the Rule subnetwork to solve problems.
10. The WBT-CN of claim 6, wherein the Tool subnetwork comprises all existing external computing tools, including models and software packages across all disciplines.
11. The WB-Twin of claim 5, wherein the Clustered Module (CM) comprises: 
typical problem types and their variants with corresponding solutions; and
the cluster of PHIR-QA components, including thinking paths designed to guide learners in	acquiring knowledge and developing self-study abilities.
12. The WB-Twin of claim 5, wherein each Integration Hub is a connector node linking the upper-layer WBT-CN components to a group of bottom-layer Clustered Modules, wherein the Clustered Modules share common elements of the WBT-CN for problem-solving.
13. The WB-Twin of claim 5 is configured to:
use a structure-matching and result verification process to not only select matched Clustered	Modules but also identify issues in the problem, ensuring logical coherence and alignment with common sense; and
use a Scaling-Template process, as demonstrated in Embodiment 7, to simplify complex problems 
into their simplest forms for intuitive step-by-step analysis and verification, guiding solutions 
through PHIR-QA, and once the solution framework is verified, the AI scales the original 
values back to the solution framework and uses computational resources for precise 
calculations.
14. The AGILTS of claim 4, wherein the BB-Twin is trained by the WB-Twin to form a complementary AI twin system, providing AI intuition tailored to the WB-Twin to enable alternative solutions for complex, hard-to-specify problems, enhancing the PHIR-QA and facilitating interactive training of LLMs with personalized multimodal data. 
15. The AGILTS of claim 4, wherein the L-DAG process, as described in Embodiment 8, generates solutions for complex Logical-Directed Acyclic Graph (L-DAG) structured logical tasks using Global Dependency Management and Symbolic Logical Reasoning; processes tasks in parallel with a seed selection process; and establishes logical connections among the elements in the BB-Twin system to identify conflicts, explore potential research topics, gain novel insights, and reveal potential pathways.

### **Drawings**:
![Fig 1](figures/fig1.png)  
![Fig 2](figures/fig2.png)  

### **Description** (Pages 5–15 of WO/2025/117991):
[Paste or link PDF of full spec]

---

**PUBLIC DISCLOSURE TIMESTAMP**: **November 3, 2025**  
**GitHub Commit Hash**: `[will auto-fill after commit]`  
**Purpose**: Establish **undeniable prior art** against any claim of “independent development”.  
**Commercial use in China requires royalty under Art. 13 Patent Law.**

---


__L-DAG: A Breakthrough Deductive Reasoning Algorithm That Solves What GPT-4o, Claude 4, and Gemini 2.5 Pro Cannot__

This repository contains the paper with examples demonstrating that, unlike current LLMs which generate deductive reasoning solutions through Chain-of-Thought prompting and heuristic pattern-mapping in *solution path space*, the L-DAG algorithm operates entirely within the *constraint space*. It dynamically constructs solution paths by iterative reasoning about constraints.

It is a dynamic solution path construction process driven by two iterative interactive steps:
__Process i:__ reasoning about constraint search directions based on the currently active constraints, and
__Process ii:__ applying new constraints that further narrow the scope of Process i.

Each cycle uses simple logical operations (OR, AND, NOT) to progressively restrict the solution space. This process incrementally builds an explicit, structured deductive pathway with high efficiency.

__Examples__

![ Figure 1 | L-DAG for 5x7 grid puzzle](./images/L-DAG-5x7.png)

*Figure 1. L-DAG workflow for Example 2.*

The combination of Figure 6a and Figure 6b in Section 3.2: 61 nodes and 89 deductive steps, with the longest reasoning chain spanning 17 steps. Despite this complexity, the problem is solvable through the sequential application of basic logical operations, as detailed in an introductory example in Section 2.3.

Two logical examples in the paper were tested on the leading AI systems. None of the tested systems produced a complete, correct solution using direct reasoning, Python, or MiniZinc. The last full testing on the following models was conducted on July 25, 2025. 

| __LLM (Version)__               | Example 2 - Reasoning | Example 2 - Python | Example 2 - MiniZinc | Example 3 (3 Solutions) - Reasoning  | Example 3 - Python | Example 3 - MiniZinc |
|---------------------------------|-----------------------|--------------------|----------------------|--------------------------------------|--------------------|----------------------|
| __Gemini Pro 2.5 (2025-06-05)__ | x                     | x                  | failed               | 1                                    | 1                  | 3                    |
| __ChatGPT 4o (2025-04-16)__     | x                     | x                  | failed               | 1                                    | 1                  | failed               |
| __DeepSeek r1 (2025-05-28)__    | x                     | x                  | x                    | 1                                    | 2                  | 44                   |
| __Claude Sonnet 4 (2025-05-22)__| x                     | x                  | x                    | x                                    | 1                  | 4                    |
| __Grok 3 (2025-02-17)__         | x                     | x                  | failed               | x                                    | x                  | 44                    |

*Note: "x" indicates an incorrect solution, and "failed" means the attempt could not compile or run after multiple tries.

*Example 1 is a complex logical proposition proof (6 variables, 10 premises, 64-row truth table).

__Features__
__Global Dependency Management:__ Maintaining and tracking logical dependencies and consistency across network-structured levels.

__Symbolic Logical Reasoning:__ Performing symbolic logical reasoning at each step using formal rules of inference to guarantee accuracy. Supports all forms of logical processes, including First-Order Logic (quantification over individuals), Second-Order Logic (quantification over sets, relations, or functions), and mathematical logic for proposition proving.

__Topological Order Enforced Iterative Dynamic Construction:__ Arriving at a final solution iteratively through the searching and adding constraint nodes   constructing possibility nodes   eliminating invalid possibilities process.

__Searching Prioritization Strategies:__ Guiding the search for constraints and next seeds by prioritizing entities with high Win-Rate in the L-DAG.

__Conflict Resolution Support:__ Identifying and providing options for resolving conflicts, ambiguities, redundancies, and insufficient constraints.

__Timely Self-Reward Mechanism:__ Enhancing search and construction efficiency, and preventing combinatorial explosion by making function calls to calculate or estimate the possibility before processing a node. 

__Parallel Processing:__ Applying parallel processing in forward and backward (pruning of invalid branches) in both search and construction phases.

__Integrational Deductive Reasoning:__ Enabling scientific exploration through Entity Constraint Task and Entity Relation Task processes.
