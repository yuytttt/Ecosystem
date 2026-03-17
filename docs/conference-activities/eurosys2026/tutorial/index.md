---
layout: default
title: Tutorials
parent: EuroSys 2026
grand_parent: Conference Activities
nav_order: 1
has_toc: false
permalink: /conference-activities/eurosys2026/tutorial/
---

<h1>📖 Tutorial: Systems in the Age of AI (SysAI)</h1>

<div style="background: linear-gradient(135deg, #f8f9fa 0%, #e9ecef 100%); border-left: 5px solid #28a745; padding: 25px; border-radius: 12px; margin: 25px 0 30px 0; box-shadow: 0 4px 12px rgba(40,167,69,0.1);">
    <h2 style="margin: 0 0 15px 0; color: #155724; font-size: 1.3em; font-weight: 700;">🎯 Tutorial Overview</h2>
    <p style="font-size: 1.05em; line-height: 1.7; color: #155724; margin-bottom: 15px;">
        AI workloads are rapidly reshaping system design assumptions, exposing limitations in resource management, data paths, distributed execution, and observability that were not built for large-scale, heterogeneous, and latency-sensitive AI environments. This tutorial highlights cross-layer design across kernel, runtime, and distributed layers to support AI-native workloads.
    </p>
    <p style="font-size: 1.05em; line-height: 1.7; color: #155724; margin: 0;">
        The tutorial is structured around two complementary tracks: <strong>System Operations and Optimization Acceleration in the AI Era</strong> and <strong>System and Distributed Scheduling Solutions for AI Workloads</strong>. The former focuses on heterogeneous resource management, distributed runtimes, and container-oriented data-path optimization to improve efficiency and scalability of AI execution. The latter explores how AI enhances system intelligence through observability, agent-aware scheduling, and large-model integration into system development and operational workflows.
    </p>
</div>

<div style="background-color: #f0f7ff; border-left: 5px solid #007bff; padding: 25px; border-radius: 12px; margin-bottom: 30px; display: flex; justify-content: space-between; align-items: center; flex-wrap: wrap; gap: 16px;">
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

<hr>

<h2>📘 System Operations and Optimization Acceleration in the AI Era</h2>

<!-- Card 1 -->
<div style="border: 1px solid #e1e4e8; border-radius: 12px; padding: 24px; margin-bottom: 25px; box-shadow: 0 4px 12px rgba(0,0,0,0.08); background: white;">
    <h3 style="margin-top: 0; color: #0366d6; font-size: 1.2em; font-weight: 700; margin-bottom: 10px;">TrIO - A Flattened and Cooperative I/O Mechanism for Container Environments</h3>
    <p style="color: #666; font-size: 0.95em; margin-bottom: 12px; font-weight: 600;">📅 Time: 09:00 - 09:40 AM</p>
    <div style="display: flex; gap: 20px; align-items: flex-start; flex-wrap: wrap;">
        <div style="flex: 1; min-width: 200px;">
            <p style="font-weight: bold; color: #666; margin-bottom: 8px; font-size: 0.95em;">Topic Abstract:</p>
            <p style="font-size: 0.95em; line-height: 1.6; color: #555; margin: 0;">This tutorial delves into the I/O bottleneck of container image loading and introduces a novel solution, TrIO. TrIO proposes a memory-oriented image abstraction and a runtime page cache to achieve efficient image service. TrIO is open sourced and integrated into openEuler, and published in FAST'25.</p>
        </div>
        <div style="width: 160px; flex-shrink: 0; text-align: center;">
            <img src="{{ '/assets/images/yubo.jpeg' | relative_url }}" alt="Speaker" style="width: 90px; height: 90px; border-radius: 50%; object-fit: cover; border: 3px solid #f0f0f0; display: block; margin: 0 auto 8px auto;">
            <p style="margin: 0 0 6px 0; font-weight: bold; color: #0366d6; font-size: 0.95em;">Yubo Liu</p>
            <p style="font-size: 0.82em; color: #555; line-height: 1.5; margin: 0; text-align: left;">Research scientist at Huawei. Focuses on high-performance storage, memory, and HPC systems. Published in FAST and TOS. PC member for MSST, IPDPS, NAS.</p>
        </div>
        <div style="width: 140px; flex-shrink: 0; text-align: center;">
            <p style="font-size: 0.85em; color: #999; margin-bottom: 8px; font-weight: 600;">🧩 Mystery Gift Piece</p>
            <img src="{{ '/assets/images/puzzle.jpg' | relative_url }}" style="width: 120px; height: 120px; border-radius: 12px; box-shadow: 0 4px 8px rgba(0,0,0,0.15);">
        </div>
    </div>
