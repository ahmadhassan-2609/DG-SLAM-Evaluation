# DG-SLAM Evaluation

This repository contains evaluation scripts and test logs for our empirical evaluation of [DG-SLAM](https://github.com/fudan-zvg/DG-SLAM) (NeurIPS 2024).

## Purpose

This repository documents our testing and evaluation of the DG-SLAM paper for EECE 5550 Mobile Robotics at Northeastern University. It contains:
- Test scripts we developed
- Execution logs as proof of our experiments
- Configuration files for different test scenarios

**Note:** This is not a standalone implementation. To reproduce our experiments, you need to first set up the original [DG-SLAM repository](https://github.com/fudan-zvg/DG-SLAM).

## Repository Contents

### `/experiments/`
- `baseline/` - Scripts for testing without semantic segmentation
- `robustness/` - Frame-skipping stress tests  
- `semantic/` - YOLO-based semantic mask generation and testing

### `/results/`
- `/logs/` - Terminal output from our test runs
- Test execution timestamps and performance logs

## Team

- Ahmad Hassan
- Raphael Dias
- Mir Munavvar Ali

Course: EECE 5550 Mobile Robotics, Fall 2025

## Reference

Original paper:
> DG-SLAM: Robust Dynamic Gaussian Splatting SLAM with Hybrid Pose Optimization  
> Xu et al., NeurIPS 2024  
> [arXiv:2411.08373](https://arxiv.org/abs/2411.08373)
