# Auto Ticket Classification using Flow Designer

## Project Overview

The **Auto Ticket Classification using Flow Designer** project is a ServiceNow automation solution designed to reduce the manual effort involved in classifying IT support tickets.

In a typical school IT helpdesk, students and teachers submit support requests related to:

- Network connectivity
- Hardware failures
- Account and access issues
- System performance
- Other common IT problems

Traditionally, IT staff manually review each ticket, identify the issue, select the appropriate category and subcategory, and notify the caller.

This project uses **ServiceNow Flow Designer** to automate the ticket classification and notification process.

---

##  Problem Statement

The existing manual ticket management process is:

- Time-consuming
- Error-prone
- Difficult to scale
- Dependent on manual classification
- Inefficient when ticket volume increases

The goal of this project is to automate repetitive ticket-handling activities and improve the consistency of IT service management.

---

## Proposed Solution

The solution uses **ServiceNow Flow Designer** to create an automated workflow for incoming support requests.

### Basic Workflow

```text
          User submits IT request
                    ↓
             Ticket is created
                    ↓
          Flow Designer is triggered
                    ↓
          Identify issue information
                    ↓
        Determine ticket classification
                    ↓
        Set Category / Subcategory
                    ↓
       Notify the requester / caller
                    ↓
          Ticket ready for processing