</div>

<!-- Card 2 -->
<div style="border: 1px solid #e1e4e8; border-radius: 12px; padding: 24px; margin-bottom: 25px; box-shadow: 0 4px 12px rgba(0,0,0,0.08); background: white;">
    <h3 style="margin-top: 0; color: #0366d6; font-size: 1.2em; font-weight: 700; margin-bottom: 10px;">EulerCopilot - Key Technologies and Practices of Intelligent Fault Diagnosis and Optimization in openEuler</h3>
    <p style="color: #666; font-size: 0.95em; margin-bottom: 12px; font-weight: 600;">📅 Time: 09:40 - 10:20 AM</p>
    <div style="display: flex; gap: 20px; align-items: flex-start; flex-wrap: wrap;">
        <div style="flex: 1; min-width: 200px;">
            <p style="font-weight: bold; color: #666; margin-bottom: 8px; font-size: 0.95em;">Topic Abstract:</p>
            <p style="font-size: 0.95em; line-height: 1.6; color: #555; margin: 0;">This tutorial introduces openEuler's intelligent O&M architecture for cloud and AI infrastructure. It focuses on key technologies for intelligent fault diagnosis and performance optimization, including multi-Agent collaboration for precise root cause analysis, multi-source data integration for adaptive system optimization, and experience-driven Agent skill evolution.</p>
        </div>
        <div style="width: 160px; flex-shrink: 0; text-align: center;">
            <img src="{{ '/assets/images/wanglei.jpg' | relative_url }}" alt="Speaker" style="width: 90px; height: 90px; border-radius: 50%; object-fit: cover; border: 3px solid #f0f0f0; display: block; margin: 0 auto 8px auto;">
            <p style="margin: 0 0 6px 0; font-weight: bold; color: #0366d6; font-size: 0.95em;">Wang Lei</p>
            <p style="font-size: 0.82em; color: #555; line-height: 1.5; margin: 0; text-align: left;">Chief architect of EulerCopilot at Huawei. Expert in LLM Agents, Serverless, and DevOps. Author of "Microservice Architecture and Practice" and other books.</p>
        </div>
        <div style="width: 140px; flex-shrink: 0; text-align: center;">
            <p style="font-size: 0.85em; color: #999; margin-bottom: 8px; font-weight: 600;">🧩 Mystery Gift Piece</p>
            <img src="{{ '/assets/images/puzzle.jpg' | relative_url }}" style="width: 120px; height: 120px; border-radius: 12px; box-shadow: 0 4px 8px rgba(0,0,0,0.15);">
        </div>
    </div>
</div>

<div style="border: 2px dashed #e1e4e8; border-radius: 12px; padding: 20px; margin-bottom: 25px; background: #fcfcfc; display: flex; align-items: center; justify-content: center;">
    <div style="text-align: center;">
        <span style="font-size: 1.2em; margin-right: 15px;">☕</span>
        <span style="font-weight: bold; color: #666; font-size: 1.1em; letter-spacing: 1px;">COFFEE BREAK / NETWORKING</span>
        <span style="margin-left: 20px; color: #0366d6; font-weight: 600; font-size: 1.1em;">🕒 10:30 - 11:00 AM</span>
    </div>
</div>

<h2>📘 System and Distributed Scheduling Solutions for AI Workloads</h2>

<!-- Card 3 -->
<div style="border: 1px solid #e1e4e8; border-radius: 12px; padding: 24px; margin-bottom: 25px; box-shadow: 0 4px 12px rgba(0,0,0,0.08); background: white;">
    <h3 style="margin-top: 0; color: #0366d6; font-size: 1.2em; font-weight: 700; margin-bottom: 10px;">LLM-LA - LLM Load-Aware Load Balancing</h3>
    <p style="color: #666; font-size: 0.95em; margin-bottom: 12px; font-weight: 600;">📅 Time: 11:00 - 11:40 AM</p>
    <div style="display: flex; gap: 20px; align-items: flex-start; flex-wrap: wrap;">
        <div style="flex: 1; min-width: 200px;">
            <p style="font-weight: bold; color: #666; margin-bottom: 8px; font-size: 0.95em;">Topic Abstract:</p>
            <p style="font-size: 0.95em; line-height: 1.6; color: #555; margin: 0;">Variability in LLM input and output token lengths leads to load imbalance in multi-instance serving systems, where short and long requests share queues and increase waiting time and tail latency. This tutorial introduces LLM-LA, a load-aware request management system for LLM workloads, explaining its design and practical deployment in serving frameworks.</p>
        </div>
        <div style="width: 160px; flex-shrink: 0; text-align: center;">
            <img src="{{ '/assets/images/saeid.jpg' | relative_url }}" alt="Speaker" style="width: 90px; height: 90px; border-radius: 50%; object-fit: cover; border: 3px solid #f0f0f0; display: block; margin: 0 auto 8px auto;">
            <p style="margin: 0 0 6px 0; font-weight: bold; color: #0366d6; font-size: 0.95em;">Saeid Ghafouri</p>
            <p style="font-size: 0.82em; color: #555; line-height: 1.5; margin: 0; text-align: left;">Research Scientist at Huawei Edinburgh. PhD from Queen Mary University of London. Focuses on LLM serving infrastructure and distributed inference systems.</p>
        </div>
        <div style="width: 140px; flex-shrink: 0; text-align: center;">
            <p style="font-size: 0.85em; color: #999; margin-bottom: 8px; font-weight: 600;">🧩 Mystery Gift Piece</p>
            <img src="{{ '/assets/images/puzzle.jpg' | relative_url }}" style="width: 120px; height: 120px; border-radius: 12px; box-shadow: 0 4px 8px rgba(0,0,0,0.15);">
        </div>
    </div>
