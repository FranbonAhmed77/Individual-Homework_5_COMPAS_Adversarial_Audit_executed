# Individual-Homework_5_COMPAS_Adversarial_Audit_executed

# Homework 5: COMPAS Adversarial ML Audit

This folder contains my Homework 5 submission for DNSC 6330: Responsible Machine Learning.

## Files

- `Individual_Homework_5_COMPAS_Adversarial_Audit_executed.ipynb`
- `Homework_5_Written_Report.pdf`
- Individual_homework_01_05_(Merged).ipynb

## Overview

This notebook audits adversarial risks in the COMPAS model pipeline. It evaluates:

- PGD evasion attacks across different epsilon values
- racial false positive rates and adverse impact ratio under attack
- label-flip poisoning targeting different racial groups
- AUC and AIR degradation under poisoning
- stealth-zone behavior where fairness changes while AUC remains stable
- membership inference risk using shadow-model analysis
- the relationship between generalization gap and membership inference risk

## Written Report

The written report summarizes the main experimental findings and provides a governance recommendation. It identifies the highest-risk finding, proposes proactive and reactive mitigations, and discusses the tradeoffs introduced by those mitigations.

## Purpose

The goal is to connect adversarial ML metrics to high-stakes deployment decisions. The notebook and report explain not only what the attacks do, but also what the results imply for model selection, fairness monitoring, privacy, and governance.

## How to Run

Open the notebook in Google Colab or Jupyter and run all cells from top to bottom.
