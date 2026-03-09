---
layout: default
title: Tutorials
parent: EuroSys 2026
grand_parent: Conference Activities
nav_order: 1
has_toc: false
permalink: /conference-activities/eurosys2026/tutorial/
---

<h1 style="white-space: nowrap;">📖 Tutorial: Systems in the Age of AI (SAA)</h1>

<div style="min-width: 900px;">
<div style="background: linear-gradient(135deg, #f8f9fa 0%, #e9ecef 100%); border-left: 5px solid #28a745; padding: 25px; border-radius: 12px; margin: 25px 0 30px 0; box-shadow: 0 4px 12px rgba(40,167,69,0.1);">
    <h2 style="margin: 0 0 15px 0; color: #155724; font-size: 1.3em; font-weight: 700;">🎯 Tutorial Overview</h2>
    <p style="font-size: 1.05em; line-height: 1.7; color: #155724; margin-bottom: 15px;">
        AI workloads are rapidly reshaping system design assumptions, exposing limitations in resource management, data paths, distributed execution, and observability that were not built for large-scale, heterogeneous, and latency-sensitive AI environments. This tutorial highlights cross-layer design across kernel, runtime, and distributed layers to support AI-native workloads.
    </p>
    <p style="font-size: 1.05em; line-height: 1.7; color: #155724; margin: 0;">
        The tutorial is structured around two complementary tracks: <strong>System Operations and Optimization Acceleration in the AI Era</strong> and <strong>System and Distributed Scheduling Solutions for AI Workloads</strong>. The former focuses on heterogeneous resource management, distributed runtimes, and container-oriented data-path optimization to improve efficiency and scalability of AI execution. The latter explores how AI enhances system intelligence through observability, agent-aware scheduling, and large-model integration into system development and operational workflows.
    </p>
</div>
</div>

<div style="min-width: 900px;">
<div style="background-color: #f0f7ff; border-left: 5px solid #007bff; padding: 25px; border-radius: 12px; margin-bottom: 30px; display: flex; justify-content: space-between; align-items: center;">
    <div>
        <p style="margin: 0; font-weight: bold; color: #555; font-size: 0.9em;">📅 EVENT DATE & TIME</p>
        <p style="margin: 8px 0 0 0; font-size: 1.1em; font-weight: 600;">April 27, 2026</p>
    </div>
    <div>
        <p style="margin: 0; font-weight: bold; color: #555; font-size: 0.9em;">📍 VENUE</p>
        <p style="margin: 8px 0 0 0; font-size: 1.1em; font-weight: 600;">Edinburgh, Scotland</p>
    </div>
    <a href="https://datalink-de.gtsdata.huawei.com/datalinkpro/web/#/openFormFill?hashcode=xffJzl8q0Kyxxm0NZdfEOoW65nZOEaNQgzcTPEFWza8=" style="background-color: #007bff; color: white; padding: 12px 24px; border-radius: 8px; text-decoration: none; font-weight: bold; font-size: 1em;">Register Now</a>
</div>
</div>

---
<h2 style="white-space: nowrap;">📘 System Operations and Optimization Acceleration in the AI Era</h2>


