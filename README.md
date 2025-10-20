# .NET Modernization with AWS Transform

This project automates the modernization of a legacy .NET Framework application using AWS Transform, an agentic AI-powered service designed to refactor and upgrade legacy codebases.

## 🚀 Overview
This script creates a workspace in AWS Transform, connects to a GitHub repository, launches a modernization job, monitors its progress, and downloads a PDF report summarizing the transformation.

## 📋 Prerequisites
- AWS CLI (latest version)
- AWS account with access to AWS Transform
- IAM permissions for:
  - `transform:*`
  - `codeconnections:*`
  - `iam:PassRole`
- GitHub repository with legacy .NET code

## ⚙️ Script Workflow
1. **Create Workspace**: Initializes a workspace named `dotnet-modernization`.
2. **Connect GitHub Repo**: Links the source repository and branch.
3. **Launch Job**: Starts a `DOTNET_MODERNIZATION` job.
4. **Monitor Job**: Tracks job status and retrieves job ID.
5. **Download Report**: Fetches a PDF report of the modernization results.

## 📂 Repository Details
- **Source Repo**: `https://github.com/sugyandas/modernize.git`
- **Source Branch**: `main`
- **Target Branch**: `modernized-dotnet`

## 📄 Output
- `modernization-report.pdf`: A detailed report of the transformation job.

## 🧪 Usage
Run the script:
```bash
chmod +x TransformScriptfor.NET.txt
./TransformScriptfor.NET.txt
```

## 📞 Support
For issues or questions, please refer to the [AWS Transform Documentation](https://docs.aws.amazon.com/transform/latest/userguide/).
