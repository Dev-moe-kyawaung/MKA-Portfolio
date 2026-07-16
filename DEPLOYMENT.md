# Deployment Guide

This guide will help you deploy your portfolio to GitHub Pages and other hosting platforms.

## 📦 GitHub Pages Deployment

### Method 1: Direct Push (Recommended)

1. **Create GitHub Repository**
   ```bash
   # Create new repo on GitHub first, then:
   git init
   git add .
   git commit -m "Initial commit"
   git branch -M main
   git remote add origin https://github.com/YOUR_USERNAME/YOUR_REPO_NAME.git
   git push -u origin main
   