<div style="border: 1px solid #e1e4e8; border-radius: 12px; padding: 30px; margin-bottom: 25px; box-shadow: 0 4px 12px rgba(0,0,0,0.08); display: flex; gap: 30px; align-items: stretch; background: white; min-width: 900px;">
    <div style="flex: 2.5; min-width: 0;">
        <h3 style="margin-top: 0; color: #0366d6; font-size: 1.35em; font-weight: 700; margin-bottom: 15px;">TrIO - A Flattened and Cooperative I/O Mechanism for Container Environments</h3>
        <p style="color: #666; font-size: 1em; margin-bottom: 15px; font-weight: 600;">📅 Time: 2:00 - 2:40 PM</p>
        <p style="font-weight: bold; color: #666; margin-bottom: 8px; font-size: 1em;">Topic Abstract:</p>
        <p style="font-size: 1.05em; line-height: 1.6; color: #555;">This tutorial delves into the I/O bottleneck of container image loading and introduces a novel solution, TrIO. TrIO proposes a memory-oriented image abstraction and a runtime page cache to achieve efficient image service. TrIO is open sourced and integrated into openEuler, and published in FAST'25.</p>
    </div>
    <div style="flex: 1.5; text-align: center; border-left: 1px solid #eee; padding-left: 30px; min-width: 350px; display: flex; flex-direction: column; align-items: center; justify-content: flex-start;">
        <img src="{{ '/assets/images/yubo.jpeg' | relative_url }}" alt="Speaker" style="width: 130px; height: 130px; border-radius: 50%; object-fit: cover; border: 3px solid #f0f0f0;">
        <p style="margin: 15px 0 8px 0; font-weight: bold; color: #0366d6; font-size: 1.1em;">Yubo Liu</p>
        <p style="font-size: 0.92em; color: #555; line-height: 1.6; text-align: left; width: 100%;">
            Dr. Yubo Liu is a research scientist at Huawei. His research focuses on building high-performance storage, memory, and HPC systems. He has many publications in top conferences/journals like FAST and TOS. He served as a PC member and reviewer for several flagship conferences in multiple fields, including MSST, IPDPS, NAS, etc.
        </p>
        <div style="margin-top: 15px; text-align: center; border-top: 1px dashed #eee; padding-top: 15px;">
            <p style="font-size: 0.95em; color: #999; margin-bottom: 8px; font-weight: 600;">🧩 Mystery Gift Piece</p>
            <img src="{{ '/assets/images/puzzle.jpg' | relative_url }}" style="width: 200px; height: 200px; border-radius: 12px; box-shadow: 0 4px 8px rgba(0,0,0,0.2);">
        </div>
    </div>
</div>


<div style="border: 1px solid #e1e4e8; border-radius: 12px; padding: 30px; margin-bottom: 25px; box-shadow: 0 4px 12px rgba(0,0,0,0.08); display: flex; gap: 30px; align-items: stretch; background: white; min-width: 900px;">
    <div style="flex: 2.5; min-width: 0;">
        <h3 style="margin-top: 0; color: #0366d6; font-size: 1.35em; font-weight: 700; margin-bottom: 15px;">EulerCopilot: Key Technologies and Practices of Intelligent Fault Diagnosis and Optimization in openEuler</h3>
        <p style="color: #666; font-size: 1em; margin-bottom: 15px; font-weight: 600;">📅 Time: 2:40 - 3:20 PM</p>
        <p style="font-weight: bold; color: #666; margin-bottom: 8px; font-size: 1em;">Topic Abstract:</p>
        <p style="font-size: 1.05em; line-height: 1.6; color: #555;">With the rapid growth of cloud computing and AI infrastructure, operating systems need to support diverse workloads such as SuperPoDs and AI training and inference, significantly increasing the complexity of operations and maintenance (O&M). Traditional O&M models face significant challenges in fault localization efficiency, system observability, and performance optimization capabilities. How to leverage data-driven and AI technologies to enhance diagnostic and optimization capabilities is becoming an important research direction in the field of system software. As a critical open-source operating system for enterprise and AI infrastructure, openEuler is building a systematic technical architecture for intelligent O&M. This session will systematically introduce the key technologies of openEuler in intelligent fault diagnosis and performance optimization, including precise root cause analysis through multi-Agent collaboration, adaptive system optimization by integrating multi-source data, and the generation and self-evolution of Agent Skills based on O&M experience. These technologies will be demonstrated through their core capabilities in intelligent fault diagnosis and system optimization.</p>
    </div>
    <div style="flex: 1.5; text-align: center; border-left: 1px solid #eee; padding-left: 30px; min-width: 350px; display: flex; flex-direction: column; align-items: center; justify-content: flex-start;">
        <img src="{{ '/assets/images/wanglei.jpg' | relative_url }}" alt="Speaker" style="width: 130px; height: 130px; border-radius: 50%; object-fit: cover; border: 3px solid #f0f0f0;">
        <p style="margin: 15px 0 8px 0; font-weight: bold; color: #0366d6; font-size: 1.1em;">Wang Lei</p>
        <p style="font-size: 0.92em; color: #555; line-height: 1.6; text-align: left; width: 100%;">
            Chief architect of EulerCopilot, expert in foundational software architecture and systems engineering at Huawei. He has extensive practical experience in the fields of LLM Agents, Serverless, and DevOps, and is the author of several books, including "Microservice Architecture and Practice", "Core Technologies and Practices of Huawei Serverless" and "A Practical Guide to DevOps".
        </p>
        <div style="margin-top: 15px; text-align: center; border-top: 1px dashed #eee; padding-top: 15px;">
            <p style="font-size: 0.95em; color: #999; margin-bottom: 8px; font-weight: 600;">🧩 Mystery Gift Piece</p>
            <img src="{{ '/assets/images/puzzle.jpg' | relative_url }}" style="width: 200px; height: 200px; border-radius: 12px; box-shadow: 0 4px 8px rgba(0,0,0,0.2);">
        </div>
    </div>
