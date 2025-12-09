# BOA Terraform Level 2 Training

## Training Overview
- **Duration:** 2 days (16 hours total)
- **Level:** Advanced Terraform Concepts
- **Date:** 9th December 2025

## Training Modules

### Module 1: Advanced Control Structures
- **Advanced Looping Patterns**
  - Count-based resource creation
  - For_each with maps and sets
  - Dynamic blocks for nested configurations
  - Conditional iterations
  - Complex iteration scenarios with multiple resources

### Module 2: Functions and Data Management
- **Advanced Functions and Data Types**
  - Built-in Terraform functions (string, collection, numeric)
  - Custom variable validation
  - Complex data type handling (maps, lists, objects)
  - Type constraints and conversions
  - Local values and computed expressions

### Module 3: Resource Deployment Strategies
- **Conditional Resource Deployment**
  - Using count and for_each for conditional creation
  - Conditional expressions in resource blocks
  - Environment-based resource provisioning
  - Feature flags and toggles

- **Resource Lifecycle Management**
  - Lifecycle meta-arguments (create_before_destroy, prevent_destroy)
  - Ignore_changes configuration
  - Replace_triggered_by for dependency management
  - Resource replacement strategies

### Module 4: Configuration Architecture
- **Configuration Splitting (Layered Architecture)**
  - Multi-file organization strategies
  - Module-based architecture
  - Environment segregation (dev, staging, prod)
  - Workspace management
  - DRY principles in Terraform

- **Cross-Configuration Data Sharing**
  - Remote state data sources
  - terraform_remote_state usage
  - Output sharing between configurations
  - State locking and consistency

### Module 5: Legacy and Advanced State Operations
- **Importing Legacy AWS Resources**
  - Import command usage
  - Resource identification and mapping
  - Import blocks (Terraform 1.5+)
  - Brownfield infrastructure adoption
  - Generating configuration from existing resources

- **Advanced State Operations (State Surgery)**
  - State manipulation commands (mv, rm, replace)
  - State file structure and management
  - Disaster recovery scenarios
  - Refactoring and restructuring state
  - State migration strategies
  - Troubleshooting state issues

## Prerequisites
- Terraform basics and fundamental concepts
- AWS account and basic AWS knowledge
- Understanding of Infrastructure as Code principles

## Learning Outcomes
By the end of this training, participants will be able to:
- Implement complex resource deployment patterns
- Architect scalable and maintainable Terraform configurations
- Manage and manipulate Terraform state effectively
- Integrate legacy infrastructure into Terraform management
- Apply advanced Terraform features for real-world scenarios
