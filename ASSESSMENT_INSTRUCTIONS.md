# Technical Assessment Instructions

## Overview

Thank you for your interest in this position. This assessment evaluates your skills in blockchain development, smart contract security, Web3 integration, and full-stack development.

You'll be working on a healthcare data consent management system built on blockchain technology.

## Project Structure

The project has three components:

1. **Smart Contract** (`backend/contracts/PatientConsentManager.sol`) - **Core deliverable**
2. **Backend API** (`backend/server.js`) - Integration layer
3. **Frontend Application** (`frontend/`) - Optional

## Required Tasks

### 1. Smart Contract Development (Primary Focus)

Focus most of your time on the smart contract. This is the main deliverable.

**Tasks:**
- Review the existing contract code
- Identify and fix security vulnerabilities
- Optimize gas usage
- Add any missing critical functionality
- Write comprehensive tests (aim for >90% coverage)
- Test edge cases and error conditions
- Deploy to local Hardhat network and verify

**Security Considerations:**
- Address common vulnerabilities (reentrancy, overflow/underflow, access control)
- Apply security best practices (OWASP, Consensys Best Practices)
- Ensure proper access control and permissions

### 2. Backend Integration (Secondary Focus)

Enhance the backend to work with your deployed contract.

**Tasks:**
- Load contract ABI from compiled artifacts
- Connect to Web3 provider
- Add API endpoints to query blockchain data (consents, requests, providers)
- Implement proper error handling
- Handle transaction signing and confirmation

### 3. Frontend Enhancement (Optional)

If time permits, enhance the frontend.

**Tasks:**
- Connect Web3 wallet (MetaMask, etc.)
- Load and use contract ABI
- Display blockchain data
- Handle transaction states
- Improve UI/UX

## Evaluation Criteria

1. **Smart Contract Quality (40%)**
   - Code organization and readability
   - Security best practices
   - Gas optimization
   - Test coverage and quality
   - Documentation

2. **Backend Integration (30%)**
   - Web3 integration
   - API design and endpoints
   - Error handling
   - Code quality

3. **Frontend Development (20%)** - *Optional*
   - Web3 wallet integration
   - UI/UX quality
   - State management
   - Error handling

4. **Overall (10%)**
   - Code organization
   - Documentation
   - Best practices
   - Problem-solving approach

## Getting Started

1. Read `README.md` and `QUICK_START.md` for setup instructions
2. Install dependencies and configure Hardhat
3. Review the existing smart contract code
4. Plan your enhancements
5. Implement changes incrementally with testing
6. Integrate backend functionality
7. Enhance frontend (optional)
8. Review and document your work

## What We're Looking For

- **Security-first mindset**: Healthcare data requires high security standards
- **Clean code**: Well-organized, readable, maintainable
- **Best practices**: Follow Solidity and Web3 best practices
- **Problem-solving**: Show your analytical thinking and decision-making
- **Documentation**: Comment your code and explain your decisions

## Submission

Please submit:

**Code Repository**
   - GitHub repository (preferred) or zip file
   - All source code, tests, and deployment scripts

**Good luck! We look forward to reviewing your submission.**