</div>


<div style="min-width: 900px;">
<div style="border: 2px dashed #e1e4e8; border-radius: 12px; padding: 20px; margin-bottom: 25px; background: #fcfcfc; display: flex; align-items: center; justify-content: center; min-width: 900px;">
    <div style="text-align: center;">
        <span style="font-size: 1.2em; margin-right: 15px;">☕</span>
        <span style="font-weight: bold; color: #666; font-size: 1.1em; letter-spacing: 1px;">COFFEE BREAK / NETWORKING</span>
        <span style="margin-left: 20px; color: #0366d6; font-weight: 600; font-size: 1.1em;">🕒 3:30 - 4:00 PM</span>
    </div>
</div>
</div>

<h2 style="white-space: nowrap;">📘 System and Distributed Scheduling Solutions for AI Workloads</h2>
<div style="border: 1px solid #e1e4e8; border-radius: 12px; padding: 30px; margin-bottom: 25px; box-shadow: 0 4px 12px rgba(0,0,0,0.08); display: flex; gap: 30px; align-items: stretch; background: white; min-width: 900px;">
    <div style="flex: 2.5; min-width: 0;">
        <h3 style="margin-top: 0; color: #0366d6; font-size: 1.35em; font-weight: 700; margin-bottom: 15px;">LLM-LA: LLM Load-Aware Load Balancing</h3>
        <p style="color: #666; font-size: 1em; margin-bottom: 15px; font-weight: 600;">📅 Time: 4:00 - 4:40 PM</p>
        <p style="font-weight: bold; color: #666; margin-bottom: 8px; font-size: 1em;">Topic Abstract:</p>
        <p style="font-size: 1.05em; line-height: 1.6; color: #555;">Variability in LLM input and output token lengths leads to load imbalance in multi-instance serving systems, where short and long requests share queues and increase waiting time and tail latency. This tutorial introduces LLM-LA, a load-aware request management system for LLM workloads, and explains its design and practical deployment in serving frameworks to mitigate imbalance and improve efficiency, targeting practitioners working on multi-instance LLM deployment, request scheduling, and load balancing, with basic familiarity in LLM containerization and serving frameworks assumed.</p>
    </div>
    <div style="flex: 1.5; text-align: center; border-left: 1px solid #eee; padding-left: 30px; min-width: 350px; display: flex; flex-direction: column; align-items: center; justify-content: flex-start;">
        <img src="{{ '/assets/images/saeid.jpg' | relative_url }}" alt="Speaker" style="width: 130px; height: 130px; border-radius: 50%; object-fit: cover; border: 3px solid #f0f0f0;">
        <p style="margin: 15px 0 8px 0; font-weight: bold; color: #0366d6; font-size: 1.1em;">Saeid Ghafouri</p>
        <p style="font-size: 0.92em; color: #555; line-height: 1.6; text-align: left; width: 100%;">
            Saeid Ghafouri is a machine learning systems researcher focusing on scalable AI inference infrastructure and the deployment of machine learning models in distributed cloud environments. He received his PhD in Computer Science from Queen Mary University of London and is currently a Research Scientist at Huawei Technologies R&D in Edinburgh, where he works on optimizing large language model (LLM) serving infrastructure and distributed inference systems. His research interests include ML inference systems, Kubernetes-based resource management, and efficient deployment of deep learning models on distributed platforms.
        </p>
        <div style="margin-top: 15px; text-align: center; border-top: 1px dashed #eee; padding-top: 15px;">
            <p style="font-size: 0.95em; color: #999; margin-bottom: 8px; font-weight: 600;">🧩 Mystery Gift Piece</p>
            <img src="{{ '/assets/images/puzzle.jpg' | relative_url }}" style="width: 200px; height: 200px; border-radius: 12px; box-shadow: 0 4px 8px rgba(0,0,0,0.2);">
        </div>
    </div>
