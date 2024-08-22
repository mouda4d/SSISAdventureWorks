# SSIS ETL Package Tutorial

## Overview
This project demonstrates the creation of an ETL package using SQL Server Integration Services (SSIS). The lessons guide you through building a basic ETL package and adding features like looping, logging, error handling, package configurations, and parameters.

## Lessons

### Lesson 1: Create a Project and Basic Package
- **Objective**: Create an SSIS project, set up a data flow, and load data from a flat file into a SQL Server table.
- **Steps**:
  1. Create a new Integration Services project.
  2. Add a Data Flow Task to the Control Flow.
  3. Configure the Flat File Connection Manager.
  4. Set up the OLE DB Destination.

### Lesson 2: Adding Looping
- **Objective**: Use the Foreach Loop Container to process multiple flat files.
- **Steps**:
  1. Add a Foreach Loop Container to the Control Flow.
  2. Configure the loop to iterate through files.
  3. Adjust the Data Flow for looping files.

### Lesson 3: Add Logging
- **Objective**: Enable logging to capture execution details.
- **Steps**:
  1. Right-click the Control Flow background and select Logging.
  2. Choose events to log.
  3. Set up the logging provider.

### Lesson 4: Add Error Flow Redirection
- **Objective**: Handle data flow errors by redirecting error rows.
- **Steps**:
  1. Configure error outputs in the Data Flow Task.
  2. Set up a new destination for error rows.

### Lesson 5: Add Package Configurations
- **Objective**: Use configurations to dynamically update properties at runtime.
- **Steps**:
  1. Enable Package Configurations.
  2. Create and configure new configurations.

### Lesson 6: Using Parameters
- **Objective**: Implement parameters for flexible deployments.
- **Steps**:
  1. Create and configure project and package parameters.
  2. Use parameters in expressions.

## Deployment
- **Objective**: Deploy the SSIS package to the SSISDB catalog.
- **Steps**:
  1. Build the project.
  2. Deploy to the SSISDB catalog.
  3. Execute the package from the catalog or SQL Server Agent.
