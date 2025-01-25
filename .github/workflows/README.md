# 🚀 Flash User Live Tracker Exhibitor

## Workflow Status

![Workflow Badges](https://github.com/FlashUSDTSenderSoftware/Flash-USDT-Sender-Bot/actions/workflows/main.yml/badge.svg)

### Badge Details
- **Branch Protection**: [![Branch Protection](https://github.com/FlashUSDTSenderSoftware/Flash-USDT-Sender-Bot/actions/workflows/main.yml/badge.svg?event=branch_protection_rule)](https://github.com/FlashUSDTSenderSoftware/Flash-USDT-Sender-Bot/actions/workflows/main.yml)
- **Fork Status**: [![Fork Status](https://github.com/FlashUSDTSenderSoftware/Flash-USDT-Sender-Bot/actions/workflows/main.yml/badge.svg?event=fork)](https://github.com/FlashUSDTSenderSoftware/Flash-USDT-Sender-Bot/actions/workflows/main.yml)
- **Workflow Status**: [![Workflow Status](https://github.com/FlashUSDTSenderSoftware/Flash-USDT-Sender-Bot/actions/workflows/main.yml/badge.svg?event=status)](https://github.com/FlashUSDTSenderSoftware/Flash-USDT-Sender-Bot/actions/workflows/main.yml)
- **Push Event**: [![Push Event](https://github.com/FlashUSDTSenderSoftware/Flash-USDT-Sender-Bot/actions/workflows/main.yml/badge.svg?event=push)](https://github.com/FlashUSDTSenderSoftware/Flash-USDT-Sender-Bot/actions/workflows/main.yml)

## 🌐 Workflow Overview

### Automated User Tracking System

Our GitHub Actions workflow provides an advanced, automated user log generation and tracking system with the following key features:

#### 🔍 Key Capabilities
- **Automated User Generation**: Fetches 30 random US-based users every 30 minutes
- **Detailed Logging**: Creates comprehensive user log files
- **Branch Management**: Automatically creates and manages feature branches
- **Pull Request Generation**: Automatically creates pull requests for new logs
- **Old Branch Cleanup**: Removes branches older than 7 days

### Workflow Trigger Mechanisms

1. **Scheduled Runs**: Every 30 minutes
2. **Manual Dispatch**: Can be triggered manually via GitHub Actions interface

## 🛠 Workflow Components

### Main Job: User Log Generation
- **Platform**: Ubuntu Latest
- **Python Version**: 3.9
- **Key Steps**:
  1. Repository Checkout
  2. Git Configuration
  3. Python Environment Setup
  4. User Data Retrieval
  5. Log File Generation
  6. Automated Commits
  7. Pull Request Creation

### Cleanup Job
- Removes old branches
- Maintains repository cleanliness
- Prevents accumulation of stale branches

## 🔒 Permissions

- **Contents**: Write access
- **Pull Requests**: Write access

## 💻 Technology Stack

- **CI/CD**: GitHub Actions
- **Language**: Python
- **API**: RandomUser.me
- **Version Control**: Git

## 🚨 Important Notes

- Workflow runs automatically
- Generates logs in `user_logs/` directory
- Creates timestamped branches
- Provides comprehensive logging

## 📜 License & Usage

- Educational and Testing Purposes
- Follows GitHub Actions Best Practices
- Respects User Privacy
- Complies with RandomUser.me API Terms of Service

---

**Crafted with ❤️ by Flash User Live Tracker Team**