</div>

<div style="border: 1px solid #e1e4e8; border-radius: 12px; padding: 30px; margin-bottom: 25px; box-shadow: 0 4px 12px rgba(0,0,0,0.08); display: flex; gap: 30px; align-items: stretch; background: white; min-width: 900px;">
    <div style="flex: 2.5; min-width: 0;">
        <h3 style="margin-top: 0; color: #0366d6; font-size: 1.35em; font-weight: 700; margin-bottom: 15px;">Distributed Serverless AI Computing Engine</h3>
        <p style="color: #666; font-size: 1em; margin-bottom: 15px; font-weight: 600;">📅 Time: 4:40 - 5:20 PM</p>
        <p style="font-weight: bold; color: #666; margin-bottom: 8px; font-size: 1em;">Topic Abstract:</p>
        <p style="font-size: 1.05em; line-height: 1.6; color: #555;">TBD</p>
    </div>
    <div style="flex: 1.5; text-align: center; border-left: 1px solid #eee; padding-left: 30px; min-width: 350px; display: flex; flex-direction: column; align-items: center; justify-content: flex-start;">
        <img src="{{ '/assets/images/mohamed.jpg' | relative_url }}" alt="Speaker" style="width: 130px; height: 130px; border-radius: 50%; object-fit: cover; border: 3px solid #f0f0f0;">
        <p style="margin: 15px 0 8px 0; font-weight: bold; color: #0366d6; font-size: 1.1em;">Mohamed Kassem</p>
        <p style="font-size: 0.92em; color: #555; line-height: 1.6; text-align: left; width: 100%;">
            Mohamed is currently a principal engineer and TL for the Serverless AI team at Huawei Edinburgh Research Centre. He earned his PhD in Informatics from The University of Edinburgh in 2020. His research focuses on LLM serving engines, Agentic AI and networking for AI including congestion control for distributed training jobs. Before joining Huawei, Mohamed served as postdoctoral researcher at both The University of Edinburgh and the University of Surrey. Mohamed also served as CTO of a multi-million tech company for 2 years. 
        </p>
        <div style="margin-top: 15px; text-align: center; border-top: 1px dashed #eee; padding-top: 15px;">
            <p style="font-size: 0.95em; color: #999; margin-bottom: 8px; font-weight: 600;">🧩 Mystery Gift Piece</p>
            <img src="{{ '/assets/images/puzzle.jpg' | relative_url }}" style="width: 200px; height: 200px; border-radius: 12px; box-shadow: 0 4px 8px rgba(0,0,0,0.2);">
        </div>
    </div>
</div>


<div style="min-width: 900px;">
<div style="background: linear-gradient(135deg, #fff8e1, #fff3cd); border: 2px solid #ffc107; border-radius: 12px; padding: 40px; margin-top: 40px; text-align: center;">
  <h2 style="color: #856404; margin-bottom: 10px; font-size: 1.5em;">🎁 Collect All Puzzle Pieces & Win a Prize!</h2>
  <p style="color: #856404; font-size: 1.05em; margin-bottom: 25px;">Attend all tutorials, collect every puzzle piece, and bring them to the registration desk to claim your reward.</p>
  <img src="{{ '/assets/images/final.PNG' | relative_url }}" alt="Prize" style="max-width: 350px; width: 100%; border-radius: 16px; box-shadow: 0 8px 24px rgba(0,0,0,0.15);">
</div>
</div>