</div>

<!-- Card 4 -->
<div style="border: 1px solid #e1e4e8; border-radius: 12px; padding: 24px; margin-bottom: 25px; box-shadow: 0 4px 12px rgba(0,0,0,0.08); background: white;">
    <h3 style="margin-top: 0; color: #0366d6; font-size: 1.2em; font-weight: 700; margin-bottom: 10px;">openYuanrong - Distributed Serverless AI Computing Engine</h3>
    <p style="color: #666; font-size: 0.95em; margin-bottom: 12px; font-weight: 600;">📅 Time: 11:40 AM - 12:20 PM</p>
    <div style="display: flex; gap: 20px; align-items: flex-start; flex-wrap: wrap;">
        <div style="flex: 1; min-width: 200px;">
            <p style="font-weight: bold; color: #666; margin-bottom: 8px; font-size: 0.95em;">Topic Abstract:</p>
            <p style="font-size: 0.95em; line-height: 1.6; color: #555; margin: 0;">This tutorial introduces openYuanrong, a Serverless distributed compute engine that unifies diverse applications, from AI and big data to microservices, on a single, streamlined architecture. It provides multi-language function interfaces that simplify the development of complex distributed applications. Powered by dynamic scheduling and efficient data sharing, openYuanrong ensures high-performance execution and maximum cluster resource utilization.</p>
        </div>
        <div style="width: 160px; flex-shrink: 0; text-align: center;">
            <img src="{{ '/assets/images/mohamed.jpg' | relative_url }}" alt="Speaker" style="width: 90px; height: 90px; border-radius: 50%; object-fit: cover; border: 3px solid #f0f0f0; display: block; margin: 0 auto 8px auto;">
            <p style="margin: 0 0 6px 0; font-weight: bold; color: #0366d6; font-size: 0.95em;">Mohamed Kassem</p>
            <p style="font-size: 0.82em; color: #555; line-height: 1.5; margin: 0; text-align: left;">Principal engineer at Huawei Edinburgh. PhD from University of Edinburgh (2020). Focuses on LLM serving engines and Agentic AI. Former CTO of a multi-million tech company.</p>
        </div>
        <div style="width: 140px; flex-shrink: 0; text-align: center;">
            <p style="font-size: 0.85em; color: #999; margin-bottom: 8px; font-weight: 600;">🧩 Mystery Gift Piece</p>
            <img src="{{ '/assets/images/puzzle.jpg' | relative_url }}" style="width: 120px; height: 120px; border-radius: 12px; box-shadow: 0 4px 8px rgba(0,0,0,0.15);">
        </div>
    </div>
</div>

<div style="background: linear-gradient(135deg, #fff8e1, #fff3cd); border: 2px solid #ffc107; border-radius: 12px; padding: 40px; margin-top: 40px; text-align: center;">
  <h2 style="color: #856404; margin-bottom: 10px; font-size: 1.5em;">🎁 Collect All Puzzle Pieces & Win a Prize!</h2>
  <p style="color: #856404; font-size: 1.05em; margin-bottom: 25px;">Attend all tutorials, collect every puzzle piece, and bring them to the registration desk to claim your reward.</p>
  <img src="{{ '/assets/images/final.PNG' | relative_url }}" alt="Prize" style="max-width: 350px; width: 100%; border-radius: 16px; box-shadow: 0 8px 24px rgba(0,0,0,0.15);">
</div>
