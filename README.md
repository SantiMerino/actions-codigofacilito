# GitHub Actions Practice Project

This repository contains examples and practices for working with GitHub Actions. It demonstrates various features and capabilities of GitHub Actions through practical examples.

## 🚀 Features

- Multiple job workflows
- Job dependencies
- Environment variables
- Artifacts handling
- Matrix strategies
- Conditional job execution
- GitHub Context usage

## 📋 Workflow Structure

The project includes several example jobs that demonstrate different GitHub Actions concepts:

1. **Deploy Practice Job**

   - Demonstrates environment variables
   - Output variables between steps
   - Basic echo commands

2. **Second Job**

   - Shows job dependencies
   - Uses outputs from previous job

3. **Third Job**

   - Conditional execution based on branch
   - Working directory operations
   - Checkout action usage

4. **Fourth Job**

   - Artifact creation
   - File generation
   - Artifact upload

5. **Fifth Job**

   - Artifact download
   - File content display

6. **Sixth Job**
   - Matrix strategy implementation
   - Version iteration

## 🔧 Usage

The workflow is triggered on pushes to the main branch. Each job demonstrates different aspects of GitHub Actions:

```yaml
on:
  push:
    branches: ["main"]
```

## 📦 Artifacts

The project demonstrates how to:

- Create artifacts
- Upload artifacts
- Download artifacts
- Use artifacts between jobs

## 🔄 Job Dependencies

Shows how to:

- Chain jobs using `needs`
- Pass data between jobs
- Ensure proper execution order

## 🎯 Matrix Strategy

Demonstrates running jobs with different configurations using matrix strategy:

```yaml
strategy:
  matrix:
    version: [1, 2, 3]
```

## 📝 Notes

- The workflow uses Ubuntu latest as the runner
- Includes examples of GitHub Context usage
- Demonstrates environment variable handling
- Shows conditional job execution

## 🔍 Learn More

For more information about GitHub Actions, visit:

- [GitHub Actions Documentation](https://docs.github.com/en/actions)
- [GitHub Actions Workflow Syntax](https://docs.github.com/en/actions/using-workflows/workflow-syntax-for-github-actions)
