---
title: "QRTLib"
date: 2025-11-23
description: "QRTlib: A Library for Fast Quantum Real Transforms"
tags: ["Quantum Computing", "Library", "Research"]
featured: true
layout: "simple"
---

<div style="display: flex; gap: 0.5rem; margin-bottom: 2rem; flex-wrap: wrap;">
  <span style="background-color: #e5e5e5; color: #333; font-size: 0.75rem; font-weight: bold; padding: 0.2rem 0.6rem; border-radius: 0.25rem;">Python</span>
  <span style="background-color: #6929c4; color: #fff; font-size: 0.75rem; font-weight: bold; padding: 0.2rem 0.6rem; border-radius: 0.25rem;">Qiskit</span>
  <span style="background-color: #e5e5e5; color: #333; font-size: 0.75rem; font-weight: bold; padding: 0.2rem 0.6rem; border-radius: 0.25rem;">Algèbre linéaire</span>
  <span style="background-color: #3b82f6; color: #fff; font-size: 0.75rem; font-weight: bold; padding: 0.2rem 0.6rem; border-radius: 0.25rem;">arXiv:2510.16625</span>
</div>

<p style="font-size: 1.1rem; line-height: 1.8; margin-bottom: 2rem; opacity: 0.9;">
  Real-valued transforms such as the discrete cosine, sine, and Hartley transforms play a central role in classical computing, complementing the Fourier transform in applications from signal processing to data compression. <strong>QRTLib</strong> addresses the gap in quantum computing by providing a unified framework for implementing these transforms efficiently on quantum hardware.
</p>

<style>
  .project-grid {
    display: grid;
    grid-template-columns: 1fr;
    gap: 1rem;
    margin-bottom: 2rem;
  }
  @media (min-width: 768px) {
    .project-grid {
      grid-template-columns: 1fr 1fr; /* 2 Columns on tablet/desktop */
    }
  }
  .feature-card {
    padding: 1.5rem;
    border-radius: 0.75rem;
    background-color: rgba(128, 128, 128, 0.05);
    border: 1px solid rgba(128, 128, 128, 0.1);
    transition: transform 0.2s ease;
  }
  .feature-card:hover {
    transform: translateY(-3px);
    border-color: #3b82f6;
  }
  .feature-title {
    font-weight: bold;
    margin-bottom: 0.5rem;
    display: flex;
    align-items: center;
    color: #3b82f6;
  }
  .feature-icon {
    width: 1.25rem;
    height: 1.25rem;
    margin-right: 0.5rem;
  }
  .feature-text {
    font-size: 0.9rem;
    opacity: 0.8;
    line-height: 1.5;
  }
</style>

<div class="project-grid">

  <div class="feature-card">
    <div class="feature-title">
      <svg class="feature-icon" xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke="currentColor"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M9 19v-6a2 2 0 00-2-2H5a2 2 0 00-2 2v6a2 2 0 002 2h2a2 2 0 002-2zm0 0V9a2 2 0 012-2h2a2 2 0 012 2v10m-6 0a2 2 0 002 2h2a2 2 0 002-2m0 0V5a2 2 0 012-2h2a2 2 0 012 2v14a2 2 0 01-2 2h-2a2 2 0 01-2-2z" /></svg>
      Unified Framework
    </div>
    <div class="feature-text">
      The first complete implementation of Quantum Hartley, Cosine, and Sine transforms of various types within a single library.
    </div>
  </div>

  <div class="feature-card">
    <div class="feature-title">
      <svg class="feature-icon" xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke="currentColor"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M13 10V3L4 14h7v7l9-11h-7z" /></svg>
      LCU Technique
    </div>
    <div class="feature-text">
      Introduces a quantum Hartley transform based on <em>Linear Combination of Unitaries</em>, achieving a reduction in circuit size compared to prior methods.
    </div>
  </div>

  <div class="feature-card">
    <div class="feature-title">
      <svg class="feature-icon" xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke="currentColor"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M9 3v2m6-2v2M9 19v2m6-2v2M5 9H3m2 6H3m18-6h-2m2 6h-2M7 19h10a2 2 0 002-2V7a2 2 0 00-2-2H7a2 2 0 00-2 2v10a2 2 0 002 2zM9 9h6v6H9V9z" /></svg>
      Circuit Optimization
    </div>
    <div class="feature-text">
      Novel optimization strategies including two's-complement arithmetic and or-tree constructions to remove large multi-controlled operations.
    </div>
  </div>

  <div class="feature-card">
    <div class="feature-title">
      <svg class="feature-icon" xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke="currentColor"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M10 20l4-16m4 4l4 4-4 4M6 16l-4-4 4-4" /></svg>
      Native Qiskit Support
    </div>
    <div class="feature-text">
      Built directly for the Qiskit ecosystem, making it easy for researchers and developers to integrate real transforms into their existing quantum algorithms.
    </div>
  </div>

</div>

<div style="text-align: center; margin-top: 3rem;">
  <a href="https://arxiv.org/abs/2510.16625" target="_blank" style="background-color: #3b82f6; color: white; padding: 0.75rem 1.5rem; border-radius: 0.5rem; text-decoration: none; font-weight: bold; display: inline-flex; align-items: center; transition: background-color 0.2s;">
    <svg style="width: 1.2rem; height: 1.2rem; margin-right: 0.5rem;" fill="none" viewBox="0 0 24 24" stroke="currentColor"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M12 6.253v13m0-13C10.832 5.477 9.246 5 7.5 5S4.168 5.477 3 6.253v13C4.168 18.477 5.754 18 7.5 18s3.332.477 4.5 1.253m0-13C13.168 5.477 14.754 5 16.5 5c1.747 0 3.332.477 4.5 1.253v13C19.832 18.477 18.247 18 16.5 18c-1.746 0-3.332.477-4.5 1.253" /></svg>
    Lire l'article complet sur arXiv
  </a>
</div>